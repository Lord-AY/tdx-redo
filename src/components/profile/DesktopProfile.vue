<template>
  <div class="mt-12">
    <div
      class="w-11/12 mx-auto px-12 pb-12 grid grid-flow-col grid-cols-6 gap-8 space-x-4"
    >
      <div class="col-span-2">
        <ProfileSidebar
          :tabs="tabs"
          :selectedTab="currentTab"
          @switchTab="ChangeTab"
        />
      </div>
      <div class="col-span-4">
        <div class="bg-white shadow-md rounded-md">
          <keep-alive>
            <AdvertTabComponent :is="currentTab" />
            <FeedbackTabComponent :is="currentTab" />
            <FollowersTabComponent :is="currentTab" />
          </keep-alive>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import ProfileSidebar from "@/components/profile/ProfileSidebar";
export default {
  components: {
    ProfileSidebar,
    AdvertTabComponent: () => import("@/components/profile/AdvertTabComponent"),
    FeedbackTabComponent: () =>
      import("@/components/profile/FeedbackTabComponent"),
    FollowersTabComponent: () =>
      import("@/components/profile/FollowersTabComponent"),
  },
  data() {
    return {
      currentTab: "AdvertTabComponent",
      tabs: [
        {
          name: "My Adverts",
          type: "tab",
          component: "AdvertTabComponent",
          icon: "advert.svg",
        },
        {
          name: "Make money on tradexplora",
          type: "link",
          route: "SellingInfo",
          icon: "money.svg",
        },
        {
          name: "Feedback",
          type: "tab",
          component: "FeedbackTabComponent",
          icon: "feedback.svg",
        },
        {
          name: "Followers",
          type: "tab",
          component: "FollowersTabComponent",
          icon: "followers.svg",
        },
        {
          name: "Settings",
          type: "link",
          route: "Settings",
          icon: "settings.svg",
        },
      ],
    };
  },
  methods: {
    ChangeTab(tab) {
      if (tab.type == "tab") {
        return (this.currentTab = tab.component);
      }
      console.log(tab);
    },
  },
};
</script>
		<style lang="scss" scoped></style>