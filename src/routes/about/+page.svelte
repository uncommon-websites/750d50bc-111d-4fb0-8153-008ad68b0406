<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Clinical precision",
			description: "Our tri-fiber blend combines soluble, insoluble, and prebiotic fibers in scientifically proven ratios. No guesswork, just results backed by digestive health research."
		},
		{
			title: "Daily simplicity",
			description: "Better gut health shouldn't disrupt your routine. One scoop daily delivers everything your digestive system needs, seamlessly fitting into busy lifestyles."
		},
		{
			title: "Whole-person wellness",
			description: "We believe gut health is the foundation of energy, focus, and confidence. Our mission extends beyond digestion to helping you feel your absolute best."
		}
	];
</script>

<SecondaryHero
	title="Gut health, made daily"
	subtitle="Better digestion starts with fiber"
	imageSrc="/generated/image-a-diverse-group-of-wellness-researchers-.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Gut health isn't just about digestion—it's the foundation of energy, focus, and how we feel all day. But for many of us, busy schedules and inconsistent habits lead to bloating, irregular digestion, and daily discomfort. We wanted better for ourselves and for everyone juggling wellness with real life.",
		"So we teamed up with gut health researchers to create a solution that actually works. Our formula is built around three targeted types of fiber—soluble, insoluble, and prebiotic—that work together to feed beneficial bacteria and regulate digestive function. Unlike outdated single-fiber options, it's a complete system rooted in the best of clinical science and made simple for everyday use.",
		"Our mission is to help you feel your best without overhauling your routine. Customers tell us they feel more energized, less weighed down, and more in control—from better digestion to more balanced days overall. Because when your gut works, everything else does too. We're here to make that your new normal."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed as no real team members or confirmed investors available -->

<!-- CTA Section -->
<CallToAction
	title="Transform your gut health"
	subtitle="Starting today"
	description="Join thousands who've discovered what real digestive wellness feels like. Our science-backed tri-fiber blend works in just days to reduce bloating, improve regularity, and restore your natural energy."
	imageSrc="/generated/image-bright-natural-light-fills-a-cozy-kitche.webp"
	callsToAction={[
		{
			href: "/shop",
			label: "Order now",
			variant: "primary"
		},
		{
			href: "/results",
			label: "See results",
			variant: "secondary"
		}
	]}
/>
