<template>
  <section class="flex flex-col justify-center items-center gap-10">
    <!-- Bagian Profil -->
    <div class="min-h-screen flex items-center justify-center bg-gradient-to-br from-purple-800 via-blue-600 to-indigo-700">
      <div class="flex items-center space-x-6 bg-white p-12 rounded-3xl shadow-2xl transform hover:scale-105 transition-transform duration-500 ease-in-out">
        <!-- Foto Profil -->
        <div class="relative w-36 h-36 rounded-full overflow-hidden border-4 border-pink-500 shadow-lg">
          <img src="/aliff.jpeg" alt="Alif Musa Fahrezi" class="w-full h-full object-cover">
        </div>

        <!-- Informasi Profil -->
        <div class="text-gray-900">
          <h1 class="text-5xl font-extrabold bg-clip-text text-transparent bg-gradient-to-r from-yellow-400 via-pink-500 to-red-500 animate-pulse">
            Halo, Saya ALIF MUSA FAHREZI!
          </h1>
          <p class="text-lg mt-4 text-gray-700">Mahasiswa Universitas Brawijaya</p>
          <p class="text-lg text-gray-700">Jurusan Teknologi Informasi</p>

          <!-- Media Sosial -->
          <div class="flex items-center mt-6 space-x-6">
            <span class="text-pink-500 font-bold">HUBUNGI SAYA</span>
            <a href="https://www.facebook.com/profile.php?id=100009346263806&mibextid=LQQJ4d" target="_blank" class="text-gray-900 hover:text-pink-400 transition-transform duration-300 transform hover:scale-150">
              <i class="fab fa-facebook-f"></i>
            </a>
            <a href="https://www.linkedin.com/in/alif-musa-6bb436287?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank" class="text-gray-900 hover:text-blue-400 transition-transform duration-300 transform hover:scale-150">
              <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="https://www.instagram.com/alippooo____?igsh=MTBxd3o5a3E2aGM5Nw%3D%3D&utm_source=qr" target="_blank" class="text-gray-900 hover:text-red-400 transition-transform duration-300 transform hover:scale-150">
              <i class="fab fa-instagram"></i>
            </a>
          </div>
        </div>
      </div>
    </div>

    <!-- Bagian Tentang Saya -->
    <div class="bg-gradient-to-tr from-pink-50 via-yellow-100 to-purple-100 py-20">
      <div class="max-w-7xl mx-auto px-5">
        <h2 class="text-4xl font-extrabold text-center text-gray-800 mb-8">Tentang Saya</h2>
        <p class="text-xl text-center text-gray-700">Saya adalah mahasiswa yang bersemangat dalam Teknologi Informasi di Universitas Brawijaya, dengan fokus pada pengembangan perangkat lunak dan sistem cerdas.</p>
      </div>
    </div>

    <!-- Bagian Keterampilan -->
    <div class="bg-gradient-to-bl from-white to-blue-50 py-20">
      <div class="max-w-7xl mx-auto px-5">
        <h2 class="text-4xl font-extrabold text-center text-gray-800 mb-8">Keterampilan</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <div class="bg-gradient-to-r from-purple-200 to-pink-100 p-6 rounded-lg shadow-xl text-center transform hover:scale-105 transition-transform duration-500">
            <i class="fas fa-code text-4xl text-purple-600 mb-4"></i>
            <h3 class="text-xl font-semibold text-gray-800">Bahasa Pemrograman</h3>
            <p class="mt-2 text-gray-700">JavaScript, Python, HTML, CSS</p>
          </div>
          <div class="bg-gradient-to-r from-blue-200 to-green-100 p-6 rounded-lg shadow-xl text-center transform hover:scale-105 transition-transform duration-500">
            <i class="fas fa-laptop-code text-4xl text-blue-600 mb-4"></i>
            <h3 class="text-xl font-semibold text-gray-800">Framework</h3>
            <p class="mt-2 text-gray-700">Vue.js, Nuxt.js, TailwindCSS</p>
          </div>
          <div class="bg-gradient-to-r from-yellow-200 to-orange-100 p-6 rounded-lg shadow-xl text-center transform hover:scale-105 transition-transform duration-500">
            <i class="fas fa-database text-4xl text-yellow-600 mb-4"></i>
            <h3 class="text-xl font-semibold text-gray-800">Basis Data</h3>
            <p class="mt-2 text-gray-700">MySQL, MongoDB</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Bagian Pendidikan -->
    <div class="bg-gradient-to-r from-purple-50 via-pink-50 to-red-50 py-20">
      <div class="max-w-7xl mx-auto px-5">
        <h2 class="text-4xl font-extrabold text-center text-gray-800 mb-8">Pendidikan</h2>
        <div class="space-y-6">
          <div class="bg-white p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-500">
            <h3 class="text-2xl font-semibold text-gray-800">Universitas Brawijaya</h3>
            <p class="text-lg text-gray-700">Sarjana Teknologi Informasi (2023 - Sekarang)</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Bagian Kontak -->
    <div class="bg-gradient-to-br from-blue-50 via-purple-50 to-pink-50 py-20">
      <div class="max-w-7xl mx-auto px-5">
        <h2 class="text-4xl font-extrabold text-center text-gray-800 mb-8">Hubungi Saya</h2>
        <form class="max-w-lg mx-auto bg-white p-8 rounded-xl shadow-xl space-y-4 transform hover:scale-105 transition-transform duration-500">
          <div>
            <label for="name" class="block text-gray-700">Nama</label>
            <input type="text" id="name" class="w-full p-3 mt-2 border border-gray-300 rounded-md" />
          </div>
          <div>
            <label for="email" class="block text-gray-700">Email</label>
            <input type="email" id="email" class="w-full p-3 mt-2 border border-gray-300 rounded-md" />
          </div>
          <div>
            <label for="message" class="block text-gray-700">Pesan</label>
            <textarea id="message" class="w-full p-3 mt-2 border border-gray-300 rounded-md" rows="5"></textarea>
          </div>
          <button type="submit" class="w-full bg-gradient-to-r from-purple-500 to-pink-500 text-white p-3 rounded-md hover:shadow-lg transition duration-300">Kirim Pesan</button>
        </form>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  head() {
    return {
      title: 'Alif Musa Fahrezi - Profil'
    }
  }
}
</script>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css');
body {
  font-family: 'Poppins', sans-serif;
}
</style>
