<template>
<div>
learning vue components
<h2>msg:{{message}}</h2>
<h2>name:{{name}}</h2>
<h2>number:{{number}}</h2>   
</div>
</template>
<script>
export default {
    name : "propS",
components:{
},
props : {
    message: String,
    name : String,
    number : {
        default:1138,
        type:Number
    },
Items:[
      {age:20,firstname:"navya",lastname:"doddi"},
      {age:24,firstname:"chaitrika",lastname:"lagadapati"}
    ]
    },
methods:{
    fun(){
        alert("keep it up")
    }
}


}
</script>