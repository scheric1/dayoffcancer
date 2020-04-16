<template>
	<v-row no-gutters>
		<v-col cols="12">
			<v-img src="/images/header.jpg" width="100%" height="550px">
				<v-container class="fill-height" fluid>
					<v-row justify="center" no-gutters>
						<v-col cols="12" class="text-center">
							<h1
								:class="[
									$vuetify.breakpoint.smAndDown ? 'display-2' : 'display-3',
									'white--text text-shadow font-weight-black',
								]"
							>
								Cancer may have started the fight...<br />
								... but I will finish it
							</h1>
						</v-col>
					</v-row>
				</v-container>
			</v-img>
		</v-col>
	</v-row>
</template>
