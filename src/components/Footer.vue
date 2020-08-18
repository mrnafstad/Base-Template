<template>
		<b-row id="footer" align-v="end">
			<b-col>Created by: <p>Halvor Nafstad</p></b-col>
			<b-col>Contact: <p>mrnfastad@gmail.com</p></b-col>
		</b-row>
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
	bottom: 0%;
	width: 102vw;
}

#footerCont {
	margin: auto;
	width: 50%;
	padding: 0.5em;
}
</style>