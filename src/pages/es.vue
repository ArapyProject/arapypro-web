<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col sm:flex-row justify-between py-16">
      <div class="text-4xl font-bold w-full sm:w-3/5 text-center sm:text-left">
        <div class="leading-tight">Bienvenido al</div>
        <div class="text-yellow-700 leading-tight">Programa de Desarrollo Blockchain</div>
      </div>
      <div class="mt-8 sm:mt-0">
        <g-image src="../../static/connected_world.svg" alt="hero" class="mx-auto sm:mx-0" />
      </div>
    </div>
    <!-- end hero -->

    <div class="container-inner mx-auto">
      <p
        class="text-lg sm:text-xl"
      >Estamos en proceso de desarrollo y pre-lanzamiento de la moneda/token AgoraCash en fecha 13/06/2020, una criptomoneda/token para los agoristas latinoamericanos. Nos encontramos trabajando en los servicios que van a formar parte del ecosistema de AgoraCash, por ello, en lugar de lanzar una ICO más pensamos que sería buena idea recaudar fondos mediante el Programa de Desarrollo Blockchain.</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/version_control.svg" alt="Development" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/nakamoto.svg" alt="Blockchain" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div
        class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative"
      >
        <h2
          class="font-bold mb-6"
          id="program"
        >El programa está dividido en bloques basados en proyectos en los cuales usted aprenderá paso a paso:</h2>
        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>Entorno de desarrollo:</div>
            <div
              class="text-lg text-gray-600"
            >Instalación y configuración de las herramientas y tecnologías a ser utilizadas durante el programa (Git, Github, VirtualBox, Ubuntu, Visual Studio Code, Truffle, Ganache, Metamask, Node.Js, NPM, servidores VPS, Unity, etc)</div>
          </li>
          <li class="checkmark mb-6">
            <div>Forking:</div>
            <div
              class="text-lg text-gray-600"
            >Cómo clonar criptomonedas con distintos algoritmos (Scrypt/X11/NeoScrypt/Cryptonight/tokens ERC-20), wallets, block explorers, nodos, masternodes, sentinels.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Fundamentos de Programación:</div>
            <div
              class="text-lg text-gray-600"
            >Desarrollo Full stack con JavaScript (Node.js, React, etc) para crear una blockchain de prueba desde cero.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Smart contracts:</div>
            <div
              class="text-lg text-gray-600"
            >Desarrollo de smart contracts en la blockchain de Ethereum utilizando el lenguaje de programación Solidity. (token, token sale, ballot, eCommerce, plataforma de Crowdfunding y Exchanges decentralizados).</div>
          </li>
          <li class="checkmark mb-6">
            <div>Requisitos:</div>
            <div
              class="text-lg text-gray-600"
            >No se necesitan conocimientos previos de blockchain, criptomonedas, programación, línea de comandos, Linux, servidores. Todas las lecciones van a ser desarrolladas desde cero.</div>
          </li>
        </ul>
      </div>
      <!-- end projects -->
    </div>

    <div class="container-inner mx-auto">
      <p
        class="text-lg sm:text-xl"
      >Aprenda a desarrollar soluciones Blockchain Full Stack. Este no es un curso de "Sólo Smart contracts". Aprenda a crear y lanzar 4 criptomonedas diferentes usando como base Litecoin, Dash, Monero y los ERC20 token.</p>

      <div class="flex justify-between items-center py-6">
        <div class="w-full sm:w-1/2 px-8 py-8 sm:py-0">
          <g-image src="../../static/building_blocks.svg" alt="learning blocks" />
        </div>
        <div class="w-1/2 px-8 hidden sm:flex justify-end">
          <g-image src="../../static/maker.svg" alt="blockchain solutions" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div
        class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative"
      >
        <h2
          class="font-bold mb-6"
          id="enroll"
        >Regístrese ahora y conviértase en un Desarrollador Blockchain Full Stack!</h2>
        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>

        <ul class="text-lg sm:text-xl">
          <li class="checkmark mb-6">
            <div>Acceso a todos los Bloques de Aprendizaje</div>
          </li>
          <li class="checkmark mb-6">
            <div>4 Proyectos terminados y listos para lanzamiento</div>
          </li>
          <li class="checkmark mb-6">
            <div>Laboratorio con 3 VPS incluidos para realizar las pruebas de los proyectos</div>
          </li>
          <li class="checkmark mb-6">
            <div>Tokenomics: 50% de los tokens AgoraCash (AGOX) serán distribuidos entre los participantes del programa</div>
          </li>
          <li class="checkmark mb-6">
            <div>Inicio: 13/03/2020</div>
          </li>
          <li class="checkmark mb-6">
            <div>Duración: 12 semanas</div>
          </li>
          <li class="checkmark mb-6">
            <div>Costo: U$D 120.00 (Marzo)</div>
          </li>
          <li class="checkmark mb-6">
            <div>Costo: U$D 60.00 (Febrero)</div>
          </li>
          <li class="checkmark mb-6">
            <div>Aceptamos criptomonedas: BTC, ETH, LTC, DASH, XMR, DOGE, EOS, TRX, NEO.</div>
          </li>
          <li class="checkmark mb-6">
            <div>No Aceptamos: Tarjetas de Crédito, transferencias bancarias, Paypal y otros métodos de pago centralizados.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Participe del Programa haciendo click en el botón de abajo, será redirigido al procesador de pagos CoinPayments para finalizar la inscripción.</div>
          </li>
          <li class="checkmark mb-6">
            <div>Una vez realizado el pago usted recibirá un mail de confirmación con los detalles de acceso a nuestro LMS.</div>
          </li>
          <li>
            <div>
              <form action="https://www.coinpayments.net/index.php" method="post">
                <input type="hidden" name="cmd" value="_pay_simple" />
                <input type="hidden" name="reset" value="1" />
                <input type="hidden" name="merchant" value="96b59fa673a4948629f4c90b0c168c71" />
                <input type="hidden" name="item_name" value="Programa de Desarrollo Blockchain" />
                <input type="hidden" name="currency" value="USD" />
                <input type="hidden" name="amountf" value="60.00000000" />
                <input type="hidden" name="want_shipping" value="0" />
                <input type="hidden" name="success_url" value="https://www.arapy.pro/success" />
                <input type="hidden" name="cancel_url" value="https://www.arapy.pro" />
                <input
                  type="image"
                  src="https://www.coinpayments.net/images/pub/buynow.png"
                  alt="Buy Now with CoinPayments.net"
                />
              </form>
            </div>
          </li>
        </ul>
      </div>
      <!-- end program -->
    </div>
    <!-- Soon Youtube presentation will go here 
    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" />
          </svg>
        </div>
    
        <div class="responsive-container">
          <iframe
            class="responsive-iframe w-full h-full top-0 left-0 border-0"
            src="https://www.youtube.com/embed/uHo6o1TNQeE"
            style="border:0;"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
      
    </div>
    -->
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Home"
  }
};
</script>