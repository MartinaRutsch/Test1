<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="wrapper">
    <h1 class="ueberschrift">QUIZ-BATTLE</h1>
    <img alt="Würfel" class="wuefel" src="@/assets/wuerfel.png" width="80" height="80"/>
    <img alt="Würfel" class="wuefel" src="@/assets/wuerfel.png" width="80" height="80"/>
  </div>
  <div>
    <nav>
      <RouterLink to="/quiz">Start Quiz</RouterLink>
    </nav>
  </div>
</template>

<style scoped>
h1 {
  color: orange;
  font-weight:bold;
  font-size: 5em;
}
.wrapper {
  display: flex;
  align-items: center;
  gap: 5px;
}

/* .wuerfel {
  display: block;
  margin: 0 auto 2rem;
} */

</style>
