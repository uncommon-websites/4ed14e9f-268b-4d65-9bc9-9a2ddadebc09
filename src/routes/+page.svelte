<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconMap from "~icons/lucide/map";
	import IconDatabase from "~icons/lucide/database";
	import IconZap from "~icons/lucide/zap";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconShield from "~icons/lucide/shield";
</script>

<CenteredTextOnlyHero
	title="The AI operating system for executive search"
	subtitle="Infrastructure that transforms weeks of manual research into hours of precision-driven intelligence. Built for search firms, funds, and talent teams who need speed without compromise."
	imageSrc="/generated/image-a-team-of-mid-career-to-senior-professio.webp"
/>
<LogoScroller
	label="Trusted by leading tech companies and funds"
	logoUrls={[
		'https://cdn.brandfetch.io/miro.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/prosus.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/helsing.ai/w/400/h/400/logo',
		'https://cdn.brandfetch.io/psg.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Executive search, rebuilt"
	text="Topliner serves executive search firms, funds, and corporate talent teams who need to hire senior leaders faster and smarter. We transform manual, weeks-long research into structured, data-driven intelligence delivered in hours. Our AI infrastructure turns scattered recruiting processes into a unified system where human expertise meets precision automation."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "Partner",
			company: "Vertex Search Partners",
			quote:
				"Topliner reduced our initial research phase from three weeks to two days. The AI matching engine surfaces candidates we would have missed entirely through manual search, and the quality of insights has transformed how we present shortlists to clients.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Henrik Larsson",
			position: "Head of Talent",
			company: "Nordic Ventures",
			quote:
				"We're running eight portfolio companies simultaneously. Topliner's market mapping automation lets us build complete talent landscapes in hours instead of hiring external researchers. That's saved us over €80K this year alone while improving candidate quality.",
			image: "/generated/image-documentary-style-candid-image-of-a-prof.webp"
		},
		{
			name: "Aisha Williams",
			position: "VP of Executive Hiring",
			company: "Quantum Systems",
			quote:
				"Before Topliner, every C-level search meant weeks of spreadsheets and scattered data. Now our team closes senior hires 60% faster with better data confidence. The knowledge-based insights layer is like having a research team that never sleeps.",
			image: "/generated/image-editorial-medium-shot-of-a-professional-.webp"
		}
	]}
/>

<Features
	title="Built for precision at scale"
	subtitle="Infrastructure that transforms human intuition into structured intelligence"
	features={[
		{
			title: "AI matching engine",
			description:
				"Goes beyond keywords to understand context, achievements, and career trajectories. Our AI evaluates candidates through the lens of leadership patterns and strategic fit.",
			icon: IconBrain
		},
		{
			title: "Market mapping automation",
			description:
				"Automatically builds comprehensive talent maps across companies, geographies, and sectors. What used to take weeks now takes hours.",
			icon: IconMap
		},
		{
			title: "Knowledge-based insights",
			description:
				"Unifies open data, search history, and proprietary signals into decision-ready insights that amplify recruiter intuition with precision.",
			icon: IconDatabase
		},
		{
			title: "Weeks to hours",
			description:
				"Executive searches that traditionally took 3-4 weeks are now completed in hours. Speed without compromising accuracy or depth.",
			icon: IconZap
		},
		{
			title: "Network intelligence",
			description:
				"Every search makes the system smarter. Each new firm improves our AI engine, creating compound learning effects across the platform.",
			icon: IconTrendingUp
		},
		{
			title: "Enterprise-ready infrastructure",
			description:
				"Built for high-stakes hiring at scale with security protocols trusted by defense AI firms and venture-backed companies across Europe.",
			icon: IconShield
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to move from weeks to hours?"
	subtitle="Join the AI-powered search revolution"
	description="Every day you wait, your competitors are closing searches faster with better data. Join 30+ firms already using Topliner to transform manual research into precision intelligence. Our network gets smarter with every search—and the advantage compounds."
	imageSrc="/generated/image-editorial-style-portrait-of-a-profession.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Request a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>
