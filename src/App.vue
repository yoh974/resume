<template>
  <div id="app">
    <Bio></Bio>
    <Formation></Formation>
    <Info></Info>
    <ProXP></ProXP>
    <Skill></Skill>
    <div>{{resume}}</div>
  </div>
</template>

<script>
import Bio from './components/Bio.vue'
import Formation from "@/components/Formation";
import Info from "@/components/Info";
import ProXP from "@/components/ProXP";
import Skill from "@/components/Skill";
import json from "./data.json";

export default {
  name: 'App',
  components: {
    Bio,
    Formation,
    Info,
    ProXP,
    Skill

  },
  data(){
    return{

      resume: JSON.parse(json)
    }
  }
}
</script>

<style>
#app {

}
</style>
