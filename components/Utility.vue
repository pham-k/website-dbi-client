<template>
  <div class="mx-4">
    <h1 class="text-2xl font-bold tracking-wide my-4">Utility</h1>
    <div class="flex flex-row flex-wrap justify-start">
      <div v-for="(item, index) in items" :key="index" class="basis-full md:basis-1/2 lg:basis-1/3 p-2">
        <div class="bg-white rounded-lg shadow p-4">
          <div class="flex flex-row align-center">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 stroke-gray-700 mr-4" fill="none"
              viewBox="0 0 24 24">
              <path d="M12 14l9-5-9-5-9 5 9 5z" />
              <path
                d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z" />
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222" />
            </svg>
            <p class="text-gray-700 text-base">{{item.text}}</p>
          </div>

        </div>
      </div>

    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          {
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          },
          {
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          },{
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          },{
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          },{
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          },{
            text: "Đăng ký CME",
            path: "/",
            icon: ""
          }
        ]
      }
    } 
  }

</script>