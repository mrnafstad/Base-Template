<template>
	<div id="profile">
		<b-row >
			<b-col class="profile-part">
				<h4>Jane Doe</h4>
				<p>Age: 24</p>
				<p>Country: Nepal</p>
			</b-col>
			<b-col class="profile-part">
				<h4>Posts</h4>
			</b-col>
			<b-col class="profile-part">
				<h4>Friends List</h4>
			</b-col>
		</b-row>
	</div>
</template>

<style>
#profile {
	padding: 5%;
}

.profile-part {
	background-color: snow;
}
</style>

<script>
export default {
	name: 'Profile'
}
</script>
