<script setup></script>
<template>
  <div>
  
      <div
        class=" text-sm bg-custom-color rounded  py-2"
      ><div class="w-[80%] m-auto flex justify-end text-white space-x-4">
        <Nuxtlink to="/">Giới thiệu</Nuxtlink>
        <Nuxtlink to="/">Trung tâm bảo hành</Nuxtlink>
        <Nuxtlink to="/">Hệ thống cửa hàng</Nuxtlink>
        <Nuxtlink to="/">Tuyển dụng</Nuxtlink>
        <Nuxtlink to="/">Kiểm tra đơn hàng</Nuxtlink>
        <Nuxtlink to="/">Đăng nhập</Nuxtlink>
      </div>
      </div>
    

    <div class=" w-[80%] m-auto header_menu">
      <div class="">
        
        <div class="flex items-center justify-center">
          <div class="w-[20%]">
            <div class="flex justify-center items-center">
          <img
            class="img"
            src="https://hoanghamobile.com/Uploads/2024/03/12/logo-hh.png"
          />
          </div>
        </div>

        <div class="w-[60%]">
          <div class=" flex rounded-3xl text-sm items-center">
            <div class=" flex-1 search-box rounded-full overflow-hidden">
              <form
                method="get"
                action="/tim-kiem"
                onsubmit="return submitSearch(this);"
                enctype="application/x-www-form-urlencoded"
              >
                <div class="border flex">
                  <input
                    type="text"
                    id="kwd"
                    name="kwd"
                    placeholder="Hôm nay bạn cần tìm gì?"
                    autocomplete="off"
                    class="py-2 px-4 outline-none w-full rounded-l-full"
                  />
                  <button type="submit" class="flex items-center justify-center  px-4 bg-[#00483d] rounded-r">
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-6 h-6 fill-current text-[#FFFFFF]">
    <path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"/>
  </svg>
  <i class="icon-search"></i>
</button>

                </div>
              </form>
            </div>
            <div class="ml-4">
            <a href=""
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-8 h-8 fill-current text-[#00483d]"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M2.25 3h1.386c.51 0 .955.343 1.087.835l.383 1.437M7.5 14.25a3 3 0 0 0-3 3h15.75m-12.75-3h11.218c1.121-2.3 2.1-4.684 2.924-7.138a60.114 60.114 0 0 0-16.536-1.84M7.5 14.25 5.106 5.272M6 20.25a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Zm12.75 0a.75.75 0 1 1-1.5 0 .75.75 0 0 1 1.5 0Z"
                />
              </svg>
            </a>
          </div>
          </div>
        </div>
        <div class="w-[20%]">
          <div class="flex justify-center items-center">
            <button class=" bg-custom-color text-white  py-2 px-4 rounded">
              <Nuxt-link to="https://hoanghamobile.com/">Đăng nhập</Nuxt-link>
            </button>
            <button class="ml-1 bg-custom-color text-white  py-2 px-4 rounded">
              Đăng ký
            </button>
          </div>
        </div>
        </div>
      </div>
    </div>
    <div class="w-[80%] m-auto mb-4">
      <div class="bg-custom-color rounded px-4 py-3 text-white">
        <div
          class="flex justify-center text-base items-center bg-custom-color rounded px-5 py-2 text-white"
        >
          <div class="m-auto">
            <Nuxt-link to="/"> Iphone </Nuxt-link>
          </div>
          <div class="m-auto">
            <Nuxt-link to="/"> Samsung </Nuxt-link>
          </div>
          <div class="m-auto">
            <Nuxtlink to="/">Oppo </Nuxtlink>
          </div>
          <div class="m-auto">
            <Nuxt-link to="/">realme</Nuxt-link>
          </div>
          <div class="m-auto">
            <Nuxt-link to="/">Xiaomi</Nuxt-link>
          </div>
          <div class="m-auto">
            <Nuxt-link to="/">Vivo</Nuxt-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-custom-color {
  background-color: #00483d;
}
.header__search {
  margin: 0 340px;
  height: 50px;
}

.header__search-input {
  width: 100%;
  height: 100%;
  padding: 0 16px;
}
.img {
  width: 200px; /* Đặt kích thước chiều rộng tùy ý */
  height: 60px; /* Giữ tỉ lệ khung hình */
}


</style>
