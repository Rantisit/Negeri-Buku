<template>
    <nav class="bg-orange-100 py-4 sticky top-0 z-20 shadow">
  <div class="container mx-auto flex justify-between items-center">
    <!-- Logo -->
    <img src="../assets/logo.png" alt="logo toko buku" class="w-32 h-auto">
    <div class="text-black text-xl font-semibold">Negeri Buku</div>

    <!-- Navigation Links -->
    <div class="ml-10 flex items-baseline space-x-4">
        <a href="#" class="text-black py-2 rounded-md text-sm font-medium">Fiksi</a>
        <a href="#" class="text-black py-2 rounded-md text-sm font-medium">Non-Fiksi</a>
        <a href="#" class="text-black py-2 rounded-md text-sm font-medium">Kamus</a>
        <a href="#" class="text-black py-2 rounded-md text-sm font-medium">Biografi</a>
        <a href="#" class="text-black py-2 rounded-md text-sm font-medium">Ensiklopedia</a>
    </div>


    <div class="flex gap-10">
      <a href="/all" class="cursor-pointer hover:opacity-50">
        <i class="bi bi-search"></i>
      </a>
      <a href="/cart" class="cursor-pointer hover:opacity-50 relative">
        <i class="bi bi-cart-dash"></i>
      </a>
    </div>
  </div>
</nav>

<section class="relative">
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
    <section class="lg:py-20 py-10 w-full bg-orange-100">
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
              <i class="bi bi-check2-circle"></i>
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
    <section class="py-16 lg:px-20 px-4 flex flex-col gap-10" id="kategori-produk">
    <div class="w-full text-start text-xl text-dark">Kategori Produk</div>
    <div class="w-[362px] md:w-full overflow-x-auto">
      <div class="flex w-full">
        <div v-for="(category, index) in categories" :key="index" class="w-full p-8 cursor-pointer hover:opacity-50 lg:h-36 flex justify-center items-center" :class="category.color">{{ category.name }}</div>
      </div>
    </div>
    </section>
    <section v-for="(book, index) in books" :key="index" class="py-8 lg:py-16 lg:px-20 px-4 flex flex-col gap-10 overflow-auto">
      <div class="text-center w-full text-xl text-dark">{{ book.name }}</div>
      <div class="grid grid-cols-2 lg:grid-cols-5 gap-4">
        <div v-for="(product, index) in book.products" :key="index" :class="{'hidden lg:block': index === 4}">
          <img :src="product.image" :alt="product.name" class="cursor-pointer hover:opacity-70 w-full h-56 object-cover">
          <div class="bg-orange-100 w-full p-4">
            <div class="mb-1">{{ product.name }}</div>
            <div class="flex items-center mb-1 space-x-1">
              <i v-for="i in 5" :key="i" class="bi bi-star-fill text-yellow-400"></i>
            </div>
            <div class="flex items-center justify-between">{{ product.price }}
              <div class="bg-orange-200 w-8 h-8 flex items-center justify-center rounded-full hover:opacity-50">
                <i class="bi bi-cart-plus text-lg text-white"></i>
              </div>
            </div>
          </div>
        </div>
      </div><div class="text-center hover:opacity-50"><a href="/">See All Product</a></div>
    </section>
    <section class="py-16 lg:px-20 px-4 flex flex-col gap-6">
        <div class="text-lg font-medium"> Toko Buku - Toko Buku Online Se Indonesia </div>
        <div> Temukan dunia pengetahuan, imajinasi, dan inspirasi dalam genggaman Anda di toko buku online kami. Dari karya sastra klasik hingga buku-buku terbaru dalam berbagai genre, kami menyediakan koleksi yang luas untuk memenuhi setiap minat baca dan kebutuhan pembaca.</div>
    </section>
    <section class="py-16 lg:px-18 px-4 flex flex-col gap-6 bg-orange-200">
    <div class="w-full text-center text-xl text-dark mb-9">Testimoni Pelanggan</div>

    <div class="w-full text-dark flex flex-wrap justify-center gap-6  overflow-x-auto">
      <div v-for="(testimonial, index) in testimonials" :key="index" class="w-full sm:w-72 h-auto bg-yellow-50 text-black flex flex-col justify-center items-center rounded-lg px-8 py-4">
        <i class="bi bi-person-circle text-4xl"></i>
        <div class="text-lg font-semibold mt-4">{{ testimonial.name }}</div>
        <div class="text-sm mt-2 text-center">{{ testimonial.comment }}</div>
      </div>
    </div>
  </section>
    <section class="py-8 lg:py-16 px-4 lg:px-20 flex flex-col gap-10 bg-aboo">
        <div class="w-full text-start text-xl text-dark"> Metode Pembayaran </div><div class="flex gap-8">
            <div class="bg-orange-100 rounded p-8"><div>
                <img src="../assets/dana.png" alt="metode dana" class="w-24 h-auto"></div>
            </div>
            <div class="bg-orange-100 rounded p-8"><div>
                <img src="../assets/bca.png" alt="metode bca" class="w-24 h-auto"></div>
            </div>
        </div>
    </section>
    <section class="mx-24 my-20">
    <div class="text-2xl mb-10">Pertanyaan Umum</div>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
        <div class="bg-orange-200 p-6 rounded-lg">
            <div class="text-lg font-semibold mb-2">Apakah toko ini menyediakan pengiriman internasional?</div>
            <p class="text-black">Ya, kami menyediakan layanan pengiriman internasional. Silakan pilih opsi pengiriman internasional saat checkout, dan pastikan untuk memeriksa informasi pengiriman dan biaya yang terkait sebelum menyelesaikan pembelian.</p>
        </div>
        <div class="bg-orange-200 p-6 rounded-lg">
            <div class="text-lg font-semibold mb-2">Apakah produk yang dibeli dapat dikembalikan jika tidak sesuai?</div>
            <p class="text-black">Ya, kami menerima pengembalian produk jika tidak sesuai dengan ekspektasi Anda. Anda dapat mengembalikan produk dalam jangka waktu tertentu setelah pembelian. Namun, pastikan untuk membaca kebijakan pengembalian kami untuk memahami syarat dan ketentuan yang berlaku.</p>
        </div>
        <div class="bg-orange-100 p-6 rounded-lg">
            <div class="text-lg font-semibold mb-2">Apakah ada potongan harga untuk pembelian dalam jumlah besar?</div>
            <p class="text-black">Kami menyediakan program diskon khusus untuk pembelian dalam jumlah besar atau untuk pelanggan korporat. Silakan hubungi tim layanan pelanggan kami untuk informasi lebih lanjut tentang diskon volume dan penawaran khusus lainnya.</p>
        </div>
        <div class="bg-orange-100 p-6 rounded-lg">
            <div class="text-lg font-semibold mb-2">Apakah ada program keanggotaan atau diskon khusus untuk pelanggan setia?</div>
            <p class="text-black">Ya, kami memiliki program keanggotaan dan penawaran khusus untuk pelanggan setia. Dengan mendaftar sebagai anggota, Anda dapat memperoleh manfaat seperti diskon, penawaran eksklusif, dan penghargaan lainnya. Daftar sekarang dan nikmati keuntungannya!</p>
        </div>
    </div>
    </section>
    <footer class="bg-orange-100 text-black py-12">
    <div class="container mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            <!-- Tentang Kami -->
            <div>
            <div class="flex items-center mb-6">
                <img src="../assets/logo.png" alt="Logo Toko Buku" class="h-8 w-8 mr-2">
                <h3 class="text-xl font-semibold">Negeri Buku</h3>
            </div>
            </div>
            <!-- Navigasi Cepat -->
            <div>
                <h3 class="text-xl font-semibold mb-4">Produk</h3>
                <ul>
                    <li><a href="#" class="hover:text-gray-300">Fiksi</a></li>
                    <li><a href="#" class="hover:text-gray-300">Non-Fiksi</a></li>
                    <li><a href="#" class="hover:text-gray-300">Kamus</a></li>
                    <li><a href="#" class="hover:text-gray-300">Biografi</a></li>
                    <li><a href="#" class="hover:text-gray-300">Non-Fiksi</a></li>
                </ul>
            </div>
            <!-- Ikuti Kami -->
            <div>
    <h3 class="text-xl font-semibold mb-4">Ikuti Kami</h3>
    <ul class="flex space-x-4">
        <li>
            <a href="#" class="hover:text-gray-300">
                <i class="fab fa-facebook-f"></i>
                <span class="ml-2">Dunia Buku</span>
            </a>
        </li>
        <li>
            <a href="#" class="hover:text-gray-300">
                <i class="fab fa-twitter"></i>
                <span class="ml-2">Negeri_Buku</span>
            </a>
        </li>
        <li>
            <a href="#" class="hover:text-gray-300">
                <i class="fab fa-instagram"></i>
                <span class="ml-2">Admin@negeribuku</span>
            </a>
        </li>
    </ul>
    </div>
        </div>
            <!-- Hak Cipta -->
        <div class="mt-8 text-center text-sm">
            &copy; 2024 Perpustakaan Buku. Hak Cipta Dilindungi.
        </div>
    </div>
    </footer>
</template>

<script setup>
import { ref, reactive } from 'vue';
import buku1 from '../assets/Fiksi/buku1.jpg';
import buku2 from '../assets/Fiksi/buku2.jpg';
import buku3 from '../assets/Fiksi/buku3.jpg';
import buku4 from '../assets/Fiksi/buku4.jpg';
import buku5 from '../assets/Fiksi/buku5.jpg';

import book1 from '../assets/Non-Fiksi/book1.jpg';
import book2 from '../assets/Non-Fiksi/book2.jpg';
import book3 from '../assets/Non-Fiksi/book3.jpg';
import book4 from '../assets/Non-Fiksi/book4.jpg';
import book5 from '../assets/Non-Fiksi/book5.jpg';

import kamus1 from '../assets/Kamus/kamus1.jpg';
import kamus2 from '../assets/Kamus/kamus2.jpg';
import kamus3 from '../assets/Kamus/kamus3.jpg';
import kamus4 from '../assets/Kamus/kamus4.jpg';
import kamus5 from '../assets/Kamus/kamus5.jpg';

import bio1 from '../assets/Biografi/bio1.jpg';
import bio2 from '../assets/Biografi/bio2.jpg';
import bio3 from '../assets/Biografi/bio3.jpg';
import bio4 from '../assets/Biografi/bio4.jpg';
import bio5 from '../assets/Biografi/bio5.jpg';

import ensi1 from '../assets/Ensiklopedia/ensi1.jpg';
import ensi2 from '../assets/Ensiklopedia/ensi2.jpg';
import ensi3 from '../assets/Ensiklopedia/ensi3.jpg';
import ensi4 from '../assets/Ensiklopedia/ensi4.jpg';
import ensi5 from '../assets/Ensiklopedia/ensi5.jpg';

const categories = reactive([
  { name: 'Fiksi', color: 'bg-orange-200' },
  { name: 'Non-Fiksi', color: 'bg-orange-100' },
  { name: 'Kamus', color: 'bg-orange-200' },
  { name: 'Biografi', color: 'bg-orange-100' },
  { name: 'Ensiklopedia', color: 'bg-orange-200' },
  // Add more categories if needed
]);

const books = reactive([
  {
    name: 'Fiksi',
    products: [
      { name: 'Azzamine', price: 'Rp 106.000', image: buku1 },
      { name: 'Bumi dan Lukanya', price: 'Rp 80.000', image: buku2 },
      { name: 'Diary of Canva', price: 'Rp 85.000', image: buku3 },
      { name: 'Eccedentiast', price: 'Rp 99.000', image: buku4 },
      { name: 'Laut Bercerita', price: 'Rp 92.000', image: buku5 }
    ]
  },
  {
    name: 'Non-Fiksi',
    products: [
      { name: 'Kartini', price: 'Rp 100.000', image: book1 },
      { name: 'Tan Malaka', price: 'Rp 75.000', image: book2 },
      { name: 'Bumi Manusia', price: 'Rp 145.000', image: book3 },
      { name: 'Habibi & Ainun', price: 'RP 50.000', image: book4 },
      { name: 'Meraba Indonesia', price: 'Rp 49.000', image: book5 }
    ]
  },
  {
    name: 'Kamus',
    products: [
      { name: 'Kamus B.Inggris', price: 'Rp 106.000', image: kamus1 },
      { name: 'Kamus B.Jepang', price: 'Rp 80.000', image: kamus2 },
      { name: 'Kamus B.Korea', price: 'Rp 85.000', image: kamus3 },
      { name: 'Kamus B.Arab', price: 'Rp 99.000', image: kamus4 },
      { name: 'Kamus B.Mandarin', price: 'Rp 92.000', image: kamus5 }
    ]
  },
  {
    name: 'Biografi',
    products: [
      { name: 'Biografi Andy Noya', price: 'Rp 106.000', image: bio1 },
      { name: 'Biografi Gus Dur', price: 'Rp 80.000', image: bio2 },
      { name: 'Biografi Habibie', price: 'Rp 85.000', image: bio3 },
      { name: 'Biografi Kartini', price: 'Rp 99.000', image: bio4 },
      { name: 'Biografi Tan Malaka', price: 'Rp 92.000', image: bio5 }
    ]
  },
  {
    name: 'Ensiklopedia',
    products: [
      { name: 'Ensiklopedia Pendidikan Indonesia', price: 'Rp 106.000', image: ensi1 },
      { name: 'Ensiklopdia Sejarah Indonesia', price: 'Rp 80.000', image: ensi2 },
      { name: 'Ensiklopedia Nasional & Dunia', price: 'Rp 85.000', image: ensi3 },
      { name: 'Ensiklopedia Sains & Teknologi', price: 'Rp 99.000', image: ensi4 },
      { name: 'Ensiklopedia Teori Komunikasi', price: 'Rp 92.000', image: ensi5 }
    ]
  }
]);

const testimonials = reactive([
  { name: "hgbjv", comment: "Lorem Ipsum Dolor Sit Amet" },
  { name: "huyfu", comment: "Lorem Ipsum Dolor Sit Amet" },
  { name: "hfryd", comment: "Lorem Ipsum Dolor Sit Amet" },
  { name: "gdfgh", comment: "Lorem Ipsum Dolor Sit Amet" }
]);
</script>






    
    


    


