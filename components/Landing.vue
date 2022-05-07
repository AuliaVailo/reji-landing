<!-- Please remove this file from your project -->
<template>
  <div id="landing">
    <!-- Menu Section -->
    <div class="relative bg-white overflow-hidden">
      <div class="max-w-7xl mx-auto">
        <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
          <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
            <polygon points="50,0 100,0 50,100 0,100" />
          </svg>

          <div>
            <Menu/>
          </div>

          <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28" id="home">
            <div class="sm:text-center lg:text-left">
              <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
                <span class="block xl:inline">Reji POS</span>
                <span class="block text-indigo-600 xl:inline">Aplikasi Kasir Untuk Semuanya</span>
              </h1>
              <p class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">Mudah mencatat transaksi penjualan Anda.</p>
              <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
                <div class="rounded-md shadow">
                  <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 md:py-4 md:text-lg md:px-10"> Get started </a>
                </div>
                <!-- <div class="mt-3 sm:mt-0 sm:ml-3">
                  <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-md text-indigo-700 bg-indigo-100 hover:bg-indigo-200 md:py-4 md:text-lg md:px-10"> Live demo </a>
                </div> -->
              </div>
            </div>
          </main>
        </div>
      </div>
      <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
        <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="../assets/images/home.jpeg" alt="">
      </div>
    </div>

    <!-- Pricing -->
    <div class=" bg-gray-50" id="pricing">
        <div class="container mx-auto px-4 py-10">
            <header class="text-center mb-16">
                <h1 class="text-5xl mb-4">Harga Berlangganan</h1>
                <p class="leading-normal text-grey-dark md:w-1/2 md:mx-auto">Nikmati harga berlangganan terbaik untuk menggunakan Reji di usahamu.</p>
            </header>

            <div class="lg:flex lg:items-center lg:-mx-2 justify-center">
                <div class="mb-4 lg:mb-0 lg:w-1/3 lg:px-2">
                    <div
                        class="text-center border border-grey-light p-10 rounded lg:py-16 lg:shadow-lg">
                        <h2 class="text-lg mb-4">Free</h2>
                        <div class="mb-6">
                            <span class="block text-4xl pb-2">Rp. 0</span>
                            <span class="text-sm text-grey">Setiap Bulan</span>
                        </div>
                        <ul class="text-grey leading-loose list-reset mb-6">
                            <li>10 Produk Terkelola</li>
                            <li>Share Resi/Bukti Transaksi</li>
                            <li>Cetak Ke Bluethooth Printer</li>
                            <li>Iklan Di Applikasi</li>
                        </ul>
                        <a class="text-sm tracking-wide uppercase inline-block border border-red text-red bg-indigo-600 lg:border-none lg:bg-red lg:hover:bg-red-dark text-white font-bold w-full p-3 rounded no-underline"
                            href="#">Mulai Sekarang</a>
                    </div>
                </div>
                <div class="mb-4 lg:mb-0 lg:w-1/3 lg:px-2">
                    <div
                        class="text-center border border-grey-light p-10 rounded">
                        <h2 class="text-lg mb-4">PRO</h2>
                        <div class="mb-6">
                            <span class="block text-4xl pb-2">Rp. 500.000</span>
                            <span class="text-sm text-grey">Setiap Bulan</span>
                        </div>
                        <ul class="text-grey leading-loose list-reset mb-6">
                            <li>Produk Terkelola Tidak Terbatas</li>
                            <li>Share Resi/Bukti Transaksi</li>
                            <li>Cetak Ke Bluethooth Printer</li>
                            <li>Aplikasi Tanpa Iklan</li>
                        </ul>
                        <a class="text-sm tracking-wide uppercase inline-block bg-white border border-indigo-600 text-indigo-600 font-bold w-full p-3 rounded no-underline"
                            href="#">Segera Hadir</a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <Footer/>
  </div>
</template>
<script>
export default {

}
</script>
