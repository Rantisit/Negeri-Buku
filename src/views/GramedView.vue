<template>
    <div class="bg-orange-100 w-full sticky top-0 z-20 shadow">
      <div class="w-full lg:px-20 px-8 flex justify-between items-center">
        <a aria-current="page" href="/" class="router-link-active router-link-exact-active cursor-pointer">
          <img src="../assets/logo.png" alt="logo toko buku" class="w-32 h-auto"></a>
          <p class="text-lg font-bold text-left">Negeri Buku</p>
        <div class="text-dark gap-6 items-center justify-center text-sm lg:flex hidden">
          <a href="" class="cursor-pointer hover:opacity-50">Buku Fiksi</a>
          <a href="" class="cursor-pointer hover:opacity-50">Buku Non-Fiksi</a>
        </div>
        <div class="flex gap-10">
      <div class="cursor-pointer hover:opacity-50">
        <i class="bi bi-search"></i>
      </div>
      <a href="/cart" class="cursor-pointer hover:opacity-50 relative">
        <i class="bi bi-cart text-dark text-xl"></i><!----></a>
      </div>
      </div>
    </div>
   
    
    
    <section id="section-1" class="relative">
        <img src="../assets/background-main.jpg" alt="" class="w-full lg:h-auto h-[265px] object-fill">
        <div class="absolute z-10 w-full h-full top-1/4 lg:px-20 px-4">
            <div class="capitalize text-light text-xl lg:text-4xl tracking-wide leading-snug text-right text">
                <span class="font-bold">Temukan </span> 
                Keajaian<br> 
                <span class="font-bold">dalam </span>
                 Setiap <br> Halaman</div>
                 <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded text-right">
                Dapatkan Sekarang
                </button>
            </div>
    </section>

     <section id="section-2" class="lg:py-20 py-10 w-full bg-orange-200">
        <div class="w-full text-center text-xl text-dark"> Keuntungan Yang Kami Berikan </div>
        <div class="mt-6 lg:mt-12 w-full grid grid-cols-2 lg:flex gap-6 lg:gap-10 justify-between lg:px-20 px-4">
          <div class="bg-white py-6 lg:w-[287px] rounded flex flex-col gap-2 col-span-1 px-4">
            <div class="w-full text-center text-primary">
              <i class="bi bi-truck text-5xl"></i>
            </div>
            <div class="text-dark w-full text-center lg:text-lg">Kirim Sampai Rumah</div>
          </div>
          <div class="bg-white py-6 lg:w-[287px] rounded flex flex-col gap-2 col-span-1 px-4">
            <div class="w-full text-center text-primary">
              <i class="bi bi-person-check text-5xl"></i>
            </div>
            <div class="text-dark w-full text-center lg:text-lg">Pelanggan Puas</div>
          </div>
          <div class="bg-white py-6 lg:w-[287px] rounded flex flex-col gap-2 col-span-1 px-4">
            <div class="w-full text-center text-primary">
              <i class="bi bi-check2-circle text-5xl"></i>
            </div>
            <div class="text-dark w-full text-center lg:text-lg">Terjamin Hasilnya</div>
          </div>
          <div class="bg-white py-6 lg:w-[287px] rounded flex flex-col gap-2 col-span-1 px-4">
            <div class="w-full text-center text-primary">
              <i class="bi bi-shield-check text-5xl"></i>
            </div>
            <div class="text-dark w-full text-center lg:text-lg">Pembayaran Terpercaya</div>
          </div>
        </div>
    </section>

    <section id="section-2" class="py-16 lg:px-20 px-4 flex flex-col gap-10">
      <div class="w-full text-start text-xl text-dark"> Kategori Produk </div>
      <div class="w-[362px] md:w-full overflow-x-auto">
        <div class="flex w-full">
          <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-orange-200">Buku Fiksi</div>
          <div class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center bg-orange-100">Buku Non-Fiksi</div>
        </div>
      </div>
    </section>

    <section class="mx-24 my-20">
        <div class="text-2xl mb-10">Buku Fiksi</div>
        <!-- <div class="grid grid-cols-2 lg:grid-cols-5 gap-4"><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga1.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga2.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga3.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga4.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded hidden lg:block"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga5.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div></div> -->
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11  overflow-x-auto">
            <div>
                <img src="../assets/buku/buku1.jpg" alt="buku 1" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Azzamine
                        Sophi Aulia
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 106.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/buku/buku2.jpg" alt="buku 2" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Bumi dan Lukanya
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 80.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/buku/buku3.jpg" alt="buku 3" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Diary of Canva
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 85.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/buku/buku4.jpg" alt="buku 4" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Eccedentiast
                        Ita Krn
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 99.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/buku/buku5.jpg" alt="buku 5" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Laut Bercerita
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 92.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
    </section>

    <section class="mx-24 my-20">
        <div class="text-2xl mb-10">Buku Non-Fiksi</div>
        <!-- <div class="grid grid-cols-2 lg:grid-cols-5 gap-4"><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga1.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga2.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga3.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga4.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div><div data-v-6151ebec="" class="bg-accent3 rounded hidden lg:block"><div data-v-6151ebec="" class=""><img data-v-6151ebec="" alt="buket uang 1" class="w-full h-56 object-cover image-lazy pulse" lazy="loaded" src="/bungapapan/papanbunga5.png"></div><div data-v-6151ebec="" class="flex flex-col gap-1 mx-3 lg:mx-4 mb-4 mt-3"><div data-v-6151ebec="" class="text-dark text-sm font-medium">Bunga Papan</div><div data-v-6151ebec="" class="flex items-center gap-1"><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i><i data-v-6151ebec="" class="bi bi-star-fill text-xs text-secondary"></i></div><div data-v-6151ebec="" class="flex justify-between w-full items-center"><div data-v-6151ebec="" class="text-dark font-medium text-sm">Rp&nbsp;150.000</div><div data-v-6151ebec="" class="bg-primary w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-60"><i data-v-6151ebec="" class="bi bi-cart-plus text-lg text-white"></i></div></div></div></div></div> -->
        <div class="grid grid-rows-1 grid-flow-col gap-4 justify-between pb-11  overflow-x-auto">
            <div>
                <img src="../assets/book/book1.jpg" alt="book 1" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Melunasi Janji Kemerdekaan
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 79.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/book/book2.jpg" alt="book 2" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Bukan 350 Tahun di Jajah
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 135.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/book/book3.jpg" alt="book 3" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Dibalik Tragedi 1965
                        Sulastomo
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 195.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/book/book4.jpg" alt="book 4" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Tenggelamnya Kapal Van Der Wijck
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 279.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
            <div>
                <img src="../assets/book/book5.jpg" alt="book 5" class="w-52 h-52">
                <div class="bg-red-100 p-4">
                    <div class="mb-1">
                        Catatan Seorang Demonstran
                    </div>
                    <div class="flex items-center mb-1 space-x-1">
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                        <i class="bi bi-star-fill text-yellow-400"></i>
                    </div>
                    <div class="flex items-center justify-between">
                        Rp 36.000
                        <div class="bg-red-300 w-8 h-8 flex items-center justify-center rounded-full cursor-pointer hover:opacity-50">
                            <i class="bi bi-cart-plus text-lg text-white"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="text-center hover:opacity-50">
            <a href="#">Lihat Semuanya</a>
        </div>
    </section>    

    <section id="section-8" class="py-16 lg:px-20 px-4 flex flex-col gap-6">
        <div class="text-lg font-medium"> Toko Buku - Toko Buku Online Se Indonesia </div>
        <div> Temukan dunia pengetahuan, imajinasi, dan inspirasi dalam genggaman Anda di toko buku online kami. Dari karya sastra klasik hingga buku-buku terbaru dalam berbagai genre, kami menyediakan koleksi yang luas untuk memenuhi setiap minat baca dan kebutuhan pembaca.</div>
    </section>

<section class="py-16 lg:px-18 px-4 flex flex-col gap-6 bg-orange-200">
  <div class="w-full text-center text-xl text-dark mb-9">Testimoni Pelanggan</div>

  <div class="w-full text-dark flex flex-wrap justify-center gap-6  overflow-x-auto">
    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">tisaf</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">ehyipa</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">kangalu</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>

    <div class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
      <i class="bi bi-person-circle text-4xl"></i>
      <div class="text-lg font-semibold mt-4">yierli</div>
      <div class="text-sm mt-2 text-center">Lorem Ipsum Dolor Sit Amet</div>
    </div>
  </div>
</section>

    <section id="section-9" class="py-8 lg:py-16 px-4 lg:px-20 flex flex-col gap-10 bg-aboo">
        <div class="w-full text-start text-xl text-dark"> Metode Pembayaran </div><div class="flex gap-8">
            <div class="bg-orange-100 rounded p-8"><div>
                <img src="../assets/dana.png" alt="metode dana" class="w-24 h-auto"></div>
            </div>
            <div class="bg-orange-100 rounded p-8"><div>
                <img src="../assets/bca.png" alt="metode bca" class="w-24 h-auto"></div>
            </div>
        </div>
    </section>

    <section id="section-9" class="py-8 lg:py-16 px-4 lg:px-20 flex flex-col gap-10 bg-aboo">
        <div class="w-full text-start text-xl text-dark"> Pertanyaan Umum </div>
        <div class="flex flex-col gap-4">
            <div class="bg-orange-100 cursor-pointer p-4 flex flex-col gap-2">
                <div class="flex w-full justify-between items-center text-dark">
                    <div class="font-medium">Apakah saya dapat melakukan pengembalian jika saya tidak puas dengan pembelian saya?</div>
                    <div>
                        <i class="bi bi-chevron-down"></i>
                        </div>
                    </div><!---->
                </div>
                <div class="bg-orange-100 cursor-pointer p-4 flex flex-col gap-2">
                    <div class="flex w-full justify-between items-center text-dark">
                        <div class="font-medium">Apakah ada program loyalitas atau diskon untuk pelanggan tetap?</div>
                        <div>
                            <i class="bi bi-chevron-down"></i>
                        </div>
                    </div><!---->
                </div>
                <div class="bg-orange-100 cursor-pointer p-4 flex flex-col gap-2">
                    <div class="flex w-full justify-between items-center text-dark">
                        <div class="font-medium">Apakah Anda memiliki opsi hadiah atau pembungkusan khusus untuk hadiah?</div>
                        <div>
                            <i class="bi bi-chevron-down"></i>
                            </div>
                        </div><!---->
                    </div>
                <div class="bg-orange-100 cursor-pointer p-4 flex flex-col gap-2">
                <div class="flex w-full justify-between items-center text-dark">
                    <div class="font-medium">Apakah buku-buku yang dijual di toko online Anda baru atau bekas?</div>
                    <div>
                        <i class="bi bi-chevron-down"></i>
                    </div>
                </div><!---->
            </div>
        </div>
    </section>

    <footer>
        <div id="cta" class="bg-orange-100 py-12 w-full flex lg:flex-row flex-col gap-4 justify-between items-center px-4 lg:px-20">
            <div class="text-xl lg:text-2xl text-center lg:text-start font-medium text-dark leading-normal tracking-tighter"> Lebih Mudah Mengirim Hadiah dan <br> Bunga Untuk Orang Tercinta </div>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
                 Dapatkan Sekarang
            </button>
        </div>
            <div class="bg-primary w-full pt-16 pb-4 px-4 lg:px-20 flex flex-col items-center lg:items-start gap-12"><div>
                <img src="../assets/logo.png" alt="logo white toko buket" class="w-52 h-auto"></div>
            <div class="flex lg:flex-row flex-col lg:gap-0 gap-8 justify-center items-center lg:justify-between w-full lg:items-start">
                <div class="flex flex-col gap-4 text-black text-center lg:text-start">
                    <div class="font-medium lg:text-lg">Alamat</div>
                    <div class="text-sm lg:text-base">Bandung, Jawa Barat</div>
                </div>
                <div class="flex flex-col gap-4 text-black text-center lg:text-start">
                    <div class="font-medium lg:text-lg">Kategori Produk</div>
                    <div class="text-sm lg:text-base">Buku Fiksi</div>
                    <div class="text-sm lg:text-base">Buku Non-Fiksi</div>
                </div>
                <div class="flex flex-col gap-4 text-black text-center lg:text-start">
                    <div class="font-medium lg:text-lg">Kontak Kami</div>
                    <div class="text-sm lg:text-base">0804-343-543</div>
                    <div class="text-sm lg:text-base">@negeribuku.com</div>
                </div>
            </div>
        </div>
    </footer>
</template>
  