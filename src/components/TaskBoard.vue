<template>
  <main>
    <section class="text-gray-600 body-font">
      <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
        <div
          class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center hero-text">
          <h1 class="title-font sm:text-5xl text-3xl mb-4 font-bold text-gray-900">Boom! school season is
            <br class="hidden lg:inline-block">back
          </h1>
          <p class="mb-8 leading-relaxed paragraph-text">They claim that nothing is insurmountable to learn. Learning to program is also
            not impossible. All we need is your dedication and time. Our platform will help you stay focused with lots of
            our features and curriculum</p>
          <div class="flex justify-center items-center enrol-btn">

            <a class="inline-block py-4 px-10 bg-btn text-md " href="#">
              Enroll Now
            </a>
            <a class="w-12 h-12 inline-flex items-center justify-center rounded-full bg-indigo-50 text-orange-500 mb-1 ml-8 enrol-btn"
              href="https">
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round"
                  d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.348a1.125 1.125 0 010 1.971l-11.54 6.347a1.125 1.125 0 01-1.667-.985V5.653z" />
              </svg>

            </a>
            <span class="items-center px-2">
              Play video
            </span>
          </div>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
          <img class="object-cover object-center rounded hero-image" alt="hero" src="../assets/boy.png">
        </div>
      </div>
    </section>



    <!-- component -->
    <div class="py-20 ">
      <div class="container mx-auto px-6 md:px-12 xl:px-32">
        <div class="mb-16 text-center">
          <div class="h-2 bg-gray-200 rounded overflow-hidden hr-line">
            <div class="w-16 h-full bg-orange-400"></div>
          </div>
          <h2 class="mb-4 text-center text-2xl text-gray-900 font-bold md:text-4xl py-8">Meet our Brilliant Students</h2>
          <p class="text-gray-600 lg:w-8/12 lg:mx-auto"> Meet our pupils who won the English and Mathematics competitions;
            we develop students who are eager to learn and provide them with opportunities to communicate what they have
            learned.

          </p>
        </div>

        <div class="grid gap-12 items-center md:grid-cols-3">
          <div class="space-y-4 text-center">
            <img class="w-64 h-64 mx-auto object-cover rounded-xl md:w-40 md:h-40 lg:w-64 lg:h-64" src="../assets/jas.png"
              alt="woman" loading="lazy" width="640" height="805">
            <div>
              <h4 class="text-2xl">Jessica Frednar</h4>
              <span class="block text-sm text-gray-500">Best in Spelling</span>
            </div>
          </div>
          <div class="space-y-4 text-center">
            <img class="w-64 h-64 mx-auto object-cover rounded-xl md:w-48 md:h-64 lg:w-64 lg:h-80" src="../assets/gib.png"
              alt="man" loading="lazy" width="1000" height="667">
            <div>
              <h4 class="text-2xl">Gibson Doe</h4>
              <span class="block text-sm text-gray-500">Best in Mathematics</span>
            </div>
          </div>
          <div class="space-y-4 text-center">
            <img class="w-64 h-64 mx-auto object-cover rounded-xl md:w-40 md:h-40 lg:w-64 lg:h-64" src="../assets/kar.png"
              alt="woman" loading="lazy" width="1000" height="667">
            <div>
              <h4 class="text-2xl">Anabelle Karen</h4>
              <span class="block text-sm text-gray-500">Best in English</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <section class="text-gray-600 body-font">
      <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 mb-10 md:mb-0">
          <img class="object-cover object-center " alt="hero" src="../assets/Group 1.png">
        </div>
        <div
          class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Enroll your Kids for
            <br class="hidden lg:inline-block"> Quality Education
          </h1>
          <p class="mb-8 leading-relaxed">Copper mug try-hard pitchfork pour-over freegan heirloom neutra air plant
            cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk tote bag selvage hot chicken authentic
            tumeric truffaut hexagon try-hard chambray.</p>
          <div class="flex justify-center">

            <a class="inline-block py-4 px-10 bg-btn text-md " href="#">
              Enroll Now
            </a>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="flex h-screen w-full  justify-center items-center">
        <img src="../assets/main-page.png" alt="hero">
      </div>
    </section>
  </main>
</template>
<script>
import gsap from "gsap";
// import { onMounted } from "vue";
export default {
  name: 'TaskBoard',
  mounted: function () {
    gsap.from('.hero-image', { duration: 3, scale: 2, ease: "bounce.out" });
    gsap.fromTo(
      ".hero-text",
      {
        opacity: 0,
        x: "-100%",
      },
      {
        duration: 1.8,
        opacity: 1,
        x: 0,
        ease: "power4.inOut",
        delay: 0.3,
      }
    );
    gsap.fromTo(
      ".enrol-btn",
      {
        y: "100%",
      },
      {
        duration: 1.5,
        opacity: 1,
        y: 0,
        delay: 1.5,
      }
    );
    
  

  }
}

</script>
<style>
.free-btn {
  background-color: white;
  border: 2px solid #1E1822;
  color: #1E1822;
}
</style>