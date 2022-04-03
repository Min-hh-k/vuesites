<template>
	<v-app
		id="home"
		:style="{ background: $vuetify.theme.themes.dark.background }"
	>
		<Navbar />

		<v-container>
			<v-row>
				<v-col cols="6">
					<v-img src="logo.png" contain max-height="300"></v-img>
				</v-col>
				<v-col cols="6">
					<h5 class="red--text text-darken-4 top">Hello We're 엠에이치씨</h5>
					<h1 class="white--text">Min Hyeok Kim,,</h1>
					<p class="grey--text">회사설명 추가</p>
					<v-btn title color="#A7121D" dark>about me</v-btn>
				</v-col>
				<v-col cols="12" class="padd">
					<!-- 프로덕트-->
					<div class="first" id="product">
						<v-row>
							<v-col cols="12">
								<div class="child bgColor1">
									<v-icon color="#A7121D" x-large class="ml-4">
										mdi-palette-swatch
									</v-icon>
									<h3 class="white--text ml-3 mt-4">UI Design</h3>
									<p class="grey--text ml-3 mt-6">설명</p>
									<v-btn color="#A7121D" dark text
										>know more<v-icon right>mdi-arrow-right</v-icon></v-btn
									>
								</div>

								<div class="child bgColor1">
									<v-icon color="#A7121D" x-large class="ml-3"
										>mdi-shopping</v-icon
									>
									<h3 class="white--text ml-3 mt-4">Product</h3>
									<p class="grey--text ml-3 mt-6">설명</p>
									<v-btn color="#A7121D" dark text
										>know more<v-icon right>mdi-arrow-right</v-icon></v-btn
									>
								</div>

								<div class="child bgColor1">
									<v-icon color="#A7121D" x-large class="ml-3"
										>mdi-book-open-page-variant</v-icon
									>
									<h3 class="white--text ml-3 mt-4">Branding</h3>
									<p class="grey--text ml-3 mt-6">설명</p>
									<v-btn color="#A7121D" dark text
										>know more<v-icon right>mdi-arrow-right</v-icon></v-btn
									>
								</div>
							</v-col>

							<v-col cols="12" class="mt-10">
								<div class="child1">
									<h1 class="red--text text-darken-4 mt-4 number">12</h1>
									<h3 class="white--text mt-4">Years Experience</h3>
								</div>

								<div class="child2 mRight">
									<v-row>
										<v-col cols="12" class="childcol">
											<div class="child2 mButton padding bgColor1">
												<h1 class="red--text text--darken-4">60+</h1>
												<p class="grey--text">Clients</p>
											</div>
										</v-col>

										<v-col cols="12" class="childcol">
											<div class="child2 padding bgColor1">
												<h1 class="red--text text--darken-4">120+</h1>
												<p class="grey--text">Completed</p>
											</div>
										</v-col>
									</v-row>
								</div>

								<div class="child2">
									<v-row>
										<v-col cols="12" class="childcol">
											<div class="child2 mButton padding bgColor1">
												<h1 class="red--text text--darken-4">08</h1>
												<p class="grey--text">Years Experience</p>
											</div>
										</v-col>

										<v-col cols="12" class="childcol">
											<div class="child2 padding bgColor1">
												<h1 class="red--text text--darken-4">10</h1>
												<p class="grey--text">Achievements</p>
											</div>
										</v-col>
									</v-row>
								</div>
							</v-col>
						</v-row>
					</div>
				</v-col>

				<!-- 어바웃-->
				<v-col md="3" offset-md="3" id="about">
					<h1 class="white--text">Featured Project</h1>
					<p class="grey--text">설명</p>
				</v-col>

				<v-col md="3" class="text-end">
					<v-btn color="#A7121D" dark>View All</v-btn>
				</v-col>

				<v-col md="3" offset-md="3">
					<v-card
						class="pa-2 py-12"
						outlined
						tile
						heigt="250px"
						color="#1E1E1E"
					>
						<v-img src="logo1.png" contain></v-img>
					</v-card>
				</v-col>

				<v-col md="3">
					<v-card
						class="pa-2 py-12"
						outlined
						tile
						heigjt="250px"
						color="#1E1E1E"
					>
						<v-img src="logo1.png" contain></v-img>
					</v-card>
				</v-col>

				<v-col md="3" offset-md="3">
					<v-btn color="white" dark text class="m1-n4">The Vintage</v-btn>
					<br />
					<v-btn color="#A7121D" dark text class="m1-n4"
						>Know more<v-icon right>mdi-arrow-right</v-icon></v-btn
					>
				</v-col>

				<v-col md="3">
					<v-btn color="white" dark text class="m1-n4">Foodasa</v-btn> <br />
					<v-btn color="#A7121D" dark text class="m1-n4"
						>Know more<v-icon right>mdi-arrow-right</v-icon></v-btn
					>
				</v-col>

				<v-col md="3" offset-md="3">
					<v-card
						class="pa-2 py-12"
						outlined
						tile
						heigjt="250px"
						color="#1E1E1E"
					>
						<v-img src="logo1.png" contain></v-img>
					</v-card>
				</v-col>

				<v-col md="3">
					<v-card
						class="pa-2 py-12"
						outlined
						tile
						heigjt="250px"
						color="#1E1E1E"
					>
						<v-img src="logo1.png" contain></v-img>
					</v-card>
				</v-col>

				<v-col md="3" offset-md="3">
					<v-btn color="white" dark text class="m1-n4">The Vintage</v-btn>
					<br />
					<v-btn color="#A7121D" dark text class="m1-n4"
						>Know more<v-icon right>mdi-arrow-right</v-icon></v-btn
					>
				</v-col>

				<v-col md="3">
					<v-btn color="white" dark text class="m1-n4">Foodasa</v-btn> <br />
					<v-btn color="#A7121D" dark text class="m1-n4"
						>Know more<v-icon right>mdi-arrow-right</v-icon></v-btn
					>
				</v-col>
			</v-row>

			<!-- 컨택트 -->.
			<v-col cols="12" class="topInverse">
				<div class="second">
					<div class="secondChild" id="contact">
						<v-row>
							<v-col cols="7">
								<h1 class="white--text">
									Let's work together on<br />your next project
								</h1>
								<p class="grey--text">~~설명설명</p>
							</v-col>
						</v-row>
					</div>
				</div>
			</v-col>
		</v-container>

		<Footer />
	</v-app>
</template>

<script>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";

export default {
	name: "Home",

	components: {
		Navbar,
		Footer,
	},
};
</script>

<style scoped>
.top {
	margin-top: 100px;
}

.topInverse {
	margin-top: 150px;
}

.topTolbar {
	margin-top: 100px;
	text-align: center;
}

.first {
	width: 100%;
	height: 600px;
	background: linear-gradient(
		to right,
		#181818,
		#181818 50%,
		#111111 50%,
		#111111 50%
	);
	text-align: center;
	padding: 2rem 2rem;
}

.second {
	width: 100%;
	height: 200px;
	background: #181818;
	text-align: center;
	padding: 2rem 2rem;
}

.secondChild1 {
	display: inline-block;
	background-color: #1e1e1e;
	padding: 2rem 1rem;
	vertical-align: middle;
	text-align: left;
	margin-top: 250px;
}

.child {
	display: inline-block;
	padding: 2rem 1rem;
	vertical-align: middle;
	text-align: left;
	margin-right: 8px;
}

.bgColor1 {
	background-color: #1e1e1e;
}

.bgColor2 {
	background-color: #ce1d2a;
}

.child1 {
	display: inline-block;
	padding: 2rem 1rem;
	vertical-align: middle;
	margin-right: 5px;
	width: 240px;
}

.child2 {
	display: inline-block;
	width: 240px;
	vertical-align: middle;
}

.mRight {
	margin-right: 8px;
}

.mButton {
	margin-bottom: 8px;
}
.padding {
	padding: 8px 8px;
}

.col-12.pad {
	padding: 12px 0 !important;
}

.col-12.childcol {
	padding: 0 !important;
}

h1.number {
	font-size: 50px;
	font-weight: bold;
}
</style>
