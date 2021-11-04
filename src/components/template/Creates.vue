<template>
  <div class="flex w-full">
    <div
      class="
        flex flex-col
        lg:flex-row
        justify-around
        items-center
        pt-4
        bg-purple-50
        w-full
        text-center
      "
    >
      <div class="flex justify-center">
        <div class="w-2/3 mr-8 ml-4">
          <p
            v-for="luk in name"
            v-bind:key="luk"
            class="
              text-center
              cursor-pointer
              border-b border-transparent
              hover:text-purple-800
              mb-2
              font-semibold
              text-3xl
              md:text-3xl
              lg:text-5xl
              text-gray-900
            "
          >
            {{ luk.text }}
          </p>
          <div class="flex text-center">
            <div class="text-justify text-center text-center"></div>
          </div>
          <div class="flex">
            <div class="max-w-6xl mx-auto sm:px-6 lg:px-4 py-8 center">
              <div
                class="
                  grid grid-cols-1
                  sm:grid-cols-2
                  md:grid-cols-2
                  lg:grid-cols-3
                  gap-6
                "
              >
                <div
                  class="
                    w-full
                    bg-white
                    rounded-lg
                    p-12
                    flex flex-col
                    justify-center
                    items-center
                  "
                >
                  <div class="mb-8">
                    <img
                      class="object-center object-cover rounded-full h-36 w-36"
                      src="@/assets/images/github1.png"
                      alt="photo"
                    />
                  </div>
                  <div class="text-center">
                    <p class="text-xl text-gray-700 font-bold mb-2">
                      Plataforma Feedbacker
                    </p>
                    <p class="text-base text-gray-400 font-normal mb-2">
                      Javascript | Vue.js | Tailwind.css
                    </p>
                  </div>
                  <button
                    class="
                      bg-blue-800
                      hover:bg-purple-600
                      text-white
                      font-bold
                      py-1
                      px-4
                      border-b-4 border-blue-900
                       hover:border-blue-900
                      rounded
                      ml-2
                      mt-4
                    "
                  >
                    Link
                  </button>
                </div>
                <div
                  class="
                    w-full
                    bg-white
                    rounded-lg
                    p-12
                    flex flex-col
                    justify-center
                    items-center
                  "
                >
                  <div class="mb-8">
                    <img
                      class="object-center object-cover rounded-full h-36 w-36"
                      src="@/assets/images/github2.png"
                      alt="photo"
                    />
                  </div>
                  <div class="text-center">
                    <p class="text-xl text-gray-700 font-bold mb-8">
                      Twitter clone
                    </p>
                    <p class="text-base text-gray-400 font-normal mb-4">
                      Javascript | Vue.js | Tailwind.css
                    </p>
                  </div>
                  <button
                    class="
                      bg-blue-800
                      hover:bg-blue-600
                      text-white
                      font-bold
                      py-1
                      px-4
                      border-b-4 border-blue-900
                      hover:border-blue-900
                      rounded
                      ml-2
                      mt-8
                    "
                  >
                    Link
                  </button>
                </div>
                <div
                  class="
                    w-full
                    bg-white
                    rounded-lg
                    p-12
                    flex flex-col
                    justify-center
                    items-center
                  "
                >
                  <div class="mb-8">
                    <img
                      class="object-center object-cover rounded-full h-36 w-36"
                      src="@/assets/images/github3.png"
                      alt="photo"
                    />
                  </div>
                  <div class="text-center">
                    <p class="text-xl text-gray-700 font-bold mb-2">
                      Plataforma cod3r
                    </p>
                    <p class="text-base text-gray-400 font-normal">
                      Javascript | Vue.js | Tailwind.css
                    </p>
                    <button
                      class="
                        bg-blue-800
                        hover:bg-gray-900
                        text-white
                        font-bold
                        py-1
                        px-4
                        border-b-4 border-blue-900
                        hover:border-blue-900
                        rounded
                        ml-2
                        mt-2
                      "
                    >
                      Link
                    </button>
                  </div>
                </div>
              </div>
            </div>
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
      name: [{ text: "<Melhores projetos />" }],
    };
  },
};
</script>