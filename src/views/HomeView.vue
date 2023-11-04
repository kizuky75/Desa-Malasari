<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Malasari</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Gotong Royong Membangun Desa Malasari Yang Jujur, Adil, Makmur dan Transparan”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Mewujudkan pemerintahan desa dengan pengambilan keputusan yang cepat dan tepat;
        </li>
        <li>
          2. Meningkatan profesionalitas dan mengaktifkan seluruh perangkat desa;
        </li>
        <li>
          3. Mewujudkan sarana dan prasarana desa;
        </li>
        <li>
          4. Mewujudkan perekonomian dan kesejahteraan warga desa;
        </li>
        <li>
          5. Meningkatkan pelayanan masyarakat dengan maksimal.
        </li>
        <li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
