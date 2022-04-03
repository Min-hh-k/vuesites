<template>
	<div>
		<v-footer dark padless>
			<v-card
				flat
				tile
				class="black white--text py-5 px-5 text-center"
				width="100%"
			>
				<v-row>
					<v-col cols="12" sm="4">
						<v-card-text class="white--text pt-2">
							<v-btn icon>
								<v-icon color="#a7121D">fas fa-dragon</v-icon>
							</v-btn>
						</v-card-text>
					</v-col>

					<v-col cols="12" sm="4">
						<v-card-text class="pt-2">
							<v-btn
								v-for="icon in icons"
								:key="icon"
								class="mx-1 white--text"
								icon
							>
								<v-icon size="20px">{{ icon }}</v-icon>
							</v-btn>
						</v-card-text>
					</v-col>

					<v-col cols="12" sm="4">
						<v-card-text class="pt-2">
							<v-btn class="mx-1 white--text" icon>
								<v-icon color="#A7121D">mdi-heart</v-icon>
							</v-btn>
							Created by mh
						</v-card-text>
					</v-col>
				</v-row>
			</v-card>
		</v-footer>
	</div>
</template>

<script>
export default {
	data: () => ({
		icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
	}),
};
</script>

<style></style>
