<template>
  <div class="w-full bg-purple-500 text-white">
    <div class="xl:px-40 pb-12 lg:px-20 md:px-10 sm:px-5 px-10">
      <div
        class="w-full pt-12 flex flex-col sm:flex-row space-y-2 justify-start"
      >
        <div
          class="w-full sm:w-2/5 pr-6 flex flex-col space-y-4"
          v-for="luk in name"
          v-bind:key="luk"
        >
          <h2 class="font-mono text-xl text-gray-900 hover:text-purple-900">
            {{ luk.text }}
          </h2>
          <p class="opacity-60">
            front-end developer focused on user experience
          </p>
        </div>
        <div class="w-full sm:w-1/5 flex flex-col space-y-4">
          <a class="opacity-60 cursor-pointer">Sobre</a>
          <a class="opacity-60 cursor-pointer">Contato</a>
          <a class="opacity-60 cursor-pointer">Projetos</a>
        </div>
        <div class="w-full sm:w-1/5 pt-6 flex items-end mb-1">
          <img src="@/assets/images/git.png" class="w-8 h-6 mr-2" alt="" />
          <img src="@/assets/images/linkedin.png" class="w-8 h-6 mr-2" alt="" />
          <img src="@/assets/images/gmail.png" class="w-8 h-6 mr-2" alt="" />
          <img src="@/assets/images/twitter.png" class="w-8 h-6" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      name: [{ text: "<Lucas Oliveira/>" }],
    };
  },
};
</script>