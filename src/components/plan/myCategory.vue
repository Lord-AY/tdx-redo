<template>
  <div>
    <div class="mx-auto text-center text-white mt-16">
      <div class="mx-auto justify-center block">
        <div class="my-4 font-bold">
          <h5>my category is:</h5>
        </div>
        <div class="justify-center flex block">
          <div class="w-96 h-45 py-2 flex justify-center justify-around mb-12">
            <router-link :to="{ name: 'Property' }">
              <div class="w-28 h-28 bg-white px-2 rounded">
                <span class="">
                  <svg
                    id="ps-real_estate"
                    viewBox="0 0 34 34"
                    class="w-16 h-16 ml-2 mt-1"
                  >
                    <path
                      fill="#FFA010"
                      fill-rule="evenodd"
                      d="M16.69 3.48L1.678 12.977l-.089.069v20.1h5.034V16.41h9.162v16.735h16.029V12.585L16.69 3.48zm10.531 20.1h-6.866V16.41h6.866v7.169z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#E18700"
                      d="M16.61 15.403H5.985v17.708H16.61V15.403z"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M28.988 9.496l-4.305-1.383V.622h4.305v8.874z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#E18700"
                      d="M32.256 11.917l-14.439-8.92-16.249 10.05v2.074L18.502 5.07l13.246 8.114.508-1.268z"
                    ></path>
                    <path
                      fill="#303A4B"
                      d="M33.05 10.142L16.558 0 0 10.188v3.62L16.558 3.664 33.05 13.807v-3.665z"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M2.892 34H0v-6.846l1.347-1.96 1.545 1.96v6.845zM7.33 34H4.438v-6.846l1.346-1.96 1.546 1.96v6.845zM11.767 34h-2.87v-6.846l1.347-1.96 1.523 1.96v6.845zM16.205 34h-2.87v-6.846l1.347-1.96 1.523 1.96v6.845zM20.664 34h-2.892v-6.846l1.347-1.96 1.545 1.96v6.845zM25.102 34h-2.87v-6.846l1.347-1.96 1.523 1.96v6.845zM29.54 34h-2.87v-6.846l1.346-1.96 1.524 1.96v6.845zM34 34h-2.892v-6.846l1.347-1.96L34 27.154v6.845z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      d="M32.542 29.596H.353v1.706h32.19v-1.706zM29.805.275h-6.027v1.96h6.027V.275z"
                    ></path>
                    <path
                      fill="#7FA8FC"
                      d="M28.017 15.56h-8.455v8.827h8.455V15.56z"
                    ></path>
                    <path
                      fill="#fff"
                      d="M27.774 15.812v8.32h-7.97v-8.32h7.97zm.485-.507h-8.941v9.335h8.941v-9.335z"
                    ></path>
                    <path
                      fill="#fff"
                      d="M24.088 15.743h-.574v8.644h.574v-8.644z"
                    ></path>
                    <path
                      fill="#fff"
                      d="M27.928 19.777h-8.28v.6h8.28v-.6z"
                    ></path>
                  </svg>
                </span>
                <span class="category-text">Property</span>
              </div>
            </router-link>

            <router-link :to="{ name: 'Cars' }">
              <div class="w-28 h-28 bg-white px-2 rounded">
                <span>
                  <svg
                    id="ps-cars"
                    viewBox="0 0 42 24"
                    class="w-16 h-16 ml-2 mt-1"
                  >
                    <path
                      fill="#2B51A5"
                      fill-rule="evenodd"
                      d="M41.884 12.862c.376 2.609-.167 5.26-1.588 7.492h-.564c.23-.584.355-1.231.355-1.899a5.133 5.133 0 0 0-5.138-5.134 5.132 5.132 0 0 0-5.139 5.134c0 .668.126 1.315.355 1.9H12.557c.23-.585.355-1.232.355-1.9a5.132 5.132 0 0 0-5.139-5.134 5.132 5.132 0 0 0-5.138 5.134c0 .668.125 1.315.355 1.9H1.716A7.838 7.838 0 0 1 .19 13.738l1.002-.355.773-1.461c-.104-1.273 2.716-3.297 8.48-6.073A22.078 22.078 0 0 1 20.85.132 51.613 51.613 0 0 1 37.33 1.613a20.128 20.128 0 0 1 3.008 10.581l1.546.668z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#2B51A5"
                      fill-rule="evenodd"
                      d="M39.754 20.354a5.132 5.132 0 0 0-1.671-5.99c-1.838-1.398-4.387-1.398-6.204 0a5.162 5.162 0 0 0-1.671 5.99c-1.17-2.358-.522-5.217 1.525-6.866a5.628 5.628 0 0 1 7.04 0c2.046 1.649 2.694 4.508 1.524 6.866h-.543zM13.685 20.354H12.6a5.132 5.132 0 0 0-1.671-5.99 5.112 5.112 0 0 0-6.204 0 5.162 5.162 0 0 0-1.67 5.99 5.814 5.814 0 0 1 1.754-6.866c2.089-1.607 5.013-1.607 7.08 0a5.773 5.773 0 0 1 1.797 6.866z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M39.879 14.678c.815-.334 1.483-.94 2.005-1.816.376 2.609-.167 5.26-1.587 7.492a5.587 5.587 0 0 0-.418-5.676z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#2B51A5"
                      fill-rule="evenodd"
                      d="M41.885 12.862c-.523.898-1.191 1.503-2.006 1.816a5.948 5.948 0 0 0-1.107-1.19c.71-.27 1.254-.71 1.588-1.273l1.525.647z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M.19 13.76c1.484.5 2.988.458 4.492-.126a5.783 5.783 0 0 0-1.609 6.741H1.716A7.87 7.87 0 0 1 .19 13.759z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#2B51A5"
                      fill-rule="evenodd"
                      d="M4.682 13.614c-1.504.605-3.008.646-4.491.125l1.002-.355c1.045.271 2.611.083 4.7-.564a5.582 5.582 0 0 0-1.065.647c-.042.063-.105.105-.146.146zM13.727 15.867H30a5.663 5.663 0 0 0 .209 4.508H13.685c.627-1.482.627-3.11.042-4.508zM29.998 15.847H13.726a5.592 5.592 0 0 0-.857-1.44h17.964c-.355.459-.626.939-.835 1.44z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#FFA010"
                      fill-rule="evenodd"
                      d="M6.602 10.336c-.522-.271-1.274-.355-2.276-.25-.961.459-1.567 1.085-1.776 1.878 1.588.188 2.945-.355 4.052-1.628zM40.359 12.216c0-1.67-.209-3.36-.627-4.967-.668.5-1.044.918-1.149 1.252.543 2.17 1.15 3.402 1.776 3.715z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#C1C1C1"
                      fill-rule="evenodd"
                      d="M10.99 6.351c14.769.668 22.163.98 22.163.98 1.713-.542 2.966-2.19 3.802-4.924A38.301 38.301 0 0 0 20.912.925a20.074 20.074 0 0 0-9.921 5.426z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#7FA8FC"
                      fill-rule="evenodd"
                      d="M22.082 14.428c.02-2.546.02-5.072 0-7.576l11.07.5-3.739 7.076h-7.331z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#7FA8FC"
                      fill-rule="evenodd"
                      d="M22.082 6.852c.02 2.504.02 5.03 0 7.576H12.87a13.01 13.01 0 0 0-3.656-5.635l1.776-2.42 11.092.48z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M35.01 13.634a4.803 4.803 0 0 0-4.804 4.8c0 2.65 2.151 4.8 4.804 4.8a4.803 4.803 0 0 0 4.804-4.8c0-2.65-2.151-4.8-4.804-4.8z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M35.013 14.156a4.295 4.295 0 0 0-4.304 4.299c0 2.358 1.922 4.3 4.304 4.3 2.36 0 4.303-1.92 4.303-4.3-.021-2.38-1.943-4.3-4.303-4.3z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#DBDCDC"
                      fill-rule="evenodd"
                      d="M35.01 15.721a2.709 2.709 0 0 0-2.715 2.713 2.709 2.709 0 0 0 2.716 2.713 2.709 2.709 0 0 0 2.715-2.713c0-1.481-1.232-2.713-2.715-2.713z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M35.012 16.953c-.815 0-1.483.668-1.483 1.482s.668 1.482 1.483 1.482c.815 0 1.483-.668 1.483-1.482s-.668-1.482-1.483-1.482zM7.858 13.634a4.803 4.803 0 0 0-4.805 4.8c0 2.65 2.152 4.8 4.805 4.8a4.803 4.803 0 0 0 4.804-4.8c0-2.65-2.13-4.8-4.804-4.8z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M7.856 14.156a4.295 4.295 0 0 0-4.303 4.299c0 2.358 1.922 4.3 4.303 4.3 2.381 0 4.303-1.942 4.303-4.32 0-2.36-1.922-4.28-4.303-4.28z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#DBDCDC"
                      fill-rule="evenodd"
                      d="M7.857 15.721a2.709 2.709 0 0 0-2.716 2.713 2.709 2.709 0 0 0 2.716 2.713 2.709 2.709 0 0 0 2.715-2.713 2.722 2.722 0 0 0-2.715-2.713z"
                      clip-rule="evenodd"
                    ></path>
                    <path
                      fill="#303A4B"
                      fill-rule="evenodd"
                      d="M7.856 16.953c-.815 0-1.483.668-1.483 1.482s.668 1.482 1.483 1.482c.815 0 1.483-.668 1.483-1.482s-.668-1.482-1.483-1.482z"
                      clip-rule="evenodd"
                    ></path>
                  </svg>
                </span>
                <span class="category-text">Cars</span>
              </div>
            </router-link>

            <router-link :to="{ name: 'Others' }">
              <div class="w-28 h-28 bg-white px-2 rounded">
                <span>
                  <svg
                    id="ps-others"
                    viewBox="0 0 23 33"
                    class="w-16 h-16 ml-2 mt-1"
                  >
                    <path
                      fill="#3DB83A"
                      d="M23 21.888c0 1.183-.288 2.366-.719 3.55-1.581 3.845-5.175 6.655-9.2 7.098-.575 0-1.15.148-1.581.148-6.325 0-11.5-4.732-11.5-10.796 0-1.035.144-2.218.575-3.254.863-2.514 2.731-4.732 5.031-5.915.288 2.366 1.438 4.584 3.306 5.915.288.296.72.592 1.15.74-.143-.296-.287-.444-.43-.74-1.294-2.07-1.87-4.288-1.87-6.655v-.148c0-2.514.72-4.88 2.157-6.95C11.212 2.81 13.08 1.182 15.238 0c-.432 1.183-.575 2.366-.575 3.55v.443c0 3.697 1.58 7.099 4.312 9.613 1.15 1.035 2.3 2.219 3.019 3.697.718 1.331 1.006 2.958 1.006 4.585z"
                    ></path>
                    <path
                      fill="#279625"
                      d="M23 22.066c0 1.164-.288 2.328-.719 3.491-1.581 3.782-5.175 6.546-9.2 6.982-.575 0-1.15.145-1.581.145C5.175 32.684 0 28.03 0 22.066c0-.236.03-.535.078-.854l-.035-.1.253-1.068c.141-.654.279-1.178.279-1.178l-.279 1.178c-.08.371-.16.784-.218 1.168.33.896 3.066 7.509 11.422 6.33 9.108-1.287 7.475-13.62 7.475-13.62 1.15 1.017 2.3 2.18 3.019 3.635.718 1.31 1.006 2.91 1.006 4.51z"
                    ></path>
                  </svg>
                </span>
                <span class="category-text">Others</span>
              </div>
            </router-link>
          </div>
        </div>
      </div>
      <div>
        <button class="w-40 h-8 bg-white rounded text-gray-500">
          how it works?
        </button>
      </div>
    </div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "myCategory",
  components: {},
};
</script>

<style lang="css" scoped>
.category-text {
  display: inline-block;
  width: 100%;
  text-align: center;
  font-size: 16px;
  line-height: 27px;
  font-weight: 500;
  color: #303a4b;
  margin-top: 10px;
}
</style>
