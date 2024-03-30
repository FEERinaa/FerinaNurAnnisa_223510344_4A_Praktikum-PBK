<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tujuan</template>
    Portofolio ini bertujuan untuk memenuhi tugas dari Pemrograman Berbasis Komponen atau dikenal
    dengan PBK. Tugas PBK ini dilakukan dengan mengubah vue yang ada menjadi Portofolio atau CV. Di
    sini kami dibebaskan untuk berkreasi mengenai isinya.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Profil</template>
    <table id="data">
      <tr>
        <th>Nama Lengkap</th>
        <th>Nama Panggilan</th>
        <th>TTL</th>
        <th>Golongan Darah</th>
      </tr>

      <tr>
        <td>Ferina Nur Annisa</td>
        <td>Ferina</td>
        <td>Padang, 05 Januari 2004</td>
        <td>B-</td>
      </tr>
    </table>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Deskripsi Karakteristik</template>
    Sebagai wanita independen, saya tak terlepas dari karakteristik yang melekat di diri, sebagai
    berikut :<br />
    <ul>
      <li>bertanggungjawab</li>
      <li>Jujur</li>
      <li>Amanah</li>
      <li>Ramah</li>
    </ul>
    dan sebagainya yang menunjang sebuah pekerjaan terlaksana.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Pengalaman</template>
    <ol>
      <li>Volunteer dalam kegiatan IT FUNDAY 2023 sebagai Pamong</li>
      <li>Volunteer dalam kegiatan FUTSAL CUP 4 2023 di devisi Acara</li>
      <li>Volunteer dalam kegiatan Seminar BITS LAB 2023 di devisi Acara</li>
      <li>Volunteer dalam kegiatan MILAD TI UIR KE-16 2023 sebagai CO Acara</li>
      <li>Sedang Menjabat di Organisasi HIMATIF sebagai Bendahara Umum</li>
    </ol>
    dan organisasi lainnya.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hubungi</template>
    WA : 08-58-....<br />
    IG :
  </WelcomeItem>
</template>
