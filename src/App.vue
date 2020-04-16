<template>
	<v-app>
		<v-app-bar app color="white">
			<div class="d-flex align-center">
				<v-img src="/images/gofundme.png" contain height="35px" class="d-none d-sm-flex"></v-img>
				<span class="title mt-1">A Day Off From Cancer</span>
			</div>

			<v-spacer></v-spacer>

			<v-btn
				href="https://www.gofundme.com/f/wzkfb-a-day-off-from-cancer"
				target="_blank"
				color="#00B964"
				dark
				:large="$vuetify.breakpoint.mdAndUp"
			>
				<span>Donate</span>
				<!-- <v-icon>mdi-open-in-new</v-icon> -->
			</v-btn>
		</v-app-bar>

		<v-content>
			<router-view></router-view>
		</v-content>
		<v-footer absolute class="font-weight-medium grey lighten-2">
			<v-col class="text-center" cols="12">
				If you know a person or family in need with cancer please contact us.
				<br v-if="$vuetify.breakpoint.smAndDown" />
				<v-btn color="orange" class="mx-3" dark href="mailto:adayofffromcancer@gmail.com">Message Us</v-btn>
			</v-col>
		</v-footer>
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
		font-size: 2.5rem !important;
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
