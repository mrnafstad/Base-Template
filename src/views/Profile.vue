<template>
	<div id="profile">
		<h3>User overview</h3>
		<b-row >
			<b-col class="profile-part">
				<h4>Profile</h4>
				<b-row>
					<b-col>
						Name:
					</b-col>
					<b-col id="privInfo">
						Jane Doe
					</b-col>
				</b-row>
				<b-row>
					<b-col>Age:</b-col>
					<b-col id="privInfo">24</b-col>
				</b-row>
				<b-row>
					<b-col>Country:</b-col>
					<b-col id="privInfo">Nepal</b-col>
				</b-row>
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

#privInfo {
	color: red;
	font-family: Didot;
	font-style: oblique;
}
</style>

<script>
export default {
	name: 'Profile'
}
</script>
