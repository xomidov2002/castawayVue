<template>
	<Navbar />
	<HeroSection />
	<EpisodesSection />
	<AboutSection />
	<TestimonialsSection />
	<FooterSection />
</template>

<script>
import "./assets/mainStyle.css"
import "./assets/media.css"

import HeroSection from "./sections/Hero.vue"
import EpisodesSection from "./sections/Episodes.vue"
import AboutSection from "./sections/About.vue"
import TestimonialsSection from "./sections/Testimonials.vue"
import FooterSection from "./sections/Footer.vue"
import Navbar from "./components/navbar.vue"

export default {
	components: {
		Navbar,
		HeroSection,
		EpisodesSection,
		AboutSection,
		TestimonialsSection,
		FooterSection,
	}
}
</script>

<style lang="scss">

</style>