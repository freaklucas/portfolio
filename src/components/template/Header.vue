<template>
  <div class="flex items-center justify-between w-full">
    <header
      class="
        
        items-center
        justify-between
        flex-wrap
        p-4
        w-full
        text-gray-100
        bg-gray-900
        font-mono
        shadow
      "
    >
      <div
        class="
          container
          mx-auto
          flex flex-wrap
          p-4
          flex-col
          md:flex-row
          items-center
        "
      >
        <nav
          class="
            flex
            lg:w-full
            flex-wrap
            items-center
            text-base
            md:ml-auto
            inline-flex
            space-x-4
            sm:w-full
          "
        >
          <a
            v-for="luk in name" v-bind:key="luk"
            class="
              flex-1
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
            "
          >
            {{ luk.text}}
          </a>
          <a
            class="
              flex-2
              inline-flex
              justify-end
              ml-2
              mr-4
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
            "
          >
            Quem sou?
          </a>
          <a
            class="
              flex-2
              inline-flex
              justify-end
              ml-2
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
            "
          >
            Contato
          </a>
          <a
            class="
              flex-3
              inline-flexjustify-end
              ml-4
              lg:ml-0
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
            "
          >
            Projetos
          </a>
        </nav>
      </div>
    </header>
  </div>
</template>

<script>
export default {
    data() {
        return {
            name: [ 
               { text: '<Lucas Oliveira/>' }
            ]
        }
    }
};
</script>

<style>
</style>