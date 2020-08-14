<template>
	<div id="menu">
		<div>
			<div id="hamburger"> </div>
			<div id="hamburger"> </div>
			<div id="hamburger"> </div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Menu',
	data() {
		return {
			active: false
		}
	}
}
</script>

<style>
#hamburger {
	border-radius: 5px;
	width: 0.2em;
	background-color: white;
}

#menu {
	position: relative;
	left: 40%;
	top: -1.5em;
}
</style>