<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconLayers from "~icons/lucide/layers";
	import IconHeart from "~icons/lucide/heart";
	import IconBattery from "~icons/lucide/battery";
	import IconClock from "~icons/lucide/clock";
	import IconFlask from "~icons/lucide/flask";
	import IconLeaf from "~icons/lucide/leaf";
</script>

<Hero
	title="Transform your gut health from the inside out"
	subtitle="Three targeted fiber types that feed beneficial bacteria, reduce bloating, and restore your natural energy—so you can feel your best every day."
	imageSrc="/generated/image-a-professional-woman-in-her-30s-energeti.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by health-conscious companies"
	logoUrls={[
		'https://cdn.brandfetch.io/wholefoodsmarket.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/onepeloton.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/blueapron.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/headspace.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Backed by science. Built for daily life"
	text="We help busy, health-conscious professionals take charge of their gut health through a clinically studied, triple-fiber supplement that fits easily into daily life. Designed to feed beneficial bacteria, reduce bloating, and restore energy—our formula delivers digestive balance without the guesswork.

95% of Americans fall short of daily fiber intake, leading to digestive issues that affect energy and well-being. Our precise blend of three targeted fiber types fills that gap in one simple scoop, so you can feel your best every day."
/>

<Testimonials
	testimonials={[
		{
			name: "Maya Chen",
			position: "Marketing Director",
			company: "BrandForward",
			quote:
				"After years of afternoon energy crashes and digestive issues, this fiber blend changed everything. I save 2 hours weekly that I used to spend managing bloating and discomfort—now I can focus on what matters most.",
			image: "/generated/image-professional-headshot-of-a-confident-asi.webp"
		},
		{
			name: "Marcus Williams",
			position: "Healthcare Consultant",
			company: "Wellness Partners",
			quote:
				"As someone who advises clients on gut health, I was skeptical of supplements. But this tri-blend approach eliminated my irregular digestion within 3 weeks, saving me hundreds in specialist consultations I was considering.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Carmen Rodriguez",
			position: "Operations Manager",
			company: "TechFlow Solutions",
			quote:
				"Between managing a team and family, I had no time for complex wellness routines. This simple daily supplement reduced my bloating by 80% and gave me consistent energy—worth every penny of the meal prep services I used to rely on.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		}
	]}
/>

<Features
	title="Why our fiber works differently"
	subtitle="Three targeted fiber types that transform gut health from the inside out, addressing the root causes other supplements miss."
	features={[
		{
			title: "Triple-action fiber blend",
			description: "Unlike single-fiber supplements, our scientifically-formulated tri-blend feeds diverse beneficial bacteria while regulating digestion naturally. Experience comprehensive gut transformation that goes beyond basic regularity.",
			icon: IconLayers
		},
		{
			title: "Reduces bloating within days",
			description: "Targeted prebiotic fibers restore optimal gut flora balance, eliminating uncomfortable bloating and digestive distress. Feel lighter and more energized as your gut finds its natural rhythm.",
			icon: IconHeart
		},
		{
			title: "Sustained energy throughout your day",
			description: "Balanced fiber absorption stabilizes blood sugar and supports consistent energy levels. No more afternoon crashes—just steady vitality that powers your demanding lifestyle.",
			icon: IconBattery
		},
		{
			title: "Convenient daily ritual",
			description: "One simple scoop seamlessly integrates into your morning routine, delivering professional-grade gut health benefits. Transform your wellness without disrupting your busy schedule.",
			icon: IconClock
		},
		{
			title: "Clinically-backed formulation",
			description: "Each fiber type is precisely dosed based on published gut microbiome research, ensuring maximum effectiveness. Experience the confidence of science-driven nutrition that delivers measurable results.",
			icon: IconFlask
		},
		{
			title: "Gentle yet powerful results",
			description: "Our premium fiber blend works harmoniously with your digestive system, avoiding harsh effects common in traditional supplements. Achieve optimal gut health through gentle, sustainable transformation.",
			icon: IconLeaf
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
