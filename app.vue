<template>
  <div class="min-h-screen" style="background-color: #e0e0e0;">
    <header class="bg-white shadow">
      <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold text-black">Profil Saya</h1>
      </div>
    </header>
    <main>
      <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8 flex">
        <!-- Left Section -->
        <div class="w-1/3 bg-white p-6 rounded-lg shadow-md mt-6 border-2 border-blue-900">
          <img src="./img/fotodiri2.jpeg" alt="Your Photo" class="w-72 h-72 rounded-full mx-auto mb-4">
          <h1 class="text-3xl font-bold mb-4 text-black">Fadilian Risdianto</h1>
          <ul class="list-disc list-inside text-black">
              <li class="mb-2">087701514226</li>
              <li class="mb-2">fadilian1124@gmail.com</li>
              <li class="mb-2">Gondanglegi, Malang, Jawa Timur</li>
            </ul>
        </div>
        <!-- Right Section -->
        <div class="w-2/3 ml-6">
          
          <section class="bg-white p-6 rounded-lg shadow-md mt-6 border border-blue-900">
            <h2 class="text-2xl font-bold mb-4 text-black">Tentang Saya</h2>
            <p class="text-black">Saya pernah magang di perusahaan ISP selama 1 tahun. Saya berpengalaman menjadi teknisi lapangan di bagian instalasi jaringan dan maintenance. Saya juga pernah membuat sebuah website untuk perpustakaan</p>
          </section>

          <section class="bg-white p-6 rounded-lg shadow-md mt-6 border border-blue-900">
            <h2 class="text-2xl font-bold mb-2 text-black">Pendidikan</h2>
            <ul class="list-disc list-inside text-black">
              <li class="mb-2">SMK Negeri 1 Kepanjen (2020 - 2023)</li>
              <li class="mb-2">Universitas Brawijaya (2023 - sekarang)</li>
            </ul>
          </section>

          <section class="bg-white p-6 rounded-lg shadow-md mt-6 border border-blue-900">
            <h2 class="text-2xl font-bold mb-4 text-black">Pengalaman Magang</h2>
            <ul class="list-disc list-inside text-black">
              <li class="text-black">Teknisi Jaringan di PT J.R.Nusa (2022)</li>
            </ul>
          </section>

          <section class="bg-white p-6 rounded-lg shadow-md mt-6 border border-blue-900">
            <h2 class="text-2xl font-bold mb-4 text-black">Proyek</h2>
            <ul class="list-disc list-inside flex items-center text-black">
              <li class="text-black">Membuat website perpustakaan</li>
              <a href="https://github.com/fadilian/perpus.git" target="_blank" class="ml-4 bg-blue-500 text-white px-4 py-2 rounded-lg shadow-md hover:bg-blue-700">Lihat Repo</a>
            </ul>
          </section>

          <section class="bg-white p-6 rounded-lg shadow-md mt-6 border border-blue-900">
            <h2 class="text-2xl font-bold mb-4 text-black">Sertifikat</h2>
            <ul class="list-disc list-inside text-black">
              <li class="text-black">Magang 1 tahun di PT J.R.Nusa</li>
              <li class="text-black">MTCNA</li>
            </ul>
          </section>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
}
</script>

<style scoped>

section {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1), 0 6px 20px rgba(0, 0, 0, 0.1);
  border: 2px solid #1E3A8A; /* Dark blue border */
}

.text-black {
  color: black;
}

</style>
