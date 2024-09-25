<template>
  <section class="flex justify-center align-middle items-center gap-10">
    <div class="min-h-screen flex items-center justify-center bg-gradient-to-r from-purple-600 via-blue-500 to-indigo-600">
    <div class="flex items-center space-x-6 bg-white p-10 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-500 ease-in-out">
      <!-- Foto Profil -->
      <div class="relative w-32 h-32 rounded-full overflow-hidden border-4 border-purple-500 shadow-lg">
        <img src="/orang tua.jpg" alt="Alif Musa Fahrezi" class="w-full h-full object-cover">
      </div>

      <!-- Informasi Profil -->
      <div class="text-gray-900">
        <h1 class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-yellow-400 to-pink-500 animate-pulse">
          Hello, I'm ALIF MUSA FAHREZI!
        </h1>
        <p class="text-lg mt-2 text-gray-700">Mahasiswa Universitas Brawijaya</p>
        <p class="text-lg text-gray-700">Jurusan Teknologi Informasi</p>

        <!-- Bagian Sosial Media -->
        <div class="flex items-center mt-4 space-x-4">
          <span class="text-yellow-400 font-semibold">LET'S CONNECT</span>
          <!-- Icon Sosial Media -->
          <a href="https://www.facebook.com/profile.php?id=100009346263806&mibextid=LQQJ4d" target="_blank" class="text-gray-900 hover:text-yellow-400 transition duration-300 transform hover:scale-125">
            <i class="fab fa-facebook-f"></i>
          </a>
          <a href="https://www.linkedin.com/in/alif-musa-6bb436287?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank" class="text-gray-900 hover:text-yellow-400 transition duration-300 transform hover:scale-125">
            <i class="fab fa-linkedin-in"></i>
          </a>
          <a href="https://www.instagram.com/alippooo____?igsh=MTBxd3o5a3E2aGM5Nw%3D%3D&utm_source=qr" target="_blank" class="text-gray-900 hover:text-yellow-400 transition duration-300 transform hover:scale-125">
            <i class="fab fa-instagram"></i>
          </a>
        </div>
      </div>
    </div>
    
  </div>
 
  </section>
  
</template>

<script>
export default {
  head() {
    return {
      title: 'Alif Musa Fahrezi - Profile'
    }
  }
}
</script>

<style>
@import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css');
</style>
