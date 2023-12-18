
<script>
    import Navbar from '../Navbar.svelte'; // Ajusta la ruta según tu estructura de carpetas
    import savvittp from '../images/savvittp.png';
  
    import { fly} from 'svelte/transition';

let showLogo = true;
let showContent = false;




setTimeout(() => {
  showLogo = false;
  showContent = true;
}, 1000);
</script>


<style>
    .logo {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      z-index: 1; /* Ensure the logo is above the content */
    }
  
    .content {
      opacity: 0;
      transition: opacity 0.5s; /* Add a smooth transition effect */
    }
  
    .content.visible {
      opacity: 1;
    }
  </style>
  
  {#if showLogo}
  
    <img class="logo" src={savvittp} alt="Logo"  transition:fly="{{y: 200, duration: 500}}" />
  {/if}
  
  {#if showContent}
  
 <!--  <Navbar /> -->  
    <div class="content visible">
       
      <!-- Your content goes here -->

      <div class="relative isolate overflow-hidden bg-gray-900 py-24 sm:py-32">
       <!-- <img src="https://www.purestorage.com/content/dam/purestorage/knowledge/what-is-a-rack-server.png.imgw.720.720.png" alt="Descripción de la imagen"  class="grayscale hover:grayscale-0 absolute inset-0 -z-10 h-full w-full object-cover object-right md:object-center" /> -->
        <div class="hidden sm:absolute sm:-top-10 sm:right-1/2 sm:-z-10 sm:mr-10 sm:block sm:transform-gpu sm:blur-3xl" aria-hidden="true">
          <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
        </div>
        <div class="absolute -top-52 left-1/2 -z-10 -translate-x-1/2 transform-gpu blur-3xl sm:top-[-28rem] sm:ml-16 sm:translate-x-0 sm:transform-gpu" aria-hidden="true">
          <div class="aspect-[1097/845] w-[68.5625rem] bg-gradient-to-tr from-[#ff4694] to-[#776fff] opacity-20" style="clip-path: polygon(74.1% 44.1%, 100% 61.6%, 97.5% 26.9%, 85.5% 0.1%, 80.7% 2%, 72.5% 32.5%, 60.2% 62.4%, 52.4% 68.1%, 47.5% 58.3%, 45.2% 34.5%, 27.5% 76.7%, 0.1% 64.9%, 17.9% 100%, 27.6% 76.8%, 76.1% 97.7%, 74.1% 44.1%)"></div>
        </div>
        <div class="mx-auto max-w-full px-6 lg:px-8">
          <img src="/savvitt.png" class="flex justify-center" alt="Descripción de la imagen"  />
          <div class="mx-auto mt-10 max-w-2xl lg:mx-0 lg:max-w-none">
            <dl class="mt-16 grid grid-cols-1 gap-4 sm:mt-20 sm:grid-cols-1 lg:grid-cols-7">
              <div class="flex flex-col-reverse">
                <dd class="text-2xl font-bold leading-9 tracking-tight text-white"><a href="/" >INICIO</a></dd>
              </div>

              <div class="flex flex-col-reverse">
                
                <dd class="text-2xl font-bold leading-9 tracking-tight text-white"><a href="/nosotros">NOSOTROS</a></dd>
              </div>

              <div class="flex flex-col-reverse col-span-2">
                <dd class="text-2xl font-bold leading-9 tracking-tight text-white whitespace-nowrap"><a href="/desarrollo" >DESARROLLO DE SOFTWARE</a></dd>
              </div>

              <div class="flex flex-col-reverse col-span-2">
              <dd class="text-2xl font-bold leading-9 tracking-tight text-white whitespace-nowrap"><a href="/sistemarespaldos">SISTEMA DE RESPALDOS</a></dd>
              </div>

              <div class="flex flex-col-reverse">
                <dd class="text-2xl font-bold leading-9 tracking-tight text-white"><a href="/contacto">CONTACTANOS</a></dd>
                </div>
            </dl>
          </div>
        </div>
      </div>
      
      
    </div>

  {/if}


