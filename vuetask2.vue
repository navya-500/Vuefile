<template>
<div>
<p>vue.js</p>
<p>hello world</p>
</template>
<script>
var name = "navya"
export default {
    name:example,
    data(){
        return {
            firstname:"navya",
            lastname:"doddi",
            fullname:" "
        }
    },
    created(){
        console.log(this.firstname);
    }
    mounted(){
        this.fullname = this.firstname+this.lastname
        console.log(this.fullname)
    }
    methods:{
        
    }
}