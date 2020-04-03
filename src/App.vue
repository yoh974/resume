<template>
    <div id="app">
        <Bio
          :bio="resume.resume.bio"
        />
        <Formation
                :formation="formation"
                :key="formation.id"
                v-for="formation in resume.resume.formations"
        />
        <Info
            :info="resume.resume.infos"
        />
        <ProXP
                :proXp="proXp"
                :key="proXp.id"
                v-for="proXp in resume.resume.profesionnal_exp"
        />
        <Skill
                :skill="skill"
                :key="skill.id"
                v-for="skill in resume.resume.skills"
        />
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
        data() {
            return {
                resume: json
            }
        }
    }
</script>

<style>
    #app {

    }
</style>
