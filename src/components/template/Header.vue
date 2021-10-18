<template>
  <div class="flex items-center justify-between w-full">
    <header
      class="
        items-center
        flex-wrap
        md:p-4
        lg:p-4
        w-full
        text-gray-100
        bg-gray-900
        font-mono
        shadow
        sm:text-sm
      "
    >
      <div class="container mx-auto flex p-4 flex-col md:flex-row items-center">
        <div
          class="
            flex
            lg:w-full
            sm:w-full
            flex-wrap
            items-center
            text-base
            md:ml-auto
            inline-flex
            space-x-2
          "
        >
          <a
            v-for="luk in name"
            v-bind:key="luk"
            class="
              lg:flex-auto
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
              text-normal
              transition
              duration-500
              ease-in-out
              transform
              hover:-translate-y-1 hover:scale-110
            "
          >
            {{ luk.text }}
          </a>
          <a
            class="
              inline-flex
              sm:center
              justify-end
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
              sm:text-sm
              transition
              duration-500
              ease-in-out
              transform
              hover:-translate-y-1 hover:scale-110
            "
          >
            Sobre
          </a>
          <a
            class="
              sm:center
              inline-flex
              justify-end
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
              sm:text-sm
              transition
              duration-500
              ease-in-out
              transform
              hover:-translate-y-1 hover:scale-110
            "
          >
            Contato
          </a>
          <a
            class="
              sm:center
              inline-flex
              justify-end
              lg:ml-0
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
              sm:text-sm
              transition
              duration-500
              ease-in-out
              transform
              hover:-translate-y-1 hover:scale-110
            "
          >
            Projetos
          </a>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: [{ text: "<Lucas/>" }],
    };
  },
};
</script>

<style>
</style>