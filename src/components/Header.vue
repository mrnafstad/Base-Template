<template>
	<div id="header">
		<div id="headerFields">
			<router-link to='/'>Home</router-link>
		</div>
		<Menu />
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
	height: 4em;
	text-align: center;
	vertical-align: middle;
}

#headerFields {
  margin: auto;
  width: 50%;
  padding: 1em;
  color: lightblue;
}

a {
	color: snow;
}
a:hover {
	color: lightblue
}
</style>