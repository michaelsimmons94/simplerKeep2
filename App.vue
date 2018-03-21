<template>
  <v-app>
	<div id="app">
 		<h1>Even Simpler Keep</h1>
		<br>
		<h3>A more bayzic version of Google Keep</h3>
		<router-view>
	</div>
  </v-app>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
background-color: dodgerblue;
}
h1
{
text-align: center;
font-family: 'Pacifico', cursive;
color: white;
font-size: 4em;
}
h3{
text-align: center;
color: white;
font-size: 1.5em;
}
</style>
