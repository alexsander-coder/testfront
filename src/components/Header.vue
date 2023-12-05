
<script setup lang="ts">
import Footer from '../components/Footer.vue';
import ArticleCard from './ArticleCard.vue';
import Top from './Top.vue';
import NewsLetter from './NewsLetter.vue';
import ImageFour from './ImageFour.vue';
</script>

<template>
<div style="">
  <div style="width: 100%; height: 2874px; position: relative; background: #F1F4F9;">
    <div class="one"></div>
    <div class="two"></div>
    <div class="thre">
      <div class="four">Viva uma nova experiência de comunicação integrada com foco nos resultados.</div>
      <div class="five">Escreva-nos sobre o seu projeto</div>
    </div>
    <div class="one1">
      <div class="two2">Construímos estratégias, design e tecnologia de ponta para o seu negócio</div>
      <div class="thre3">Converse com nossa equipe sobre o seu projeto.</div>
      <div class="four4">
        <button style="cursor: pointer; width: 150px; height: 52px; left: 0px; top: 0px; position: absolute; background: #0AB2B7; border-radius: 40px"></button>
        <div style="left: 39px; top: 16px; position: absolute; color: white; font-size: 16px; font-family: Plus Jakarta Sans; font-weight: 700; word-wrap: break-word">Começar</div>
      </div>
    </div>
    <ImageFour />
    <NewsLetter />
    <ArticleCard/>
    <Top/>
    <Footer />
    <div style="left: 876px; top: 62px; position: absolute; color: rgba(0, 0, 0, 0.70); font-size: 15px; font-family: Plus Jakarta Sans; font-weight: 600; word-wrap: break-word">Agende uma reunião conosco</div>
  </div>
  </div>
      </template>   
      
      <style scoped>
      .one1{
        width: 505px; height: 289px; left: 50px; top: 192px; position: absolute
      }

      .two2{
        width: 505px; left: 0px; top: 0px; position: absolute; color: #08111E; font-size: 36px; font-family: Plus Jakarta Sans; font-weight: 600; word-wrap: break-word
      }

      .thre3{
        width: 505px; left: 0px; top: 166px; position: absolute; color: #08111E; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 500; word-wrap: break-word
      }

      .four4{
        width: 150px; height: 52px; left: 0px; top: 237px; position: absolute
      }


    .one{
      width: 100%; height: 1961px; left: 0px; top: 729px; position: absolute; background: white
    }

    .two{
      width: 1280px; height: 0px; left: 0px; top: 729px; position: absolute; border: 2px #E7EBEE solid
    }

    .thre{
      height: 166px; left: 150px; top: 1750px; position: absolute
    }

    .four{
      width: 415px; left: 0px; top: 0px; position: absolute; color: #080808; font-size: 32px; font-family: Plus Jakarta Sans; font-weight: 600; word-wrap: break-word
    }

    .five{
      width: 419px; left: 0px; top: 141px; position: absolute; color: #08111E; font-size: 20px; font-family: Plus Jakarta Sans; font-weight: 500; word-wrap: break-word
    }
    </style>