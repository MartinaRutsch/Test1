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
    <div class="wrapperSpalten">
        <div class="spalte">
            <h1>Fragen über die Neuen</h1>
            <div class="punkte"> 
                <h2>25</h2> 
            </div>
            <div class="punkte"> 
                <h2>50</h2> 
            </div>
            <div class="punkte"> 
                <h2>100</h2> 
            </div>
            <div class="punkte"> 
                <h2>200</h2> 
            </div>
            <div class="punkte"> 
                <h2>250</h2> 
            </div>
        </div>
        <div class="spalte">
            <h1>Wer isch's?</h1>
            <div class="punkte"> 
                <h2>25</h2> 
            </div>
            <div class="punkte"> 
                <h2>50</h2> 
            </div>
            <div class="punkte"> 
                <h2>100</h2> 
            </div>
            <div class="punkte"> 
                <h2>200</h2> 
            </div>
            <div class="punkte"> 
                <h2>250</h2> 
            </div>
        </div>
        <div class="spalte">
            <h1>Mischmasch</h1>
            <div class="punkte"> 
                <h2>25</h2> 
            </div>
            <div class="punkte"> 
                <h2>50</h2> 
            </div>
            <div class="punkte"> 
                <h2>100</h2> 
            </div>
            <div class="punkte"> 
                <h2>200</h2> 
            </div>
            <div class="punkte"> 
                <h2>250</h2> 
            </div>
        </div>
        <div class="spalte">
            <h1>Morphing Faces</h1>
            <div class="punkte"> 
                <h2>25</h2> 
            </div>
            <div class="punkte"> 
                <h2>50</h2> 
            </div>
            <div class="punkte"> 
                <h2>100</h2> 
            </div>
            <div class="punkte"> 
                <h2>200</h2> 
            </div>
            <div class="punkte"> 
                <h2>250</h2> 
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped>
h1 {
  color: darkorange;
  font-weight:bold;
  font-size: 1.5em;
}
h2 {
    color: darkred;
    font-weight: bold;
    font-size: 1.5em
}
.wrapper {
    display: flex;
    width: 80em;
}

.wrapperSpalten {
    display: flex;
    width: 100%;
    justify-content: space-between;
}

.spalte {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    width: 17em;
    height: 50em;
    background-color: darkred;
    border-radius: 30px
}

.punkte {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 10em;
    height: 4em;
    background-color: darkorange;
    border-radius: 15px
}

/* .wuerfel {
  display: block;
  margin: 0 auto 2rem;
} */

</style>
