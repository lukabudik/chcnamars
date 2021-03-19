<template>
  <div class="telo text-indigo-400 bg-cover bg-fixed height-full h-screen font-sans" style="background-image: url('header.webp');">
      <!--Main-->
      <div class="container pt-24 md:pt-36 mx-auto flex flex-wrap flex-col md:flex-row items-center">
        <!--Left Col-->
        <div class="flex flex-col w-full xl:w-2/5 justify-center lg:items-start overflow-y-hidden">
          <h1 class="my-4 text-3xl md:text-5xl text-white font-bold leading-tight text-center md:text-left">
            Připoj se k letu na Mars
          </h1>
          <p class="leading-normal text-base md:text-2xl mb-8 text-center md:text-left">
            19.03. 2021 - 12:00
          </p>

          <form class="bg-gray-900 w-full shadow-lg rounded-lg px-8 pt-6 pb-8 mb-4">
            <div class="mb-4">
              <label class="block text-blue-300 py-2 font-bold mb-2" for="emailaddress">
                Staň se jedním ze šťastlivců a vyhraj letenku na Mars a dárkové předměty jako je obal na telefon, mikina či vzpomínková placka!
              </label>
            </div>
            <div class="mb-4">
              <label class="block text-blue-300 py-2 font-bold mb-2" for="emailaddress">
                Pošli SMS ve tvaru "CHC" na číslo +420 420 696969, soutěžící bude náhodně vybrán!
              </label>
            </div>

            
            
          </form>
        </div>

        <!--Right Col-->
        <div class="w-full xl:w-3/5 p-12 overflow-hidden">
          <iframe width="1120" height="630" src="https://www.youtube.com/embed/QEXnrBvj_e0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>

        <!--Footer-->
        <div class="w-full pt-16 pb-6 text-sm text-center md:text-left fade-in">
          <a class="text-gray-500 no-underline hover:no-underline" href="#">&copy; CHC letí na Mars - </a>
          made by mega frajeři - Veronika Gazdová, Adéla Ševčíková, Luka Budík, Jiří Michalec, Robert Goldmann, Filip Havlík, Matěj Höhl
        </div>
      </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "page",
  setup: () => {},
});
</script>

<style>
.telo {
    font-family: 'earthorbiter';
}
</style>
