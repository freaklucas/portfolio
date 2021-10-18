<template>
  <div class="flex items-center justify-between w-full">
    <header
      class="
        items-center
        justify-between
        flex-wrap
        md:p-4
        lg:p-4
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
            sm:w-full
            flex-wrap
            items-center
            text-base
            md:ml-auto
            inline-flex
            space-x-2      "
        >
          <a
            v-for="luk in name" v-bind:key="luk"
            class="
              lg:flex-auto
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
              text-lg
              
            "
          >
            {{ luk.text}}
          </a>
          <a
            class="
              flex-1
              inline-flex
               sm:center
              justify-end
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
               sm:text-sm
            "
          >
            Quem sou?
          </a>
          <a
            class="
              flex-2
               sm:center
              inline-flex
              justify-end
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
               sm:text-sm
            "
          >
            Contato
          </a>
          <a
            class="
              flex-2
              sm:center
              inline-flex
              justify-end
              lg:ml-0
              hover:text-purple-300
              cursor-pointer
              border-b border-transparent
              hover:border-indigno-600
               sm:text-sm
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