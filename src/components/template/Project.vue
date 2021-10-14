<template>
  <div class="flex w-full">
    <!-- <particles-bg type="cobweb" :bg="true" /> -->
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
          <p class="font-mono text-lg mt-4 hover:text-blue-200 text-center">
            Entre em contato através das redes sociais abaixo
          </p>
          <div class="">
            <div class="flex items-center">
              <div
                class="
                  grid
                  xl:grid-cols-3
                  md:grid-cols-2
                  grid-cols-2
                  gap-4
                  max-w-6xl
                  mb-8
                "
              >
                <div
                  class="
                    flex flex-col
                    bg-gray-200
                    rounded-lg
                    p-4
                    m-2
                    hover:bg-yellow-100
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
                    hover:bg-yellow-100
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
                    hover:bg-yellow-50
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