<template>
	<div class="home">
		<header-image />
		<v-container fluid class="pt-0">
			<v-row class="py-12">
				<v-col cols="12" sm="10" offset-sm="1" md="8" offset-md="2" lg="6" offset-lg="3">
					<v-row class="about">
						<v-col cols="12" class="text-center">
							<h3 class="display-3 mt-0 mb-5">About the Cause</h3>
						</v-col>
						<v-col cols="12" class="text-center">
							<p class="headline mb-0 font-weight-bold">
								We are starting a nonprofit for adults going through cancer treatment. We would like to give them a weekend
								away from the daily stress of treatment and the worries that go with it.
							</p>
						</v-col>
						<v-col cols="12">
							<ul>
								<li class="title font-weight-regular mb-2">
									We are raising money for hotel rooms and to give that person a $500 prepaid Visa card.
								</li>
								<li class="title font-weight-regular mb-2">
									We will work with local cancer hospitals to find people who have been hit hard financially by cancer.
								</li>
								<li class="title font-weight-regular mb-2">
									Cancer doesn't just attack the body. This disease spreads to the mind and spirit of everyone affected by
									it.
								</li>
								<li class="title font-weight-regular mb-2">
									One of our goals would be to send a young family to a waterpark resort for a fun weekend away from their
									daily stresses.
								</li>
								<li class="title font-weight-regular mb-2">
									I know personally how just one weekend away from everything can change your attitude and recharge you to
									keep fighting.
								</li>
								<li class="title font-weight-regular mb-2">
									My goal is to reach out and give back to as many people as i can. I appreciate you taking the time to
									read this, thank you for your support.
								</li>
							</ul>
						</v-col>
					</v-row>
				</v-col>
			</v-row>
			<v-row class="grey lighten-5 py-12">
				<v-col cols="12" sm="10" offset-sm="1" md="8" offset-md="2" lg="6" offset-lg="3" class="text-center">
					<v-row class="brian">
						<v-col cols="12">
							<h3 class="display-3 mt-0 mb-5">Brian Couchie</h3>
						</v-col>
						<v-col cols="12" class="py-3">
							<p class="title font-weight-regular">
								In September 2019 I was diagnosed with a rare cancer <strong>Carcinoma of Unknown Primary (CUP)</strong>. As
								of today I have undergone <strong class="orange--text px-2">35 treatments</strong> of radiation and
								<strong class="orange--text px-2">7 treatments</strong> of chemotherapy but still have not beat it. I still
								have a tumor in my neck which I am still dealing with. My First CT scan after treatment showed a 1.2 cm mass
								which will need to be surgically removed in the near future.
							</p>
						</v-col>
						<v-col cols="12" md="6">
							<v-card>
								<v-img src="/images/brian.jpg"></v-img>
							</v-card>
						</v-col>
						<v-col cols="12" md="6">
							<v-card>
								<v-img src="/images/ring-the-bell.jpg"></v-img>
							</v-card>
						</v-col>
						<v-col cols="12" class="py-3">
							<p class="title font-weight-regular">
								My goal is to help adults with cancer who have been hit hard financially, as I know first hand what it is
								like. When I was diagnosed, I had to stop driving my truck during treatment (Driving for 18 years) which had
								a huge impact on my life, my family and my moral.
							</p>
						</v-col>
						<v-col cols="12" md="6">
							<v-card>
								<v-img src="/images/family.jpg"></v-img>
							</v-card>
						</v-col>
						<v-col cols="12" md="6">
							<v-card>
								<v-img src="/images/family2.jpg"></v-img>
							</v-card>
						</v-col>

						<v-col cols="12" class="py-3">
							<p class="title font-weight-regular">
								I hope others can help me raise money for those in similar circumstances, so they can take a day off of
								cancer, without having to worry about finances, even if it's just for a day.
							</p>
						</v-col>
						<v-col cols="12">
							<v-card>
								<v-img src="/images/truck.jpg"></v-img>
							</v-card>
						</v-col>
					</v-row>
				</v-col>
			</v-row>
			<v-row class="py-12">
				<v-col cols="12" sm="10" offset-sm="1" md="8" offset-md="2" lg="6" offset-lg="3" class="text-center">
					<v-row class="donate">
						<v-col cols="12">
							<h3 class="display-3 mt-0 mb-5">How to Donate</h3>
						</v-col>
						<v-col cols="12">
							<p class="headline mb-6 font-weight-bold">
								Even a small amount could make a difference for someone going through Cancer. Please help us shine a little
								light even if it's just for one day.
							</p>
						</v-col>
						<v-col cols="12">
							<go-fund-me />
						</v-col>
						<v-col cols="12">
							<p class="title font-weight-regular mb-6">
								If you are unable to donate, please consider sharing our GoFundMe
							</p>
						</v-col>
						<v-col cols="12">
							<v-row>
								<v-col cols="4" sm="2" offset-sm="3">
									<v-btn
										fab
										x-large
										elevation="0"
										href="https://www.facebook.com/dialog/share?app_id=407682420960&display=popup&href=https%3A%2F%2Fwww.gofundme.com%2Ff%2Fwzkfb-a-day-off-from-cancer%3Futm_source%3Dfacebook%26utm_medium%3Dsocial%26utm_campaign%3Dp_cp%2Bshare-sheet"
									>
										<v-icon>mdi-facebook</v-icon>
									</v-btn>
								</v-col>
								<v-col cols="4" sm="2">
									<v-btn
										fab
										x-large
										elevation="0"
										href="https://twitter.com/intent/tweet?lang=en&text=A%20Day%20Off%20From%20Cancer&url=https%3A%2F%2Fwww.gofundme.com%2Ff%2Fwzkfb-a-day-off-from-cancer%3Futm_source%3Dtwitter%26utm_medium%3Dsocial%26utm_campaign%3Dp_cp%2Bshare-sheet"
									>
										<v-icon>mdi-twitter</v-icon>
									</v-btn>
								</v-col>
								<v-col cols="4" sm="2">
									<v-btn
										fab
										x-large
										elevation="0"
										href="mailto:?subject=Have you seen 'A Day Off From Cancer'?&amp;body=Hello 
 
 I thought you might be interested in supporting this GoFundMe, https://www.gofundme.com/f/wzkfb-a-day-off-from-cancer?utm_source=customer&utm_medium=email&utm_campaign=p_cp+share-sheet. 
 
 Even a small donation could help Brian Couchie reach their fundraising goal. And if you can't make a donation, it would be great if you could share the fundraiser to help spread the word. 
 
 Thanks for taking a look!"
									>
										<v-icon>mdi-email-open</v-icon>
									</v-btn>
								</v-col>
							</v-row>
						</v-col>
					</v-row>
				</v-col>
			</v-row>
		</v-container>
	</div>
</template>

<script>
// @ is an alias to /src
import GoFundMe from "@/components/GoFundMe";
import HeaderImage from "@/components/HeaderImage";
export default {
	name: "Home",
	components: { GoFundMe, HeaderImage },
};
</script>
