<script setup lang="ts">
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
    <template #heading>PENDIDIKAN</template>
    sd pandau jaya<br>
    smp alhusna<br>
    smk hasanah<br>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>HOBI</template>
    traveling<br>
    bulu tangkis<br>
    


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>BIODATA</template>
    Tanggal Lahir : 12-12-2003<br>
    Asal : Pekanbaru<br>
    Nama Ayah : Jumanto<br>
    Nama Ibu : Reni Elviza<br>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>PENGALAMAN HIDUP</template>
    Magang di perusahaan swasta<br>
    

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>CONTACT ME</template>
    Wa : 0858322613<br>
    Ig : __dimasadrr<br>
    Fb : Dimasandreananda<br>

  </WelcomeItem>
</template>
