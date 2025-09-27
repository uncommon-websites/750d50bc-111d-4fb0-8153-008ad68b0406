<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Science-driven",
			description: "Every formula is backed by clinical research, not trends or gimmicks. We combine proven fiber types that work together for real digestive results."
		},
		{
			title: "Everyday simplicity",
			description: "Gut health shouldn't be complicated. We create solutions that fit seamlessly into real life, making wellness accessible for busy schedules."
		},
		{
			title: "Genuine care",
			description: "Your wellbeing is our mission. We're here to support your journey to feeling lighter, more energized, and confidently in control of your health."
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

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Better fiber. Better digestion."
	subtitle="Gut health starts here"
	description="A daily fiber supplement designed to reduce bloating, support regularity, and help you feel lighter—naturally. Powered by a clinically studied blend of three essential fiber types."
	imageSrc="/generated/image-a-professional-woman-in-her-home-kitchen.webp"
	callsToAction={[
		{
			href: "/shop",
			label: "Start your routine",
			variant: "primary"
		},
		{
			href: "/learn",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
