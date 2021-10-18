<template>
  <div class="flex w-full">
    <div
      class="
        flex flex-col
        lg:flex-row
        justify-around
        items-center
        pt-4
        w-full
        text-center
      "
    >
      <div class="flex">
        <div class="text-justify text-center">
          <p
            class="
              text-3xl
              md:text-3xl
              lg:text-5xl
              font-semibold
              text-gray-900
              cursor-pointer
              border-b border-transparent
              hover:text-purple-800
              mb-4
              text-center
            "
            v-for="desc in name"
            v-bind:key="desc"
          >
            {{ desc.text }}
          </p>
          <p class="font-mono text-lg mt-4 hover:text-blue-900 text-center">
            Entre em contato através das redes sociais
          </p>
          <div class="">
            <div class="flex items-center flex-col">
              <div class="grid sm:row-span-3 md:grid-flow-col">
                <div
                  class="
                    flex flex-col
                    bg-gray-200
                    rounded-lg
                    p-4
                    m-2
                    hover:bg-purple-50
                    transition
                    duration-500
                    ease-in-out
                    transform
                    hover:-translate-y-1 hover:scale-180
                  "
                >
                  <div class="flex flex-col bg-gray-200 rounded-lg">
                    <img
                      src="@/assets/images/frontend.svg"
                      alt="ilustração frontend"
                    />
                    <div class="flex flex-col items-center mt-4">
                      <h2 class="text-xl font-semibold text-gray-900">
                        Aplicações frontend
                      </h2>
                    </div>
                  </div>
                </div>
                <div
                  class="
                    flex flex-col
                    bg-gray-200
                    rounded-lg
                    p-4
                    m-2
                    hover:bg-purple-50
                    transition
                    duration-500
                    ease-in-out
                    transform
                    hover:-translate-y-1 hover:scale-180
                  "
                >
                  <div class="flex flex-col bg-gray-200 rounded-lg">
                    <img src="@/assets/images/frontend1.png" alt="" />
                    <div class="flex flex-col items-center mt-4">
                      <h2 class="text-xl font-semibold text-gray-900">
                        Responsividade
                      </h2>
                    </div>
                  </div>
                </div>
                <div
                  class="
                    flex flex-col
                    bg-gray-200
                    rounded-lg
                    p-4
                    m-2
                    hover:bg-purple-50
                    transition
                    duration-500
                    ease-in-out
                    transform
                    hover:-translate-y-1 hover:scale-180
                  "
                >
                  <div class="flex flex-col bg-gray-200 rounded-lg">
                    <img src="@/assets/images/tests1.png" alt="" />
                    <div class="flex flex-col items-center mt-4">
                      <h2 class="text-xl font-semibold text-gray-900">
                        Testes automatizados
                      </h2>
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
  name: "Project",
  data() {
    return {
      name: [{ text: "<Tire sua ideia do papel />" }],
    };
  },
};
</script>