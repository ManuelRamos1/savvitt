<script>
    import Navbar from "../../Navbar.svelte";
    import synologyBanner from '../../images/synologybanner.png';

    import savvittp from '../../images/savvittp.png';
    import Footer from "../../footer.svelte";

 
</script>

<Navbar/>

<div class="overflow-hidden bg-white py-24 sm:py-32">
    <div class="mx-auto max-w-7xl px-6 lg:px-8">
      <div class="mx-auto grid max-w-2xl grid-cols-1 gap-x-8 gap-y-16 sm:gap-y-20 lg:mx-0 lg:max-w-none lg:grid-cols-2">
        <div class="lg:pr-8 lg:pt-4">
          <div class="lg:max-w-lg">
            <!-- <h2 class="text-base font-semibold leading-7 text-indigo-600">Deploy faster</h2> -->
            <p style="color: #6800EF;" class="mt-2 text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Protege los datos criticos de tu empresa o negocio</p>
            <p class="mt-6 text-lg leading-8 text-gray-600"> Somos tu aliado confiable en respaldos integrales de datos. Ofrecemos servicios y hardware avanzados para asegurar la seguridad y disponibilidad de tus datos críticos, ya sea en entornos personales, comerciales o empresariales.</p>
            <dl class="mt-10 max-w-xl space-y-8 text-base leading-7 text-gray-600 lg:max-w-none">
              <div class="relative pl-9">
                <dt class="inline font-semibold text-gray-900">
                  <svg class="absolute left-1 top-1 h-5 w-5 text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path fill-rule="evenodd" d="M5.5 17a4.5 4.5 0 01-1.44-8.765 4.5 4.5 0 018.302-3.046 3.5 3.5 0 014.504 4.272A4 4 0 0115 17H5.5zm3.75-2.75a.75.75 0 001.5 0V9.66l1.95 2.1a.75.75 0 101.1-1.02l-3.25-3.5a.75.75 0 00-1.1 0l-3.25 3.5a.75.75 0 101.1 1.02l1.95-2.1v4.59z" clip-rule="evenodd" />
                  </svg>
                 <b style="color: #6800EF;">Respaldo Automatizado:</b> 
                </dt>
                <dd class="inline">Implementamos soluciones avanzadas que automatizan el proceso de respaldo, asegurando que tus datos estén protegidos de manera constante y sin intervención manual.</dd>
              </div>
              <div class="relative pl-9">
                <dt class="inline font-semibold text-gray-900">
                  <svg class="absolute left-1 top-1 h-5 w-5 text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path fill-rule="evenodd" d="M10 1a4.5 4.5 0 00-4.5 4.5V9H5a2 2 0 00-2 2v6a2 2 0 002 2h10a2 2 0 002-2v-6a2 2 0 00-2-2h-.5V5.5A4.5 4.5 0 0010 1zm3 8V5.5a3 3 0 10-6 0V9h6z" clip-rule="evenodd" />
                  </svg>
                  <b style="color: #6800EF;"> Recuperación Rápida:</b> 
            
                </dt>
                <dd class="inline">En caso de pérdida de datos, garantizamos una recuperación rápida y eficiente para minimizar el tiempo de inactividad y proteger tu continuidad operativa.</dd>
              </div>
              <div class="relative pl-9">
                <dt class="inline font-semibold text-gray-900">
                  <svg class="absolute left-1 top-1 h-5 w-5 text-indigo-600" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                    <path d="M4.632 3.533A2 2 0 016.577 2h6.846a2 2 0 011.945 1.533l1.976 8.234A3.489 3.489 0 0016 11.5H4c-.476 0-.93.095-1.344.267l1.976-8.234z" />
                    <path fill-rule="evenodd" d="M4 13a2 2 0 100 4h12a2 2 0 100-4H4zm11.24 2a.75.75 0 01.75-.75H16a.75.75 0 01.75.75v.01a.75.75 0 01-.75.75h-.01a.75.75 0 01-.75-.75V15zm-2.25-.75a.75.75 0 00-.75.75v.01c0 .414.336.75.75.75H13a.75.75 0 00.75-.75V15a.75.75 0 00-.75-.75h-.01z" clip-rule="evenodd" />
                  </svg>

                  <b style="color: #6800EF;">Hardware Confiable:</b> 
           
                </dt>
                <dd class="inline">Trabajamos con los principales fabricantes de hardware para ofrecer productos de calidad y confianza que cumplen con los estándares más exigentes de la industria.</dd>
              </div>
            </dl>
          </div>
        </div>
        <img src={savvittp} alt="Product screenshot" class="" width="2432" height="1442">
      </div>
    </div>
    <br>
    <img alt="The project logo" src={synologyBanner} />
  </div>
  






<div class="bg-white py-24 sm:py-32">
  <div class="mx-auto max-w-7xl px-6 lg:px-8">
    <dl class="grid grid-cols-1 gap-x-8 gap-y-16 text-center lg:grid-cols-3">
      <div class="mx-auto flex max-w-xs flex-col gap-y-4">
        <dt class="text-base leading-7 text-gray-600">Ataques de ransomware en todo el mundo en 2023</dt>
        <dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">+ 400,000</dd>
      </div>
      <div class="mx-auto flex max-w-xs flex-col gap-y-4">
        <dt class="text-base leading-7 text-gray-600">Empresas que sufrieron un ataque y pagaron el rescate en 2023 </dt>
        <dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl">+ 41% </dd>
      </div>
      <div class="mx-auto flex max-w-xs flex-col gap-y-4">
        <dt class="text-base leading-7 text-gray-600">Mas de 20 mil millones en pagos de rescate de ramsomware en 2023</dt>
        <dd class="order-first text-3xl font-semibold tracking-tight text-gray-900 sm:text-5xl"> + 20,000 M</dd>
      </div>
    </dl>
  </div>
</div>



<br>

<button type="button" class="text-white bg-gradient-to-br from-purple-600 to-blue-500 hover:bg-gradient-to-bl focus:ring-4 focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2">Purple to Blue</button>

<button class="transition ease-in-out delay-150 bg-blue-500 hover:-translate-y-1 hover:scale-110 hover:bg-indigo-500 duration-300 ...">
  Save Changes
</button>
<br>







<div class="bg-white">
  <div class="mx-auto grid max-w-2xl grid-cols-1 items-center gap-x-8 gap-y-16 px-4 py-24 sm:px-6 sm:py-32 lg:max-w-7xl lg:grid-cols-2 lg:px-8">
    <div>
      <h2 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">Technical Specifications</h2>
      <p class="mt-4 text-gray-500">The walnut wood card tray is precision milled to perfectly fit a stack of Focus cards. The powder coated steel divider separates active cards from new ones, or can be used to archive important task lists.</p>

      <dl class="mt-16 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 sm:gap-y-16 lg:gap-x-8">
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Origin</dt>
          <dd class="mt-2 text-sm text-gray-500">Designed by Good Goods, Inc.</dd>
        </div>
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Material</dt>
          <dd class="mt-2 text-sm text-gray-500">Solid walnut base with rare earth magnets and powder coated steel card cover</dd>
        </div>
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Dimensions</dt>
          <dd class="mt-2 text-sm text-gray-500">6.25&quot; x 3.55&quot; x 1.15&quot;</dd>
        </div>
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Finish</dt>
          <dd class="mt-2 text-sm text-gray-500">Hand sanded and finished with natural oil</dd>
        </div>
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Includes</dt>
          <dd class="mt-2 text-sm text-gray-500">Wood card tray and 3 refill packs</dd>
        </div>
        <div class="border-t border-gray-200 pt-4">
          <dt class="font-medium text-gray-900">Considerations</dt>
          <dd class="mt-2 text-sm text-gray-500">Made from natural materials. Grain and color vary with each item.</dd>
        </div>
      </dl>
    </div>
    <div class="grid grid-cols-2 grid-rows-2 gap-4 sm:gap-6 lg:gap-8">
      <img src="https://tailwindui.com/img/ecommerce-images/product-feature-03-detail-01.jpg" alt="Walnut card tray with white powder coated steel divider and 3 punchout holes." class="rounded-lg bg-gray-100">
      <img src="https://tailwindui.com/img/ecommerce-images/product-feature-03-detail-02.jpg" alt="Top down view of walnut card tray with embedded magnets and card groove." class="rounded-lg bg-gray-100">
      <img src="https://tailwindui.com/img/ecommerce-images/product-feature-03-detail-03.jpg" alt="Side of walnut card tray with card groove and recessed card area." class="rounded-lg bg-gray-100">
      <img src="https://tailwindui.com/img/ecommerce-images/product-feature-03-detail-04.jpg" alt="Walnut card tray filled with cards and card angled in dedicated groove." class="rounded-lg bg-gray-100">
    </div>
  </div>
</div>












<Footer/>






  
  
  