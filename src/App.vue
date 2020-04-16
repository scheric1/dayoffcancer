<template>
	<v-app>
		<v-app-bar app color="white">
			<div class="d-flex align-center">
				<v-img src="/images/gofundme.png" contain height="35px"></v-img> <span class="title mt-1">A Day Off Cancer</span>
			</div>

			<v-spacer></v-spacer>

			<v-btn href="https://www.gofundme.com/f/wzkfb-a-day-off-from-cancer" target="_blank" text>
				<span class="mr-2">Donate</span>
				<v-icon>mdi-open-in-new</v-icon>
			</v-btn>
		</v-app-bar>

		<v-content>
			<router-view></router-view>
		</v-content>
	</v-app>
</template>

<style>
h1.display-3 {
	line-height: 80px !important;
}
.gofund {
	width: 100%;
	height: 200px;
}
.text-shadow {
	text-shadow: 2px 2px 2px #000000;
}
.marker {
	font-family: "Permanent Marker", cursive;
}

@media screen and (max-width: 547px) {
	.v-application .display-3 {
		font-size: 20px !important;
	}
}
</style>

<script>
export default {
	name: "App",

	components: {},

	data: () => ({
		//
	}),
};
</script>
