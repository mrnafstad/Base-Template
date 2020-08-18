<template>
	<div id="header">
		<!--<div id="headerFields">
			<router-link to='/'>Home</router-link>
		</div>
		<Menu />-->
		<b-row align-v="center">
			<b-col><router-link to='/'>Home</router-link></b-col>
			<b-col></b-col>
			<b-col><Menu /></b-col>
		</b-row>
	</div>
</template>

<script>
import Menu from './Menu.vue'
	export default {
		name: 'Header',
		components: {
			Menu
		}
	}
</script>

<style>
#header {
	background-color: black;
	text-align: center;
	vertical-align: middle;
}

#headerFields {
  margin: auto;
  width: 50%;
  padding: 1em;
  color: lightblue;
}

a.router-link-active:hover {
	color: blue;
	text-decoration: none
}
</style>