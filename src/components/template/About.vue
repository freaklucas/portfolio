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
      "
    >
      <div class="lg:w-2/3 md:w-2/3 mr-8 ml-4 sm:px-6 lg:px-4 center">
        <h1 class="font-bold text-3xl mb-4 text-gray-200 text-justify ml-1">
          Seja muito bem vindo(a), sou o
        </h1>
        <div class="flex line">
          <div class="text-justify">
            <a
              v-for="luk in name"
              v-bind:key="luk"
              class="
                text-1xl
                font-bold
                text-purple-900
                cursor-pointer
                border-b border-transparent
                hover:text-blue-200
                mt-4
                ml-1
              "
            >
              {{ luk.text }}
            </a>
            <h2
              class="
                center
                font-bold
                text-gray-800 text-2xl text-justify
                justify-center
                mt-4
                ml-2
              "
            >
              Desenvolvedor front-end focado na experiência do usuário
            </h2>
            <h2
              class="
                font-bold
                text-gray-900 text-sm text-justify
                justify-center
                mt-2
                ml-2
                mb-4
              "
            >
              UI/UX | Javascript | Vue.js | Tailwind | Vite
            </h2>
          </div>
        </div>
        <button
          class="
            bg-blue-800
            hover:bg-blue-600
            text-white
            font-bold
            py-4
            px-4
            border-b-4 border-blue-900
            hover:border-blue-900
            rounded-full
            ml-2
            mt-2
            transition
            duration-500
            ease-in-out
            transform
            hover:-translate-y-1
            hover:scale-110
          "
        >
          Conheça meu trabalho
        </button>
      </div>
      <div class="lg:w-2/3 w-2/3 mt-4 lg:mt-2 pl-4 ml-4">
        <img
          src="@/assets/images/computer.png"
          alt=""
          class="pl-8 flex flex-end"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: [{ text: "<Lucas Oliveira/>" }],
    };
  },
};
</script>

<style>
</style>