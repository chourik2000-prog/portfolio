<template>
  <div class="bg-gray-800">
      <div class="flex ml-16 px-12 grid gap-1">
        <span class="text-xl text-white">Salut, Je suis</span> <br>
        <span class="font-bold text-2xl text-white">Chourik FOUSSENI.</span> <br>
        <span class="text-xl text-gray-300">Je construis des choses pour le web.</span><br>
        <span class="text-sm text-gray-300">
            Je suis un ingénieur logiciel spécialisé dans la création <br> de <span class="font-bold text-lg">site web</span> et 
            de <span class="font-bold text-lg">gestion de base de donnée</span>.
        </span>
      </div>
    <!-- <div class="flex mt-2 justify-center text-white">
      <button 
        class="brightness-200 h-10 w-40 shadow-lg shadow-cyan-500/50
        rounded-l-lg animate-spin">
        Voir mon parcours
      </button>
    </div> -->
    <div class="flex flex-row mt-12">
      <h2 class="flex flex-row font-bold text-lg opacity-50 mt-12 mr-4 text-green-600">01.A Propos</h2>
      <h4 class="w-1/2 text-justify mt-2 text-sm text-white">
          En cliquant sur "Tout accepter", vous acceptez 
          que le Groupe Furet du nord-Decitre traite vos données
          personnelles stockées sur votre appareil et accède à vos
          données afin d'améliorer la navigation sur le site,
          personnaliser votre expérience selon vos centres d'intérêt,
          assurer une navigation en toute sécurité et établir des statistiques 
          de fréquentation et de navigation. Vous pouvez changer d'avis en 
          paramétrant vos cookies depuis la rubrique "Paramètres des cookies".
      </h4>
      <div class="flex pl-12 w-1/2 gap-4">
          <img class="brightness-20 shadow-lg shadow-cyan-500/50 w-40 h-40
            rounded-l-lg border-1 border-indigo-600" src="@/assets/image/femme1.jpg" alt="logo de tailwind">
          <img class="brightness-20 shadow-lg shadow-cyan-500/50 w-40 h-40
            rounded-l-lg border-1 border-indigo-600" src="@/assets/image/femme2.jpg" alt="logo de tailwind">
      </div>
    </div>
    <div class="flex flex-row mt-12">
      <h2 class="flex flex-row font-bold text-lg opacity-50 mt-14 mr-4 text-green-600">02.Expérience</h2>
      <h4 class="w-1/3 text-justify mt-2 text-sm text-white">
          En cliquant sur "Tout accepter", vous acceptez 
          que le Groupe Furet du nord-Decitre traite vos données
          personnelles stockées sur votre appareil et accède à vos
          données afin d'améliorer la navigation sur le site,
          personnaliser votre expérience selon vos centres d'intérêt,
          assurer une navigation en toute sécurité et établir des statistiques 
          de fréquentation et de navigation. Vous pouvez changer d'avis en 
          paramétrant vos cookies depuis la rubrique "Paramètres des cookies".
      </h4>
    </div>
    <div class="flex row-full mt-12 ">
      <h2 class="font-bold text-lg opacity-50 mt-14 mr-4 text-green-600">03.Projet</h2>
      <div class="pl-12">
          <img class="brightness-20 shadow-lg shadow-cyan-500/50 w-85 h-60
            rounded-l-lg border-1 border-indigo-600" src="@/assets/image/code5.jpg" alt="logo de code">
      </div>
      <div class="brightness-20 basis-1/3 p-4 shadow-lg shadow-cyan-500/50 rounded-l-lg border-1 border-indigo-600"> 
          <p class="text-justify mt-2 text-sm text-white">
            personnaliser votre expérience selon vos centres d'intérêt,
            assurer une navigation en toute sécurité et établir des statistiques
            de fréquentation et de navigation.Vous pouvez changer d'avis en
            paramétrant vos cookies depuis la rubrique "Paramètres des cookies".
          </p>
      </div>
    </div>
    <div class="flex mt-8 ml-8">
      <div class="max-w-sm rounded bg-teal-900 overflow-hidden ml-12 shadow-lg">
        <div class="px-6 py-4">
          <div class="font-bold text-xl opacity-50 mb-2 text-white">aidedon</div>
          <p class="text-base text-white">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">laravel</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">tailwindcss</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">PHP</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">css</span>
        </div>
      </div>
      <div class="max-w-sm bg-teal-900 rounded overflow-hidden ml-6 shadow-lg">
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2 opacity-50 text-white">iaigestion</div>
          <p class="text-base text-white">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia, nulla! Maiores et perferendis eaque, exercitationem praesentium nihil.
          </p>
        </div>
        <div class="px-6 pt-4 pb-2">
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">html</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">github</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">SQL</span>
          <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700 mr-2 mb-2">Bootstrap</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default
{
  layout: "default",
}

</script>
