<!-- Please remove this file from your project -->
<template>
  <main class="relative flex min-h-screen flex-col">
    <div>
      <div class="wrapper max-w-screen overflow-x-hidden">
        <div class="relative min-h-screen z-20 bg-black">
          <div class="w-screen overflow-hidden">
            <div
              class="-z-10 pointer-events-none overflow-hidden relative h-[216vw] max-h-[800px] md:max-h-full md:h-[80vw] w-screen overflow-hidden after:h-[25vh] bg-bottom-fade">
              <div class="absolute w-full h-full animate-fade-up">
                <img class="duration-500 opacity-1 absolute w-full h-full object-cover object-top object-cover"
                  src="../assets/images/1_Map_002.webp" loading="lazy" aria-hidden="true" style=" animation-delay: 0ms;"
                  alt="Background image" />
              </div>
            </div>
          </div>
          <section class="standard-wrapper flex h-auto w-full flex-col items-center z-20 relative -mt-36">
            <div
              class="px-4 py-3 rounded-md bg-white/10 block font-cta text-[13px] tracking-[0.15em] mb-8 uppercase backdrop-blur-md">
              BREAK ON THROUGH
            </div>
            <div
              class="intro-h1 headline-1 mt-0 flex w-full items-center justify-center leading-[0.8] lg:mt-10 sm:h-[140px] md:pb-2 animate-scale-down">
              <div class="markdown" style="animation-delay: 0ms;">
                <h1><strong>ENTER</strong> <em><strong>the</strong></em><strong>OTHERSIDE</strong></h1>
              </div>
            </div>
            <div class="flex flex-col items-center text-left intro-p mt-10 md:mt-16 animate-fade-up">
              <div class="text-justify text-gray-medium" style="max-width: 500px;  animation-delay: 0ms;">
                <div class="markdown">
                  <p>You got here just in time.</p>
                  <p>Otherside is a gamified, interoperable metaverse currently under development. The game blends
                    mechanics from massively multiplayer online role playing games (MMORPGs) and web3-enabled virtual
                    worlds. Think of it as a metaRPG where the players own the world, your NFTs can become playable
                    characters, and thousands can play together in real time.</p>
                </div>
              </div>
            </div>
          </section>
          <PRODUCTVERTICALS />

        </div>
      </div>
    </div>

  </main>
</template>

<script>
export default {
  name: 'NuxtTutorial'
}
</script>
