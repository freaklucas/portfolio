<template>
  <div class="flex w-full">
    <div
      class="
        flex flex-col
        lg:flex-row
        justify-around
        items-center
        pt-4
        bg-purple-600
        w-full
        text-center
      "
    >
      <div class="flex">
        <div class="w-2/3 mr-8 ml-4">
          <div class="flex">
            <div class="text-justify text-center">
              <p
                v-for="luk in name"
                v-bind:key="luk"
                class="
                  text-3xl
                  md:text-3xl
                  lg:text-5xl
                  font-semibold
                  text-gray-900
                  cursor-pointer
                  border-b border-transparent
                  hover:text-purple-900
                  mb-2
                  text-center
                "
              >
                {{ luk.text }}
              </p>
              <div class="center">
                <div class="flex items-center">
                  <div class="grid grid-cols-2 gap-4 mb-12">
                    <div
                      class="
                        flex flex-col
                        bg-gray-200
                        rounded-full
                        p-4
                        m-2
                        hover:bg-blue-100
                        w-32
                        h-32
                      "
                    >
                      <img
                        src="@/assets/images/html.png"
                        alt=""
                        class="
                          transition
                          duration-500
                          ease-in-out
                          transform
                          hover:-translate-y-1
                          hover:scale-180
                        "
                      />
                    </div>
                    <div
                      class="
                        flex flex-col
                        bg-gray-200
                        rounded-full
                        p-4
                        m-2
                        hover:bg-blue-100
                        w-32
                        h-32
                        ml-4
                      "
                    >
                      <img
                        src="@/assets/images/css.png"
                        alt=""
                        class="
                          transition
                          duration-500
                          ease-in-out
                          transform
                          hover:-translate-y-1
                          hover:scale-180
                        "
                      />
                    </div>
                  </div>
                </div>
                <div class="flex items-center">
                  <div class="grid grid-cols-2 gap-4 mb-8">
                    <div
                      class="
                        flex flex-col
                        bg-gray-200
                        rounded-full
                        p-4
                        m-2
                        hover:bg-blue-100
                        w-32
                        h-32
                      "
                    >
                      <img
                        src="@/assets/images/vuejs.png"
                        alt=""
                        class="
                          transition
                          duration-500
                          ease-in-out
                          transform
                          hover:-translate-y-1
                          hover:scale-180
                        "
                      />
                    </div>
                    <div
                      class="
                        flex flex-col
                        bg-gray-200
                        rounded-full
                        p-4
                        m-2
                        hover:bg-blue-100
                        w-32
                        h-32
                        ml-4
                      "
                    >
                      <img
                        src="@/assets/images/javascript.png"
                        alt=""
                        class="
                          transition
                          duration-500
                          ease-in-out
                          transform
                          hover:-translate-y-1
                          hover:scale-200
                        "
                      />
                    </div>
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
      name: [{ text: "<Tecnologias/>" }],
    };
  },
};
</script>
