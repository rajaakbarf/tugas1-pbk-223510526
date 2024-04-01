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
    <template #heading>Education</template>

    Informatics Engineering UIR
    <a href="https://vuejs.org/" target="_blank" rel="noopener">(2022-2026)</a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Project</template>

    Making UI/UX Design from the Application called
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener">HairTime</a>.
    Which is the RPL's project
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Expertise</template>

    
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">Figma</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Canva</a>.
  
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Languages</template>

   INDONESIA
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">100%</a>, ENGLISH
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >65%</a
    >.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>CONTACT</template>

    EMAIL : 
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">akbarfebriano@gmail.com</a>.
  </WelcomeItem>
</template>
