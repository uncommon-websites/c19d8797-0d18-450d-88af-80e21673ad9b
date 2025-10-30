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
	import IconCode from "~icons/lucide/code";
	import IconBrain from "~icons/lucide/brain";
	import IconGitBranch from "~icons/lucide/git-branch";
	import IconNetwork from "~icons/lucide/network";
	import IconBookOpen from "~icons/lucide/book-open";
	import IconZap from "~icons/lucide/zap";
</script>

<CenteredTextOnlyHero
	title="Intelligent automation for modern development teams"
	subtitle="Transform your business operations with advanced machine learning and natural language processing. Built for technical founders who value clarity and power."
	imageSrc="/generated/image-a-modern-interior-space-with-a-large-fea.webp"
/>
<LogoScroller
	label="Trusted by innovative teams"
	logoUrls={[
		'https://cdn.brandfetch.io/github.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We provide developer-first AI infrastructure that makes advanced machine learning accessible to technical teams. Built for tech companies who need powerful AI integration without the specialized talent or implementation complexity.\n\nOur platform captures the $150B AI infrastructure market by turning sophisticated models into simple, well-documented tools that developers can integrate in hours, not months."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Deshmukh",
			position: "Co-founder & CTO",
			company: "VectorAI",
			quote:
				"We cut our model integration time from six weeks to eight days. Their pre-built infrastructure eliminated the need to hire three additional ML engineers, saving us $450K annually in specialized talent costs.",
			image: "/generated/image-professional-indian-woman-engineer-stand.webp"
		},
		{
			name: "Marcus Williams",
			position: "Head of Engineering",
			company: "Synthesis Labs",
			quote:
				"The security compliance framework reduced our audit preparation from two months to three weeks. We avoided a costly data breach that would have cost us our Series A funding and customer trust.",
			image: "/generated/image-professional-black-man-technical-founder.webp"
		},
		{
			name: "Li Wei Chen",
			position: "Founder & CEO",
			company: "Quantum Edge",
			quote:
				"Their documentation and GitHub examples gave our team clarity we desperately needed. We went from zero AI capability to production deployment in 12 weeks instead of the nine months we budgeted.",
			image: "/generated/image-professional-asian-woman-software-develo.webp"
		}
	]}
/>

<Features
	title="Built for developers who ship fast"
	subtitle="Enterprise-grade AI infrastructure with the developer experience you expect from modern tools"
	features={[
		{
			title: "Developer-first APIs",
			description:
				"Integrate advanced ML capabilities in minutes with intuitive APIs and SDKs designed for technical founders. No PhD required to ship production-ready AI features.",
			icon: IconCode
		},
		{
			title: "Proprietary models",
			description:
				"Access our custom-trained models optimized for real-world performance. Built from the ground up to outperform generic solutions on your specific use cases.",
			icon: IconBrain
		},
		{
			title: "Open-source foundation",
			description:
				"Start with our battle-tested open-source tools and demos. Join thousands of developers contributing to the future of AI infrastructure on GitHub.",
			icon: IconGitBranch
		},
		{
			title: "Scales to enterprise",
			description:
				"Deploy with confidence knowing our infrastructure powers production workloads for companies processing billions of requests. From prototype to IPO without switching providers.",
			icon: IconNetwork
		},
		{
			title: "Documentation that doesn't suck",
			description:
				"Clear implementation guides written by engineers, for engineers. Every endpoint documented with runnable examples and real integration patterns.",
			icon: IconBookOpen
		},
		{
			title: "Real-time intelligence",
			description:
				"Transform unstructured data into actionable insights with advanced NLP and automation. Process natural language at scale with sub-100ms latency.",
			icon: IconZap
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Ship AI features in days, not months"
	subtitle="Start building today"
	description="Join hundreds of technical founders who've eliminated integration complexity and shipped production AI without hiring specialized talent. Get started with our open-source tools or talk to our team about enterprise deployment."
	imageSrc="/generated/image-a-confident-business-founder-smiling-in-.webp"
	callsToAction={[
		{
			href: "https://github.com",
			label: "View on GitHub",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
