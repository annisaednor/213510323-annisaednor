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
    <template #heading>Documentasi</template>

    <a>Dengan adanya dokumentasi momen-momen indah akan terkenang.</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>koper</template>

    <a>Mempersiapkan barang yang akan dibutuhkan dan bermanfaat saat dedang berpergian.</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>lingkungan</template>

    <a>Menjaga kebersihan disekitar kita, dengan begitu menghindari dari adanya polusi dan banjir.</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>komunikasi</template>

    <a>menjalin hubungan yang hangat dengan orang-orang disekitar agar perjalanan lebih menyenangkan.</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>kebahagiaan</template>
      <a>menebar kebahagiaan dimana kita berada.</a>
  </WelcomeItem>
</template>