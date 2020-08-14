<template>
	<div id="footer">
		<div id="footerCont">
			Creator: Halvor Nafstad
			|
			Email: mrnafstad@gmail.com
		</div>
	</div>
</template>

<script>
export default {
	name: 'Footer'
}
</script>

<style>
#footer {
	background-color: #E8E8E8;
	position: absolute;
	bottom: 0;
	width: 100%;
	height: 2.5rem; 
}

#footerCont {
	margin: auto;
	width: 50%;
	padding: 0.5em;
}
</style>