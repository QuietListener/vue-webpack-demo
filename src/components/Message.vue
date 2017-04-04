<template>
<div>
  <div class='box' v-on:click='test'>from {{msg}}</div>
  <router-link to="/">go to home</router-link>
 </div> 
 </template>

<script>
export default{
	name:"message",
	data:function(){
		return {
		   msg:"Message "
		}
	},
	methods:{
		test:function(){
			console.log("msg:test");
		}
	}
}
</script>


<style>

<style>