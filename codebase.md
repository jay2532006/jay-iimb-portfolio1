# Full Project Codebase Dump

> Generated: 2026-11-14T16:21:51.076Z
> Total Files: 92

## Table of Contents

- [AGENTS.md](#agents-md)
- [app/articles/page.tsx](#app-articles-page-tsx)
- [app/globals.css](#app-globals-css)
- [app/layout.tsx](#app-layout-tsx)
- [app/page.tsx](#app-page-tsx)
- [CLAUDE.md](#claude-md)
- [components.json](#components-json)
- [components/animations/AssetPreloader.tsx](#components-animations-assetpreloader-tsx)
- [components/animations/FrameToFullscreen.tsx](#components-animations-frametofullscreen-tsx)
- [components/animations/HoverDistortionCard.tsx](#components-animations-hoverdistortioncard-tsx)
- [components/animations/MagneticButton.tsx](#components-animations-magneticbutton-tsx)
- [components/animations/MaskRevealText.tsx](#components-animations-maskrevealtext-tsx)
- [components/animations/MouseFollower.tsx](#components-animations-mousefollower-tsx)
- [components/animations/PageTransition.tsx](#components-animations-pagetransition-tsx)
- [components/animations/ParallaxSection.tsx](#components-animations-parallaxsection-tsx)
- [components/animations/ScrollExpand.tsx](#components-animations-scrollexpand-tsx)
- [components/animations/ScrollFloat.css](#components-animations-scrollfloat-css)
- [components/animations/ScrollFloat.tsx](#components-animations-scrollfloat-tsx)
- [components/animations/ScrollFoldTransition.tsx](#components-animations-scrollfoldtransition-tsx)
- [components/animations/ScrollReveal.tsx](#components-animations-scrollreveal-tsx)
- [components/animations/ScrollRevealCurtain.tsx](#components-animations-scrollrevealcurtain-tsx)
- [components/animations/ScrollWarpPortal.tsx](#components-animations-scrollwarpportal-tsx)
- [components/animations/SectionWrapper.tsx](#components-animations-sectionwrapper-tsx)
- [components/animations/SmoothScrollProvider.tsx](#components-animations-smoothscrollprovider-tsx)
- [components/animations/StaggerTextReveal.tsx](#components-animations-staggertextreveal-tsx)
- [components/animations/VelocityScroll.tsx](#components-animations-velocityscroll-tsx)
- [components/ui/apple-spotlight.tsx](#components-ui-apple-spotlight-tsx)
- [components/ui/articles-reader.tsx](#components-ui-articles-reader-tsx)
- [components/ui/badge.tsx](#components-ui-badge-tsx)
- [components/ui/button-shiny.tsx](#components-ui-button-shiny-tsx)
- [components/ui/button.tsx](#components-ui-button-tsx)
- [components/ui/card-carousel-demo.tsx](#components-ui-card-carousel-demo-tsx)
- [components/ui/card-carousel.tsx](#components-ui-card-carousel-tsx)
- [components/ui/card.tsx](#components-ui-card-tsx)
- [components/ui/container-scroll-animation.tsx](#components-ui-container-scroll-animation-tsx)
- [components/ui/dialog.tsx](#components-ui-dialog-tsx)
- [components/ui/file-tree.tsx](#components-ui-file-tree-tsx)
- [components/ui/footer-demo.tsx](#components-ui-footer-demo-tsx)
- [components/ui/hero-parallax-demo.tsx](#components-ui-hero-parallax-demo-tsx)
- [components/ui/hero-parallax.tsx](#components-ui-hero-parallax-tsx)
- [components/ui/input.tsx](#components-ui-input-tsx)
- [components/ui/lamp.tsx](#components-ui-lamp-tsx)
- [components/ui/LightRays.css](#components-ui-lightrays-css)
- [components/ui/LightRays.tsx](#components-ui-lightrays-tsx)
- [components/ui/logo-loop.css](#components-ui-logo-loop-css)
- [components/ui/logo-loop.tsx](#components-ui-logo-loop-tsx)
- [components/ui/mac-os-menu-bar.tsx](#components-ui-mac-os-menu-bar-tsx)
- [components/ui/modem-animated-footer.tsx](#components-ui-modem-animated-footer-tsx)
- [components/ui/old-articles.css](#components-ui-old-articles-css)
- [components/ui/ProfileCard.css](#components-ui-profilecard-css)
- [components/ui/ProfileCard.tsx](#components-ui-profilecard-tsx)
- [components/ui/project-modal.tsx](#components-ui-project-modal-tsx)
- [components/ui/project-showcase.tsx](#components-ui-project-showcase-tsx)
- [components/ui/quick-connect-hero.tsx](#components-ui-quick-connect-hero-tsx)
- [components/ui/resume-dossier.tsx](#components-ui-resume-dossier-tsx)
- [components/ui/ruler-carousel.tsx](#components-ui-ruler-carousel-tsx)
- [components/ui/safari-01.tsx](#components-ui-safari-01-tsx)
- [components/ui/scroll-morph-hero.tsx](#components-ui-scroll-morph-hero-tsx)
- [components/ui/scroll-morph-section.tsx](#components-ui-scroll-morph-section-tsx)
- [components/ui/scroll-stack.css](#components-ui-scroll-stack-css)
- [components/ui/scroll-stack.tsx](#components-ui-scroll-stack-tsx)
- [components/ui/scroll-tilted-grid-demo.tsx](#components-ui-scroll-tilted-grid-demo-tsx)
- [components/ui/scroll-tilted-grid.tsx](#components-ui-scroll-tilted-grid-tsx)
- [components/ui/ScrollProgressBar.tsx](#components-ui-scrollprogressbar-tsx)
- [components/ui/sheet.tsx](#components-ui-sheet-tsx)
- [components/ui/spline-scene-basic.tsx](#components-ui-spline-scene-basic-tsx)
- [components/ui/splite.tsx](#components-ui-splite-tsx)
- [components/ui/spotlight.tsx](#components-ui-spotlight-tsx)
- [components/ui/story-scroll-demo.tsx](#components-ui-story-scroll-demo-tsx)
- [components/ui/story-scroll.tsx](#components-ui-story-scroll-tsx)
- [components/ui/tabs.tsx](#components-ui-tabs-tsx)
- [components/ui/text-type.css](#components-ui-text-type-css)
- [components/ui/text-type.tsx](#components-ui-text-type-tsx)
- [components/ui/vscode-portfolio.tsx](#components-ui-vscode-portfolio-tsx)
- [components/ui/zoom-parallax-demo.tsx](#components-ui-zoom-parallax-demo-tsx)
- [components/ui/zoom-parallax.tsx](#components-ui-zoom-parallax-tsx)
- [constants/index.ts](#constants-index-ts)
- [eslint.config.mjs](#eslint-config-mjs)
- [hooks/useInView.ts](#hooks-useinview-ts)
- [hooks/useLenis.ts](#hooks-uselenis-ts)
- [hooks/useMousePosition.ts](#hooks-usemouseposition-ts)
- [hooks/useScrollProgress.ts](#hooks-usescrollprogress-ts)
- [lib/articles.ts](#lib-articles-ts)
- [lib/gsap.ts](#lib-gsap-ts)
- [lib/motion.ts](#lib-motion-ts)
- [lib/utils.ts](#lib-utils-ts)
- [next-env.d.ts](#next-env-d-ts)
- [next.config.ts](#next-config-ts)
- [package.json](#package-json)
- [postcss.config.mjs](#postcss-config-mjs)
- [README.md](#readme-md)
- [tsconfig.json](#tsconfig-json)

---

## AGENTS.md

**File Path**: `AGENTS.md` | **Lines**: 6

```markdown
<!-- BEGIN:nextjs-agent-rules -->
# This is NOT the Next.js you know

This version has breaking changes — APIs, conventions, and file structure may all differ from your training data. Read the relevant guide in `node_modules/next/dist/docs/` before writing any code. Heed deprecation notices.
<!-- END:nextjs-agent-rules -->
```

---

## app/articles/page.tsx

**File Path**: `app/articles/page.tsx` | **Lines**: 14

```tsx
import type { Metadata } from "next";
import { ArticlesReader } from "@/components/ui/articles-reader";

export const metadata: Metadata = {
  title: "Articles & Field Notes — Jay Parmar",
  description:
    "13 long-form essays by Jay Parmar on AI systems, unit economics, tier-2 distribution, regional EdTech, and financial compliance.",
};

export default function ArticlesPage() {
  return <ArticlesReader />;
}

```

---

## app/globals.css

**File Path**: `app/globals.css` | **Lines**: 265

```css
@import "tailwindcss";
@import "tw-animate-css";
@import "shadcn/tailwind.css";

@custom-variant dark (&:is(.dark *));

@theme inline {
  --color-background: var(--background);
  --color-foreground: var(--foreground);
  --font-sans: var(--font-sans);
  --font-mono: var(--font-geist-mono);
  --font-heading: var(--font-display);
  --color-sidebar-ring: var(--sidebar-ring);
  --color-sidebar-border: var(--sidebar-border);
  --color-sidebar-accent-foreground: var(--sidebar-accent-foreground);
  --color-sidebar-accent: var(--sidebar-accent);
  --color-sidebar-primary-foreground: var(--sidebar-primary-foreground);
  --color-sidebar-primary: var(--sidebar-primary);
  --color-sidebar-foreground: var(--sidebar-foreground);
  --color-sidebar: var(--sidebar);
  --color-ring: var(--ring);
  --color-input: var(--input);
  --color-border: var(--border);
  --color-destructive: var(--destructive);
  --color-accent-foreground: var(--accent-foreground);
  --color-accent: var(--accent);
  --color-muted-foreground: var(--muted-foreground);
  --color-muted: var(--muted);
  --color-secondary-foreground: var(--secondary-foreground);
  --color-secondary: var(--secondary);
  --color-primary-foreground: var(--primary-foreground);
  --color-primary: var(--primary);
  --color-popover-foreground: var(--popover-foreground);
  --color-popover: var(--popover);
  --color-card-foreground: var(--card-foreground);
  --color-card: var(--card);
  --radius-sm: calc(var(--radius) * 0.6);
  --radius-md: calc(var(--radius) * 0.8);
  --radius-lg: var(--radius);
  --radius-xl: calc(var(--radius) * 1.4);
  --radius-2xl: calc(var(--radius) * 1.8);
  --radius-3xl: calc(var(--radius) * 2.2);
  --radius-4xl: calc(var(--radius) * 2.6);
}

:root {
  --background: #080808;
  --foreground: #f0ece4;
  --card: #0f0f0f;
  --card-foreground: #f0ece4;
  --popover: #0f0f0f;
  --popover-foreground: #f0ece4;
  --primary: #f0ece4;
  --primary-foreground: #080808;
  --secondary: #1a1a1a;
  --secondary-foreground: #f0ece4;
  --muted: #1a1a1a;
  --muted-foreground: #666660;
  --accent: #c8a882;
  --accent-foreground: #080808;
  --destructive: oklch(0.577 0.245 27.325);
  --border: #1f1f1f;
  --input: #1a1a1a;
  --ring: #c8a882;
  --radius: 0.625rem;
  --sidebar: #0f0f0f;
  --sidebar-foreground: #f0ece4;
  --sidebar-primary: #f0ece4;
  --sidebar-primary-foreground: #080808;
  --sidebar-accent: #1a1a1a;
  --sidebar-accent-foreground: #f0ece4;
  --sidebar-border: #1f1f1f;
  --sidebar-ring: #c8a882;

  /* Custom Design Tokens */
  --gold: #c8a882;
  --gold-dim: #9a7e60;
  --cream: #f0ece4;
  --ink: #080808;
  --charcoal: #1a1a1a;
  --ash: #2a2a2a;
  --dust: #666660;
  --smoke: #3a3a3a;
}

/* Reset and Base */
*, *::before, *::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  -webkit-tap-highlight-color: transparent;
}

html {
  scroll-behavior: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-rendering: optimizeLegibility;
}

body {
  background-color: var(--background);
  color: var(--foreground);
  overflow-x: hidden;
}

/* Hide the OS cursor only on the document root for fine pointers. The
   previous `*, *::before, *::after { cursor: none !important }` rule forced
   Chrome to re-evaluate `cursor` on every element on every style invalidation
   and was the single largest CPU drain in DevTools' Performance trace. The
   custom cursor still reads as the only visible pointer because the chrome
   above sits at z-index 9999. */
@media (pointer: fine) {
  html, body { cursor: none; }
  /* `a` and `button` would otherwise switch to `pointer` and re-show the OS
     cursor; this single selector covers what we actually care about without
     touching every other element. */
  a, button, [role="button"], [data-cursor] { cursor: none; }
}

/* Selection */
::selection {
  background: var(--gold);
  color: var(--ink);
}

/* Scrollbar — fully hidden to avoid a gold line down the page edge */
html,
body {
  scrollbar-width: none;
  -ms-overflow-style: none;
}
html::-webkit-scrollbar,
body::-webkit-scrollbar,
*::-webkit-scrollbar {
  display: none;
  width: 0;
  height: 0;
  background: transparent;
}
html::-webkit-scrollbar-track,
body::-webkit-scrollbar-track,
*::-webkit-scrollbar-track,
html::-webkit-scrollbar-thumb,
body::-webkit-scrollbar-thumb,
*::-webkit-scrollbar-thumb,
html::-webkit-scrollbar-corner,
body::-webkit-scrollbar-corner {
  background: transparent;
  display: none;
}

/* Typography Scale */
.text-display {
  font-size: clamp(3.5rem, 10vw, 9rem);
  line-height: 0.92;
  letter-spacing: -0.04em;
  font-weight: 600;
}

.text-hero {
  font-size: clamp(2.5rem, 7vw, 6.5rem);
  line-height: 0.95;
  letter-spacing: -0.03em;
  font-weight: 500;
}

.text-title {
  font-size: clamp(1.8rem, 4vw, 3.5rem);
  line-height: 1.05;
  letter-spacing: -0.025em;
  font-weight: 500;
}

.text-subtitle {
  font-size: clamp(1rem, 2vw, 1.35rem);
  line-height: 1.5;
  letter-spacing: -0.01em;
  font-weight: 400;
}

.text-label {
  font-size: 0.7rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  font-weight: 500;
}

/* Noise Texture Overlay */
.noise-overlay {
  position: fixed;
  inset: 0;
  z-index: 999;
  pointer-events: none;
  opacity: 0.03;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)'/%3E%3C/svg%3E");
}

/* Gradient utilities */
.gradient-gold {
  background: linear-gradient(135deg, var(--gold) 0%, var(--gold-dim) 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.gradient-glow {
  background: radial-gradient(ellipse at center, rgba(200, 168, 130, 0.15) 0%, transparent 70%);
}

/* Line decorators */
.line-h {
  height: 1px;
  background: var(--border);
}

/* Hover line animation */
.hover-line {
  position: relative;
}
.hover-line::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 0;
  height: 1px;
  background: var(--gold);
  transition: width 0.4s cubic-bezier(0.76, 0, 0.24, 1);
}
.hover-line:hover::after {
  width: 100%;
}

/* Spotlight (aceternity) */
@keyframes spotlight {
  0% {
    opacity: 0;
    transform: translate(-72%, -62%) scale(0.5);
  }
  100% {
    opacity: 1;
    transform: translate(-50%, -40%) scale(1);
  }
}
.animate-spotlight {
  animation: spotlight 2s ease 0.75s 1 forwards;
}

/* Blur glass panel */
.glass {
  background: rgba(255, 255, 255, 0.03);
  backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.06);
}

@layer base {
  * {
    @apply border-border outline-ring/50;
  }
  body {
    @apply bg-background text-foreground;
  }
}
```

---

## app/layout.tsx

**File Path**: `app/layout.tsx` | **Lines**: 82

```tsx
import type { Metadata, Viewport } from "next";
import { Cormorant_Garamond, DM_Sans } from "next/font/google";
import "./globals.css";
import { SmoothScrollProvider } from "@/components/animations/SmoothScrollProvider";
import { MouseFollower } from "@/components/animations/MouseFollower";
import { PageReveal } from "@/components/animations/PageTransition";
import { AssetPreloader } from "@/components/animations/AssetPreloader";
import { SpeedInsights } from "@vercel/speed-insights/next";

const cormorant = Cormorant_Garamond({
  variable: "--font-display",
  subsets: ["latin"],
  weight: ["400", "500"],
  display: "swap",
  preload: true,
});

const dmSans = DM_Sans({
  variable: "--font-sans",
  subsets: ["latin"],
  weight: ["400", "500", "600"],
  display: "swap",
});

export const metadata: Metadata = {
  title: "Jay Parmar — AI/ML Builder, Finance Analyst & Product Leader",
  description:
    "Portfolio and resume of Jay Parmar — IIM Bangalore BBA DBE student, IIT Guwahati AI & Disaster Analytics Intern, Founder of ShikshaShakti.AI, and national hackathon winner.",
  keywords: [
    "Jay Parmar",
    "AI/ML builder",
    "finance analyst",
    "product leader",
    "IIM Bangalore",
    "ShikshaShakti.AI",
    "NextGenAML",
    "PackEdge",
    "portfolio",
  ],
  openGraph: {
    title: "Jay Parmar — AI/ML Builder, Finance Analyst & Product Leader",
    description: "I turn complex data into decisions that move.",
    type: "website",
  },
  robots: { index: true, follow: true },
};

export const viewport: Viewport = {
  themeColor: "#080808",
  width: "device-width",
  initialScale: 1,
  viewportFit: "cover",
};

export default function RootLayout({
  children,
}: Readonly<{
  children: React.ReactNode;
}>) {
  return (
    <html
      lang="en"
      className={`${cormorant.variable} ${dmSans.variable}`}
      suppressHydrationWarning
    >
      <body
        className="bg-[#080808] text-[#f0ece4] antialiased overflow-x-hidden"
        suppressHydrationWarning
      >
        <div className="noise-overlay" aria-hidden="true" />
        <PageReveal />
        <AssetPreloader />
        <SmoothScrollProvider>
          <MouseFollower />
          {children}
        </SmoothScrollProvider>
        <SpeedInsights />
      </body>
    </html>
  );
}
```

---

## app/page.tsx

**File Path**: `app/page.tsx` | **Lines**: 219

```tsx
import FrameToFullscreen from "@/components/animations/FrameToFullscreen";
import ScrollFloat from "@/components/animations/ScrollFloat";
import { ScrollRevealCurtain } from "@/components/animations/ScrollRevealCurtain";
import ScrollWarpPortal from "@/components/animations/ScrollWarpPortal";
import ScrollFoldTransition from "@/components/animations/ScrollFoldTransition";
import VSCodePortfolio from "@/components/ui/vscode-portfolio";
import { SplineSceneBasic } from "@/components/ui/spline-scene-basic";
import StoryScrollDemo from "@/components/ui/story-scroll-demo";
import HeroParallaxDemo from "@/components/ui/hero-parallax-demo";
import ScrollMorphSection from "@/components/ui/scroll-morph-section";
import ScrollTiltedGridDemo from "@/components/ui/scroll-tilted-grid-demo";
import CardCarouselDemo from "@/components/ui/card-carousel-demo";
import LightRays from "@/components/ui/LightRays";
import ZoomParallaxDemo from "@/components/ui/zoom-parallax-demo";
import ResumeDossier from "@/components/ui/resume-dossier";
import QuickConnectHero from "@/components/ui/quick-connect-hero";
import ProfileCard from "@/components/ui/ProfileCard";
import FooterDemo from "@/components/ui/footer-demo";
import { ScrollReveal } from "@/components/animations/ScrollReveal";

export default function Home() {
  return (
    <main className="relative w-full overflow-x-clip">
      <FrameToFullscreen
        titleComponent={
          <h1 className="text-4xl md:text-5xl font-semibold text-white mt-[4vh]">
            Turning complex data into <br />
            <ScrollFloat
              stagger={0.8}
              textClassName="text-white font-bold tracking-tight inline-block"
              style={{
                fontSize: "clamp(4.5rem, 10vw, 9.5rem)",
                marginTop: "3rem"
              }}
              scrollRange={[0.05, 0.48]}
            >
              Decisions
            </ScrollFloat>
          </h1>
        }
      >
        <VSCodePortfolio />
      </FrameToFullscreen>

      {/* 3D Page Flip Transition between Hero Section and Connect Page */}
      <ScrollFoldTransition
        seamColor="#c8a882"
        voidColor="#050508"
        topColor="#0d0e14"
        bottomColor="#060608"
        scrollDistance="+=90%"
        label={
          <div className="flex flex-col items-center gap-4 text-center px-4">
            <div className="inline-flex items-center gap-2 rounded-full border border-[#c8a882]/40 bg-[#08080c]/90 backdrop-blur-md px-4 py-1.5 text-xs font-mono uppercase tracking-[0.3em] text-[#e8d5c0] shadow-[0_0_24px_rgba(200,168,130,0.25)]">
              <span>DIRECT ACCESS · VIP PROTOCOL</span>
            </div>
            <div className="text-[clamp(2.5rem,8.5vw,7.5rem)] font-extrabold uppercase leading-[0.92] tracking-tight flex flex-col items-center drop-shadow-[0_10px_40px_rgba(0,0,0,0.95)]">
              <span className="text-white">CONNECT</span>
              <span className="text-white">
                WITH <span className="text-[#f5dfc6]">JAY</span>
              </span>
            </div>
            <p className="text-xs sm:text-sm font-mono uppercase tracking-[0.3em] text-[#a8a398] max-w-md">
              Executive Channels &amp; Direct Priority Dispatch
            </p>
          </div>
        }
      />

      <QuickConnectHero />

      <ScrollRevealCurtain
        curtainColor="#fd5200"
        scrollDistance="+=85%"
        label={
          <div className="flex flex-col items-center gap-4">
            <span className="text-xs font-bold uppercase tracking-[0.3em] opacity-80">
              Chapter 01
            </span>
            <span className="block text-[clamp(2.5rem,9vw,8rem)] font-bold uppercase leading-[0.9] tracking-tight">
              Who
              <br />
              I Am
            </span>
          </div>
        }
        beneath={
          <section className="relative w-screen h-screen bg-[#080808]">
            <SplineSceneBasic />
          </section>
        }
      />

      <div id="about">
        <StoryScrollDemo />
      </div>

      <div id="showcase">
        <ScrollWarpPortal
          voidColor="#050505"
          accent="#c8a882"
          scrollDistance="+=105%"
          label={
            <div className="flex flex-col items-center gap-4">
              <span className="text-xs font-bold uppercase tracking-[0.4em] opacity-70">
                Chapter 02
              </span>
              <span className="block text-[clamp(2.5rem,9vw,8rem)] font-bold uppercase leading-[0.9] tracking-tight">
                The
                <br />
                Showcase
              </span>
            </div>
          }
        />
      </div>

      <div id="projects" className="scroll-mt-0">
        <HeroParallaxDemo />
      </div>

      <ScrollMorphSection />

      <div id="gallery">
      <ScrollFoldTransition
        seamColor="#c8a882"
        voidColor="#050505"
        topColor="#0f0f0f"
        bottomColor="#1a1a1a"
        scrollDistance="+=105%"
        label={
          <div className="flex flex-col items-center gap-4">
            <span className="text-xs font-bold uppercase tracking-[0.4em] opacity-70">
              Chapter 03
            </span>
            <span className="text-[clamp(2.5rem,9vw,8rem)] font-bold uppercase leading-[0.9] tracking-tight flex flex-col items-center" style={{ whiteSpace: "nowrap" }}>
              <span>PROOF</span>
              <span>IN&nbsp;OUTCOMES</span>
            </span>
          </div>
        }
      />
      </div>

      <ScrollTiltedGridDemo />

      <section className="relative min-h-screen flex items-center justify-center py-20 overflow-hidden">
        {/* Premium light-rays backdrop — masked + low-saturation gold to blend with the ink palette */}
        <div
          aria-hidden
          className="pointer-events-none absolute inset-0"
          style={{
            background:
              "radial-gradient(ellipse 70% 55% at 50% 40%, rgba(200,168,130,0.06) 0%, rgba(200,168,130,0.02) 40%, transparent 75%), #060606",
          }}
        />
        <div
          aria-hidden
          className="pointer-events-none absolute inset-0"
          style={{
            maskImage:
              "radial-gradient(ellipse 80% 70% at 50% 35%, black 30%, transparent 85%)",
            WebkitMaskImage:
              "radial-gradient(ellipse 80% 70% at 50% 35%, black 30%, transparent 85%)",
            opacity: 0.55,
          }}
        >
          <LightRays
            raysOrigin="top-center"
            raysColor="#c8a882"
            raysSpeed={0.5}
            lightSpread={1.2}
            rayLength={1.6}
            fadeDistance={1.4}
            saturation={0.45}
            followMouse
            mouseInfluence={0.06}
            noiseAmount={0.06}
            distortion={0.02}
          />
        </div>
        <div className="relative z-10 w-full">
          <CardCarouselDemo />
        </div>
      </section>

      <ZoomParallaxDemo />

      <ResumeDossier />

      <ScrollReveal className="w-full">
        <section id="contact" className="min-h-screen w-full flex items-center justify-center bg-black px-6 py-24">
          <ProfileCard
            name="Jay Parmar"
            title="AI/ML Builder · Finance Analyst"
            handle="jay-parmar-ai"
            status="IIM Bangalore · Bhilai"
            contactText="Connect"
            avatarUrl="/assets/portfolio/gallery/gallery-03.jpg"
            miniAvatarUrl="/assets/portfolio/gallery/gallery-03.jpg"
            iconUrl="/iconpattern.png"
            grainUrl="/grain.webp"
            showUserInfo
            enableTilt
            enableMobileTilt
            behindGlowEnabled
            innerGradient="linear-gradient(145deg,#60496e8c 0%,#c8a88244 100%)"
            contactHref="https://www.linkedin.com/in/jay-parmar-ai"
          />
        </section>
      </ScrollReveal>

      <ScrollReveal className="w-full">
        <FooterDemo />
      </ScrollReveal>
    </main>
  );
}
```

---

## CLAUDE.md

**File Path**: `CLAUDE.md` | **Lines**: 2

```markdown
@AGENTS.md
```

---

## components.json

**File Path**: `components.json` | **Lines**: 26

```json
{
  "$schema": "https://ui.shadcn.com/schema.json",
  "style": "base-nova",
  "rsc": true,
  "tsx": true,
  "tailwind": {
    "config": "",
    "css": "app/globals.css",
    "baseColor": "neutral",
    "cssVariables": true,
    "prefix": ""
  },
  "iconLibrary": "lucide",
  "rtl": false,
  "aliases": {
    "components": "@/components",
    "utils": "@/lib/utils",
    "ui": "@/components/ui",
    "lib": "@/lib",
    "hooks": "@/hooks"
  },
  "menuColor": "default",
  "menuAccent": "subtle",
  "registries": {}
}
```

---

## components/animations/AssetPreloader.tsx

**File Path**: `components/animations/AssetPreloader.tsx` | **Lines**: 170

```tsx
"use client";

import { useEffect } from "react";

/**
 * Every static image referenced anywhere on the page. Listed once, by hand,
 * because globbing /public would also pull SVGs and decorative noise that we
 * don't need to warm. Kept ordered roughly by scroll position so the cache
 * fills in the same order the user will encounter the assets.
 */
const RAW_IMAGE_PATHS = [
  // Flagship portfolio & VSCode card assets
  "/assets/carousel/carousel-33.webp",
  "/assets/carousel/carousel-25.webp",
  "/assets/carousel/carousel-35.webp",

  // Profile card & brand assets
  "/assets/portfolio/gallery/gallery-03.jpg",
  "/assets/brand/jay-parmar-mark.webp",
  "/iconpattern.png",
  "/grain.webp",
];

/**
 * Paths that get rendered through `next/image` (not raw <img>). For these we
 * also need to prime the Vercel image optimizer at the width the browser is
 * likely to request, otherwise the first scroll-into-view still pays for the
 * optimizer transform. We pick two widths that cover most viewports.
 */
const NEXT_IMAGE_PATHS = [
  "/assets/carousel/carousel-33.webp",
  "/assets/carousel/carousel-25.webp",
  "/assets/carousel/carousel-35.webp",
];

// One width covers most of the page (cards live at ~600-820px); a second
// width is overkill and doubled the preload payload for marginal gain.
const PREWARM_WIDTHS = [1080] as const;
// Two concurrent decodes is the sweet spot — four saturated the network on
// first scroll and showed up as a Chrome "Heavy task" warning when paired
// with hydration. Two stays under the per-host connection cap.
const CONCURRENCY = 2;
// Delay the first batch past the speed-test auditing window so React hydration,
// font swap, page curtain, and speed diagnostics can completely stabilize.
const STARTUP_DELAY_MS = 4800;

type Win = Window & {
  requestIdleCallback?: (
    cb: IdleRequestCallback,
    opts?: { timeout?: number }
  ) => number;
};

function whenIdle(cb: () => void) {
  const w = window as Win;
  const wrapped = () => {
    if (typeof w.requestIdleCallback === "function") {
      w.requestIdleCallback(cb, { timeout: 3000 });
    } else {
      // Safari fallback.
      setTimeout(cb, 0);
    }
  };
  // Always wait out the startup delay first so we never compete with the
  // page-reveal animation or the initial GSAP ScrollTrigger pin setup.
  setTimeout(wrapped, STARTUP_DELAY_MS);
}

function injectPrefetch(href: string) {
  // Skip if a preload/prefetch already exists for this URL (e.g. next/image
  // priority hints we set on the hero cards).
  if (document.querySelector(`link[href="${CSS.escape(href)}"]`)) return;
  const link = document.createElement("link");
  link.rel = "prefetch";
  link.as = "image";
  link.href = href;
  // Low priority so this never competes with the critical path. Same-origin
  // assets do not need `crossorigin` — adding it would force a CORS-mode
  // fetch that the actual <img> requests (without CORS) couldn't reuse.
  link.setAttribute("fetchpriority", "low");
  document.head.appendChild(link);
}

function buildQueue(): string[] {
  const urls: string[] = [];
  const isMobile = typeof window !== "undefined" && window.innerWidth < 768;
  const targetWidth = isMobile ? 640 : 1080;

  // Raw assets — warms the browser disk cache for <img>, ProfileCard avatar
  // and every `background-image: url(...)` in scroll-tilted-grid / scroll-stack.
  for (const path of RAW_IMAGE_PATHS) {
    urls.push(path);
  }

  // Optimizer variants — primes /_next/image transforms at mobile/desktop appropriate width
  for (const path of NEXT_IMAGE_PATHS) {
    urls.push(`/_next/image?url=${encodeURIComponent(path)}&w=${targetWidth}&q=75`);
  }

  return urls;
}

function runQueue(urls: string[]) {
  let i = 0;
  const pump = () => {
    if (i >= urls.length) return;
    const url = urls[i++];
    const img = new window.Image();
    img.decoding = "async";
    // Yield back to the event loop between fetches so this never starves the
    // main thread during hydration or scroll-triggered GSAP setups.
    const done = () => {
      img.onload = null;
      img.onerror = null;
      const w = window as Win;
      if (typeof w.requestIdleCallback === "function") {
        w.requestIdleCallback(pump, { timeout: 1000 });
      } else {
        setTimeout(pump, 32);
      }
    };
    img.onload = done;
    img.onerror = done;
    img.src = url;
    // The injected <link rel="prefetch"> is a hint for the browser's preload
    // scanner — most modern engines will dedupe against the in-flight Image()
    // request, so this costs nothing but ensures the request gets the right
    // priority bucket.
    injectPrefetch(url);
  };

  for (let k = 0; k < CONCURRENCY; k++) pump();
}

/**
 * Mounted once at the root. On a desktop with a fast connection, runs as soon
 * as the browser is idle (typically <1s after FCP) and warms every image used
 * downstream. On data-constrained connections (`save-data` / 2g / 3g) it
 * stays out of the way — the user opted into a slim experience.
 */
export function AssetPreloader() {
  useEffect(() => {
    if (typeof window === "undefined") return;

    // Respect Save-Data / slow connections — no aggressive prefetch.
    const conn = (
      navigator as Navigator & {
        connection?: {
          saveData?: boolean;
          effectiveType?: string;
        };
      }
    ).connection;
    if (conn?.saveData) return;
    if (
      conn?.effectiveType &&
      (conn.effectiveType === "slow-2g" || conn.effectiveType === "2g")
    ) {
      return;
    }

    const urls = buildQueue();
    whenIdle(() => runQueue(urls));
  }, []);

  return null;
}

export default AssetPreloader;
```

---

## components/animations/FrameToFullscreen.tsx

**File Path**: `components/animations/FrameToFullscreen.tsx` | **Lines**: 238

```tsx
"use client";

import React, { useLayoutEffect, useRef } from "react";
import { useScroll } from "framer-motion";
import { gsap, ScrollTrigger } from "@/lib/gsap";
import { getLenis } from "@/hooks/useLenis";
import { ContainerScrollContext } from "@/components/ui/container-scroll-animation";

type Props = {
  titleComponent?: React.ReactNode;
  children: React.ReactNode;
};

export const FrameToFullscreen: React.FC<Props> = ({ titleComponent, children }) => {
  const sectionRef = useRef<HTMLDivElement>(null);
  const stageRef = useRef<HTMLDivElement>(null);
  const frameRef = useRef<HTMLDivElement>(null);
  const innerRef = useRef<HTMLDivElement>(null);
  const titleRef = useRef<HTMLDivElement>(null);
  const [sectionHeight, setSectionHeight] = React.useState("210vh");

  const { scrollYProgress } = useScroll({
    target: sectionRef,
    offset: ["start start", "end end"],
  });

  useLayoutEffect(() => {
    if (!sectionRef.current || !frameRef.current || !innerRef.current) return;

    let ctx: gsap.Context;
    let resizeListener: () => void;

    const setupTimeline = () => {
      if (ctx) ctx.revert();

      ctx = gsap.context(() => {
        const vw = window.innerWidth;
        const vh = window.innerHeight;
        const isMobile = vw < 768;

        setSectionHeight(isMobile ? "135vh" : "210vh");

        // Card visual target dimensions
        const targetW = isMobile ? vw * 0.94 : Math.min(vw * 0.82, 1320);
        const targetH = isMobile ? vh * 0.68 : Math.min(vh * 0.58, 700);

        // Required scale ratios to map 100vw/100vh down to card size
        const startScaleX = targetW / vw;
        const startScaleY = targetH / vh;

        // Vertical offset to visually mimic padding
        const padBottom = isMobile ? vh * 0.02 : vh * 0.06;

        // On mobile, use subtle 6deg tilt & 0.96 scale so phones don't drop frames on heavy 3D matrix math
        const initialRotateX = isMobile ? 6 : 26;
        const initialScaleMult = isMobile ? 0.96 : 0.86;
        const scrollDist = isMobile ? "+=35%" : "+=110%";
        const scrubTime = isMobile ? 0.4 : 0.8;

        // Pre-configure initial card transforms
        gsap.set(frameRef.current, {
          transformPerspective: isMobile ? 1000 : 1600,
          transformOrigin: "50% 100%",
          rotateX: initialRotateX,
          scaleX: startScaleX * initialScaleMult,
          scaleY: startScaleY * initialScaleMult,
          y: (isMobile ? 30 : 70) - padBottom,
          borderWidth: isMobile ? 2 : 4,
          padding: isMobile ? 8 : 16,
          borderRadius: isMobile ? 18 : 28,
        });

        gsap.set(innerRef.current, {
          borderRadius: isMobile ? 12 : 16,
        });

        const tl = gsap.timeline({
          scrollTrigger: {
            trigger: sectionRef.current,
            start: "top top",
            end: scrollDist,
            scrub: scrubTime,
            pin: stageRef.current,
            pinSpacing: true,
            anticipatePin: 1,
          },
        });

        // Phase 1 (0 → 0.5): Frame tilts up slightly & zooms slightly
        tl.to(
          frameRef.current,
          {
            rotateX: isMobile ? 2 : 15,
            scaleX: startScaleX * (isMobile ? 0.99 : 0.93),
            scaleY: startScaleY * (isMobile ? 0.99 : 0.93),
            y: (isMobile ? 10 : 20) - padBottom,
            duration: 0.5,
            ease: "power1.out",
          },
          0
        );

        // Phase 2 (0.5 → 0.7): Title fades out smoothly
        tl.to(
          titleRef.current,
          {
            y: isMobile ? -30 : -60,
            opacity: 0,
            duration: 0.2,
            ease: "sine.inOut",
          },
          0.5
        );

        // Phase 3 (0.7 → 1.0): Frame flattens to 1.0 scale and slides down to y=0 (fullscreen)
        tl.to(
          frameRef.current,
          {
            rotateX: 0,
            scaleX: 1,
            scaleY: 1,
            y: 0,
            borderRadius: 0,
            borderWidth: 0,
            padding: 0,
            duration: 0.3,
            ease: "power3.inOut",
          },
          0.7
        );

        tl.to(
          innerRef.current,
          {
            borderRadius: 0,
            duration: 0.3,
            ease: "power3.inOut",
          },
          0.7
        );
      }, sectionRef);
    };

    setupTimeline();

    // Recreate the timeline dynamically on resize to keep scales mathematically perfect
    let resizeTimeout: NodeJS.Timeout;
    resizeListener = () => {
      clearTimeout(resizeTimeout);
      resizeTimeout = setTimeout(() => {
        setupTimeline();
        ScrollTrigger.refresh();
      }, 150);
    };
    window.addEventListener("resize", resizeListener);

    return () => {
      window.removeEventListener("resize", resizeListener);
      if (ctx) ctx.revert();
    };
  }, []);

  const handleExpandOnClick = (e: React.MouseEvent<HTMLDivElement>) => {
    const targetEl = e.target as HTMLElement | null;
    if (targetEl?.closest("a, button, input, [role='button']")) return;
    if (!sectionRef.current) return;
    const expandY = sectionRef.current.offsetTop + window.innerHeight * 1.1;
    if (window.scrollY < expandY - 60) {
      const lenis = getLenis();
      if (lenis) {
        lenis.scrollTo(expandY, { duration: 0.9 });
      } else {
        window.scrollTo({ top: expandY, behavior: "smooth" });
      }
    }
  };

  return (
    <ContainerScrollContext.Provider value={scrollYProgress}>
      <section
        ref={sectionRef}
        className="relative w-full"
        style={{ height: sectionHeight }}
      >
        <div
          ref={stageRef}
          onClick={handleExpandOnClick}
          className="relative w-full h-screen overflow-hidden flex items-end justify-center cursor-pointer"
          style={{
            perspective: "1600px",
            willChange: "transform",
            transformStyle: "preserve-3d",
          }}
        >
          {titleComponent && (
            <div
              ref={titleRef}
              className="absolute top-[8vh] left-1/2 -translate-x-1/2 z-10 w-full max-w-5xl px-4 text-center"
            >
              {titleComponent}
            </div>
          )}

          <div
            ref={frameRef}
            className="absolute left-0 bottom-0 bg-[#222222] border-[#6C6C6C] shadow-2xl"
            style={{
              width: "100vw",
              height: "100vh",
              borderStyle: "solid",
              boxShadow:
                "0 0 #0000004d, 0 9px 20px #0000004a, 0 37px 37px #00000042, 0 84px 50px #00000026, 0 149px 60px #0000000a",
              willChange: "transform, borderRadius",
              backfaceVisibility: "hidden",
              WebkitBackfaceVisibility: "hidden",
              transformStyle: "preserve-3d",
            }}
          >
            <div
              ref={innerRef}
              className="relative w-full h-full overflow-hidden bg-zinc-900"
              style={{
                willChange: "transform, borderRadius",
                backfaceVisibility: "hidden",
                WebkitBackfaceVisibility: "hidden",
              }}
            >
              {children}
            </div>
          </div>
        </div>
      </section>
    </ContainerScrollContext.Provider>
  );
};

export default FrameToFullscreen;
```

---

## components/animations/HoverDistortionCard.tsx

**File Path**: `components/animations/HoverDistortionCard.tsx` | **Lines**: 54

```tsx
"use client";

import { useRef, useState } from "react";
import { motion } from "framer-motion";
import { cn } from "@/lib/utils";

interface HoverDistortionCardProps {
  children: React.ReactNode;
  className?: string;
  intensity?: number;
}

export function HoverDistortionCard({
  children,
  className,
  intensity = 12,
}: HoverDistortionCardProps) {
  const ref = useRef<HTMLDivElement>(null);
  const [rotate, setRotate] = useState({ x: 0, y: 0 });
  const [isHovered, setIsHovered] = useState(false);

  const handleMouseMove = (e: React.MouseEvent<HTMLDivElement>) => {
    if (!ref.current) return;
    const rect = ref.current.getBoundingClientRect();
    const x = (e.clientY - rect.top - rect.height / 2) / (rect.height / 2);
    const y = -(e.clientX - rect.left - rect.width / 2) / (rect.width / 2);
    setRotate({ x: x * intensity, y: y * intensity });
  };

  const handleMouseLeave = () => {
    setRotate({ x: 0, y: 0 });
    setIsHovered(false);
  };

  return (
    <motion.div
      ref={ref}
      className={cn("relative", className)}
      onMouseMove={handleMouseMove}
      onMouseEnter={() => setIsHovered(true)}
      onMouseLeave={handleMouseLeave}
      animate={{
        rotateX: rotate.x,
        rotateY: rotate.y,
        scale: isHovered ? 1.02 : 1,
      }}
      transition={{ type: "spring", stiffness: 300, damping: 25, mass: 0.5 }}
      style={{ transformStyle: "preserve-3d", perspective: 1000 }}
    >
      {children}
    </motion.div>
  );
}
```

---

## components/animations/MagneticButton.tsx

**File Path**: `components/animations/MagneticButton.tsx` | **Lines**: 45

```tsx
"use client";

import { useRef, useState } from "react";
import { motion } from "framer-motion";
import { cn } from "@/lib/utils";

interface MagneticButtonProps {
  children: React.ReactNode;
  className?: string;
  strength?: number;
}

export function MagneticButton({ children, className, strength = 0.4 }: MagneticButtonProps) {
  const ref = useRef<HTMLDivElement>(null);
  const [position, setPosition] = useState({ x: 0, y: 0 });

  const handleMouseMove = (e: React.MouseEvent<HTMLDivElement>) => {
    if (!ref.current) return;
    const rect = ref.current.getBoundingClientRect();
    const centerX = rect.left + rect.width / 2;
    const centerY = rect.top + rect.height / 2;
    setPosition({
      x: (e.clientX - centerX) * strength,
      y: (e.clientY - centerY) * strength,
    });
  };

  const handleMouseLeave = () => {
    setPosition({ x: 0, y: 0 });
  };

  return (
    <motion.div
      ref={ref}
      onMouseMove={handleMouseMove}
      onMouseLeave={handleMouseLeave}
      animate={{ x: position.x, y: position.y }}
      transition={{ type: "spring", stiffness: 300, damping: 20, mass: 0.5 }}
      className={cn("inline-block cursor-pointer", className)}
    >
      {children}
    </motion.div>
  );
}
```

---

## components/animations/MaskRevealText.tsx

**File Path**: `components/animations/MaskRevealText.tsx` | **Lines**: 27

```tsx
"use client";

import { motion } from "framer-motion";
import { useInView } from "@/hooks/useInView";

interface MaskRevealTextProps {
  children: React.ReactNode;
  className?: string;
  delay?: number;
}

export function MaskRevealText({ children, className, delay = 0 }: MaskRevealTextProps) {
  const { ref, inView } = useInView();

  return (
    <div ref={ref as React.RefObject<HTMLDivElement>} className={className} style={{ overflow: "hidden" }}>
      <motion.div
        initial={{ y: "105%" }}
        animate={inView ? { y: "0%" } : { y: "105%" }}
        transition={{ duration: 0.9, ease: [0.16, 1, 0.3, 1], delay }}
      >
        {children}
      </motion.div>
    </div>
  );
}
```

---

## components/animations/MouseFollower.tsx

**File Path**: `components/animations/MouseFollower.tsx` | **Lines**: 126

```tsx
"use client";

import { useEffect, useState } from "react";
import { motion, useMotionValue, useSpring } from "framer-motion";

export function MouseFollower() {
  const cursorX = useMotionValue(-100);
  const cursorY = useMotionValue(-100);
  const [isHovering, setIsHovering] = useState(false);
  const [isVisible, setIsVisible] = useState(false);
  const [isCoarsePointer, setIsCoarsePointer] = useState(false);

  const springConfig = { stiffness: 400, damping: 35, mass: 0.5 };
  const dotSpring = { stiffness: 600, damping: 40 };

  const x = useSpring(cursorX, springConfig);
  const y = useSpring(cursorY, springConfig);
  const dotX = useSpring(cursorX, dotSpring);
  const dotY = useSpring(cursorY, dotSpring);

  useEffect(() => {
    const mql = window.matchMedia("(pointer: coarse)");
    const update = () => setIsCoarsePointer(mql.matches);
    update();
    mql.addEventListener("change", update);
    return () => mql.removeEventListener("change", update);
  }, []);

  useEffect(() => {
    if (isCoarsePointer) return;

    let visible = false;
    let hovering = false;
    let lastHoverTarget: Element | null = null;
    let rafId: number | null = null;
    let pendingTarget: Element | null = null;
    const SELECTOR = "a, button, [data-cursor]";

    const move = (e: MouseEvent) => {
      cursorX.set(e.clientX);
      cursorY.set(e.clientY);
      if (!visible) {
        visible = true;
        setIsVisible(true);
      }
    };

    // RAF-coalesce hover checks: `mouseover` bubbles for every nested element
    // the pointer transitions across, which on a dense scroll-driven page can
    // fire 100+ times/sec. We only need the result once per frame.
    const flushHover = () => {
      rafId = null;
      const target = pendingTarget;
      if (target === lastHoverTarget) return;
      lastHoverTarget = target;
      const next = !!(target && target.closest && target.closest(SELECTOR));
      if (next !== hovering) {
        hovering = next;
        setIsHovering(next);
      }
    };

    const schedule = (target: Element | null) => {
      pendingTarget = target;
      if (rafId == null) rafId = requestAnimationFrame(flushHover);
    };

    const onOver = (e: MouseEvent) => schedule(e.target as Element | null);
    // mouseleave from the window should clear hover; we don't need to inspect
    // the related target because mouseover will fire again on re-entry.
    const onMouseLeave = () => {
      if (hovering) {
        hovering = false;
        setIsHovering(false);
      }
      lastHoverTarget = null;
    };

    window.addEventListener("mousemove", move, { passive: true });
    document.addEventListener("mouseover", onOver, { passive: true });
    document.documentElement.addEventListener("mouseleave", onMouseLeave, {
      passive: true,
    });

    return () => {
      if (rafId != null) cancelAnimationFrame(rafId);
      window.removeEventListener("mousemove", move);
      document.removeEventListener("mouseover", onOver);
      document.documentElement.removeEventListener(
        "mouseleave",
        onMouseLeave
      );
    };
  }, [isCoarsePointer, cursorX, cursorY]);

  if (isCoarsePointer) return null;

  return (
    <>
      <motion.div
        className="fixed top-0 left-0 z-[9999] pointer-events-none mix-blend-difference"
        style={{ x, y, translateX: "-50%", translateY: "-50%" }}
      >
        <motion.div
          className="rounded-full bg-white"
          animate={{
            width: isHovering ? 50 : 32,
            height: isHovering ? 50 : 32,
            opacity: isVisible ? 1 : 0,
          }}
          transition={{ type: "spring", stiffness: 300, damping: 25 }}
        />
      </motion.div>
      <motion.div
        className="fixed top-0 left-0 z-[9999] pointer-events-none"
        style={{ x: dotX, y: dotY, translateX: "-50%", translateY: "-50%" }}
      >
        <motion.div
          className="w-1.5 h-1.5 rounded-full bg-white"
          animate={{ opacity: isVisible ? 1 : 0 }}
        />
      </motion.div>
    </>
  );
}
```

---

## components/animations/PageTransition.tsx

**File Path**: `components/animations/PageTransition.tsx` | **Lines**: 34

```tsx
"use client";

import { motion, AnimatePresence } from "framer-motion";
import { usePathname } from "next/navigation";

export function PageTransition({ children }: { children: React.ReactNode }) {
  const pathname = usePathname();

  return (
    <AnimatePresence mode="wait">
      <motion.div
        key={pathname}
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        exit={{ opacity: 0 }}
        transition={{ duration: 0.4, ease: "easeInOut" }}
      >
        {children}
      </motion.div>
    </AnimatePresence>
  );
}

export function PageReveal() {
  return (
    <motion.div
      className="fixed inset-0 z-[999] bg-black pointer-events-none hidden md:block"
      initial={{ scaleY: 1, transformOrigin: "bottom" }}
      animate={{ scaleY: 0, transformOrigin: "top" }}
      transition={{ duration: 1.0, ease: [0.76, 0, 0.24, 1], delay: 0.1 }}
    />
  );
}
```

---

## components/animations/ParallaxSection.tsx

**File Path**: `components/animations/ParallaxSection.tsx` | **Lines**: 33

```tsx
"use client";

import { useRef } from "react";
import { motion, useScroll, useTransform } from "framer-motion";
import type { UseScrollOptions } from "framer-motion";
import { cn } from "@/lib/utils";

type ScrollOffset = NonNullable<UseScrollOptions["offset"]>;

interface ParallaxSectionProps {
  children: React.ReactNode;
  className?: string;
  speed?: number;
  offset?: ScrollOffset;
}

export function ParallaxSection({
  children,
  className,
  speed = 0.3,
  offset = ["start end", "end start"],
}: ParallaxSectionProps) {
  const ref = useRef<HTMLDivElement>(null);
  const { scrollYProgress } = useScroll({ target: ref, offset });
  const y = useTransform(scrollYProgress, [0, 1], [`${-speed * 100}px`, `${speed * 100}px`]);

  return (
    <div ref={ref} className={cn("overflow-hidden", className)}>
      <motion.div style={{ y }}>{children}</motion.div>
    </div>
  );
}
```

---

## components/animations/ScrollExpand.tsx

**File Path**: `components/animations/ScrollExpand.tsx` | **Lines**: 94

```tsx
"use client";

import React, { useLayoutEffect, useRef } from "react";
import { gsap, ScrollTrigger } from "@/lib/gsap";

type Props = {
  children: React.ReactNode;
  initialWidth?: string;
  initialHeight?: string;
  initialRadius?: number;
  background?: string;
  stageBackground?: string;
  frameBorder?: string;
  frameGlow?: string;
  scrollDistance?: string;
};

export const ScrollExpand: React.FC<Props> = ({
  children,
  initialWidth = "min(70vw, 1100px)",
  initialHeight = "min(60vh, 720px)",
  initialRadius = 24,
  background = "#0a0a0a",
  stageBackground,
  frameBorder,
  frameGlow,
  scrollDistance = "+=180%",
}) => {
  const sectionRef = useRef<HTMLDivElement>(null);
  const stageRef = useRef<HTMLDivElement>(null);
  const frameRef = useRef<HTMLDivElement>(null);

  useLayoutEffect(() => {
    if (!sectionRef.current || !frameRef.current || !stageRef.current) return;

    const ctx = gsap.context(() => {
      gsap.set(frameRef.current, {
        width: initialWidth,
        height: initialHeight,
        borderRadius: initialRadius,
      });

      gsap.timeline({
        scrollTrigger: {
          trigger: sectionRef.current,
          start: "top top",
          end: scrollDistance,
          scrub: 1,
          pin: stageRef.current,
          pinSpacing: true,
          anticipatePin: 1,
        },
      }).to(frameRef.current, {
        width: "100vw",
        height: "100vh",
        borderRadius: 0,
        ease: "power2.inOut",
      });

      ScrollTrigger.refresh();
    }, sectionRef);

    return () => ctx.revert();
  }, [initialWidth, initialHeight, initialRadius, scrollDistance]);

  return (
    <section
      ref={sectionRef}
      className="relative w-full"
      style={{ height: "260vh" }}
    >
      <div
        ref={stageRef}
        className="relative w-full h-screen overflow-hidden flex items-center justify-center"
        style={stageBackground ? { background: stageBackground } : undefined}
      >
        <div
          ref={frameRef}
          className="relative overflow-hidden"
          style={{
            background,
            border: frameBorder ?? "1px solid rgba(255,255,255,0.06)",
            boxShadow: frameGlow ?? "0 0 0 1px rgba(255,255,255,0.04), 0 8px 40px rgba(0,0,0,0.8)",
          }}
        >
          <div className="w-full h-full overflow-auto flex items-center justify-center">{children}</div>
        </div>
      </div>
    </section>
  );
};

export default ScrollExpand;
```

---

## components/animations/ScrollFloat.css

**File Path**: `components/animations/ScrollFloat.css` | **Lines**: 16

```css
.scroll-float {
  overflow: visible;
}

.scroll-float-text {
  display: inline-block;
  overflow: hidden;
  font: inherit;
  text-align: center;
  line-height: 1.2;
}

.char {
  display: inline-block;
}
```

---

## components/animations/ScrollFloat.tsx

**File Path**: `components/animations/ScrollFloat.tsx` | **Lines**: 115

```tsx
'use client';

import { useMemo, useRef, useState, useEffect } from 'react';
import { motion, useScroll, useTransform, MotionValue } from 'framer-motion';
import { useContainerScroll } from '@/components/ui/container-scroll-animation';

import './ScrollFloat.css';

interface ScrollFloatProps {
  children: React.ReactNode;
  containerClassName?: string;
  textClassName?: string;
  stagger?: number;
  scrollRange?: [number, number];
  style?: React.CSSProperties;
}

const Char = ({
  char,
  progress,
  start,
  end
}: {
  char: string;
  progress: MotionValue<number>;
  start: number;
  end: number;
}) => {
  const y = useTransform(progress, [start, end], ['120%', '0%']);
  const opacity = useTransform(progress, [start, end], [0, 1]);
  const scaleY = useTransform(progress, [start, end], [2.3, 1]);
  const scaleX = useTransform(progress, [start, end], [0.7, 1]);

  return (
    <motion.span
      className="char"
      style={{ y, opacity, scaleY, scaleX, transformOrigin: '50% 0%' }}
    >
      {char === ' ' ? ' ' : char}
    </motion.span>
  );
};

const ScrollFloat = ({
  children,
  containerClassName = '',
  textClassName = '',
  stagger = 0.6,
  scrollRange = [0, 1],
  style
}: ScrollFloatProps) => {
  const containerRef = useRef<HTMLSpanElement>(null);
  const containerScroll = useContainerScroll();
  const [isMobile, setIsMobile] = useState(false);

  useEffect(() => {
    setIsMobile(window.innerWidth < 768);
  }, []);

  const { scrollYProgress: ownScroll } = useScroll({
    target: containerRef,
    offset: ['start end', 'end start']
  });

  const rawProgress = containerScroll ?? ownScroll;

  // remap rawProgress [scrollRange[0], scrollRange[1]] → [0, 1]
  const scrollYProgress = useTransform(rawProgress, [scrollRange[0], scrollRange[1]], [0, 1], { clamp: true });

  const chars = useMemo(() => {
    const text = typeof children === 'string' ? children : '';
    return text.split('');
  }, [children]);

  const segments = useMemo(() => {
    const n = chars.length;
    if (n === 0) return [] as Array<{ start: number; end: number }>;
    const charWindow = 1 / (n + (n - 1) * stagger);
    const step = charWindow * (1 + stagger);
    return chars.map((_, i) => {
      const start = i * step;
      const end = Math.min(1, start + charWindow);
      return { start, end };
    });
  }, [chars, stagger]);

  if (isMobile) {
    return (
      <span ref={containerRef} className={`scroll-float ${containerClassName}`} style={style}>
        <span className={`scroll-float-text ${textClassName} inline-block font-bold tracking-tight text-white`}>
          {children}
        </span>
      </span>
    );
  }

  return (
    <span ref={containerRef} className={`scroll-float ${containerClassName}`} style={style}>
      <span className={`scroll-float-text ${textClassName}`}>
        {chars.map((char, i) => (
          <Char
            key={i}
            char={char}
            progress={scrollYProgress}
            start={segments[i].start}
            end={segments[i].end}
          />
        ))}
      </span>
    </span>
  );
};

export default ScrollFloat;
```

---

## components/animations/ScrollFoldTransition.tsx

**File Path**: `components/animations/ScrollFoldTransition.tsx` | **Lines**: 280

```tsx
"use client";

import React, { useLayoutEffect, useRef } from "react";
import { gsap, ScrollTrigger } from "@/lib/gsap";

type Props = {
  label?: React.ReactNode;
  /** Color of the fold seam glow. */
  seamColor?: string;
  /** Background color shown behind the fold. */
  voidColor?: string;
  /** Color of the outgoing page (top half). */
  topColor?: string;
  /** Color of the incoming page (bottom half). */
  bottomColor?: string;
  /** Total scroll distance the transition occupies. */
  scrollDistance?: string;
};

export const ScrollFoldTransition: React.FC<Props> = ({
  label,
  seamColor = "#c8a882",
  voidColor = "#050505",
  topColor = "#0f0f0f",
  bottomColor = "#1a1a1a",
  scrollDistance = "+=280%",
}) => {
  const sectionRef = useRef<HTMLDivElement>(null);
  const stageRef = useRef<HTMLDivElement>(null);
  const topRef = useRef<HTMLDivElement>(null);
  const bottomRef = useRef<HTMLDivElement>(null);
  const seamRef = useRef<HTMLDivElement>(null);
  const labelRef = useRef<HTMLDivElement>(null);
  const linesRef = useRef<HTMLDivElement>(null);
  const dustRef = useRef<HTMLDivElement>(null);
  const [computedVh, setComputedVh] = React.useState("280vh");

  useLayoutEffect(() => {
    if (!sectionRef.current) return;

    const ctx = gsap.context(() => {
      const isMobile = window.innerWidth < 768;
      const effectiveDist = isMobile ? "+=30%" : scrollDistance;
      const parsedExtra = parseInt(effectiveDist.replace(/[^0-9]/g, ""), 10) || (isMobile ? 30 : 280);
      setComputedVh(`${100 + parsedExtra}vh`);

      gsap.set(stageRef.current, { perspective: isMobile ? 1200 : 2000 });

      gsap.set(topRef.current, {
        transformOrigin: "50% 100%",
        rotateX: 0,
        z: 0,
      });
      gsap.set(bottomRef.current, {
        transformOrigin: "50% 0%",
        rotateX: 90,
        z: 0,
        opacity: 0,
      });
      gsap.set(seamRef.current, {
        scaleX: 0,
        opacity: 0,
        transformOrigin: "50% 50%",
      });
      gsap.set(labelRef.current, {
        opacity: 0,
        y: 60,
        scale: 0.85,
      });

      const lineEls = linesRef.current
        ? Array.from(linesRef.current.children)
        : [];
      gsap.set(lineEls, { scaleX: 0, opacity: 0, transformOrigin: "0% 50%" });

      const dustEls = dustRef.current
        ? Array.from(dustRef.current.children)
        : [];
      gsap.set(dustEls, { opacity: 0, y: 40 });

      const tl = gsap.timeline({
        defaults: { ease: "none" },
        scrollTrigger: {
          trigger: sectionRef.current,
          start: "top top",
          end: effectiveDist,
          scrub: isMobile ? 0.35 : 0.6,
          pin: stageRef.current,
          pinSpacing: true,
          anticipatePin: 1,
        },
      });

      // 1. Seam glow ignites along the horizon
      tl.to(seamRef.current, { scaleX: 1, opacity: 1, duration: 0.3 }, 0);

      // 2. Horizontal kinetic lines sweep across
      tl.to(
        lineEls,
        {
          scaleX: 1,
          opacity: 0.5,
          stagger: 0.04,
          duration: 0.4,
        },
        0.05
      );

      // 3. Top page folds backward (rotateX -100, z away)
      tl.to(
        topRef.current,
        {
          rotateX: -110,
          z: -300,
          duration: 0.7,
        },
        0.2
      );

      // 4. Dust particles drift up through the void
      tl.to(
        dustEls,
        {
          opacity: 0.6,
          y: -60,
          stagger: { each: 0.02, from: "random" },
          duration: 0.6,
        },
        0.3
      );

      // 5. Label warps into the void
      tl.to(
        labelRef.current,
        {
          opacity: 1,
          y: 0,
          scale: 1,
          duration: 0.45,
        },
        0.4
      );

      // 6. Hold a beat
      tl.to({}, { duration: 0.1 }, 0.85);

      // 7. Label rises out of the way (with dynamic scale zoom)
      tl.to(
        labelRef.current,
        {
          y: -120,
          scale: 1.12,
          opacity: 0,
          duration: 0.25,
        },
        0.95
      );

      // 8. Bottom page rotates up into view
      tl.to(
        bottomRef.current,
        {
          rotateX: 0,
          opacity: 1,
          duration: 0.45,
        },
        0.95
      );

      // 9. Lines and seam snap closed
      tl.to(
        lineEls,
        { scaleX: 0, opacity: 0, stagger: 0.02, duration: 0.2 },
        1.05
      );
      tl.to(seamRef.current, { scaleX: 0, opacity: 0, duration: 0.2 }, 1.1);
    }, sectionRef);

    return () => ctx.revert();
  }, [scrollDistance]);

  return (
    <section
      ref={sectionRef}
      className="relative w-full"
      style={{ height: computedVh }}
      aria-label="Page fold transition"
    >
      <div
        ref={stageRef}
        className="relative w-screen h-screen overflow-hidden"
        style={{ backgroundColor: voidColor }}
      >
        {/* Outgoing top half */}
        <div
          ref={topRef}
          className="absolute left-0 top-0 w-full h-1/2 will-change-transform"
          style={{
            background: `linear-gradient(180deg, ${topColor} 0%, #000 100%)`,
            boxShadow: "0 20px 60px rgba(0,0,0,0.6)",
          }}
        />

        {/* Incoming bottom half */}
        <div
          ref={bottomRef}
          className="absolute left-0 bottom-0 w-full h-1/2 will-change-transform"
          style={{
            background: `linear-gradient(0deg, ${bottomColor} 0%, #000 100%)`,
            boxShadow: "0 -20px 60px rgba(0,0,0,0.6)",
          }}
        />

        {/* Seam glow */}
        <div
          ref={seamRef}
          className="absolute left-0 top-1/2 -translate-y-1/2 w-full h-[3px] will-change-transform z-10 pointer-events-none"
          style={{
            background: `linear-gradient(90deg, transparent 0%, ${seamColor} 50%, transparent 100%)`,
            boxShadow: `0 0 30px ${seamColor}, 0 0 60px ${seamColor}66`,
          }}
        />

        {/* Kinetic horizontal lines */}
        <div
          ref={linesRef}
          className="pointer-events-none absolute inset-0 flex flex-col justify-around py-[10vh]"
        >
          {Array.from({ length: 8 }).map((_, i) => (
            <div
              key={i}
              className="h-px w-full will-change-transform"
              style={{
                background: `linear-gradient(90deg, transparent, ${seamColor}88, transparent)`,
              }}
            />
          ))}
        </div>

        {/* Dust particles */}
        <div
          ref={dustRef}
          className="pointer-events-none absolute inset-0"
        >
          {Array.from({ length: 30 }).map((_, i) => {
            const x = (i * 37) % 100;
            const y = (i * 53) % 100;
            const size = 2 + ((i * 7) % 4);
            return (
              <div
                key={i}
                className="absolute rounded-full will-change-transform"
                style={{
                  left: `${x}%`,
                  top: `${y}%`,
                  width: size,
                  height: size,
                  background: seamColor,
                  boxShadow: `0 0 8px ${seamColor}`,
                }}
              />
            );
          })}
        </div>

        {/* Center label */}
        <div
          ref={labelRef}
          className="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 will-change-transform text-center z-20 pointer-events-none"
          style={{ color: "#f0ece4" }}
        >
          {label}
        </div>
      </div>
    </section>
  );
};

export default ScrollFoldTransition;
```

---

## components/animations/ScrollReveal.tsx

**File Path**: `components/animations/ScrollReveal.tsx` | **Lines**: 31

```tsx
"use client";

import { motion } from "framer-motion";
import { useInView } from "@/hooks/useInView";
import { fadeUp, staggerContainer } from "@/lib/motion";
import { cn } from "@/lib/utils";

interface ScrollRevealProps {
  children: React.ReactNode;
  className?: string;
  delay?: number;
  stagger?: boolean;
}

export function ScrollReveal({ children, className, delay = 0, stagger = false }: ScrollRevealProps) {
  const { ref, inView } = useInView();

  return (
    <motion.div
      ref={ref as React.RefObject<HTMLDivElement>}
      variants={stagger ? staggerContainer : fadeUp}
      initial="hidden"
      animate={inView ? "visible" : "hidden"}
      transition={{ delay }}
      className={cn(className)}
    >
      {children}
    </motion.div>
  );
}
```

---

## components/animations/ScrollRevealCurtain.tsx

**File Path**: `components/animations/ScrollRevealCurtain.tsx` | **Lines**: 183

```tsx
"use client";

import React, { useLayoutEffect, useRef } from "react";
import { gsap, ScrollTrigger } from "@/lib/gsap";

type Props = {
  /** Content displayed before the transition (the "outgoing" page). */
  beneath: React.ReactNode;
  /** Color of the incoming panel that sweeps in. */
  curtainColor?: string;
  /** Big label rendered inside the incoming panel during the reveal. */
  label?: React.ReactNode;
  /** Total scroll distance for the transition (e.g. "+=200%"). */
  scrollDistance?: string;
};

export const ScrollRevealCurtain: React.FC<Props> = ({
  beneath,
  curtainColor = "#fd5200",
  label,
  scrollDistance = "+=220%",
}) => {
  const sectionRef = useRef<HTMLDivElement>(null);
  const stageRef = useRef<HTMLDivElement>(null);
  const beneathRef = useRef<HTMLDivElement>(null);
  const curtainRef = useRef<HTMLDivElement>(null);
  const labelRef = useRef<HTMLDivElement>(null);
  const shardRef = useRef<HTMLDivElement>(null);
  const dimRef = useRef<HTMLDivElement>(null);
  const [computedVh, setComputedVh] = React.useState("220vh");

  useLayoutEffect(() => {
    if (!sectionRef.current || !curtainRef.current) return;

    const ctx = gsap.context(() => {
      const isMobile = window.innerWidth < 768;
      const effectiveDist = isMobile ? "+=35%" : scrollDistance;
      const parsedExtra = parseInt(effectiveDist.replace(/[^0-9]/g, ""), 10) || (isMobile ? 35 : 220);
      setComputedVh(`${100 + parsedExtra}vh`);

      gsap.set(stageRef.current, { perspective: isMobile ? 1000 : 1600 });

      gsap.set(beneathRef.current, {
        transformOrigin: "50% 50%",
        scale: 1,
        rotateX: 0,
        z: 0,
      });

      gsap.set(dimRef.current, {
        opacity: 0,
      });

      // Vertical wipe instead of a diagonal clip-path sweep — feels far more natural.
      gsap.set(curtainRef.current, {
        yPercent: 100,
        opacity: 1,
      });

      gsap.set(shardRef.current, {
        opacity: 0,
      });

      gsap.set(labelRef.current, {
        opacity: 0,
        y: isMobile ? 24 : 40,
        scale: isMobile ? 0.98 : 0.96,
      });

      const tl = gsap.timeline({
        defaults: { ease: "power2.inOut" },
        scrollTrigger: {
          trigger: sectionRef.current,
          start: "top top",
          end: effectiveDist,
          scrub: isMobile ? 0.4 : 0.75,
          pin: stageRef.current,
          pinSpacing: true,
          anticipatePin: 1,
        },
      });

      // Brief beat (0 → 0.05): one moment to register the Spline scene
      tl.to({}, { duration: 0.05 }, 0);

      // Phase 2 (0.05 → 0.8): smooth vertical curtain rise + gentle depth fade
      tl.to(
        beneathRef.current,
        {
          scale: 0.92,
          duration: 0.75,
          ease: "sine.inOut",
        },
        0.05
      );

      tl.to(
        dimRef.current,
        {
          opacity: 0.65,
          duration: 0.75,
          ease: "sine.inOut",
        },
        0.05
      );

      tl.to(
        curtainRef.current,
        {
          yPercent: 0,
          duration: 0.75,
          ease: "power2.inOut",
        },
        0.05
      );

      tl.to(
        labelRef.current,
        { opacity: 1, y: 0, scale: 1, duration: 0.4, ease: "power2.out" },
        0.55
      );

      // Small breathing hold at the end so the next section snaps in (0.95 → 1.0)
      tl.to({}, { duration: 0.05 }, 0.95);
    }, sectionRef);

    return () => ctx.revert();
  }, [scrollDistance]);

  return (
    <section
      ref={sectionRef}
      className="relative w-full"
      style={{ height: computedVh }}
      aria-label="Scroll transition"
    >
      <div
        ref={stageRef}
        className="relative w-screen h-screen overflow-hidden bg-black"
      >
        <div
          ref={beneathRef}
          className="absolute inset-0 w-full h-full will-change-transform"
        >
          {beneath}
        </div>

        {/* Dynamic overlay to dim the scene smoothly on scroll without layout-triggering blur filters */}
        <div
          ref={dimRef}
          className="pointer-events-none absolute inset-0 w-full h-full bg-black z-[2]"
          style={{ opacity: 0 }}
        />

        <div
          ref={shardRef}
          className="pointer-events-none absolute inset-0 w-full h-full will-change-transform z-[3]"
          style={{
            background: `linear-gradient(135deg, ${curtainColor} 0%, #000 100%)`,
            mixBlendMode: "screen",
          }}
        />

        <div
          ref={curtainRef}
          className="pointer-events-none absolute inset-0 w-full h-full will-change-transform flex items-center justify-center z-[4]"
          style={{ backgroundColor: curtainColor }}
        >
          <div
            ref={labelRef}
            className="will-change-transform px-8 text-center"
            style={{ color: "#fff" }}
          >
            {label}
          </div>
        </div>
      </div>
    </section>
  );
};

export default ScrollRevealCurtain;
```

---

## components/animations/ScrollWarpPortal.tsx

**File Path**: `components/animations/ScrollWarpPortal.tsx` | **Lines**: 353

```tsx
"use client";

import React, { useLayoutEffect, useRef } from "react";
import { gsap } from "@/lib/gsap";

type Props = {
  /** Label shown in the void during the warp. */
  label?: React.ReactNode;
  /** Background color of the void. */
  voidColor?: string;
  /** Accent color for slats / depth frames. */
  accent?: string;
  /** Total scroll distance the transition occupies. */
  scrollDistance?: string;
};

const DEPTH_FRAMES = 7;

export const ScrollWarpPortal: React.FC<Props> = ({
  label,
  voidColor = "#050505",
  accent = "#c8a882",
  scrollDistance = "+=260%",
}) => {
  const sectionRef = useRef<HTMLDivElement>(null);
  const stageRef = useRef<HTMLDivElement>(null);
  const vignetteRef = useRef<HTMLDivElement>(null);
  const framesRef = useRef<HTMLDivElement>(null);
  const labelRef = useRef<HTMLDivElement>(null);
  const haloRef = useRef<HTMLDivElement>(null);
  const glowRef = useRef<HTMLDivElement>(null);
  const beamsRef = useRef<HTMLDivElement>(null);
  const [computedVh, setComputedVh] = React.useState("260vh");

  useLayoutEffect(() => {
    if (!sectionRef.current) return;

    const ctx = gsap.context(() => {
      const isMobile = window.innerWidth < 768;
      const effectiveDist = isMobile ? "+=30%" : scrollDistance;
      const parsedExtra = parseInt(effectiveDist.replace(/[^0-9]/g, ""), 10) || (isMobile ? 30 : 260);
      setComputedVh(`${100 + parsedExtra}vh`);

      gsap.set(stageRef.current, { perspective: isMobile ? 1000 : 1600 });

      const frameEls = framesRef.current
        ? Array.from(framesRef.current.children)
        : [];
      const beamEls = beamsRef.current
        ? Array.from(beamsRef.current.children)
        : [];

      // Frames start tiny at center, invisible
      gsap.set(frameEls, (i: number) => ({
        scale: 0.12,
        opacity: 0,
        force3D: true,
        zIndex: DEPTH_FRAMES - i,
      }));

      gsap.set(labelRef.current, {
        scale: 0.7,
        opacity: 0,
        force3D: true,
      });

      gsap.set(haloRef.current, {
        scale: 0.3,
        opacity: 0,
        force3D: true,
      });

      gsap.set(glowRef.current, {
        opacity: 0,
        force3D: true,
      });

      gsap.set(vignetteRef.current, {
        opacity: 1,
      });

      gsap.set(beamEls, {
        opacity: 0,
        scaleY: 0.4,
        transformOrigin: "50% 50%",
        force3D: true,
      });

      const tl = gsap.timeline({
        defaults: { ease: "power2.out", force3D: true },
        scrollTrigger: {
          trigger: sectionRef.current,
          start: "top top",
          end: effectiveDist,
          scrub: isMobile ? 0.35 : 0.6,
          pin: stageRef.current,
          pinSpacing: true,
          anticipatePin: 1,
        },
      });

      // 1. Vignette lifts gently as the portal awakens (0 → 0.18)
      tl.to(
        vignetteRef.current,
        { opacity: 0.45, duration: 0.18, ease: "sine.inOut" },
        0
      );

      // 2. Halo glow blooms outward (0 → 0.35)
      tl.to(
        haloRef.current,
        {
          scale: 1.4,
          opacity: 0.7,
          duration: 0.35,
          ease: "sine.out",
        },
        0
      );

      // 3. Frames: deterministic progress-driven update (no chained tweens — survives scrub reversal cleanly)
      const frameState = { p: 0 };
      const easeOut = gsap.parseEase("power2.out");
      const easeInOut = gsap.parseEase("sine.inOut");
      const easeIn = gsap.parseEase("power2.in");

      const updateFrames = () => {
        const p = frameState.p;
        frameEls.forEach((el, i) => {
          let scale: number;
          let opacity: number;
          const s0 = 0.12;
          const s1 = 0.55 + i * 0.32;
          const s2 = 0.7 + i * 0.36;
          const s3 = 2.6 + i * 0.7;
          const o1 = 0.95 - i * 0.11;

          if (p <= 0.05) {
            scale = s0;
            opacity = 0;
          } else if (p < 0.45) {
            const t = easeOut((p - 0.05) / 0.4);
            scale = s0 + (s1 - s0) * t;
            opacity = o1 * t;
          } else if (p < 0.5) {
            scale = s1;
            opacity = o1;
          } else if (p < 0.78) {
            const t = easeInOut((p - 0.5) / 0.28);
            scale = s1 + (s2 - s1) * t;
            opacity = o1;
          } else if (p < 0.95) {
            const t = easeIn((p - 0.78) / 0.17);
            scale = s2 + (s3 - s2) * t;
            opacity = o1 * (1 - t);
          } else {
            scale = s3;
            opacity = 0;
          }

          gsap.set(el, { scale, opacity, force3D: true });
        });
      };

      tl.to(
        frameState,
        {
          p: 1,
          duration: 1,
          ease: "none",
          onUpdate: updateFrames,
        },
        0
      );

      // 4. Subtle light beams sweep in (0.1 → 0.4)
      tl.to(
        beamEls,
        {
          opacity: 0.25,
          scaleY: 1,
          duration: 0.3,
          ease: "power1.out",
        },
        0.1
      );

      // 5. Label warps in (0.2 → 0.5) — slower, more elegant
      tl.to(
        labelRef.current,
        {
          scale: 1,
          opacity: 1,
          duration: 0.3,
          ease: "power2.out",
        },
        0.2
      );

      // 6. White flash ignites (0.78 → 0.92)
      tl.to(
        glowRef.current,
        { opacity: 1, duration: 0.14, ease: "power2.in" },
        0.78
      );

      // 10. Label drifts forward & dissolves
      tl.to(
        labelRef.current,
        {
          scale: 1.18,
          opacity: 0,
          duration: 0.17,
          ease: "power2.in",
        },
        0.78
      );

      // 11. Halo expands & dissolves
      tl.to(
        haloRef.current,
        { scale: 2.8, opacity: 0, duration: 0.17, ease: "power2.in" },
        0.78
      );

      // 12. Beams fade
      tl.to(
        beamEls,
        { opacity: 0, duration: 0.14, ease: "power2.in" },
        0.78
      );

      // 13. Glow gently fades, revealing next page (0.92 → 1)
      tl.to(
        glowRef.current,
        { opacity: 0, duration: 0.16, ease: "sine.inOut" },
        0.92
      );
    }, sectionRef);

    return () => ctx.revert();
  }, [scrollDistance]);

  return (
    <section
      ref={sectionRef}
      className="relative w-full"
      style={{ height: computedVh }}
      aria-label="Warp transition"
    >
      <div
        ref={stageRef}
        className="relative w-screen h-screen overflow-hidden"
        style={{
          backgroundColor: voidColor,
        }}
      >
        {/* Base atmosphere: subtle radial fall-off */}
        <div
          className="pointer-events-none absolute inset-0"
          style={{
            background: `radial-gradient(ellipse at center, ${accent}0d 0%, transparent 55%)`,
          }}
        />

        {/* Soft vertical light beams (decorative depth) */}
        <div
          ref={beamsRef}
          className="pointer-events-none absolute inset-0 flex items-center justify-center"
        >
          {[0, 1, 2, 3].map((i) => (
            <div
              key={i}
              className="absolute"
              style={{
                width: "1px",
                height: "120vh",
                left: `${20 + i * 20}%`,
                background: `linear-gradient(to bottom, transparent 0%, ${accent}66 50%, transparent 100%)`,
                filter: "blur(1.5px)",
              }}
            />
          ))}
        </div>

        {/* Outer vignette for cinematic framing */}
        <div
          ref={vignetteRef}
          className="pointer-events-none absolute inset-0"
          style={{
            background: `radial-gradient(ellipse at center, transparent 35%, ${voidColor} 85%)`,
          }}
        />

        {/* Radial halo glow */}
        <div
          ref={haloRef}
          className="pointer-events-none absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 will-change-transform"
          style={{
            width: "70vmin",
            height: "70vmin",
            borderRadius: "50%",
            background: `radial-gradient(circle, ${accent}55 0%, ${accent}11 35%, transparent 70%)`,
            filter: "blur(30px)",
          }}
        />

        {/* Concentric depth frames (the tunnel) */}
        <div
          ref={framesRef}
          className="pointer-events-none absolute inset-0 flex items-center justify-center"
          style={{ transformStyle: "preserve-3d" }}
        >
          {Array.from({ length: DEPTH_FRAMES }).map((_, i) => (
            <div
              key={i}
              className="absolute will-change-transform"
              style={{
                width: "68vmin",
                height: "40vmin",
                border: `1px solid ${accent}`,
                borderRadius: 8,
                boxShadow: `0 0 80px ${accent}22 inset, 0 0 24px ${accent}1a`,
                background: `linear-gradient(135deg, ${accent}05 0%, transparent 60%)`,
              }}
            />
          ))}
        </div>

        {/* Center label */}
        <div
          ref={labelRef}
          className="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 will-change-transform text-center z-10"
          style={{
            color: "#f4ede0",
            textShadow: `0 0 40px ${accent}55, 0 0 80px ${accent}33`,
          }}
        >
          {label}
        </div>

        {/* Final white flash (bright fade-out) */}
        <div
          ref={glowRef}
          className="pointer-events-none absolute inset-0 bg-white"
        />
      </div>
    </section>
  );
};

export default ScrollWarpPortal;
```

---

## components/animations/SectionWrapper.tsx

**File Path**: `components/animations/SectionWrapper.tsx` | **Lines**: 26

```tsx
"use client";

import { cn } from "@/lib/utils";

interface SectionWrapperProps {
  children: React.ReactNode;
  className?: string;
  id?: string;
  fullHeight?: boolean;
}

export function SectionWrapper({ children, className, id, fullHeight }: SectionWrapperProps) {
  return (
    <section
      id={id}
      className={cn(
        "relative w-full px-6 md:px-12 lg:px-20 xl:px-28",
        fullHeight && "min-h-screen",
        className
      )}
    >
      {children}
    </section>
  );
}
```

---

## components/animations/SmoothScrollProvider.tsx

**File Path**: `components/animations/SmoothScrollProvider.tsx` | **Lines**: 9

```tsx
"use client";

import { useLenis } from "@/hooks/useLenis";

export function SmoothScrollProvider({ children }: { children: React.ReactNode }) {
  useLenis();
  return <>{children}</>;
}
```

---

## components/animations/StaggerTextReveal.tsx

**File Path**: `components/animations/StaggerTextReveal.tsx` | **Lines**: 50

```tsx
"use client";

import React, { ElementType } from "react";
import { motion } from "framer-motion";
import { useInView } from "@/hooks/useInView";
import { splitTextToWords } from "@/lib/utils";

interface StaggerTextRevealProps {
  text: string;
  className?: string;
  delay?: number;
  as?: ElementType;
}

export function StaggerTextReveal({
  text,
  className,
  delay = 0,
  as: Tag = "p",
}: StaggerTextRevealProps) {
  const { ref, inView } = useInView();
  const words = splitTextToWords(text);

  return (
    <Tag
      ref={ref}
      className={className}
      style={{ display: "flex", flexWrap: "wrap", gap: "0.25em" }}
      aria-label={text}
    >
      {words.map((word: string, i: number) => (
        <span key={i} style={{ overflow: "hidden", display: "inline-block" }}>
          <motion.span
            style={{ display: "inline-block" }}
            initial={{ y: "110%", opacity: 0 }}
            animate={inView ? { y: "0%", opacity: 1 } : { y: "110%", opacity: 0 }}
            transition={{
              duration: 0.7,
              ease: [0.16, 1, 0.3, 1],
              delay: delay + i * 0.05,
            }}
          >
            {word}
          </motion.span>
        </span>
      ))}
    </Tag>
  );
}
```

---

## components/animations/VelocityScroll.tsx

**File Path**: `components/animations/VelocityScroll.tsx` | **Lines**: 29

```tsx
"use client";

import { useRef } from "react";
import { motion, useScroll, useTransform, useSpring } from "framer-motion";
import { cn } from "@/lib/utils";

interface VelocityScrollProps {
  text: string;
  className?: string;
  baseVelocity?: number;
}

export function VelocityScroll({ text, className, baseVelocity = 3 }: VelocityScrollProps) {
  const ref = useRef<HTMLDivElement>(null);
  const { scrollYProgress } = useScroll();
  const x = useTransform(scrollYProgress, [0, 1], ["0%", `${-baseVelocity * 100}%`]);
  const smoothX = useSpring(x, { stiffness: 100, damping: 30 });

  const repeated = Array(8).fill(text).join(" · ");

  return (
    <div ref={ref} className={cn("overflow-hidden whitespace-nowrap", className)}>
      <motion.div style={{ x: smoothX }} className="inline-block">
        {repeated}&nbsp;&nbsp;{repeated}
      </motion.div>
    </div>
  );
}
```

---

## components/ui/apple-spotlight.tsx

**File Path**: `components/ui/apple-spotlight.tsx` | **Lines**: 557

```tsx
"use client";

import { cn } from "@/lib/utils";
import { AnimatePresence, motion } from "framer-motion";
import {
  Activity,
  Briefcase,
  ChevronRight,
  Code2,
  Files,
  FileText,
  Folder,
  Globe,
  Image as ImageIcon,
  Layers,
  LayoutGrid,
  Mail,
  MessageSquare,
  Search,
  Settings,
  StickyNote,
  Terminal,
} from "lucide-react";
import React, { useEffect, useMemo, useRef, useState } from "react";

export interface Shortcut {
  label: string;
  icon: React.ReactNode;
  link: string;
}

export interface SearchResult {
  icon: React.ReactNode;
  label: string;
  description: string;
  link: string;
}

const SVGFilter = () => (
  <svg width="0" height="0" className="absolute" aria-hidden>
    <filter id="blob-spotlight">
      <feGaussianBlur stdDeviation="10" in="SourceGraphic" />
      <feColorMatrix
        values="1 0 0 0 0  0 1 0 0 0  0 0 1 0 0  0 0 0 18 -9"
        result="blob"
      />
      <feBlend in="SourceGraphic" in2="blob" />
    </filter>
  </svg>
);

const ShortcutButton = ({ icon, link }: { icon: React.ReactNode; link: string }) => (
  <a href={link} target="_blank" rel="noreferrer">
    <div className="rounded-full cursor-pointer opacity-40 hover:opacity-100 transition-opacity duration-200">
      <div className="size-16 aspect-square flex items-center justify-center text-[#e9defb]">
        {icon}
      </div>
    </div>
  </a>
);

const SpotlightPlaceholder = ({
  text,
  className,
}: {
  text: string;
  className?: string;
}) => (
  <motion.div
    layout
    className={cn(
      "absolute text-[#7a7a7a] flex items-center pointer-events-none z-10",
      className
    )}
  >
    <AnimatePresence mode="popLayout">
      <motion.p
        layoutId={`placeholder-${text}`}
        key={`placeholder-${text}`}
        initial={{ opacity: 0, y: 10, filter: "blur(5px)" }}
        animate={{ opacity: 1, y: 0, filter: "blur(0px)" }}
        exit={{ opacity: 0, y: -10, filter: "blur(5px)" }}
        transition={{ duration: 0.2, ease: "easeOut" }}
      >
        {text}
      </motion.p>
    </AnimatePresence>
  </motion.div>
);

interface SpotlightInputProps {
  placeholder: string;
  hidePlaceholder: boolean;
  value: string;
  onChange: (value: string) => void;
  onEnter?: () => void;
  placeholderClassName?: string;
}

const SpotlightInput = ({
  placeholder,
  hidePlaceholder,
  value,
  onChange,
  onEnter,
  placeholderClassName,
}: SpotlightInputProps) => {
  const inputRef = useRef<HTMLInputElement>(null);

  useEffect(() => {
    const t = setTimeout(() => inputRef.current?.focus(), 50);
    return () => clearTimeout(t);
  }, []);

  return (
    <div className="flex items-center w-full justify-start gap-7 h-24" style={{ paddingLeft: "3.5rem", paddingRight: "3.5rem" }}>
      <div className="text-[#a78bfa] shrink-0">
        <Search className="!w-8 !h-8" />
      </div>
      <div className="flex-1 relative text-3xl py-2">
        {!hidePlaceholder && (
          <SpotlightPlaceholder text={placeholder} className={placeholderClassName} />
        )}
        <motion.input
          ref={inputRef}
          layout="position"
          type="text"
          value={value}
          onChange={(e) => onChange(e.target.value)}
          onKeyDown={(e) => {
            if (e.key === "Enter") onEnter?.();
          }}
          className="w-full bg-transparent outline-none ring-0 text-[#f0ece4] caret-[#a78bfa] font-mono"
        />
      </div>
      <kbd className="hidden sm:inline-flex items-center gap-1 text-[11px] text-[#7a7a7a] border border-[#2a2a2a] rounded-md px-2 py-1 font-mono">
        ESC
      </kbd>
    </div>
  );
};

interface SearchResultCardProps extends SearchResult {
  isLast: boolean;
}

const smoothScrollToId = (id: string) => {
  const target = document.getElementById(id);
  if (!target) return;
  const rect = target.getBoundingClientRect();
  const absoluteTop = rect.top + window.scrollY;
  // Native smooth scroll — browser optimizes for the user's reduced-motion
  // settings, scrollbar thumb, and refresh rate. Feels the most natural.
  window.scrollTo({ top: absoluteTop, behavior: "smooth" });
};

const SearchResultCard = ({
  icon,
  label,
  description,
  link,
  onActivate,
}: SearchResultCardProps & { onActivate?: () => void }) => (
  <a
    href={link}
    target={
      link.startsWith("#") ||
      link.startsWith("/") ||
      /^(mailto:|tel:|sms:)/i.test(link)
        ? "_self"
        : "_blank"
    }
    rel={/^https?:\/\//i.test(link) ? "noopener noreferrer" : undefined}
    className="overflow-hidden w-full group/card"
    onClick={(e) => {
      if (link.startsWith("#")) {
        e.preventDefault();
        onActivate?.();
        // Defer the scroll a frame so the spotlight starts closing first —
        // avoids a jolt as the modal unmounts mid-animation.
        requestAnimationFrame(() => smoothScrollToId(link.slice(1)));
      } else if (/^(mailto:|tel:|sms:)/i.test(link)) {
        // Close the spotlight before the OS handler hijacks focus; the
        // browser will still navigate to the protocol URL after this tick.
        onActivate?.();
      }
    }}
  >
    <div
      className={cn(
        "relative flex items-center text-[#cfcfcf] justify-start gap-7 py-5 px-4 rounded-2xl w-full",
        "transition-all duration-300 ease-out",
        "group-hover/card:bg-[linear-gradient(90deg,rgba(167,139,250,0.14)_0%,rgba(167,139,250,0.04)_100%)]",
        "group-hover/card:shadow-[inset_0_1px_0_rgba(255,255,255,0.04),0_8px_24px_-12px_rgba(167,139,250,0.4)]"
      )}
    >
      <span
        aria-hidden
        className="absolute left-0 top-1/2 -translate-y-1/2 w-[3px] h-0 rounded-r-full bg-gradient-to-b from-[#c4b5fd] to-[#a78bfa] transition-all duration-300 ease-out group-hover/card:h-8"
      />
      <div
        className={cn(
          "relative size-12 rounded-xl bg-[#15101f] border border-[#2a2240] text-[#c4b5fd]",
          "[&_svg]:stroke-[1.5] [&_svg]:size-[22px] aspect-square flex items-center justify-center shrink-0",
          "transition-all duration-300 ease-out",
          "group-hover/card:border-[#a78bfa]/55 group-hover/card:bg-[#1f1830]",
          "group-hover/card:shadow-[0_0_20px_-4px_rgba(167,139,250,0.45)]"
        )}
      >
        {icon}
      </div>
      <div className="flex flex-col min-w-0 gap-1.5">
        <p className="font-medium font-mono text-[15px] truncate transition-colors duration-300 group-hover/card:text-white">
          {label}
        </p>
        <p className="text-[13px] text-[#7a7a7a] truncate transition-colors duration-300 group-hover/card:text-[#a8a3bd]">
          {description}
        </p>
      </div>
      <div
        className={cn(
          "flex-1 flex items-center justify-end pr-2 text-[#a78bfa]",
          "opacity-0 -translate-x-1 transition-all duration-300 ease-out",
          "group-hover/card:opacity-100 group-hover/card:translate-x-0"
        )}
      >
        <ChevronRight className="size-5" />
      </div>
    </div>
  </a>
);

const SearchResultsContainer = ({
  searchResults,
  onHover,
  onActivate,
}: {
  searchResults: SearchResult[];
  onHover: (index: number | null) => void;
  onActivate?: () => void;
}) => (
  <motion.div
    layout
    onMouseLeave={() => onHover(null)}
    style={{ paddingLeft: "2.5rem", paddingRight: "2.5rem", paddingTop: "1.75rem", paddingBottom: "1.75rem" }}
    className="border-t border-[#1f1f1f] flex flex-col bg-[#0d0a14]/95 max-h-[34rem] overflow-y-auto w-full gap-4 [scrollbar-width:thin]"
  >
    {searchResults.length === 0 ? (
      <div className="px-4 py-6 text-center text-sm text-[#7a7a7a] font-mono">
        No results found
      </div>
    ) : (
      searchResults.map((result, index) => (
        <motion.div
          key={`search-result-${result.label}-${index}`}
          onMouseEnter={() => onHover(index)}
          initial={{ opacity: 0, y: 4 }}
          animate={{ opacity: 1, y: 0 }}
          exit={{ opacity: 0 }}
          transition={{ delay: Math.min(index * 0.04, 0.2), duration: 0.18, ease: "easeOut" }}
        >
          <SearchResultCard
            icon={result.icon}
            label={result.label}
            description={result.description}
            link={result.link}
            isLast={index === searchResults.length - 1}
            onActivate={onActivate}
          />
        </motion.div>
      ))
    )}
  </motion.div>
);

interface AppleSpotlightProps {
  shortcuts?: Shortcut[];
  results?: SearchResult[];
  isOpen?: boolean;
  handleClose?: () => void;
}

const DEFAULT_SHORTCUTS: Shortcut[] = [
  { label: "Projects", icon: <LayoutGrid />, link: "#showcase" },
  { label: "Dossier", icon: <Folder />, link: "#dossier" },
  { label: "Contact", icon: <Activity />, link: "#contact" },
  { label: "Articles", icon: <Files />, link: "/articles" },
];

const DEFAULT_RESULTS: SearchResult[] = [
  { icon: <Code2 />, label: "GitHub", description: "View repositories (jay2532006)", link: "https://github.com/jay2532006" },
  { icon: <Briefcase />, label: "LinkedIn", description: "Connect on LinkedIn", link: "https://www.linkedin.com/in/jay-parmar-ai" },
  { icon: <Mail />, label: "Email", description: "jaydeepak2532006@gmail.com", link: "mailto:jaydeepak2532006@gmail.com" },
  { icon: <Globe />, label: "Projects", description: "Browse all 6 flagship builds", link: "#showcase" },
  { icon: <StickyNote />, label: "About & Experience", description: "IIT Guwahati, ShikshaShakti.AI & IIM-B", link: "#about" },
  { icon: <Layers />, label: "Resume Dossier", description: "Experience, credentials & skills", link: "#dossier" },
  { icon: <ImageIcon />, label: "Field Archive", description: "Press features, summits & wins", link: "#gallery" },
  { icon: <Settings />, label: "Certificates", description: "IIT Bombay, TCS, MSME & IIT Bhilai", link: "#certificates" },
  { icon: <Terminal />, label: "Articles", description: "13 long-form essays & notes", link: "/articles" },
  { icon: <FileText />, label: "Resume PDF", description: "Download Jay Parmar CV", link: "/assets/portfolio/resume/Jay-Parmar-Resume.pdf" },
  { icon: <MessageSquare />, label: "Contact", description: "+91 77730 60203 · Bhilai / IIM-B", link: "#contact" },
];

interface SpotlightSearchProps {
  shortcuts?: Shortcut[];
  results?: SearchResult[];
  triggerClassName?: string;
}

export const SpotlightSearch = ({
  shortcuts = DEFAULT_SHORTCUTS,
  results = DEFAULT_RESULTS,
  triggerClassName,
}: SpotlightSearchProps) => {
  const [open, setOpen] = useState(false);

  useEffect(() => {
    const onKey = (e: KeyboardEvent) => {
      if ((e.metaKey || e.ctrlKey) && e.key.toLowerCase() === "k") {
        e.preventDefault();
        setOpen((v) => !v);
      }
    };
    window.addEventListener("keydown", onKey);
    return () => window.removeEventListener("keydown", onKey);
  }, []);

  return (
    <>
      <SVGFilter />
      {!open && (
        <button
          onClick={() => setOpen(true)}
          aria-label="Open search"
          style={{ borderRadius: 5 }}
          className={cn(
            "group flex items-center gap-2 px-3 text-[11px] text-[#bdbdbd] bg-[#161616] border border-[#222] hover:border-[#a78bfa]/50 hover:bg-[#1a1424] hover:text-white transition-colors cursor-pointer",
            triggerClassName
          )}
        >
          <span className="flex items-center text-[#a78bfa]">
            <Search className="!w-3 !h-3" />
          </span>
          <span className="truncate">Search portfolio…</span>
          <span className="ml-auto flex items-center gap-1 text-[10px] text-[#7a7a7a]">
            <kbd className="px-1 py-px rounded-[3px] bg-[#0d0a14] border border-[#2a2240] font-mono">⌘</kbd>
            <kbd className="px-1 py-px rounded-[3px] bg-[#0d0a14] border border-[#2a2240] font-mono">K</kbd>
          </span>
        </button>
      )}
      <AppleSpotlight
        shortcuts={shortcuts}
        results={results}
        isOpen={open}
        handleClose={() => setOpen(false)}
      />
    </>
  );
};

const AppleSpotlight = ({
  shortcuts = DEFAULT_SHORTCUTS,
  results = DEFAULT_RESULTS,
  isOpen = true,
  handleClose = () => {},
}: AppleSpotlightProps) => {
  const [hovered, setHovered] = useState(false);
  const [hoveredSearchResult, setHoveredSearchResult] = useState<number | null>(null);
  const [hoveredShortcut, setHoveredShortcut] = useState<number | null>(null);
  const [searchValue, setSearchValue] = useState("");
  const panelRef = useRef<HTMLDivElement | null>(null);

  // Escape to close
  useEffect(() => {
    if (!isOpen) return;
    const onKey = (e: KeyboardEvent) => {
      if (e.key === "Escape") handleClose();
    };
    window.addEventListener("keydown", onKey);
    return () => window.removeEventListener("keydown", onKey);
  }, [isOpen, handleClose]);

  // Close on any pointerdown outside the panel (needed because a transformed
  // parent can constrain `fixed inset-0` and leave the topmost areas uncovered).
  useEffect(() => {
    if (!isOpen) return;
    const t = setTimeout(() => {
      const onPointerDown = (e: PointerEvent) => {
        const panel = panelRef.current;
        if (panel && !panel.contains(e.target as Node)) handleClose();
      };
      document.addEventListener("pointerdown", onPointerDown, true);
      cleanup = () => document.removeEventListener("pointerdown", onPointerDown, true);
    }, 0);
    let cleanup: (() => void) | undefined;
    return () => {
      clearTimeout(t);
      cleanup?.();
    };
  }, [isOpen, handleClose]);

  // Lock body scroll when open
  useEffect(() => {
    if (!isOpen) return;
    const prev = document.body.style.overflow;
    document.body.style.overflow = "hidden";
    return () => {
      document.body.style.overflow = prev;
    };
  }, [isOpen]);

  const filtered = useMemo(() => {
    const q = searchValue.trim().toLowerCase();
    if (!q) return results;
    return results.filter(
      (r) =>
        r.label.toLowerCase().includes(q) ||
        r.description.toLowerCase().includes(q)
    );
  }, [searchValue, results]);

  const openFirst = () => {
    const first = filtered[0];
    if (!first) return;
    if (first.link.startsWith("#")) {
      handleClose();
      requestAnimationFrame(() => smoothScrollToId(first.link.slice(1)));
      return;
    }
    if (
      first.link.startsWith("/") ||
      /^(mailto:|tel:|sms:)/i.test(first.link)
    ) {
      window.location.href = first.link;
    } else {
      window.open(first.link, "_blank", "noopener,noreferrer");
    }
    handleClose();
  };

  return (
    <AnimatePresence mode="wait">
      {isOpen && (
        <motion.div
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          exit={{ opacity: 0 }}
          transition={{ duration: 0.25 }}
          className="fixed inset-0 z-[100] flex flex-col items-center justify-center px-4"
          onClick={handleClose}
        >
          {/* Backdrop */}
          <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            className="absolute inset-0 bg-black/60 backdrop-blur-md"
          />

          <div
            ref={panelRef}
            onMouseEnter={() => setHovered(true)}
            onMouseLeave={() => {
              setHovered(false);
              setHoveredShortcut(null);
            }}
            onClick={(e) => e.stopPropagation()}
            className={cn(
              "w-full flex items-center justify-end gap-4 z-20 group relative",
              "[&_svg]:size-7 [&_svg]:stroke-[1.4]",
              "max-w-4xl"
            )}
          >
            <AnimatePresence mode="popLayout">
              <motion.div
                key="spotlight-panel"
                initial={{ opacity: 0, scale: 0.96, y: 8 }}
                animate={{ opacity: 1, scale: 1, y: 0 }}
                exit={{ opacity: 0, scale: 0.98, y: 4 }}
                transition={{ duration: 0.28, ease: [0.22, 1, 0.36, 1] }}
                style={{ borderRadius: "30px" }}
                className="h-full w-full flex flex-col items-center justify-start z-10 relative bg-[#0d0a14]/95 text-[#f0ece4] backdrop-blur-xl shadow-[0_30px_80px_-20px_rgba(167,139,250,0.35),0_0_0_1px_rgba(167,139,250,0.15)] overflow-hidden border border-[#231a36]"
              >
                <SpotlightInput
                  placeholder={
                    !searchValue && hoveredShortcut !== null
                      ? shortcuts[hoveredShortcut].label
                      : !searchValue && hoveredSearchResult !== null
                        ? filtered[hoveredSearchResult]?.label ?? "Search"
                        : "Search portfolio…"
                  }
                  placeholderClassName={
                    !searchValue && hoveredSearchResult !== null ? "text-[#c4b5fd]" : "text-[#7a7a7a]"
                  }
                  hidePlaceholder={!!searchValue}
                  value={searchValue}
                  onChange={setSearchValue}
                  onEnter={openFirst}
                />

                {searchValue && (
                  <SearchResultsContainer
                    searchResults={filtered}
                    onHover={setHoveredSearchResult}
                    onActivate={handleClose}
                  />
                )}
              </motion.div>

              {hovered &&
                !searchValue &&
                shortcuts.map((shortcut, index) => (
                  <motion.div
                    key={`shortcut-${index}`}
                    onMouseEnter={() => setHoveredShortcut(index)}
                    layout
                    initial={{ scale: 0.7, x: -1 * (64 * (index + 1)) }}
                    animate={{ scale: 1, x: 0 }}
                    exit={{
                      scale: 0.7,
                      x:
                        1 *
                        (16 * (shortcuts.length - index - 1) +
                          64 * (shortcuts.length - index - 1)),
                    }}
                    transition={{
                      duration: 0.8,
                      type: "spring",
                      bounce: 0.2,
                      delay: index * 0.05,
                    }}
                    className="rounded-full cursor-pointer bg-[#0d0a14]/95 backdrop-blur-xl border border-[#231a36] text-[#f0ece4]"
                  >
                    <ShortcutButton icon={shortcut.icon} link={shortcut.link} />
                  </motion.div>
                ))}
            </AnimatePresence>
          </div>

          {/* Hint */}
          <motion.div
            initial={{ opacity: 0, y: 8 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ delay: 0.2 }}
            className="relative z-20 mt-6 text-[11px] text-[#7a7a7a] font-mono tracking-wider"
          >
            press <span className="text-[#a78bfa]">↵</span> to open · <span className="text-[#a78bfa]">esc</span> to close
          </motion.div>
        </motion.div>
      )}
    </AnimatePresence>
  );
};

export { AppleSpotlight };
export default AppleSpotlight;
```

---

## components/ui/articles-reader.tsx

**File Path**: `components/ui/articles-reader.tsx` | **Lines**: 336

```tsx
"use client";

import React, { useMemo, useState } from "react";
import Link from "next/link";
import { articles, categories, type Article } from "@/lib/articles";
import "./old-articles.css";

function searchable(article: Article) {
  return [
    article.title,
    article.dek,
    article.category,
    article.quote,
    ...article.sections.flatMap((section) => [
      section.heading,
      ...section.paragraphs,
      ...(section.points ?? []),
    ]),
  ]
    .filter(Boolean)
    .join(" ")
    .toLowerCase();
}

export function ArticlesReader() {
  const [search, setSearch] = useState("");
  const [activeCategory, setActiveCategory] = useState<(typeof categories)[number]>("All");

  const filtered = useMemo(() => {
    const q = search.trim().toLowerCase();
    return articles.filter(
      (article) =>
        (activeCategory === "All" || article.category === activeCategory) &&
        searchable(article).includes(q),
    );
  }, [activeCategory, search]);

  const featured = useMemo(() => articles.filter((article) => article.featured), []);

  const handleOpenEssay = (id: string) => {
    const el = document.getElementById(id) as HTMLDetailsElement | null;
    if (el) {
      el.open = true;
    }
  };

  return (
    <div className="old-articles-page">
      <header className="nav">
        <Link className="logo" href="/" aria-label="Jay Parmar — home">
          {/* eslint-disable-next-line @next/next/no-img-element */}
          <img src="/assets/brand/jay-parmar-mark.webp" alt="Jay Parmar" />
        </Link>
        <nav aria-label="Main navigation">
          <Link href="/#showcase">Work</Link>
          <Link className="active" href="/articles">
            Articles
          </Link>
          <Link href="/#dossier">About</Link>
        </nav>
        <a className="nav-cta" href="mailto:jaydeepak2532006@gmail.com">
          Let&apos;s talk <span>↗</span>
        </a>
      </header>

      <main>
        <section className="hero wrap">
          <div className="hero-copy">
            <p className="eyebrow">
              <i /> Notes from the field · 2026
            </p>
            <h1>
              Ideas for a world
              <br />
              in <em>motion.</em>
            </h1>
            <p className="intro">
              Essays on AI, leadership, institutions and the human judgment that connects
              them—shaped by conversations with builders, professors and industry leaders.
            </p>
          </div>
          <aside className="manifesto" aria-label="Editorial note">
            <span>Editorial note / 01</span>
            <blockquote>
              “Technology moves quickly. Understanding still asks us to slow down.”
            </blockquote>
            <p>Written by Jay Parmar from sessions, research and lived experience.</p>
          </aside>
        </section>

        <section className="index-strip" aria-label="Article collection summary">
          <div className="wrap stats">
            <div>
              <strong>{articles.length}</strong>
              <span>long-form essays</span>
            </div>
            <div>
              <strong>06</strong>
              <span>fields explored</span>
            </div>
            <div>
              <strong>01</strong>
              <span>recurring question: what matters?</span>
            </div>
          </div>
        </section>

        <section className="featured wrap" aria-labelledby="featured-heading">
          <div className="section-label">
            <span>01</span>
            <p>Featured thinking</p>
          </div>
          <h2 id="featured-heading">
            Start with the
            <br />
            <em>big questions.</em>
          </h2>
          <div className="featured-grid">
            {featured.map((article, i) => (
              <a
                key={article.id}
                className={i === 0 ? "feature-card primary" : "feature-card"}
                href={`#${article.id}`}
                onClick={() => handleOpenEssay(article.id)}
              >
                <div className="card-meta">
                  <span>{article.category}</span>
                  <span>{article.readTime}</span>
                </div>
                <div>
                  <small>{article.number}</small>
                  <h3>{article.title}</h3>
                  <p>{article.dek}</p>
                </div>
                <b>
                  Read essay <span>↓</span>
                </b>
              </a>
            ))}
          </div>
        </section>

        <section className="library" id="library">
          <div className="wrap">
            <div className="library-head">
              <div className="section-label light">
                <span>02</span>
                <p>The complete library</p>
              </div>
              <div className="library-title">
                <h2>
                  Browse every <em>idea.</em>
                </h2>
                <p>
                  Search by subject or open any essay to read it here. Every article is part of the
                  page—nothing sends you into a maze of tabs.
                </p>
              </div>
            </div>

            <div className="tools">
              <label className="search">
                <span>Search the archive</span>
                <div>
                  <svg viewBox="0 0 24 24" aria-hidden="true">
                    <circle cx="11" cy="11" r="6.5" />
                    <path d="m16 16 4 4" />
                  </svg>
                  <input
                    value={search}
                    onChange={(e) => setSearch(e.target.value)}
                    placeholder="Try ‘sovereignty’ or ‘leadership’"
                  />
                </div>
              </label>

              <div className="filters" aria-label="Filter articles by category">
                {categories.map((category) => (
                  <button
                    key={category}
                    type="button"
                    className={activeCategory === category ? "active" : undefined}
                    onClick={() => setActiveCategory(category)}
                  >
                    {category}
                  </button>
                ))}
              </div>
            </div>

            <div className="result-line">
              <span>{String(filtered.length).padStart(2, "0")} essays</span>
              <i />
            </div>

            <div className="articles">
              {filtered.length === 0 ? (
                <div className="empty">
                  <span>0 results</span>
                  <h3>No essay found.</h3>
                  <p>Try a broader search or choose another category.</p>
                  <button
                    type="button"
                    onClick={() => {
                      setSearch("");
                      setActiveCategory("All");
                    }}
                  >
                    Clear filters
                  </button>
                </div>
              ) : (
                filtered.map((article) => (
                  <details className="article" id={article.id} key={article.id}>
                    <summary>
                      <div className="article-number">{article.number}</div>
                      <div className="article-summary">
                        <div className="article-meta">
                          <span>{article.category}</span>
                          <span>{article.date}</span>
                          <span>{article.readTime}</span>
                        </div>
                        <h3>{article.title}</h3>
                        <p>{article.dek}</p>
                      </div>
                      <div className="toggle">
                        <span className="open-label">Read</span>
                        <span className="close-label">Close</span>
                        <b>+</b>
                      </div>
                    </summary>

                    <div className="article-body">
                      <div className="article-rail">
                        <span>Words by</span>
                        <strong>Jay Parmar</strong>
                        <i />
                        <span>{article.date}</span>
                      </div>

                      <div className="prose">
                        {article.quote && <blockquote>{article.quote}</blockquote>}
                        {article.sections.map((section, idx) => (
                          <section key={idx}>
                            {section.heading && <h4>{section.heading}</h4>}
                            {section.paragraphs.map((paragraph, pIdx) => (
                              <p key={pIdx}>{paragraph}</p>
                            ))}
                            {section.points && (
                              <ul>
                                {section.points.map((point, ptIdx) => (
                                  <li key={ptIdx}>{point}</li>
                                ))}
                              </ul>
                            )}
                          </section>
                        ))}

                        {article.links && (
                          <div className="references">
                            <span>People &amp; sources</span>
                            {article.links.map((link) => (
                              <a
                                key={link.url}
                                href={link.url}
                                target="_blank"
                                rel="noreferrer"
                              >
                                {link.label} ↗
                              </a>
                            ))}
                          </div>
                        )}

                        <a className="back" href={`#${article.id}`}>
                          Back to article top ↑
                        </a>
                      </div>
                    </div>
                  </details>
                ))
              )}
            </div>
          </div>
        </section>

        <section className="closing wrap">
          <p className="eyebrow">
            <i /> The thread through it all
          </p>
          <h2>
            Automate the friction.
            <br />
            <em>Preserve the judgment.</em>
          </h2>
          <div>
            <p>
              I write to make complex systems easier to see—and to understand where technology should
              accelerate us, where institutions must protect us, and where people still need to
              decide.
            </p>
            <a href="mailto:jaydeepak2532006@gmail.com">
              Continue the conversation <span>↗</span>
            </a>
          </div>
        </section>
      </main>

      <footer>
        <div className="wrap footer-inner">
          <Link className="logo inverse" href="/" aria-label="Jay Parmar — home">
            {/* eslint-disable-next-line @next/next/no-img-element */}
            <img src="/assets/brand/jay-parmar-mark.webp" alt="Jay Parmar" />
          </Link>
          <p>
            Ideas on AI, institutions
            <br />
            and human judgment.
          </p>
          <div>
            <a
              href="https://www.linkedin.com/in/jay-parmar-ai"
              target="_blank"
              rel="noreferrer"
            >
              LinkedIn ↗
            </a>
            <Link href="/">Portfolio ↗</Link>
          </div>
          <small>© 2026 Jay Parmar</small>
        </div>
      </footer>
    </div>
  );
}
```

---

## components/ui/badge.tsx

**File Path**: `components/ui/badge.tsx` | **Lines**: 53

```tsx
import { mergeProps } from "@base-ui/react/merge-props"
import { useRender } from "@base-ui/react/use-render"
import { cva, type VariantProps } from "class-variance-authority"

import { cn } from "@/lib/utils"

const badgeVariants = cva(
  "group/badge inline-flex h-5 w-fit shrink-0 items-center justify-center gap-1 overflow-hidden rounded-4xl border border-transparent px-2 py-0.5 text-xs font-medium whitespace-nowrap transition-all focus-visible:border-ring focus-visible:ring-[3px] focus-visible:ring-ring/50 has-data-[icon=inline-end]:pr-1.5 has-data-[icon=inline-start]:pl-1.5 aria-invalid:border-destructive aria-invalid:ring-destructive/20 dark:aria-invalid:ring-destructive/40 [&>svg]:pointer-events-none [&>svg]:size-3!",
  {
    variants: {
      variant: {
        default: "bg-primary text-primary-foreground [a]:hover:bg-primary/80",
        secondary:
          "bg-secondary text-secondary-foreground [a]:hover:bg-secondary/80",
        destructive:
          "bg-destructive/10 text-destructive focus-visible:ring-destructive/20 dark:bg-destructive/20 dark:focus-visible:ring-destructive/40 [a]:hover:bg-destructive/20",
        outline:
          "border-border text-foreground [a]:hover:bg-muted [a]:hover:text-muted-foreground",
        ghost:
          "hover:bg-muted hover:text-muted-foreground dark:hover:bg-muted/50",
        link: "text-primary underline-offset-4 hover:underline",
      },
    },
    defaultVariants: {
      variant: "default",
    },
  }
)

function Badge({
  className,
  variant = "default",
  render,
  ...props
}: useRender.ComponentProps<"span"> & VariantProps<typeof badgeVariants>) {
  return useRender({
    defaultTagName: "span",
    props: mergeProps<"span">(
      {
        className: cn(badgeVariants({ variant }), className),
      },
      props
    ),
    render,
    state: {
      slot: "badge",
      variant,
    },
  })
}

export { Badge, badgeVariants }
```

---

## components/ui/button-shiny.tsx

**File Path**: `components/ui/button-shiny.tsx` | **Lines**: 106

```tsx
"use client";
import * as React from "react";
import { cn } from "@/lib/utils";

interface ButtonCtaProps extends React.ButtonHTMLAttributes<HTMLButtonElement> {
  label?: string;
  className?: string;
  children?: React.ReactNode;
}

function ButtonCta({
  label = "Get Access",
  className,
  children,
  ...props
}: ButtonCtaProps) {
  return (
    <button
      className={cn(
        "group relative inline-flex items-center justify-center h-12 px-8 rounded-[11px] overflow-hidden cursor-pointer outline-none isolate leading-none",
        "transition-[transform,box-shadow] duration-500 ease-out",
        "active:translate-y-px",
        "focus-visible:ring-2 focus-visible:ring-[#a78bfa]/50 focus-visible:ring-offset-2 focus-visible:ring-offset-[#0a0a0a]",
        "shadow-[0_10px_30px_-14px_rgba(0,0,0,0.7),0_0_0_1px_rgba(167,139,250,0.06)]",
        "hover:shadow-[0_22px_60px_-14px_rgba(167,139,250,0.55),0_0_0_1px_rgba(167,139,250,0.18)]",
        className
      )}
      {...props}
    >
      {/* 1. Rotating conic comet — the signature motion */}
      <span
        aria-hidden
        className="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 aspect-square w-[260%] animate-[spin_5s_linear_infinite] -z-10"
        style={{
          background:
            "conic-gradient(from 0deg, transparent 0deg, transparent 240deg, rgba(167,139,250,0) 250deg, rgba(167,139,250,0.85) 300deg, rgba(232,225,255,0.95) 330deg, rgba(196,181,253,0.6) 350deg, transparent 360deg)",
        }}
      />

      {/* 2. Slow counter-rotating second comet — gives it 3D parallax */}
      <span
        aria-hidden
        className="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2 aspect-square w-[260%] animate-[spin_9s_linear_infinite] [animation-direction:reverse] opacity-60 -z-10"
        style={{
          background:
            "conic-gradient(from 180deg, transparent 0deg, transparent 280deg, rgba(196,181,253,0.5) 320deg, rgba(167,139,250,0.7) 350deg, transparent 360deg)",
        }}
      />

      {/* 3. Dark glass body — clips the comet to a 1.5px border ring */}
      <span aria-hidden className="absolute inset-[1.5px] rounded-[9.5px] bg-[#0a0814]" />

      {/* 4. Vertical depth gradient inside body */}
      <span
        aria-hidden
        className="absolute inset-[1.5px] rounded-[9.5px]"
        style={{
          background:
            "linear-gradient(180deg, rgba(196,181,253,0.08) 0%, rgba(10,8,20,0) 38%, rgba(0,0,0,0.55) 100%)",
        }}
      />

      {/* 5. Top "lit glass" hairline */}
      <span
        aria-hidden
        className="absolute inset-x-4 top-[1.5px] h-px"
        style={{
          background:
            "linear-gradient(90deg, transparent, rgba(232,225,255,0.55), transparent)",
        }}
      />

      {/* 6. Bottom violet rim — picks up the comet color even when it's elsewhere */}
      <span
        aria-hidden
        className="absolute inset-x-6 bottom-[1.5px] h-px opacity-70"
        style={{
          background:
            "linear-gradient(90deg, transparent, rgba(167,139,250,0.45), transparent)",
        }}
      />

      {/* 7. Inner halo — intensifies on hover (comet "lands") */}
      <span
        aria-hidden
        className="absolute inset-[1.5px] rounded-[9.5px] transition-shadow duration-500 shadow-[inset_0_0_18px_rgba(167,139,250,0.12)] group-hover:shadow-[inset_0_0_30px_rgba(167,139,250,0.32)]"
      />

      {/* 8. Label */}
      <span className="relative flex items-center justify-center gap-2 transition-transform duration-500 ease-out group-hover:-translate-y-[1px]">
        <span
          className="text-[15px] font-light tracking-[0.01em] whitespace-nowrap bg-clip-text text-transparent drop-shadow-[0_0_12px_rgba(167,139,250,0.30)] transition-[filter] duration-500 group-hover:drop-shadow-[0_0_20px_rgba(167,139,250,0.6)]"
          style={{
            backgroundImage:
              "linear-gradient(180deg, #F8F4FF 0%, #E9DEFB 50%, #C4B5FD 100%)",
          }}
        >
          {children ?? label}
        </span>
      </span>
    </button>
  );
}

export { ButtonCta };
```

---

## components/ui/button.tsx

**File Path**: `components/ui/button.tsx` | **Lines**: 59

```tsx
import { Button as ButtonPrimitive } from "@base-ui/react/button"
import { cva, type VariantProps } from "class-variance-authority"

import { cn } from "@/lib/utils"

const buttonVariants = cva(
  "group/button inline-flex shrink-0 items-center justify-center rounded-lg border border-transparent bg-clip-padding text-sm font-medium whitespace-nowrap transition-all outline-none select-none focus-visible:border-ring focus-visible:ring-3 focus-visible:ring-ring/50 active:not-aria-[haspopup]:translate-y-px disabled:pointer-events-none disabled:opacity-50 aria-invalid:border-destructive aria-invalid:ring-3 aria-invalid:ring-destructive/20 dark:aria-invalid:border-destructive/50 dark:aria-invalid:ring-destructive/40 [&_svg]:pointer-events-none [&_svg]:shrink-0 [&_svg:not([class*='size-'])]:size-4",
  {
    variants: {
      variant: {
        default: "bg-primary text-primary-foreground [a]:hover:bg-primary/80",
        outline:
          "border-border bg-background hover:bg-muted hover:text-foreground aria-expanded:bg-muted aria-expanded:text-foreground dark:border-input dark:bg-input/30 dark:hover:bg-input/50",
        secondary:
          "bg-secondary text-secondary-foreground hover:bg-secondary/80 aria-expanded:bg-secondary aria-expanded:text-secondary-foreground",
        ghost:
          "hover:bg-muted hover:text-foreground aria-expanded:bg-muted aria-expanded:text-foreground dark:hover:bg-muted/50",
        destructive:
          "bg-destructive/10 text-destructive hover:bg-destructive/20 focus-visible:border-destructive/40 focus-visible:ring-destructive/20 dark:bg-destructive/20 dark:hover:bg-destructive/30 dark:focus-visible:ring-destructive/40",
        link: "text-primary underline-offset-4 hover:underline",
      },
      size: {
        default:
          "h-8 gap-1.5 px-2.5 has-data-[icon=inline-end]:pr-2 has-data-[icon=inline-start]:pl-2",
        xs: "h-6 gap-1 rounded-[min(var(--radius-md),10px)] px-2 text-xs in-data-[slot=button-group]:rounded-lg has-data-[icon=inline-end]:pr-1.5 has-data-[icon=inline-start]:pl-1.5 [&_svg:not([class*='size-'])]:size-3",
        sm: "h-7 gap-1 rounded-[min(var(--radius-md),12px)] px-2.5 text-[0.8rem] in-data-[slot=button-group]:rounded-lg has-data-[icon=inline-end]:pr-1.5 has-data-[icon=inline-start]:pl-1.5 [&_svg:not([class*='size-'])]:size-3.5",
        lg: "h-9 gap-1.5 px-2.5 has-data-[icon=inline-end]:pr-2 has-data-[icon=inline-start]:pl-2",
        icon: "size-8",
        "icon-xs":
          "size-6 rounded-[min(var(--radius-md),10px)] in-data-[slot=button-group]:rounded-lg [&_svg:not([class*='size-'])]:size-3",
        "icon-sm":
          "size-7 rounded-[min(var(--radius-md),12px)] in-data-[slot=button-group]:rounded-lg",
        "icon-lg": "size-9",
      },
    },
    defaultVariants: {
      variant: "default",
      size: "default",
    },
  }
)

function Button({
  className,
  variant = "default",
  size = "default",
  ...props
}: ButtonPrimitive.Props & VariantProps<typeof buttonVariants>) {
  return (
    <ButtonPrimitive
      data-slot="button"
      className={cn(buttonVariants({ variant, size, className }))}
      {...props}
    />
  )
}

export { Button, buttonVariants }
```

---

## components/ui/card-carousel-demo.tsx

**File Path**: `components/ui/card-carousel-demo.tsx` | **Lines**: 117

```tsx
import React from "react";

import { CardCarousel } from "@/components/ui/card-carousel";

const CardCarouselDemo = () => {
  const images = [
    {
      src: "/assets/carousel/carousel-09.webp",
      alt: "With TCS CEO & MD K. Krithivasan — National Hackathon Winner",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-25.webp",
      alt: "PackEdge 1st Position — Techfest IIT Bombay",
      objectPosition: "center",
      link: "https://drive.google.com/file/d/198jU7tjaPgLchEVKDLTQ7UO2OzyOkM91/view",
    },
    {
      src: "/assets/carousel/carousel-33.webp",
      alt: "ShikshaShakti.AI — ₹2L DST-NIDHI Ignition Grant",
      objectPosition: "center",
      link: "https://drive.google.com/file/d/1KB5ZEOAgdl6hEC4cCXVQ1u9I0FcxkGHx/view",
    },
    {
      src: "/assets/carousel/carousel-16.webp",
      alt: "The Hitavada — Regional Press Coverage",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-26.webp",
      alt: "Dainik Bhaskar — National Achievement Feature",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-10.webp",
      alt: "Hack-LLM Winner at IIIT Delhi — Press Coverage",
      objectPosition: "center",
    },
    {
      src: "/assets/carousel/carousel-20.webp",
      alt: "Patrika — Youth Tech & Innovation Feature",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-21.webp",
      alt: "Navabharat — Hackathon Winner Feature",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-24.webp",
      alt: "With Angel One CEO Ambarish Kenghe",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-14.webp",
      alt: "With Marsh McLennan Leadership — Pushparanjan Malajure",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-22.webp",
      alt: "With NDTV Profit — Tamanna Inamdar",
      objectPosition: "center top",
    },
    {
      src: "/assets/carousel/carousel-19.webp",
      alt: "India AI Impact Summit 2026",
      objectPosition: "center",
    },
    {
      src: "/assets/carousel/carousel-15.webp",
      alt: "Reserve Bank of India Institutional Visit",
      objectPosition: "center",
    },
    {
      src: "/assets/carousel/carousel-27.webp",
      alt: "IBM Quantum System Two Showcase",
      objectPosition: "center",
    },
    {
      src: "/assets/carousel/carousel-05.webp",
      alt: "Young Leadership Summit — IIM Bangalore (Top 20 of 70,000+)",
      objectPosition: "center",
    },
    {
      src: "/assets/portfolio/certificates/cert-01.jpg",
      alt: "Certificate — PackEdge 1st Position, IIT Bombay Techfest",
      objectPosition: "center",
      link: "/assets/portfolio/certificates/cert-01.jpg",
    },
    {
      src: "/assets/portfolio/certificates/cert-02.jpg",
      alt: "Certificate — TCS Foundation First Place, NIT Trichy",
      objectPosition: "center",
      link: "/assets/portfolio/certificates/cert-02.jpg",
    },
    {
      src: "/assets/portfolio/certificates/cert-05.jpg",
      alt: "Certificate — Drone Technology E-SDP, Ministry of MSME",
      objectPosition: "center",
      link: "/assets/portfolio/certificates/cert-05.jpg",
    },
  ];

  return (
    <div className="w-full">
      <CardCarousel
        images={images}
        autoplayDelay={3500}
        showPagination={true}
        showNavigation={true}
      />
    </div>
  );
};

export default CardCarouselDemo;
```

---

## components/ui/card-carousel.tsx

**File Path**: `components/ui/card-carousel.tsx` | **Lines**: 220

```tsx
"use client";

import React from "react";
import Image from "next/image";
import { Swiper, SwiperSlide } from "swiper/react";

import "swiper/css";
import "swiper/css/effect-coverflow";
import "swiper/css/pagination";
import "swiper/css/navigation";
import { SparklesIcon } from "lucide-react";
import {
  Autoplay,
  EffectCoverflow,
  Navigation,
  Pagination,
} from "swiper/modules";

import { Badge } from "@/components/ui/badge";

interface CarouselProps {
  images: { src: string; alt: string; objectPosition?: string; link?: string }[];
  autoplayDelay?: number;
  showPagination?: boolean;
  showNavigation?: boolean;
}

export const CardCarousel: React.FC<CarouselProps> = ({
  images,
  autoplayDelay = 1500,
  showPagination = true,
  showNavigation = true,
}) => {
  const css = `
  .swiper {
    width: 100%;
    padding-bottom: 50px;
  }

  .swiper-slide {
    background-position: center;
    background-size: cover;
    width: 300px;
  }

  .swiper-slide img {
    display: block;
    width: 100%;
  }

  .swiper-3d .swiper-slide-shadow-left {
    background-image: none;
  }
  .swiper-3d .swiper-slide-shadow-right{
    background: none;
  }

  .cc-card {
    transition: transform 0.35s cubic-bezier(0.22, 1, 0.36, 1), box-shadow 0.35s ease;
    will-change: transform;
  }
  .cc-card:hover {
    transform: scale(1.04);
    box-shadow: 0 24px 56px -16px rgba(0, 0, 0, 0.55), 0 0 0 1px rgba(255, 255, 255, 0.06);
  }

  .swiper-pagination-bullet {
    width: 7px;
    height: 7px;
    background: rgba(255, 255, 255, 0.22);
    opacity: 1;
    transition: background 0.35s ease, transform 0.35s ease, width 0.35s ease, box-shadow 0.35s ease;
    border-radius: 9999px;
  }
  .swiper-pagination-bullet:hover {
    background: rgba(255, 255, 255, 0.4);
  }
  .swiper-pagination-bullet-active {
    width: 26px;
    background: linear-gradient(90deg, #c4b5fd 0%, #a78bfa 100%);
    box-shadow: 0 0 14px rgba(167, 139, 250, 0.55);
  }
  `;
  return (
    <section
      style={{
        width: "100%",
        display: "flex",
        justifyContent: "center",
        alignItems: "center",
      }}
    >
      <style>{css}</style>
      <div
        style={{
          width: "100%",
          maxWidth: "64rem",
          marginLeft: "auto",
          marginRight: "auto",
          borderRadius: "24px",
          border: "1px solid rgba(255,255,255,0.08)",
          padding: "0.5rem",
          boxSizing: "border-box",
        }}
      >
        <div
          style={{
            position: "relative",
            width: "100%",
            display: "flex",
            flexDirection: "column",
            alignItems: "center",
            gap: "3rem",
            borderRadius: "20px",
            border: "1px solid rgba(255,255,255,0.06)",
            background: "rgba(64,64,64,0.05)",
            padding: "2rem 1rem",
            boxSizing: "border-box",
          }}
        >
          
          <div
            style={{
              display: "flex",
              flexDirection: "column",
              alignItems: "center",
              textAlign: "center",
              paddingTop: "3rem",
              paddingBottom: "2rem",
            }}
          >
            <h3 style={{ fontSize: "2.25rem", opacity: 0.85, fontWeight: 700, letterSpacing: "-0.02em" }}>
              Press, Awards &amp; Field Archive
            </h3>
            <p style={{ marginTop: "0.5rem", opacity: 0.7 }}>
              National hackathon victories, newspaper features, leadership summits, and verified credentials.
            </p>
          </div>

          <div style={{ display: "flex", width: "100%", alignItems: "center", justifyContent: "center", gap: "1rem", marginTop: "1rem" }}>
            <div style={{ width: "100%" }}>
              <Swiper
                spaceBetween={50}
                autoplay={{
                  delay: autoplayDelay,
                  disableOnInteraction: false,
                  pauseOnMouseEnter: true,
                }}
                effect={"coverflow"}
                grabCursor={true}
                centeredSlides={true}
                loop={true}
                slidesPerView={"auto"}
                coverflowEffect={{
                  rotate: 18,
                  stretch: 0,
                  depth: 130,
                  modifier: 1.5,
                  slideShadows: false,
                }}
                pagination={showPagination}
                navigation={
                  showNavigation
                    ? {
                        nextEl: ".swiper-button-next",
                        prevEl: ".swiper-button-prev",
                      }
                    : undefined
                }
                modules={[EffectCoverflow, Autoplay, Pagination, Navigation]}
              >
                {images.map((image, index) => {
                  const inner = (
                    <div
                      className="rounded-3xl overflow-hidden cc-card"
                      style={{ width: "320px", height: "480px", flexShrink: 0 }}
                    >
                      <Image
                        src={image.src}
                        width={500}
                        height={750}
                        sizes="(max-width: 640px) 320px, 500px"
                        loading="lazy"
                        className="rounded-xl"
                        style={{
                          width: "100%",
                          height: "100%",
                          objectFit: "cover",
                          objectPosition: image.objectPosition ?? "center",
                        }}
                        alt={image.alt}
                      />
                    </div>
                  );
                  return (
                    <SwiperSlide key={`a-${index}`}>
                      {image.link ? (
                        <a
                          href={image.link}
                          target="_blank"
                          rel="noopener noreferrer"
                          style={{ display: "block", cursor: "pointer" }}
                        >
                          {inner}
                        </a>
                      ) : (
                        inner
                      )}
                    </SwiperSlide>
                  );
                })}
              </Swiper>
            </div>
          </div>
        </div>
      </div>
    </section>
  );
};
```

---

## components/ui/card.tsx

**File Path**: `components/ui/card.tsx` | **Lines**: 104

```tsx
import * as React from "react"

import { cn } from "@/lib/utils"

function Card({
  className,
  size = "default",
  ...props
}: React.ComponentProps<"div"> & { size?: "default" | "sm" }) {
  return (
    <div
      data-slot="card"
      data-size={size}
      className={cn(
        "group/card flex flex-col gap-4 overflow-hidden rounded-xl bg-card py-4 text-sm text-card-foreground ring-1 ring-foreground/10 has-data-[slot=card-footer]:pb-0 has-[>img:first-child]:pt-0 data-[size=sm]:gap-3 data-[size=sm]:py-3 data-[size=sm]:has-data-[slot=card-footer]:pb-0 *:[img:first-child]:rounded-t-xl *:[img:last-child]:rounded-b-xl",
        className
      )}
      {...props}
    />
  )
}

function CardHeader({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-header"
      className={cn(
        "group/card-header @container/card-header grid auto-rows-min items-start gap-1 rounded-t-xl px-4 group-data-[size=sm]/card:px-3 has-data-[slot=card-action]:grid-cols-[1fr_auto] has-data-[slot=card-description]:grid-rows-[auto_auto] [.border-b]:pb-4 group-data-[size=sm]/card:[.border-b]:pb-3",
        className
      )}
      {...props}
    />
  )
}

function CardTitle({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-title"
      className={cn(
        "font-heading text-base leading-snug font-medium group-data-[size=sm]/card:text-sm",
        className
      )}
      {...props}
    />
  )
}

function CardDescription({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-description"
      className={cn("text-sm text-muted-foreground", className)}
      {...props}
    />
  )
}

function CardAction({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-action"
      className={cn(
        "col-start-2 row-span-2 row-start-1 self-start justify-self-end",
        className
      )}
      {...props}
    />
  )
}

function CardContent({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-content"
      className={cn("px-4 group-data-[size=sm]/card:px-3", className)}
      {...props}
    />
  )
}

function CardFooter({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="card-footer"
      className={cn(
        "flex items-center rounded-b-xl border-t bg-muted/50 p-4 group-data-[size=sm]/card:p-3",
        className
      )}
      {...props}
    />
  )
}

export {
  Card,
  CardHeader,
  CardFooter,
  CardTitle,
  CardAction,
  CardDescription,
  CardContent,
}
```

---

## components/ui/container-scroll-animation.tsx

**File Path**: `components/ui/container-scroll-animation.tsx` | **Lines**: 102

```tsx
"use client";
import React, { createContext, useContext, useRef } from "react";
import { useScroll, useTransform, motion, MotionValue } from "framer-motion";

export const ContainerScrollContext = createContext<MotionValue<number> | null>(null);

export const useContainerScroll = () => useContext(ContainerScrollContext);

export const ContainerScroll = ({
  titleComponent,
  children,
}: {
  titleComponent: string | React.ReactNode;
  children: React.ReactNode;
}) => {
  const containerRef = useRef<HTMLDivElement>(null);
  const { scrollYProgress } = useScroll({
    target: containerRef,
  });
  const [isMobile, setIsMobile] = React.useState(false);

  React.useEffect(() => {
    const checkMobile = () => {
      setIsMobile(window.innerWidth <= 768);
    };
    checkMobile();
    window.addEventListener("resize", checkMobile);
    return () => {
      window.removeEventListener("resize", checkMobile);
    };
  }, []);

  const scaleDimensions = () => {
    return isMobile ? [0.7, 0.9] : [1.05, 1];
  };

  const rotate = useTransform(scrollYProgress, [0.5, 1], [20, 0]);
  const scale = useTransform(scrollYProgress, [0.5, 1], scaleDimensions());
  const translate = useTransform(scrollYProgress, [0, 1], [0, -100]);

  return (
    <ContainerScrollContext.Provider value={scrollYProgress}>
      <div
        className="h-[60rem] md:h-[80rem] flex items-center justify-center relative p-2 md:p-20"
        ref={containerRef}
      >
        <div
          className="py-10 md:py-40 w-full relative"
          style={{
            perspective: "1000px",
          }}
        >
          <Header translate={translate} titleComponent={titleComponent} />
          <Card rotate={rotate} translate={translate} scale={scale}>
            {children}
          </Card>
        </div>
      </div>
    </ContainerScrollContext.Provider>
  );
};

export const Header = ({ translate, titleComponent }: any) => {
  return (
    <motion.div
      style={{
        translateY: translate,
      }}
      className="div max-w-5xl mx-auto text-center"
    >
      {titleComponent}
    </motion.div>
  );
};

export const Card = ({
  rotate,
  scale,
  children,
}: {
  rotate: MotionValue<number>;
  scale: MotionValue<number>;
  translate: MotionValue<number>;
  children: React.ReactNode;
}) => {
  return (
    <motion.div
      style={{
        rotateX: rotate,
        scale,
        boxShadow:
          "0 0 #0000004d, 0 9px 20px #0000004a, 0 37px 37px #00000042, 0 84px 50px #00000026, 0 149px 60px #0000000a, 0 233px 65px #00000003",
      }}
      className="max-w-7xl -mt-12 mx-auto h-[34rem] md:h-[48rem] w-full border-4 border-[#6C6C6C] p-2 md:p-6 bg-[#222222] rounded-[30px] shadow-2xl"
    >
      <div className=" h-full w-full  overflow-hidden rounded-2xl bg-gray-100 dark:bg-zinc-900 md:rounded-2xl md:p-4 ">
        {children}
      </div>
    </motion.div>
  );
};
```

---

## components/ui/dialog.tsx

**File Path**: `components/ui/dialog.tsx` | **Lines**: 161

```tsx
"use client"

import * as React from "react"
import { Dialog as DialogPrimitive } from "@base-ui/react/dialog"

import { cn } from "@/lib/utils"
import { Button } from "@/components/ui/button"
import { XIcon } from "lucide-react"

function Dialog({ ...props }: DialogPrimitive.Root.Props) {
  return <DialogPrimitive.Root data-slot="dialog" {...props} />
}

function DialogTrigger({ ...props }: DialogPrimitive.Trigger.Props) {
  return <DialogPrimitive.Trigger data-slot="dialog-trigger" {...props} />
}

function DialogPortal({ ...props }: DialogPrimitive.Portal.Props) {
  return <DialogPrimitive.Portal data-slot="dialog-portal" {...props} />
}

function DialogClose({ ...props }: DialogPrimitive.Close.Props) {
  return <DialogPrimitive.Close data-slot="dialog-close" {...props} />
}

function DialogOverlay({
  className,
  ...props
}: DialogPrimitive.Backdrop.Props) {
  return (
    <DialogPrimitive.Backdrop
      data-slot="dialog-overlay"
      className={cn(
        "fixed inset-0 isolate z-50 bg-black/10 duration-100 supports-backdrop-filter:backdrop-blur-xs data-open:animate-in data-open:fade-in-0 data-closed:animate-out data-closed:fade-out-0",
        className
      )}
      {...props}
    />
  )
}

function DialogContent({
  className,
  children,
  showCloseButton = true,
  ...props
}: DialogPrimitive.Popup.Props & {
  showCloseButton?: boolean
}) {
  return (
    <DialogPortal>
      <DialogOverlay />
      <DialogPrimitive.Popup
        data-slot="dialog-content"
        className={cn(
          "fixed top-1/2 left-1/2 z-50 grid w-full max-w-[calc(100%-2rem)] -translate-x-1/2 -translate-y-1/2 gap-4 rounded-xl bg-popover p-4 text-sm text-popover-foreground ring-1 ring-foreground/10 duration-100 outline-none sm:max-w-sm data-open:animate-in data-open:fade-in-0 data-open:zoom-in-95 data-closed:animate-out data-closed:fade-out-0 data-closed:zoom-out-95",
          className
        )}
        {...props}
      >
        {children}
        {showCloseButton && (
          <DialogPrimitive.Close
            data-slot="dialog-close"
            render={
              <Button
                variant="ghost"
                className="absolute top-2 right-2"
                size="icon-sm"
              />
            }
          >
            <XIcon
            />
            <span className="sr-only">Close</span>
          </DialogPrimitive.Close>
        )}
      </DialogPrimitive.Popup>
    </DialogPortal>
  )
}

function DialogHeader({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="dialog-header"
      className={cn("flex flex-col gap-2", className)}
      {...props}
    />
  )
}

function DialogFooter({
  className,
  showCloseButton = false,
  children,
  ...props
}: React.ComponentProps<"div"> & {
  showCloseButton?: boolean
}) {
  return (
    <div
      data-slot="dialog-footer"
      className={cn(
        "-mx-4 -mb-4 flex flex-col-reverse gap-2 rounded-b-xl border-t bg-muted/50 p-4 sm:flex-row sm:justify-end",
        className
      )}
      {...props}
    >
      {children}
      {showCloseButton && (
        <DialogPrimitive.Close render={<Button variant="outline" />}>
          Close
        </DialogPrimitive.Close>
      )}
    </div>
  )
}

function DialogTitle({ className, ...props }: DialogPrimitive.Title.Props) {
  return (
    <DialogPrimitive.Title
      data-slot="dialog-title"
      className={cn(
        "font-heading text-base leading-none font-medium",
        className
      )}
      {...props}
    />
  )
}

function DialogDescription({
  className,
  ...props
}: DialogPrimitive.Description.Props) {
  return (
    <DialogPrimitive.Description
      data-slot="dialog-description"
      className={cn(
        "text-sm text-muted-foreground *:[a]:underline *:[a]:underline-offset-3 *:[a]:hover:text-foreground",
        className
      )}
      {...props}
    />
  )
}

export {
  Dialog,
  DialogClose,
  DialogContent,
  DialogDescription,
  DialogFooter,
  DialogHeader,
  DialogOverlay,
  DialogPortal,
  DialogTitle,
  DialogTrigger,
}
```

---

## components/ui/file-tree.tsx

**File Path**: `components/ui/file-tree.tsx` | **Lines**: 254

```tsx
"use client";

import React, { useState, useCallback, memo } from "react";
import { cn } from "@/lib/utils";

export interface FileNode {
  name: string;
  type: "file" | "folder";
  children?: FileNode[];
  extension?: string;
}

interface FileTreeProps {
  data: FileNode[];
  className?: string;
  defaultOpen?: boolean;
  initialActive?: string;
}

const EXT_META: Record<string, { color: string; glyph: string }> = {
  tsx: { color: "#7dd3fc", glyph: "⚛" },
  ts: { color: "#60a5fa", glyph: "◆" },
  jsx: { color: "#67e8f9", glyph: "⚛" },
  js: { color: "#fde68a", glyph: "◆" },
  css: { color: "#c4b5fd", glyph: "◈" },
  json: { color: "#fcd34d", glyph: "{}" },
  md: { color: "#9a9a9a", glyph: "◊" },
  svg: { color: "#86efac", glyph: "◐" },
  png: { color: "#a7f3d0", glyph: "◑" },
  default: { color: "#9a9a9a", glyph: "◇" },
};

const getMeta = (ext?: string) => EXT_META[ext || "default"] || EXT_META.default;

const Chevron = memo(({ open }: { open: boolean }) => (
  <svg
    width="8"
    height="8"
    viewBox="0 0 8 8"
    fill="none"
    className={cn(
      "transition-transform duration-300 ease-out shrink-0",
      open ? "rotate-90" : "rotate-0"
    )}
  >
    <path
      d="M2 1L6 4L2 7"
      stroke="currentColor"
      strokeWidth="1.3"
      strokeLinecap="round"
      strokeLinejoin="round"
    />
  </svg>
));
Chevron.displayName = "Chevron";

const FolderGlyph = memo(({ open }: { open: boolean }) => (
  <svg width="13" height="11" viewBox="0 0 16 14" fill="currentColor" className="shrink-0">
    {open ? (
      <path d="M1.5 1C0.67 1 0 1.67 0 2.5V11.5C0 12.33 0.67 13 1.5 13H13.5C14.33 13 15 12.33 15 11.5L16 5H3.5L2.5 3H1.5Z" />
    ) : (
      <path d="M1.5 1C0.67 1 0 1.67 0 2.5V11.5C0 12.33 0.67 13 1.5 13H14.5C15.33 13 16 12.33 16 11.5V4.5C16 3.67 15.33 3 14.5 3H8L6.5 1H1.5Z" />
    )}
  </svg>
));
FolderGlyph.displayName = "FolderGlyph";

interface ItemProps {
  node: FileNode;
  depth: number;
  path: string;
  activePath: string | null;
  onSelect: (path: string, isFolder: boolean) => void;
  defaultOpen: boolean;
}

const FileItem = memo(function FileItem({
  node,
  depth,
  path,
  activePath,
  onSelect,
  defaultOpen,
}: ItemProps) {
  const [open, setOpen] = useState(defaultOpen);
  const isFolder = node.type === "folder";
  const hasChildren = isFolder && !!node.children?.length;
  const meta = getMeta(node.extension);
  const isActive = activePath === path;

  const handleClick = useCallback(() => {
    if (isFolder) setOpen((o) => !o);
    onSelect(path, isFolder);
  }, [isFolder, onSelect, path]);

  const onKey = (e: React.KeyboardEvent) => {
    if (e.key === "Enter" || e.key === " ") {
      e.preventDefault();
      handleClick();
    } else if (e.key === "ArrowRight" && isFolder && !open) {
      setOpen(true);
    } else if (e.key === "ArrowLeft" && isFolder && open) {
      setOpen(false);
    }
  };

  return (
    <div className="select-none">
      <div
        role="treeitem"
        aria-expanded={isFolder ? open : undefined}
        aria-selected={isActive}
        tabIndex={0}
        onClick={handleClick}
        onKeyDown={onKey}
        className={cn(
          "group relative flex items-center gap-1.5 py-[3px] pr-2 rounded-[4px] cursor-pointer outline-none",
          "transition-[transform,color] duration-200 ease-out",
          "hover:translate-x-[1px]",
          "focus-visible:ring-1 focus-visible:ring-[#a78bfa]/40",
          isActive && "shadow-[inset_2px_0_0_0_#a78bfa]"
        )}
        style={{ paddingLeft: `${depth * 12 + 6}px` }}
      >
        {/* Indent guide */}
        {depth > 0 && (
          <span
            aria-hidden
            className="absolute top-0 bottom-0 w-px bg-[#1f1f1f] group-hover:bg-[#a78bfa]/20 transition-colors"
            style={{ left: `${(depth - 1) * 12 + 11}px` }}
          />
        )}

        {/* Chevron slot (folders) */}
        <span
          className={cn(
            "w-[10px] flex items-center justify-center shrink-0 transition-colors",
            isFolder ? "text-[#7a7a7a] group-hover:text-[#a78bfa]" : "opacity-0"
          )}
        >
          {isFolder && <Chevron open={open} />}
        </span>

        {/* Icon */}
        <span
          className={cn(
            "flex items-center justify-center w-[14px] h-[14px] transition-all duration-200 ease-out",
            "group-hover:scale-125 group-hover:[filter:drop-shadow(0_0_6px_currentColor)]"
          )}
          style={{ color: isFolder ? (open ? "#c4b5fd" : "#a78bfa") : meta.color }}
        >
          {isFolder ? (
            <FolderGlyph open={open} />
          ) : (
            <svg width="11" height="13" viewBox="0 0 14 16" fill="currentColor">
              <path d="M1.5 0C0.67 0 0 0.67 0 1.5V14.5C0 15.33 0.67 16 1.5 16H12.5C13.33 16 14 15.33 14 14.5V4.5L9.5 0H1.5Z" opacity="0.85" />
              <path d="M9 0V4.5H14" opacity="0.4" />
            </svg>
          )}
        </span>

        {/* Name */}
        <span
          className={cn(
            "font-mono text-[12px] tracking-tight truncate transition-colors duration-200",
            isActive
              ? "text-white"
              : isFolder
                ? "text-[#d4d4d4] group-hover:text-white"
                : "text-[#bfbfbf] group-hover:text-white"
          )}
        >
          {node.name}
        </span>

        {/* Active dot */}
        <span
          aria-hidden
          className={cn(
            "ml-auto w-1 h-1 rounded-full bg-[#a78bfa] transition-all duration-300",
            isActive
              ? "opacity-100 shadow-[0_0_6px_#a78bfa]"
              : "opacity-0 group-hover:opacity-60"
          )}
        />
      </div>

      {/* Children */}
      {hasChildren && (
        <div
          role="group"
          aria-hidden={!open}
          className={cn(
            "overflow-hidden transition-[max-height,opacity,transform] duration-300 ease-out",
            open
              ? "max-h-500 opacity-100 translate-y-0"
              : "max-h-0 opacity-0 -translate-y-1 pointer-events-none"
          )}
        >
          {node.children!.map((child) => (
            <FileItem
              key={`${path}/${child.name}`}
              node={child}
              depth={depth + 1}
              path={`${path}/${child.name}`}
              activePath={activePath}
              onSelect={onSelect}
              defaultOpen={defaultOpen}
            />
          ))}
        </div>
      )}
    </div>
  );
});

export const FileTree = memo(function FileTree({
  data,
  className,
  defaultOpen = true,
  initialActive = null as unknown as string,
}: FileTreeProps) {
  const [activePath, setActivePath] = useState<string | null>(initialActive ?? null);

  const handleSelect = useCallback((path: string, isFolder: boolean) => {
    if (!isFolder) setActivePath(path);
  }, []);

  return (
    <div
      role="tree"
      aria-label="Portfolio file explorer"
      className={cn(
        "font-mono text-[#cfcfcf] [scrollbar-width:none] [&::-webkit-scrollbar]:hidden",
        className
      )}
    >
      {data.map((node) => (
        <FileItem
          key={node.name}
          node={node}
          depth={0}
          path={node.name}
          activePath={activePath}
          onSelect={handleSelect}
          defaultOpen={defaultOpen}
        />
      ))}
    </div>
  );
});

export default FileTree;
```

---

## components/ui/footer-demo.tsx

**File Path**: `components/ui/footer-demo.tsx` | **Lines**: 74

```tsx
"use client";
import type { SVGProps } from "react";
import { Footer } from "@/components/ui/modem-animated-footer";
import {
  BookOpen,
  FileText,
  Mail,
  NotepadTextDashed,
} from "lucide-react";

const LinkedinIcon = (props: SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 24 24" fill="currentColor" {...props}>
    <path d="M20.45 20.45h-3.55v-5.57c0-1.33-.03-3.04-1.85-3.04-1.86 0-2.14 1.45-2.14 2.95v5.66H9.36V9h3.41v1.56h.05c.48-.9 1.64-1.85 3.38-1.85 3.61 0 4.28 2.38 4.28 5.47v6.27ZM5.34 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12ZM7.12 20.45H3.56V9h3.56v11.45ZM22.22 0H1.77C.79 0 0 .77 0 1.72v20.55C0 23.23.79 24 1.77 24h20.45c.98 0 1.78-.77 1.78-1.73V1.72C24 .77 23.2 0 22.22 0Z" />
  </svg>
);

const GithubIcon = (props: SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 24 24" fill="currentColor" {...props}>
    <path d="M12 .5a12 12 0 0 0-3.79 23.39c.6.11.82-.26.82-.58v-2.04c-3.34.72-4.04-1.61-4.04-1.61-.54-1.39-1.33-1.76-1.33-1.76-1.09-.74.08-.73.08-.73 1.21.09 1.84 1.24 1.84 1.24 1.07 1.83 2.81 1.3 3.5.99.11-.78.42-1.3.76-1.6-2.66-.3-5.47-1.33-5.47-5.93 0-1.31.47-2.38 1.24-3.22-.13-.31-.54-1.53.11-3.19 0 0 1.01-.32 3.3 1.23a11.5 11.5 0 0 1 6 0c2.29-1.55 3.3-1.23 3.3-1.23.66 1.66.24 2.88.12 3.19.77.84 1.23 1.91 1.23 3.22 0 4.61-2.81 5.62-5.49 5.92.43.37.81 1.1.81 2.22v3.29c0 .32.22.7.83.58A12 12 0 0 0 12 .5Z" />
  </svg>
);

export default function FooterDemo() {
  const socialLinks = [
    {
      icon: <LinkedinIcon className="w-6 h-6" />,
      href: "https://www.linkedin.com/in/jay-parmar-ai",
      label: "LinkedIn",
    },
    {
      icon: <FileText className="w-6 h-6" />,
      href: "/assets/portfolio/resume/Jay-Parmar-Resume.pdf",
      label: "Resume",
    },
    {
      icon: <GithubIcon className="w-6 h-6" />,
      href: "https://github.com/jay2532006",
      label: "GitHub",
    },
    {
      icon: <BookOpen className="w-6 h-6" />,
      href: "/articles",
      label: "Articles",
    },
    {
      icon: <Mail className="w-6 h-6" />,
      href: "mailto:jaydeepak2532006@gmail.com",
      label: "Mail",
    },
  ];

  const navLinks = [
    { label: "LinkedIn", href: "https://www.linkedin.com/in/jay-parmar-ai" },
    { label: "Resume PDF", href: "/assets/portfolio/resume/Jay-Parmar-Resume.pdf" },
    { label: "GitHub", href: "https://github.com/jay2532006" },
    { label: "Articles (13)", href: "/articles" },
    { label: "Email", href: "mailto:jaydeepak2532006@gmail.com" },
  ];

  return (
    <Footer
      brandName="Jay Parmar"
      brandDescription="AI/ML builder, finance analyst & product leader at IIM Bangalore — turning complex data into decisions that move."
      socialLinks={socialLinks}
      navLinks={navLinks}
      creatorName="Jay Parmar"
      creatorUrl="https://github.com/jay2532006"
      brandIcon={
        <NotepadTextDashed className="w-8 sm:w-10 md:w-14 h-8 sm:h-10 md:h-14 text-background drop-shadow-lg" />
      }
    />
  );
}
```

---

## components/ui/hero-parallax-demo.tsx

**File Path**: `components/ui/hero-parallax-demo.tsx` | **Lines**: 83

```tsx
"use client";
import React from "react";
import { HeroParallax } from "@/components/ui/hero-parallax";

export default function HeroParallaxDemo() {
  return <HeroParallax products={products} />;
}

export const products = [
  {
    title: "ShikshaShakti.AI · ₹2L DST-NIDHI",
    link: "https://drive.google.com/file/d/1KB5ZEOAgdl6hEC4cCXVQ1u9I0FcxkGHx/view",
    thumbnail: "/assets/carousel/carousel-33.webp",
    objectPosition: "center",
  },
  {
    title: "PackEdge · 1st Place IIT Bombay",
    link: "https://drive.google.com/file/d/198jU7tjaPgLchEVKDLTQ7UO2OzyOkM91/view",
    thumbnail: "/assets/carousel/carousel-25.webp",
    objectPosition: "center",
  },
  {
    title: "NextGenAML · TCS Foundation Winner",
    link: "#showcase",
    thumbnail: "/assets/carousel/carousel-35.webp",
    objectPosition: "center",
  },
  {
    title: "TCS CEO K. Krithivasan · National Win",
    link: "#gallery",
    thumbnail: "/assets/carousel/carousel-09.webp",
    objectPosition: "center top",
  },
  {
    title: "FDR-Setu · SIH 2026 AICTE RegTech",
    link: "#showcase",
    thumbnail: "/assets/carousel/carousel-32.webp",
    objectPosition: "center",
  },
  {
    title: "CryptoTrace LEA · MHA PS 26183",
    link: "#showcase",
    thumbnail: "/assets/carousel/carousel-10.webp",
    objectPosition: "center",
  },
  {
    title: "Real-time Fraud Alerts · Sarvam AI",
    link: "#showcase",
    thumbnail: "/assets/carousel/carousel-24.webp",
    objectPosition: "center top",
  },
  {
    title: "IIM Bangalore · Young Leadership Summit",
    link: "#dossier",
    thumbnail: "/assets/carousel/carousel-05.webp",
    objectPosition: "center",
  },
  {
    title: "India AI Impact Summit 2026",
    link: "#gallery",
    thumbnail: "/assets/carousel/carousel-19.webp",
    objectPosition: "center",
  },
  {
    title: "Dainik Bhaskar & Regional Press",
    link: "#gallery",
    thumbnail: "/assets/carousel/carousel-26.webp",
    objectPosition: "center top",
  },
  {
    title: "The Hitavada Feature",
    link: "#gallery",
    thumbnail: "/assets/carousel/carousel-16.webp",
    objectPosition: "center top",
  },
  {
    title: "IBM Quantum System Two Visit",
    link: "#gallery",
    thumbnail: "/assets/carousel/carousel-27.webp",
    objectPosition: "center",
  },
];
```

---

## components/ui/hero-parallax.tsx

**File Path**: `components/ui/hero-parallax.tsx` | **Lines**: 283

```tsx
"use client";
import React from "react";
import {
  motion,
  useScroll,
  useTransform,
  useSpring,
  MotionValue,
} from "framer-motion";
import Image from "next/image";
import Link from "next/link";

export const HeroParallax = ({
  products,
}: {
  products: {
    title: string;
    link: string;
    thumbnail: string;
    objectPosition?: string;
  }[];
}) => {
  const firstRow = products.slice(0, 4);
  const secondRow = products.slice(4, 8);
  const thirdRow = products.slice(8, 12);
  const ref = React.useRef(null);
  const { scrollYProgress } = useScroll({
    target: ref,
    offset: ["start start", "end start"],
  });

  const springConfig = { stiffness: 300, damping: 30, bounce: 100 };

  const translateX = useSpring(
    useTransform(scrollYProgress, [0, 1], [0, 1000]),
    springConfig
  );
  const translateXReverse = useSpring(
    useTransform(scrollYProgress, [0, 1], [0, -1000]),
    springConfig
  );
  const rotateX = useSpring(
    useTransform(scrollYProgress, [0, 0.2], [15, 0]),
    springConfig
  );
  const opacity = useSpring(
    useTransform(scrollYProgress, [0, 0.2], [0.2, 1]),
    springConfig
  );
  const rotateZ = useSpring(
    useTransform(scrollYProgress, [0, 0.2], [20, 0]),
    springConfig
  );
  const translateY = useSpring(
    useTransform(scrollYProgress, [0, 0.2], [-700, 500]),
    springConfig
  );
  return (
    <div
      ref={ref}
      className="h-[150vh] md:h-[300vh] pt-20 md:pt-40 pb-0 overflow-hidden antialiased relative flex flex-col self-auto [perspective:1000px] [transform-style:preserve-3d]"
    >
      <Header />
      <motion.div
        style={{
          rotateX,
          rotateZ,
          translateY,
          opacity,
        }}
        className=""
      >
        <motion.div
          className="flex flex-row-reverse"
          style={{ gap: "72px", marginBottom: "88px" }}
        >
          {[...firstRow, ...firstRow].map((product, i) => (
            <ProductCard
              product={product}
              translate={translateX}
              key={`first-${i}`}
            />
          ))}
        </motion.div>
        <motion.div
          className="flex flex-row"
          style={{ gap: "72px", marginBottom: "88px" }}
        >
          {[...secondRow, ...secondRow].map((product, i) => (
            <ProductCard
              product={product}
              translate={translateXReverse}
              key={`second-${i}`}
            />
          ))}
        </motion.div>
        <motion.div
          className="flex flex-row-reverse"
          style={{ gap: "72px" }}
        >
          {[...thirdRow, ...thirdRow].map((product, i) => (
            <ProductCard
              product={product}
              translate={translateX}
              key={`third-${i}`}
            />
          ))}
        </motion.div>
      </motion.div>
    </div>
  );
};

export const Header = () => {
  return (
    <div
      className="max-w-7xl relative mx-auto py-16 md:py-40 px-6 sm:px-10 md:pl-[12vw] lg:pl-[15vh] w-full left-0 top-0"
      style={{ paddingTop: "18vh", marginBottom: "20px" }}
    >
      {/* Eyebrow / kicker */}
      <div
        className="flex items-center text-[11px] uppercase text-neutral-400 dark:text-neutral-500"
        style={{ gap: "14px", marginBottom: "28px", letterSpacing: "0.32em" }}
      >
        <span
          aria-hidden
          style={{
            display: "inline-block",
            width: "48px",
            height: "1px",
            background:
              "linear-gradient(90deg, transparent, rgba(167,139,250,0.9))",
          }}
        />
        <span className="font-medium">Chapter 02 — Projects &amp; Field Proof</span>
      </div>

      {/* Title */}
      <h1
        className="font-bold dark:text-white"
        style={{
          fontSize: "clamp(2.25rem, 6.4vw, 5.75rem)",
          lineHeight: 0.98,
          letterSpacing: "-0.035em",
          marginBottom: "36px",
        }}
      >
        Turning complex data
        <br />
        <span
          style={{
            backgroundImage:
              "linear-gradient(92deg, #ffffff 0%, #c4b5fd 55%, #a78bfa 100%)",
            WebkitBackgroundClip: "text",
            backgroundClip: "text",
            color: "transparent",
            fontStyle: "italic",
            fontWeight: 500,
          }}
        >
          into outcomes that hold.
        </span>
      </h1>

      {/* Hairline divider */}
      <div
        aria-hidden
        style={{
          width: "84px",
          height: "1px",
          marginBottom: "32px",
          background:
            "linear-gradient(90deg, rgba(167,139,250,0.55), rgba(167,139,250,0))",
        }}
      />

      {/* Body copy */}
      <p
        style={{
          maxWidth: "64ch",
          fontSize: "clamp(1.2rem, 1.5vw, 1.5rem)",
          lineHeight: 1.8,
          letterSpacing: "0.005em",
          color: "#ffffff",
          opacity: 1,
          fontWeight: 400,
        }}
      >
        Across EdTech, supply-chain economics, anti-money-laundering AI,
        regulatory architecture, and disaster telemetry, every build pairs
        rigorous quantitative validation with shipped software — tested in
        classrooms, national hackathons, and enterprise case evaluations.
      </p>

      {/* Meta row */}
      <div
        className="flex items-center text-[11px] uppercase text-neutral-500"
        style={{ gap: "18px", marginTop: "40px", letterSpacing: "0.28em" }}
      >
        <span>2024 — Present</span>
        <span aria-hidden style={{ width: "4px", height: "4px", borderRadius: "9999px", background: "#a78bfa" }} />
        <span>AI/ML · Finance · Product</span>
        <span aria-hidden style={{ width: "4px", height: "4px", borderRadius: "9999px", background: "#a78bfa" }} />
        <span>Scroll to explore</span>
      </div>
    </div>
  );
};

export const ProductCard = ({
  product,
  translate,
}: {
  product: {
    title: string;
    link: string;
    thumbnail: string;
    objectPosition?: string;
  };
  translate: MotionValue<number>;
}) => {
  return (
    <motion.div
      style={{
        x: translate,
        boxShadow:
          "0 30px 80px -30px rgba(0,0,0,0.7), 0 0 0 1px rgba(167,139,250,0.10), inset 0 1px 0 rgba(255,255,255,0.06)",
      }}
      whileHover={{
        y: -14,
        scale: 1.02,
      }}
      whileTap={{
        scale: 0.96,
      }}
      transition={{ type: "spring", stiffness: 350, damping: 25 }}
      key={product.title}
      className="group/product h-80 w-[22rem] relative flex-shrink-0 overflow-hidden rounded-[24px] cursor-pointer"
    >
      <Link
        href={product.link}
        target="_blank"
        rel="noopener noreferrer"
        className="block group-hover/product:shadow-2xl rounded-[28px] overflow-hidden"
      >
        <Image
          src={product.thumbnail}
          height="600"
          width="600"
          sizes="(max-width: 768px) 350px, 600px"
          loading="lazy"
          className="object-cover absolute h-full w-full inset-0 rounded-[28px]"
          style={{ objectPosition: product.objectPosition ?? "center" }}
          alt={product.title}
        />
      </Link>
      {/* Subtle inner sheen — adds a quiet premium gloss without changing animation */}
      <div
        aria-hidden
        className="absolute inset-0 pointer-events-none rounded-[28px]"
        style={{
          background:
            "linear-gradient(180deg, rgba(255,255,255,0.04) 0%, transparent 30%, transparent 70%, rgba(0,0,0,0.35) 100%)",
        }}
      />
      <div className="absolute inset-0 h-full w-full opacity-0 group-hover/product:opacity-80 bg-black pointer-events-none rounded-[28px]"></div>
      <h2
        className="absolute opacity-0 group-hover/product:opacity-100 text-white"
        style={{
          left: "20px",
          bottom: "18px",
          fontSize: "15px",
          fontWeight: 600,
          letterSpacing: "0.04em",
          textShadow: "0 2px 12px rgba(0,0,0,0.6)",
        }}
      >
        {product.title}
      </h2>
    </motion.div>
  );
};
```

---

## components/ui/input.tsx

**File Path**: `components/ui/input.tsx` | **Lines**: 21

```tsx
import * as React from "react"
import { Input as InputPrimitive } from "@base-ui/react/input"

import { cn } from "@/lib/utils"

function Input({ className, type, ...props }: React.ComponentProps<"input">) {
  return (
    <InputPrimitive
      type={type}
      data-slot="input"
      className={cn(
        "h-8 w-full min-w-0 rounded-lg border border-input bg-transparent px-2.5 py-1 text-base transition-colors outline-none file:inline-flex file:h-6 file:border-0 file:bg-transparent file:text-sm file:font-medium file:text-foreground placeholder:text-muted-foreground focus-visible:border-ring focus-visible:ring-3 focus-visible:ring-ring/50 disabled:pointer-events-none disabled:cursor-not-allowed disabled:bg-input/50 disabled:opacity-50 aria-invalid:border-destructive aria-invalid:ring-3 aria-invalid:ring-destructive/20 md:text-sm dark:bg-input/30 dark:disabled:bg-input/80 dark:aria-invalid:border-destructive/50 dark:aria-invalid:ring-destructive/40",
        className
      )}
      {...props}
    />
  )
}

export { Input }
```

---

## components/ui/lamp.tsx

**File Path**: `components/ui/lamp.tsx` | **Lines**: 105

```tsx
"use client";
import React from "react";
import { motion } from "framer-motion";
import { cn } from "@/lib/utils";

export const LampContainer = ({
  children,
  className,
}: {
  children: React.ReactNode;
  className?: string;
}) => {
  return (
    <div
      className={cn(
        "relative flex min-h-screen flex-col items-center justify-center overflow-hidden bg-slate-950 w-full rounded-md z-0",
        className,
      )}
    >
      <div className="relative flex w-full flex-1 scale-y-125 items-center justify-center isolate z-0 ">
        <motion.div
          initial={{ opacity: 0.5, width: "15rem" }}
          whileInView={{ opacity: 1, width: "30rem" }}
          transition={{
            delay: 0.3,
            duration: 0.8,
            ease: "easeInOut",
          }}
          style={{
            backgroundImage: `conic-gradient(var(--conic-position), var(--tw-gradient-stops))`,
          }}
          className="absolute inset-auto right-1/2 h-56 overflow-visible w-[30rem] bg-gradient-conic from-cyan-500 via-transparent to-transparent text-white [--conic-position:from_70deg_at_center_top]"
        >
          <div className="absolute  w-[100%] left-0 bg-slate-950 h-40 bottom-0 z-20 [mask-image:linear-gradient(to_top,white,transparent)]" />
          <div className="absolute  w-40 h-[100%] left-0 bg-slate-950  bottom-0 z-20 [mask-image:linear-gradient(to_right,white,transparent)]" />
        </motion.div>
        <motion.div
          initial={{ opacity: 0.5, width: "15rem" }}
          whileInView={{ opacity: 1, width: "30rem" }}
          transition={{
            delay: 0.3,
            duration: 0.8,
            ease: "easeInOut",
          }}
          style={{
            backgroundImage: `conic-gradient(var(--conic-position), var(--tw-gradient-stops))`,
          }}
          className="absolute inset-auto left-1/2 h-56 w-[30rem] bg-gradient-conic from-transparent via-transparent to-cyan-500 text-white [--conic-position:from_290deg_at_center_top]"
        >
          <div className="absolute  w-40 h-[100%] right-0 bg-slate-950  bottom-0 z-20 [mask-image:linear-gradient(to_left,white,transparent)]" />
          <div className="absolute  w-[100%] right-0 bg-slate-950 h-40 bottom-0 z-20 [mask-image:linear-gradient(to_top,white,transparent)]" />
        </motion.div>
        <div className="absolute top-1/2 h-48 w-full translate-y-12 scale-x-150 bg-slate-950 blur-2xl"></div>
        <div className="absolute top-1/2 z-50 h-48 w-full bg-transparent opacity-10 backdrop-blur-md"></div>
        <div className="absolute inset-auto z-50 h-36 w-[28rem] -translate-y-1/2 rounded-full bg-cyan-500 opacity-50 blur-3xl"></div>
        <motion.div
          initial={{ width: "8rem" }}
          whileInView={{ width: "16rem" }}
          transition={{
            delay: 0.3,
            duration: 0.8,
            ease: "easeInOut",
          }}
          className="absolute inset-auto z-30 h-36 w-64 -translate-y-[6rem] rounded-full bg-cyan-400 blur-2xl"
        ></motion.div>
        <motion.div
          initial={{ width: "15rem" }}
          whileInView={{ width: "30rem" }}
          transition={{
            delay: 0.3,
            duration: 0.8,
            ease: "easeInOut",
          }}
          className="absolute inset-auto z-50 h-0.5 w-[30rem] -translate-y-[7rem] bg-cyan-400 "
        ></motion.div>

        <div className="absolute inset-auto z-40 h-44 w-full -translate-y-[12.5rem] bg-slate-950 "></div>
      </div>

      <div className="relative z-50 flex -translate-y-80 flex-col items-center px-5">
        {children}
      </div>
    </div>
  );
};

export function LampDemo() {
  return (
    <LampContainer>
      <motion.h1
        initial={{ opacity: 0.5, y: 100 }}
        whileInView={{ opacity: 1, y: 0 }}
        transition={{
          delay: 0.3,
          duration: 0.8,
          ease: "easeInOut",
        }}
        className="mt-8 bg-gradient-to-br from-slate-300 to-slate-500 py-4 bg-clip-text text-center text-4xl font-medium tracking-tight text-transparent md:text-7xl"
      >
        Turning Complex Data <br /> Into Decisions That Move.
      </motion.h1>
    </LampContainer>
  );
}
```

---

## components/ui/LightRays.css

**File Path**: `components/ui/LightRays.css` | **Lines**: 9

```css
.light-rays-container {
  width: 100%;
  height: 100%;
  position: relative;
  pointer-events: none;
  z-index: 3;
  overflow: hidden;
}
```

---

## components/ui/LightRays.tsx

**File Path**: `components/ui/LightRays.tsx` | **Lines**: 476

```tsx
"use client";

import { useRef, useEffect, useState } from "react";
import { Renderer, Program, Triangle, Mesh } from "ogl";
import "./LightRays.css";

export type RaysOrigin =
  | "top-center"
  | "top-left"
  | "top-right"
  | "right"
  | "left"
  | "bottom-center"
  | "bottom-right"
  | "bottom-left";

export interface LightRaysProps {
  raysOrigin?: RaysOrigin;
  raysColor?: string;
  raysSpeed?: number;
  lightSpread?: number;
  rayLength?: number;
  pulsating?: boolean;
  fadeDistance?: number;
  saturation?: number;
  followMouse?: boolean;
  mouseInfluence?: number;
  noiseAmount?: number;
  distortion?: number;
  className?: string;
}

const DEFAULT_COLOR = "#ffffff";

const hexToRgb = (hex: string): [number, number, number] => {
  const m = /^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i.exec(hex);
  return m
    ? [
        parseInt(m[1], 16) / 255,
        parseInt(m[2], 16) / 255,
        parseInt(m[3], 16) / 255,
      ]
    : [1, 1, 1];
};

const getAnchorAndDir = (
  origin: RaysOrigin,
  w: number,
  h: number
): { anchor: [number, number]; dir: [number, number] } => {
  const outside = 0.2;
  switch (origin) {
    case "top-left":
      return { anchor: [0, -outside * h], dir: [0, 1] };
    case "top-right":
      return { anchor: [w, -outside * h], dir: [0, 1] };
    case "left":
      return { anchor: [-outside * w, 0.5 * h], dir: [1, 0] };
    case "right":
      return { anchor: [(1 + outside) * w, 0.5 * h], dir: [-1, 0] };
    case "bottom-left":
      return { anchor: [0, (1 + outside) * h], dir: [0, -1] };
    case "bottom-center":
      return { anchor: [0.5 * w, (1 + outside) * h], dir: [0, -1] };
    case "bottom-right":
      return { anchor: [w, (1 + outside) * h], dir: [0, -1] };
    default:
      return { anchor: [0.5 * w, -outside * h], dir: [0, 1] };
  }
};

const LightRays = ({
  raysOrigin = "top-center",
  raysColor = DEFAULT_COLOR,
  raysSpeed = 1,
  lightSpread = 1,
  rayLength = 2,
  pulsating = false,
  fadeDistance = 1.0,
  saturation = 1.0,
  followMouse = true,
  mouseInfluence = 0.1,
  noiseAmount = 0.0,
  distortion = 0.0,
  className = "",
}: LightRaysProps) => {
  const containerRef = useRef<HTMLDivElement>(null);
  const uniformsRef = useRef<Record<string, { value: unknown }> | null>(null);
  const rendererRef = useRef<Renderer | null>(null);
  const mouseRef = useRef({ x: 0.5, y: 0.5 });
  const smoothMouseRef = useRef({ x: 0.5, y: 0.5 });
  const animationIdRef = useRef<number | null>(null);
  const meshRef = useRef<Mesh | null>(null);
  const cleanupFunctionRef = useRef<(() => void) | null>(null);
  const isVisibleRef = useRef(true);
  const observerRef = useRef<IntersectionObserver | null>(null);

  useEffect(() => {
    if (!containerRef.current) return;
    observerRef.current = new IntersectionObserver(
      (entries) => {
        const entry = entries[0];
        isVisibleRef.current = entry.isIntersecting;
      },
      { threshold: 0.05 }
    );
    observerRef.current.observe(containerRef.current);
    return () => {
      if (observerRef.current) {
        observerRef.current.disconnect();
        observerRef.current = null;
      }
    };
  }, []);

  useEffect(() => {
    if (!containerRef.current) return;

    if (cleanupFunctionRef.current) {
      cleanupFunctionRef.current();
      cleanupFunctionRef.current = null;
    }

    const initializeWebGL = async () => {
      if (!containerRef.current) return;
      await new Promise((resolve) => setTimeout(resolve, 10));
      if (!containerRef.current) return;

      // Skip heavy WebGL noise shaders on mobile to keep 120Hz smooth native scroll & avoid GPU throttling
      const isMobile = typeof window !== "undefined" && window.innerWidth < 768;
      if (isMobile) {
        return;
      }

      const targetDpr = 1.5;
      const renderer = new Renderer({
        dpr: Math.min(window.devicePixelRatio || 1, targetDpr),
        alpha: true,
      });
      rendererRef.current = renderer;

      const gl = renderer.gl;
      gl.canvas.style.width = "100%";
      gl.canvas.style.height = "100%";

      while (containerRef.current.firstChild) {
        containerRef.current.removeChild(containerRef.current.firstChild);
      }
      containerRef.current.appendChild(gl.canvas);

      const vert = `
attribute vec2 position;
varying vec2 vUv;
void main() {
  vUv = position * 0.5 + 0.5;
  gl_Position = vec4(position, 0.0, 1.0);
}`;

      const frag = `precision highp float;

uniform float iTime;
uniform vec2  iResolution;

uniform vec2  rayPos;
uniform vec2  rayDir;
uniform vec3  raysColor;
uniform float raysSpeed;
uniform float lightSpread;
uniform float rayLength;
uniform float pulsating;
uniform float fadeDistance;
uniform float saturation;
uniform vec2  mousePos;
uniform float mouseInfluence;
uniform float noiseAmount;
uniform float distortion;

varying vec2 vUv;

float noise(vec2 st) {
  return fract(sin(dot(st.xy, vec2(12.9898,78.233))) * 43758.5453123);
}

float rayStrength(vec2 raySource, vec2 rayRefDirection, vec2 coord,
                  float seedA, float seedB, float speed) {
  vec2 sourceToCoord = coord - raySource;
  vec2 dirNorm = normalize(sourceToCoord);
  float cosAngle = dot(dirNorm, rayRefDirection);

  float distortedAngle = cosAngle + distortion * sin(iTime * 2.0 + length(sourceToCoord) * 0.01) * 0.2;

  float spreadFactor = pow(max(distortedAngle, 0.0), 1.0 / max(lightSpread, 0.001));

  float distance = length(sourceToCoord);
  float maxDistance = iResolution.x * rayLength;
  float lengthFalloff = clamp((maxDistance - distance) / maxDistance, 0.0, 1.0);

  float fadeFalloff = clamp((iResolution.x * fadeDistance - distance) / (iResolution.x * fadeDistance), 0.5, 1.0);
  float pulse = pulsating > 0.5 ? (0.8 + 0.2 * sin(iTime * speed * 3.0)) : 1.0;

  float baseStrength = clamp(
    (0.45 + 0.15 * sin(distortedAngle * seedA + iTime * speed)) +
    (0.3 + 0.2 * cos(-distortedAngle * seedB + iTime * speed)),
    0.0, 1.0
  );

  return baseStrength * lengthFalloff * fadeFalloff * spreadFactor * pulse;
}

void mainImage(out vec4 fragColor, in vec2 fragCoord) {
  vec2 coord = vec2(fragCoord.x, iResolution.y - fragCoord.y);

  vec2 finalRayDir = rayDir;
  if (mouseInfluence > 0.0) {
    vec2 mouseScreenPos = mousePos * iResolution.xy;
    vec2 mouseDirection = normalize(mouseScreenPos - rayPos);
    finalRayDir = normalize(mix(rayDir, mouseDirection, mouseInfluence));
  }

  vec4 rays1 = vec4(1.0) *
               rayStrength(rayPos, finalRayDir, coord, 36.2214, 21.11349,
                           1.5 * raysSpeed);
  vec4 rays2 = vec4(1.0) *
               rayStrength(rayPos, finalRayDir, coord, 22.3991, 18.0234,
                           1.1 * raysSpeed);

  fragColor = rays1 * 0.5 + rays2 * 0.4;

  if (noiseAmount > 0.0) {
    float n = noise(coord * 0.01 + iTime * 0.1);
    fragColor.rgb *= (1.0 - noiseAmount + noiseAmount * n);
  }

  float brightness = 1.0 - (coord.y / iResolution.y);
  fragColor.x *= 0.1 + brightness * 0.8;
  fragColor.y *= 0.3 + brightness * 0.6;
  fragColor.z *= 0.5 + brightness * 0.5;

  if (saturation != 1.0) {
    float gray = dot(fragColor.rgb, vec3(0.299, 0.587, 0.114));
    fragColor.rgb = mix(vec3(gray), fragColor.rgb, saturation);
  }

  fragColor.rgb *= raysColor;
}

void main() {
  vec4 color;
  mainImage(color, gl_FragCoord.xy);
  gl_FragColor  = color;
}`;

      const uniforms = {
        iTime: { value: 0 },
        iResolution: { value: [1, 1] as [number, number] },
        rayPos: { value: [0, 0] as [number, number] },
        rayDir: { value: [0, 1] as [number, number] },
        raysColor: { value: hexToRgb(raysColor) },
        raysSpeed: { value: raysSpeed },
        lightSpread: { value: lightSpread },
        rayLength: { value: rayLength },
        pulsating: { value: pulsating ? 1.0 : 0.0 },
        fadeDistance: { value: fadeDistance },
        saturation: { value: saturation },
        mousePos: { value: [0.5, 0.5] as [number, number] },
        mouseInfluence: { value: mouseInfluence },
        noiseAmount: { value: noiseAmount },
        distortion: { value: distortion },
      };
      uniformsRef.current = uniforms as unknown as Record<
        string,
        { value: unknown }
      >;

      const geometry = new Triangle(gl);
      const program = new Program(gl, {
        vertex: vert,
        fragment: frag,
        uniforms,
      });
      const mesh = new Mesh(gl, { geometry, program });
      meshRef.current = mesh;

      const updatePlacement = () => {
        if (!containerRef.current || !renderer) return;
        renderer.dpr = Math.min(window.devicePixelRatio, 1.5);
        const { clientWidth: wCSS, clientHeight: hCSS } = containerRef.current;
        renderer.setSize(wCSS, hCSS);
        const dpr = renderer.dpr;
        const w = wCSS * dpr;
        const h = hCSS * dpr;
        uniforms.iResolution.value = [w, h];
        const { anchor, dir } = getAnchorAndDir(raysOrigin, w, h);
        uniforms.rayPos.value = anchor;
        uniforms.rayDir.value = dir;
      };

      // Throttle render to ~30 fps. The rays animate slowly (raysSpeed 0.5
      // in this app) so the eye cannot tell 30 fps from 60. Halving the
      // fragment-shader frequency roughly halves the GPU cost.
      const TARGET_FRAME_MS = 1000 / 30;
      let lastDraw = 0;

      const loop = (t: number) => {
        if (!rendererRef.current || !uniformsRef.current || !meshRef.current) {
          return;
        }

        // Skip the entire frame if the tab is hidden or canvas is off-screen — no point burning GPU
        // for an offscreen canvas.
        if (
          !isVisibleRef.current ||
          (typeof document !== "undefined" && document.hidden)
        ) {
          animationIdRef.current = requestAnimationFrame(loop);
          return;
        }

        if (t - lastDraw < TARGET_FRAME_MS) {
          animationIdRef.current = requestAnimationFrame(loop);
          return;
        }
        lastDraw = t;
        uniforms.iTime.value = t * 0.001;

        if (followMouse && mouseInfluence > 0.0) {
          const smoothing = 0.92;
          smoothMouseRef.current.x =
            smoothMouseRef.current.x * smoothing +
            mouseRef.current.x * (1 - smoothing);
          smoothMouseRef.current.y =
            smoothMouseRef.current.y * smoothing +
            mouseRef.current.y * (1 - smoothing);
          uniforms.mousePos.value = [
            smoothMouseRef.current.x,
            smoothMouseRef.current.y,
          ];
        }

        try {
          renderer.render({ scene: mesh });
          animationIdRef.current = requestAnimationFrame(loop);
        } catch (error) {
          console.warn("WebGL rendering error:", error);
          return;
        }
      };

      window.addEventListener("resize", updatePlacement);
      updatePlacement();
      animationIdRef.current = requestAnimationFrame(loop);

      cleanupFunctionRef.current = () => {
        if (animationIdRef.current) {
          cancelAnimationFrame(animationIdRef.current);
          animationIdRef.current = null;
        }
        window.removeEventListener("resize", updatePlacement);
        if (renderer) {
          try {
            const canvas = renderer.gl.canvas;
            const loseContextExt = renderer.gl.getExtension(
              "WEBGL_lose_context"
            );
            if (loseContextExt) loseContextExt.loseContext();
            if (canvas && canvas.parentNode) {
              canvas.parentNode.removeChild(canvas);
            }
          } catch (error) {
            console.warn("Error during WebGL cleanup:", error);
          }
        }
        rendererRef.current = null;
        uniformsRef.current = null;
        meshRef.current = null;
      };
    };

    initializeWebGL();

    return () => {
      if (cleanupFunctionRef.current) {
        cleanupFunctionRef.current();
        cleanupFunctionRef.current = null;
      }
    };
  }, [
    raysOrigin,
    raysColor,
    raysSpeed,
    lightSpread,
    rayLength,
    pulsating,
    fadeDistance,
    saturation,
    followMouse,
    mouseInfluence,
    noiseAmount,
    distortion,
  ]);

  useEffect(() => {
    if (!uniformsRef.current || !containerRef.current || !rendererRef.current)
      return;
    const u = uniformsRef.current as unknown as {
      raysColor: { value: [number, number, number] };
      raysSpeed: { value: number };
      lightSpread: { value: number };
      rayLength: { value: number };
      pulsating: { value: number };
      fadeDistance: { value: number };
      saturation: { value: number };
      mouseInfluence: { value: number };
      noiseAmount: { value: number };
      distortion: { value: number };
      rayPos: { value: [number, number] };
      rayDir: { value: [number, number] };
    };
    const renderer = rendererRef.current;
    u.raysColor.value = hexToRgb(raysColor);
    u.raysSpeed.value = raysSpeed;
    u.lightSpread.value = lightSpread;
    u.rayLength.value = rayLength;
    u.pulsating.value = pulsating ? 1.0 : 0.0;
    u.fadeDistance.value = fadeDistance;
    u.saturation.value = saturation;
    u.mouseInfluence.value = mouseInfluence;
    u.noiseAmount.value = noiseAmount;
    u.distortion.value = distortion;
    const { clientWidth: wCSS, clientHeight: hCSS } = containerRef.current;
    const dpr = renderer.dpr;
    const { anchor, dir } = getAnchorAndDir(
      raysOrigin,
      wCSS * dpr,
      hCSS * dpr
    );
    u.rayPos.value = anchor;
    u.rayDir.value = dir;
  }, [
    raysColor,
    raysSpeed,
    lightSpread,
    raysOrigin,
    rayLength,
    pulsating,
    fadeDistance,
    saturation,
    mouseInfluence,
    noiseAmount,
    distortion,
  ]);

  useEffect(() => {
    const handleMouseMove = (e: MouseEvent) => {
      if (!containerRef.current || !rendererRef.current) return;
      const rect = containerRef.current.getBoundingClientRect();
      const x = (e.clientX - rect.left) / rect.width;
      const y = (e.clientY - rect.top) / rect.height;
      mouseRef.current = { x, y };
    };
    if (followMouse) {
      window.addEventListener("mousemove", handleMouseMove);
      return () => window.removeEventListener("mousemove", handleMouseMove);
    }
  }, [followMouse]);

  return (
    <div
      ref={containerRef}
      className={`light-rays-container ${className}`.trim()}
    />
  );
};

export default LightRays;
```

---

## components/ui/logo-loop.css

**File Path**: `components/ui/logo-loop.css` | **Lines**: 220

```css
.logoloop {
  position: relative;
  --logoloop-gap: 32px;
  --logoloop-logoHeight: 28px;
  --logoloop-fadeColorAuto: #0a0a0a;
}

.logoloop--vertical {
  height: 100%;
  display: inline-block;
}

.logoloop--scale-hover {
  padding-top: calc(var(--logoloop-logoHeight) * 0.1);
  padding-bottom: calc(var(--logoloop-logoHeight) * 0.1);
}

.logoloop__track {
  display: flex;
  width: max-content;
  will-change: transform;
  user-select: none;
  position: relative;
  z-index: 0;
}

.logoloop--vertical .logoloop__track {
  flex-direction: column;
  height: max-content;
  width: 100%;
}

.logoloop__list {
  display: flex;
  align-items: center;
  list-style: none;
  margin: 0;
  padding: 0;
}

.logoloop--vertical .logoloop__list {
  flex-direction: column;
}

.logoloop__item {
  flex: 0 0 auto;
  margin-right: var(--logoloop-gap);
  font-size: var(--logoloop-logoHeight);
  line-height: 1;
}

.logoloop--vertical .logoloop__item {
  margin-right: 0;
  margin-bottom: var(--logoloop-gap);
}

.logoloop__item:last-child {
  margin-right: var(--logoloop-gap);
}

.logoloop--vertical .logoloop__item:last-child {
  margin-right: 0;
  margin-bottom: var(--logoloop-gap);
}

.logoloop__node {
  display: inline-flex;
  align-items: center;
  height: var(--logoloop-logoHeight);
}

.logoloop__node > * {
  height: var(--logoloop-logoHeight);
  width: auto;
  display: block;
}

.logoloop__item img {
  height: var(--logoloop-logoHeight);
  width: auto;
  display: block;
  object-fit: contain;
  image-rendering: -webkit-optimize-contrast;
  -webkit-user-drag: none;
  pointer-events: none;
  transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.logoloop--scale-hover .logoloop__item {
  overflow: visible;
}

.logoloop--scale-hover .logoloop__item:hover img,
.logoloop--scale-hover .logoloop__item:hover .logoloop__node {
  transform: scale(1.2);
  transform-origin: center center;
}

.logoloop--scale-hover .logoloop__node {
  transition: transform 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.logoloop__link {
  display: inline-flex;
  align-items: center;
  text-decoration: none;
  border-radius: 4px;
  transition: opacity 0.2s ease;
}

.logoloop__link:hover {
  opacity: 1;
}

.logoloop__link:focus-visible {
  outline: 2px solid #a78bfa;
  outline-offset: 4px;
}

.logoloop--fade::before,
.logoloop--fade::after {
  content: "";
  position: absolute;
  top: 0;
  bottom: 0;
  width: clamp(24px, 12%, 80px);
  pointer-events: none;
  z-index: 10;
}

.logoloop--fade::before {
  left: 0;
  background: linear-gradient(
    to right,
    var(--logoloop-fadeColor, var(--logoloop-fadeColorAuto)) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.logoloop--fade::after {
  right: 0;
  background: linear-gradient(
    to left,
    var(--logoloop-fadeColor, var(--logoloop-fadeColorAuto)) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.logoloop--vertical.logoloop--fade::before,
.logoloop--vertical.logoloop--fade::after {
  left: 0;
  right: 0;
  width: 100%;
  height: clamp(24px, 8%, 120px);
}

.logoloop--vertical.logoloop--fade::before {
  top: 0;
  bottom: auto;
  background: linear-gradient(
    to bottom,
    var(--logoloop-fadeColor, var(--logoloop-fadeColorAuto)) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.logoloop--vertical.logoloop--fade::after {
  bottom: 0;
  top: auto;
  background: linear-gradient(
    to top,
    var(--logoloop-fadeColor, var(--logoloop-fadeColorAuto)) 0%,
    rgba(0, 0, 0, 0) 100%
  );
}

.logoloop__track--animate {
  animation-name: marquee-horizontal;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
  animation-duration: var(--marquee-duration, 15s);
}

.logoloop--vertical .logoloop__track--animate {
  animation-name: marquee-vertical;
}

.logoloop__track--paused {
  animation-play-state: paused !important;
}

@keyframes marquee-horizontal {
  0% {
    transform: translate3d(0, 0, 0);
  }
  100% {
    transform: var(--marquee-translate);
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translate3d(0, 0, 0);
  }
  100% {
    transform: var(--marquee-translate);
  }
}

@media (prefers-reduced-motion: reduce) {
  .logoloop__track {
    transform: translate3d(0, 0, 0) !important;
    animation: none !important;
  }
  .logoloop__item img,
  .logoloop__node {
    transition: none !important;
  }
}
```

---

## components/ui/logo-loop.tsx

**File Path**: `components/ui/logo-loop.tsx` | **Lines**: 354

```tsx
"use client";
import {
  useCallback,
  useEffect,
  useMemo,
  useRef,
  useState,
  memo,
  type CSSProperties,
  type ReactNode,
} from "react";
import "./logo-loop.css";

const ANIMATION_CONFIG = {
  SMOOTH_TAU: 0.25,
  MIN_COPIES: 2,
  COPY_HEADROOM: 2,
} as const;

const toCssLength = (value: number | string | undefined): string | undefined =>
  typeof value === "number" ? `${value}px` : value ?? undefined;

export type LogoItem =
  | {
      node: ReactNode;
      title?: string;
      href?: string;
      ariaLabel?: string;
    }
  | {
      src: string;
      alt?: string;
      title?: string;
      href?: string;
      srcSet?: string;
      sizes?: string;
      width?: number;
      height?: number;
    };

export interface LogoLoopProps {
  logos: LogoItem[];
  speed?: number;
  direction?: "left" | "right" | "up" | "down";
  width?: number | string;
  logoHeight?: number;
  gap?: number;
  pauseOnHover?: boolean;
  hoverSpeed?: number;
  fadeOut?: boolean;
  fadeOutColor?: string;
  scaleOnHover?: boolean;
  renderItem?: (item: LogoItem, key: React.Key) => ReactNode;
  ariaLabel?: string;
  className?: string;
  style?: CSSProperties;
}

const useResizeObserver = (
  callback: () => void,
  elements: React.RefObject<HTMLElement | null>[],
  dependencies: unknown[]
) => {
  useEffect(() => {
    if (typeof window === "undefined") return;
    if (!window.ResizeObserver) {
      const handleResize = () => callback();
      window.addEventListener("resize", handleResize);
      callback();
      return () => window.removeEventListener("resize", handleResize);
    }
    const observers = elements.map((ref) => {
      if (!ref.current) return null;
      const observer = new ResizeObserver(callback);
      observer.observe(ref.current);
      return observer;
    });
    callback();
    return () => observers.forEach((observer) => observer?.disconnect());
    // eslint-disable-next-line react-hooks/exhaustive-deps
  }, dependencies);
};

const useImageLoader = (
  seqRef: React.RefObject<HTMLElement | null>,
  onLoad: () => void,
  dependencies: unknown[]
) => {
  useEffect(() => {
    const images = seqRef.current?.querySelectorAll("img") ?? [];
    if (images.length === 0) {
      onLoad();
      return;
    }
    let remainingImages = images.length;
    const handleImageLoad = () => {
      remainingImages -= 1;
      if (remainingImages === 0) onLoad();
    };
    images.forEach((img) => {
      if ((img as HTMLImageElement).complete) {
        handleImageLoad();
      } else {
        img.addEventListener("load", handleImageLoad, { once: true });
        img.addEventListener("error", handleImageLoad, { once: true });
      }
    });
    return () => {
      images.forEach((img) => {
        img.removeEventListener("load", handleImageLoad);
        img.removeEventListener("error", handleImageLoad);
      });
    };
    // eslint-disable-next-line react-hooks/exhaustive-deps
  }, dependencies);
};

export const LogoLoop = memo(function LogoLoop({
  logos,
  speed = 120,
  direction = "left",
  width = "100%",
  logoHeight = 28,
  gap = 32,
  pauseOnHover,
  hoverSpeed,
  fadeOut = false,
  fadeOutColor,
  scaleOnHover = false,
  renderItem,
  ariaLabel = "Partner logos",
  className,
  style,
}: LogoLoopProps) {
  const containerRef = useRef<HTMLDivElement | null>(null);
  const trackRef = useRef<HTMLDivElement | null>(null);
  const seqRef = useRef<HTMLUListElement | null>(null);

  const [seqWidth, setSeqWidth] = useState(0);
  const [seqHeight, setSeqHeight] = useState(0);
  const [copyCount, setCopyCount] = useState<number>(ANIMATION_CONFIG.MIN_COPIES);
  const [isHovered, setIsHovered] = useState(false);

  const effectiveHoverSpeed = useMemo(() => {
    if (hoverSpeed !== undefined) return hoverSpeed;
    if (pauseOnHover === true) return 0;
    if (pauseOnHover === false) return undefined;
    return 0;
  }, [hoverSpeed, pauseOnHover]);

  const isVertical = direction === "up" || direction === "down";

  const updateDimensions = useCallback(() => {
    const containerWidth = containerRef.current?.clientWidth ?? 0;
    const seqRect = seqRef.current?.getBoundingClientRect();
    const sequenceWidth = seqRect?.width ?? 0;
    const sequenceHeight = seqRect?.height ?? 0;
    if (isVertical) {
      const parentHeight = containerRef.current?.parentElement?.clientHeight ?? 0;
      if (containerRef.current && parentHeight > 0) {
        const targetHeight = Math.ceil(parentHeight);
        if (containerRef.current.style.height !== `${targetHeight}px`)
          containerRef.current.style.height = `${targetHeight}px`;
      }
      if (sequenceHeight > 0) {
        setSeqHeight(Math.ceil(sequenceHeight));
        const viewport =
          containerRef.current?.clientHeight ?? parentHeight ?? sequenceHeight;
        const copiesNeeded =
          Math.ceil(viewport / sequenceHeight) + ANIMATION_CONFIG.COPY_HEADROOM;
        setCopyCount(Math.max(ANIMATION_CONFIG.MIN_COPIES, copiesNeeded));
      }
    } else if (sequenceWidth > 0) {
      setSeqWidth(Math.ceil(sequenceWidth));
      const copiesNeeded =
        Math.ceil(containerWidth / sequenceWidth) + ANIMATION_CONFIG.COPY_HEADROOM;
      setCopyCount(Math.max(ANIMATION_CONFIG.MIN_COPIES, copiesNeeded));
    }
  }, [isVertical]);

  useResizeObserver(updateDimensions, [containerRef, seqRef], [
    logos,
    gap,
    logoHeight,
    isVertical,
  ]);
  useImageLoader(seqRef, updateDimensions, [logos, gap, logoHeight, isVertical]);

  const cssVariables = useMemo<CSSProperties>(
    () =>
      ({
        "--logoloop-gap": `${gap}px`,
        "--logoloop-logoHeight": `${logoHeight}px`,
        ...(fadeOutColor && { "--logoloop-fadeColor": fadeOutColor }),
      }) as CSSProperties,
    [gap, logoHeight, fadeOutColor]
  );

  const rootClassName = useMemo(
    () =>
      [
        "logoloop",
        isVertical ? "logoloop--vertical" : "logoloop--horizontal",
        fadeOut && "logoloop--fade",
        scaleOnHover && "logoloop--scale-hover",
        className,
      ]
        .filter(Boolean)
        .join(" "),
    [isVertical, fadeOut, scaleOnHover, className]
  );

  const handleMouseEnter = useCallback(() => {
    if (effectiveHoverSpeed !== undefined) setIsHovered(true);
  }, [effectiveHoverSpeed]);
  const handleMouseLeave = useCallback(() => {
    if (effectiveHoverSpeed !== undefined) setIsHovered(false);
  }, [effectiveHoverSpeed]);

  const trackStyle = useMemo<CSSProperties>(
    () => ({
      "--marquee-translate": isVertical
        ? `translate3d(0, ${direction === "up" ? -seqHeight : seqHeight}px, 0)`
        : `translate3d(${direction === "left" ? -seqWidth : seqWidth}px, 0, 0)`,
      "--marquee-duration": `${
        speed !== 0 && (isVertical ? seqHeight : seqWidth) > 0
          ? (isVertical ? seqHeight : seqWidth) / Math.abs(speed)
          : 0
      }s`,
    }) as CSSProperties,
    [seqWidth, seqHeight, isVertical, direction, speed]
  );

  const trackClassName = useMemo(
    () =>
      [
        "logoloop__track",
        (isVertical ? seqHeight : seqWidth) > 0 && "logoloop__track--animate",
        isHovered && "logoloop__track--paused",
      ]
        .filter(Boolean)
        .join(" "),
    [isVertical, seqWidth, seqHeight, isHovered]
  );

  const renderLogoItem = useCallback(
    (item: LogoItem, key: React.Key) => {
      if (renderItem) {
        return (
          <li className="logoloop__item" key={key} role="listitem">
            {renderItem(item, key)}
          </li>
        );
      }
      const isNodeItem = "node" in item;
      const content = isNodeItem ? (
        <span className="logoloop__node" aria-hidden={!!item.href && !item.ariaLabel}>
          {item.node}
        </span>
      ) : (
        <img
          src={item.src}
          srcSet={item.srcSet}
          sizes={item.sizes}
          width={item.width}
          height={item.height}
          alt={item.alt ?? ""}
          title={item.title}
          loading="lazy"
          decoding="async"
          draggable={false}
        />
      );
      const itemAriaLabel = isNodeItem
        ? item.ariaLabel ?? item.title
        : item.alt ?? item.title;
      const itemContent = item.href ? (
        <a
          className="logoloop__link"
          href={item.href}
          aria-label={itemAriaLabel || "logo link"}
          target="_blank"
          rel="noreferrer noopener"
        >
          {content}
        </a>
      ) : (
        content
      );
      return (
        <li className="logoloop__item" key={key} role="listitem">
          {itemContent}
        </li>
      );
    },
    [renderItem]
  );

  const logoLists = useMemo(
    () =>
      Array.from({ length: copyCount }, (_, copyIndex) => (
        <ul
          className="logoloop__list"
          key={`copy-${copyIndex}`}
          role="list"
          aria-hidden={copyIndex > 0}
          ref={copyIndex === 0 ? seqRef : undefined}
        >
          {logos.map((item, itemIndex) =>
            renderLogoItem(item, `${copyIndex}-${itemIndex}`)
          )}
        </ul>
      )),
    [copyCount, logos, renderLogoItem]
  );

  const containerStyle = useMemo<CSSProperties>(
    () => ({
      width: isVertical
        ? toCssLength(width) === "100%"
          ? undefined
          : toCssLength(width)
        : toCssLength(width) ?? "100%",
      ...cssVariables,
      ...style,
    }),
    [width, cssVariables, style, isVertical]
  );

  return (
    <div
      ref={containerRef}
      className={rootClassName}
      style={containerStyle}
      role="region"
      aria-label={ariaLabel}
    >
      <div
        className={trackClassName}
        style={trackStyle}
        ref={trackRef}
        onMouseEnter={handleMouseEnter}
        onMouseLeave={handleMouseLeave}
      >
        {logoLists}
      </div>
    </div>
  );
});

LogoLoop.displayName = "LogoLoop";

export default LogoLoop;
```

---

## components/ui/mac-os-menu-bar.tsx

**File Path**: `components/ui/mac-os-menu-bar.tsx` | **Lines**: 367

```tsx
"use client";

import React, { useState, useEffect, useRef, useCallback } from "react";

interface MenuItemOption {
  label: string;
  action?: string;
  shortcut?: string;
  type?: "item" | "separator";
  hasSubmenu?: boolean;
}

interface MenuConfig {
  label: string;
  items: MenuItemOption[];
}

interface MacOSMenuBarProps {
  appName?: string;
  menus?: MenuConfig[];
  onMenuAction?: (action: string) => void;
  className?: string;
}

const DEFAULT_MENUS: MenuConfig[] = [
  {
    label: "File",
    items: [
      { label: "New Tab", action: "new-tab", shortcut: "⌘T" },
      { label: "New Window", action: "new-window", shortcut: "⌘N" },
      { label: "New Private Window", action: "new-private", shortcut: "⇧⌘N" },
      { type: "separator", label: "" },
      { label: "Open File...", action: "open-file", shortcut: "⌘O" },
      { label: "Open Location...", action: "open-location", shortcut: "⌘L" },
      { type: "separator", label: "" },
      { label: "Close Window", action: "close-window", shortcut: "⇧⌘W" },
      { label: "Close Tab", action: "close-tab", shortcut: "⌘W" },
      { label: "Save Page As...", action: "save-page", shortcut: "⌘S" },
      { type: "separator", label: "" },
      { label: "Share", action: "share", hasSubmenu: true },
      { type: "separator", label: "" },
      { label: "Print...", action: "print", shortcut: "⌘P" },
    ],
  },
  {
    label: "Edit",
    items: [
      { label: "Undo", action: "undo", shortcut: "⌘Z" },
      { label: "Redo", action: "redo", shortcut: "⇧⌘Z" },
      { type: "separator", label: "" },
      { label: "Cut", action: "cut", shortcut: "⌘X" },
      { label: "Copy", action: "copy", shortcut: "⌘C" },
      { label: "Paste", action: "paste", shortcut: "⌘V" },
      { label: "Select All", action: "select-all", shortcut: "⌘A" },
      { type: "separator", label: "" },
      { label: "Find", action: "find", shortcut: "⌘F" },
      { label: "Find Next", action: "find-next", shortcut: "⌘G" },
      { label: "Find Previous", action: "find-prev", shortcut: "⇧⌘G" },
      { type: "separator", label: "" },
      { label: "Emoji & Symbols", action: "emoji", shortcut: "⌃⌘␣" },
    ],
  },
  {
    label: "View",
    items: [
      { label: "as Icons", action: "view-icons", shortcut: "⌘1" },
      { label: "as List", action: "view-list", shortcut: "⌘2" },
      { label: "as Columns", action: "view-columns", shortcut: "⌘3" },
      { label: "as Gallery", action: "view-gallery", shortcut: "⌘4" },
      { type: "separator", label: "" },
      { label: "Use Stacks", action: "use-stacks", shortcut: "⌃⌘0" },
      { label: "Sort By", action: "sort-by", hasSubmenu: true },
      { type: "separator", label: "" },
      { label: "Hide Sidebar", action: "hide-sidebar", shortcut: "⌥⌘S" },
      { label: "Show Preview", action: "show-preview", shortcut: "⇧⌘P" },
      { type: "separator", label: "" },
      { label: "Enter Full Screen", action: "fullscreen", shortcut: "⌃⌘F" },
    ],
  },
  {
    label: "Window",
    items: [
      { label: "Minimize", action: "minimize", shortcut: "⌘M" },
      { label: "Zoom", action: "zoom" },
      { type: "separator", label: "" },
      { label: "Cycle Through Windows", action: "cycle-windows", shortcut: "⌘`" },
      { type: "separator", label: "" },
      { label: "Bring All to Front", action: "bring-to-front" },
    ],
  },
  {
    label: "Help",
    items: [
      { label: "Search", action: "search-help" },
      { type: "separator", label: "" },
      { label: "App Help", action: "app-help" },
      { label: "Keyboard Shortcuts", action: "shortcuts" },
      { type: "separator", label: "" },
      { label: "Contact Support", action: "contact-support" },
    ],
  },
];

const APPLE_MENU_ITEMS: MenuItemOption[] = [
  { label: "About This Mac", action: "about" },
  { type: "separator", label: "" },
  { label: "System Preferences...", action: "preferences" },
  { label: "App Store...", action: "app-store" },
  { type: "separator", label: "" },
  { label: "Recent Items", action: "recent", hasSubmenu: true },
  { type: "separator", label: "" },
  { label: "Force Quit Applications...", action: "force-quit", shortcut: "⌥⌘⎋" },
  { type: "separator", label: "" },
  { label: "Sleep", action: "sleep" },
  { label: "Restart...", action: "restart" },
  { label: "Shut Down...", action: "shutdown" },
  { type: "separator", label: "" },
  { label: "Lock Screen", action: "lock", shortcut: "⌃⌘Q" },
  { label: "Log Out...", action: "logout", shortcut: "⇧⌘Q" },
];

interface MenuDropdownProps {
  isOpen: boolean;
  onClose: () => void;
  items: MenuItemOption[];
  position: { x: number; y: number };
  onAction?: (action: string) => void;
}

const MenuDropdown: React.FC<MenuDropdownProps> = ({
  isOpen,
  onClose,
  items,
  position,
  onAction,
}) => {
  const dropdownRef = useRef<HTMLDivElement>(null);

  useEffect(() => {
    const handleClickOutside = (event: MouseEvent) => {
      const target = event.target as Node;
      if (dropdownRef.current && dropdownRef.current.contains(target)) return;
      // Ignore clicks on any menu-bar trigger so they can toggle the dropdown
      if (
        target instanceof Element &&
        target.closest("[data-mac-menu-trigger]")
      ) {
        return;
      }
      onClose();
    };
    if (isOpen) document.addEventListener("mousedown", handleClickOutside);
    return () => document.removeEventListener("mousedown", handleClickOutside);
  }, [isOpen, onClose]);

  if (!isOpen) return null;

  return (
    <div
      ref={dropdownRef}
      className="absolute backdrop-blur-md z-[60] mac-menu-fade-in"
      style={{
        left: `${position.x}px`,
        top: `${position.y}px`,
        background: "rgba(40, 40, 40, 0.85)",
        border: "1px solid rgba(255, 255, 255, 0.18)",
        borderRadius: "10px",
        boxShadow:
          "0 8px 32px rgba(0,0,0,0.45), 0 2px 8px rgba(0,0,0,0.3), inset 0 1px 0 rgba(255,255,255,0.12)",
        minWidth: "280px",
        paddingTop: "0.5rem",
        paddingBottom: "0.5rem",
      }}
    >
      <div className="flex flex-col" style={{ gap: "1px" }}>
        {items.map((item, index) => {
          if (item.type === "separator") {
            return (
              <div
                key={index}
                className="bg-white/15"
                style={{ height: "1px", marginTop: "0.4rem", marginBottom: "0.4rem", marginLeft: "0.75rem", marginRight: "0.75rem" }}
              />
            );
          }
          return (
            <div
              key={index}
              className="text-white text-[13px] cursor-pointer hover:bg-white/10 transition-colors duration-100 flex justify-between items-center whitespace-nowrap"
              style={{
                paddingLeft: "1.25rem",
                paddingRight: "1.25rem",
                paddingTop: "0.4rem",
                paddingBottom: "0.4rem",
                marginLeft: "0.4rem",
                marginRight: "0.4rem",
                borderRadius: "5px",
                gap: "2.5rem",
              }}
              onClick={() => {
                if (item.action) onAction?.(item.action);
                onClose();
              }}
            >
              <span className="flex items-center" style={{ gap: "0.5rem" }}>
                {item.label}
                {item.hasSubmenu && (
                  <span className="text-[10px] opacity-70">▶</span>
                )}
              </span>
              {item.shortcut && (
                <span className="text-[11px] text-white/55 font-mono tabular-nums">
                  {item.shortcut}
                </span>
              )}
            </div>
          );
        })}
      </div>
    </div>
  );
};

const MacOSMenuBar: React.FC<MacOSMenuBarProps> = ({
  appName = "Finder",
  menus = DEFAULT_MENUS,
  onMenuAction,
  className = "",
}) => {
  const [currentTime, setCurrentTime] = useState("");
  const [activeMenu, setActiveMenu] = useState<string | null>(null);
  const [dropdownPosition, setDropdownPosition] = useState({ x: 0, y: 0 });

  const appleLogoRef = useRef<HTMLDivElement>(null);
  const menuRefs = useRef<{ [key: string]: HTMLSpanElement | null }>({});

  useEffect(() => {
    const updateTime = () => {
      const now = new Date();
      setCurrentTime(
        now.toLocaleTimeString("en-US", { hour: "numeric", minute: "2-digit", hour12: true })
      );
    };
    updateTime();
    const interval = setInterval(updateTime, 60000);
    return () => clearInterval(interval);
  }, []);

  const openMenuAt = (el: HTMLElement | null, key: string) => {
    if (!el) return;
    const rect = el.getBoundingClientRect();
    const parentRect = el.offsetParent?.getBoundingClientRect() || { left: 0, top: 0 };
    setDropdownPosition({ x: rect.left - parentRect.left, y: 34 });
    setActiveMenu(key);
  };

  const handleAppleMenuClick = useCallback(() => {
    if (activeMenu === "apple") setActiveMenu(null);
    else openMenuAt(appleLogoRef.current, "apple");
  }, [activeMenu]);

  const handleMenuItemClick = useCallback(
    (menuLabel: string) => {
      if (activeMenu === menuLabel) setActiveMenu(null);
      else openMenuAt(menuRefs.current[menuLabel], menuLabel);
    },
    [activeMenu]
  );

  const closeDropdown = useCallback(() => setActiveMenu(null), []);
  const handleMenuAction = useCallback(
    (action: string) => onMenuAction?.(action),
    [onMenuAction]
  );

  return (
    <div style={{ position: "relative" }} className="w-full">
      <div
        className={`backdrop-blur-md ${className}`}
        style={{
          height: "36px",
          background: "rgba(40, 40, 40, 0.65)",
          borderBottom: "1px solid rgba(255, 255, 255, 0.08)",
          boxShadow: "inset 0 1px 0 rgba(255, 255, 255, 0.10)",
        }}
      >
        <div
          className="flex justify-between items-center h-full"
          style={{ paddingLeft: "1.75rem", paddingRight: "1.75rem", gap: "1.5rem" }}
        >
          <div className="flex items-center min-w-0" style={{ gap: "1.25rem" }}>
            <div
              ref={appleLogoRef}
              onClick={handleAppleMenuClick}
              data-mac-menu-trigger
              className="cursor-pointer hover:opacity-80 transition-opacity duration-150 shrink-0"
            >
              <svg width="14" height="17" viewBox="0 0 110 140" fill="white" style={{ display: "block" }}>
                <path d="M0 0 C5.58 2.1 9.6 0.89 14.97 -1.09 C24.52 -4.44 34.11 -4.55 43.36 -0.23 C48.12 2.41 50.87 5.09 53.41 9.91 C52.36 10.69 51.31 11.47 50.22 12.28 C44.71 17.03 41.57 23.29 40.47 30.47 C40.03 38.30 41.87 44.11 46.82 50.18 C49.70 53.31 52.90 55.56 56.41 57.91 C53.63 69.37 47.17 82.52 37.16 89.41 C32.58 91.91 28.55 92.54 23.41 91.91 C21.37 91.29 19.35 90.62 17.35 89.91 C8.57 86.84 3.24 88.21 -5.43 91.00 C-10.61 92.48 -14.47 92.64 -19.65 90.84 C-33.69 81.59 -41.79 64.33 -45.19 48.34 C-47.47 34.48 -46.65 19.76 -38.46 8.03 C-28.23 -4.15 -14.18 -5.71 0 0 Z" transform="translate(45.59,33.09)" />
                <path d="M0 0 C0.57 7.73 -0.97 14.11 -5.80 20.31 C-10.93 25.74 -15.29 28.82 -22.94 29.19 C-23.95 29.13 -24.96 29.06 -26 29 C-26.59 20.82 -24.35 14.77 -19.38 8.25 C-14.46 2.90 -7.38 -0.97 0 0 Z" transform="translate(76,0)" />
              </svg>
            </div>
            <span className="text-white text-[13px] font-semibold whitespace-nowrap shrink-0">
              {appName}
            </span>
            <div className="flex items-center" style={{ gap: "1.5rem" }}>
              {menus.map((menu) => (
                <span
                  key={menu.label}
                  ref={(el) => {
                    menuRefs.current[menu.label] = el;
                  }}
                  data-mac-menu-trigger
                  className="text-white text-[13px] cursor-pointer hover:opacity-80 transition-opacity duration-150 select-none whitespace-nowrap"
                  onClick={() => handleMenuItemClick(menu.label)}
                >
                  {menu.label}
                </span>
              ))}
            </div>
          </div>

          <div className="flex items-center shrink-0" style={{ gap: "1.25rem" }}>
            <svg width="24" height="12" viewBox="0 0 24 12" fill="none" className="opacity-90">
              <rect x="0.5" y="1.5" width="19" height="9" rx="2" stroke="white" strokeOpacity="0.85" />
              <rect x="2" y="3" width="16" height="6" rx="1" fill="white" />
              <rect x="20.5" y="4.5" width="1.5" height="3" rx="0.5" fill="white" fillOpacity="0.85" />
            </svg>
            <svg width="16" height="12" viewBox="0 0 16 12" fill="none" className="opacity-90">
              <path d="M8 11.2a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z" fill="white" />
              <path d="M3.5 7.2a6.4 6.4 0 0 1 9 0" stroke="white" strokeWidth="1.3" strokeLinecap="round" />
              <path d="M1 4.4a9.9 9.9 0 0 1 14 0" stroke="white" strokeWidth="1.3" strokeLinecap="round" />
            </svg>
            <svg width="14" height="14" viewBox="0 0 16 16" fill="none" className="opacity-90">
              <path d="M2 13s.5-3 3-3h6c2.5 0 3 3 3 3" stroke="white" strokeWidth="1.3" strokeLinecap="round" />
              <circle cx="8" cy="5" r="2.6" stroke="white" strokeWidth="1.3" />
            </svg>
            <span className="text-white text-[13px] font-medium select-none cursor-pointer hover:opacity-80 transition-opacity duration-150 whitespace-nowrap tabular-nums">
              {currentTime}
            </span>
          </div>
        </div>
      </div>

      <MenuDropdown
        isOpen={activeMenu === "apple"}
        onClose={closeDropdown}
        items={APPLE_MENU_ITEMS}
        position={dropdownPosition}
        onAction={handleMenuAction}
      />
      {menus.map((menu) => (
        <MenuDropdown
          key={menu.label}
          isOpen={activeMenu === menu.label}
          onClose={closeDropdown}
          items={menu.items}
          position={dropdownPosition}
          onAction={handleMenuAction}
        />
      ))}
    </div>
  );
};

export default MacOSMenuBar;
```

---

## components/ui/modem-animated-footer.tsx

**File Path**: `components/ui/modem-animated-footer.tsx` | **Lines**: 222

```tsx
"use client";
import React from "react";
import Link from "next/link";
import { NotepadTextDashed } from "lucide-react";
import { cn } from "@/lib/utils";

const isExternalUrl = (href: string) => /^https?:\/\//i.test(href);
const isProtocolLink = (href: string) =>
  /^(mailto:|tel:|sms:)/i.test(href);

interface FooterLink {
  label: string;
  href: string;
}

interface SocialLink {
  icon: React.ReactNode;
  href: string;
  label: string;
}

interface FooterProps {
  brandName?: string;
  brandDescription?: string;
  socialLinks?: SocialLink[];
  navLinks?: FooterLink[];
  creatorName?: string;
  creatorUrl?: string;
  brandIcon?: React.ReactNode;
  className?: string;
}

export const Footer = ({
  brandName = "YourBrand",
  brandDescription = "Your description here",
  socialLinks = [],
  navLinks = [],
  creatorName,
  creatorUrl,
  brandIcon,
  className,
}: FooterProps) => {
  return (
    <section className={cn("relative w-full min-h-screen flex flex-col mt-0 overflow-hidden", className)}>
      <footer className="border-t bg-background relative flex-1 flex flex-col">
        <div className="max-w-7xl w-full flex flex-col mx-auto min-h-screen relative px-6 md:px-12" style={{ paddingTop: "10vh", paddingBottom: "8vh", paddingLeft: "18vh"}}>
          <div className="flex-1 flex flex-col items-center justify-start w-full">
            <div className="w-full flex flex-col items-center">
              <div className="flex flex-col items-center gap-8">
                <span className="text-foreground text-4xl md:text-5xl font-bold tracking-tight">
                  {brandName}
                </span>
                <p
                  className="text-muted-foreground font-medium text-center text-base leading-loose"
                  style={{ whiteSpace: "nowrap", marginBottom: "32px" }}
                >
                  {brandDescription}
                </p>
              </div>

              {socialLinks.length > 0 && socialLinks.length === navLinks.length ? (
                <div
                  className="mt-14 grid"
                  style={{
                    gridTemplateColumns: `repeat(${socialLinks.length}, minmax(0, 1fr))`,
                    columnGap: "56px",
                    rowGap: "16px",
                    justifyItems: "center",
                  }}
                >
                  {socialLinks.map((link, index) => {
                    const proto = isProtocolLink(link.href);
                    const external = isExternalUrl(link.href);
                    return (
                      <a
                        key={`s-${index}`}
                        href={link.href}
                        className="text-muted-foreground hover:text-foreground transition-colors flex justify-center"
                        target={proto ? undefined : external ? "_blank" : undefined}
                        rel={external ? "noopener noreferrer" : undefined}
                        style={{ gridRow: 1, gridColumn: index + 1 }}
                      >
                        <div className="w-6 h-6 hover:scale-110 duration-300 flex items-center justify-center">
                          {link.icon}
                        </div>
                        <span className="sr-only">{link.label}</span>
                      </a>
                    );
                  })}
                  {navLinks.map((link, index) => {
                    const proto = isProtocolLink(link.href);
                    const external = isExternalUrl(link.href);
                    if (proto || external) {
                      return (
                        <a
                          key={`n-${index}`}
                          className="hover:text-foreground duration-300 hover:font-semibold text-base font-medium text-muted-foreground text-center"
                          href={link.href}
                          target={proto ? undefined : "_blank"}
                          rel={external ? "noopener noreferrer" : undefined}
                          style={{ gridRow: 2, gridColumn: index + 1 }}
                        >
                          {link.label}
                        </a>
                      );
                    }
                    return (
                      <Link
                        key={`n-${index}`}
                        className="hover:text-foreground duration-300 hover:font-semibold text-base font-medium text-muted-foreground text-center"
                        href={link.href}
                        style={{ gridRow: 2, gridColumn: index + 1 }}
                      >
                        {link.label}
                      </Link>
                    );
                  })}
                </div>
              ) : (
                <>
                  {socialLinks.length > 0 && (
                    <div className="flex mt-14 gap-8">
                      {socialLinks.map((link, index) => {
                        const proto = isProtocolLink(link.href);
                        const external = isExternalUrl(link.href);
                        return (
                          <a
                            key={index}
                            href={link.href}
                            className="text-muted-foreground hover:text-foreground transition-colors"
                            target={proto ? undefined : external ? "_blank" : undefined}
                            rel={external ? "noopener noreferrer" : undefined}
                          >
                            <div className="w-6 h-6 hover:scale-110 duration-300">
                              {link.icon}
                            </div>
                            <span className="sr-only">{link.label}</span>
                          </a>
                        );
                      })}
                    </div>
                  )}

                  {navLinks.length > 0 && (
                    <div className="flex flex-wrap justify-center gap-10 mt-14 text-base font-medium text-muted-foreground max-w-full px-4">
                      {navLinks.map((link, index) => {
                        const proto = isProtocolLink(link.href);
                        const external = isExternalUrl(link.href);
                        if (proto || external) {
                          return (
                            <a
                              key={index}
                              className="hover:text-foreground duration-300 hover:font-semibold"
                              href={link.href}
                              target={proto ? undefined : "_blank"}
                              rel={external ? "noopener noreferrer" : undefined}
                            >
                              {link.label}
                            </a>
                          );
                        }
                        return (
                          <Link
                            key={index}
                            className="hover:text-foreground duration-300 hover:font-semibold"
                            href={link.href}
                          >
                            {link.label}
                          </Link>
                        );
                      })}
                    </div>
                  )}
                </>
              )}
            </div>
          </div>

          <div className="flex flex-col gap-2 md:gap-1 items-center justify-center md:flex-row md:items-center md:justify-between px-4 md:px-0">
            <p className="text-base text-muted-foreground text-center md:text-left">
              ©{new Date().getFullYear()} {brandName}. All rights reserved.
            </p>
            {creatorName && creatorUrl && (
              <nav className="flex gap-4">
                <Link
                  href={creatorUrl}
                  target="_blank"
                  className="text-base text-muted-foreground hover:text-foreground transition-colors duration-300 hover:font-medium"
                >
                  Crafted by {creatorName}
                </Link>
              </nav>
            )}
          </div>
        </div>

        <div
          className="bg-gradient-to-b from-foreground/20 via-foreground/10 to-transparent bg-clip-text text-transparent leading-none absolute left-1/2 -translate-x-1/2 bottom-28 md:bottom-24 font-extrabold tracking-tighter pointer-events-none select-none text-center px-4"
          style={{
            fontSize: "clamp(4rem, 16vw, 14rem)",
            maxWidth: "95vw",
          }}
        >
          {brandName.toUpperCase()}
        </div>

        <div className="absolute hover:border-foreground duration-400 drop-shadow-[0_0px_20px_rgba(0,0,0,0.5)] dark:drop-shadow-[0_0px_20px_rgba(255,255,255,0.3)] bottom-28 md:bottom-28 backdrop-blur-sm rounded-3xl bg-background/60 left-1/2 border-2 border-border flex items-center justify-center p-3 -translate-x-1/2 z-10">
          <div className="w-12 sm:w-16 md:w-24 h-12 sm:h-16 md:h-24 bg-gradient-to-br from-foreground to-foreground/80 rounded-2xl flex items-center justify-center shadow-lg">
            {brandIcon || (
              <NotepadTextDashed className="w-8 sm:w-10 md:w-14 h-8 sm:h-10 md:h-14 text-background drop-shadow-lg" />
            )}
          </div>
        </div>

        <div className="absolute bottom-32 sm:bottom-34 backdrop-blur-sm h-1 bg-gradient-to-r from-transparent via-border to-transparent w-full left-1/2 -translate-x-1/2"></div>

        <div className="bg-gradient-to-t from-background via-background/80 blur-[1em] to-background/40 absolute bottom-28 w-full h-24"></div>
      </footer>
    </section>
  );
};
```

---

## components/ui/old-articles.css

**File Path**: `components/ui/old-articles.css` | **Lines**: 904

```css
.old-articles-page {
  background: #f4f1e8;
  color: #151712;
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, sans-serif;
  -webkit-font-smoothing: antialiased;
  min-height: 100vh;
}

.old-articles-page * {
  box-sizing: border-box;
}

.old-articles-page a {
  color: inherit;
  text-decoration: none;
}

.old-articles-page button,
.old-articles-page input {
  font: inherit;
}

.old-articles-page ::selection {
  background: #d9ff52;
  color: #151712;
}

.old-articles-page .wrap {
  width: min(1180px, calc(100% - 48px));
  margin: auto;
}

.old-articles-page .nav {
  position: sticky;
  top: 0;
  z-index: 20;
  height: 82px;
  padding: 0 max(24px, calc((100vw - 1180px) / 2));
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: rgba(244, 241, 232, 0.9);
  backdrop-filter: blur(18px);
  border-bottom: 1px solid rgba(21, 23, 18, 0.12);
}

.old-articles-page .logo {
  display: inline-grid;
  place-items: center;
  width: 52px;
  height: 52px;
}

.old-articles-page .logo img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: contain;
  border-radius: 50%;
}

.old-articles-page .nav nav {
  display: flex;
  gap: 32px;
  font-size: 13px;
  font-weight: 700;
}

.old-articles-page .nav nav a {
  position: relative;
}

.old-articles-page .nav nav a:after {
  content: "";
  position: absolute;
  left: 0;
  right: 100%;
  bottom: -8px;
  height: 2px;
  background: #151712;
  transition: 0.25s;
}

.old-articles-page .nav nav a:hover:after,
.old-articles-page .nav nav a.active:after {
  right: 0;
}

.old-articles-page .nav-cta {
  padding: 11px 17px;
  border: 1px solid #151712;
  border-radius: 100px;
  font-size: 13px;
  font-weight: 750;
}

.old-articles-page .nav-cta span {
  margin-left: 12px;
}

.old-articles-page .hero {
  min-height: 690px;
  padding: 112px 0 86px;
  display: grid;
  grid-template-columns: 1.65fr 0.7fr;
  gap: 110px;
  align-items: end;
}

.old-articles-page .eyebrow {
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  font-weight: 750;
  display: flex;
  align-items: center;
  gap: 10px;
}

.old-articles-page .eyebrow i {
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #92bd00;
  box-shadow: 0 0 0 5px rgba(146, 189, 0, 0.13);
}

.old-articles-page h1,
.old-articles-page h2,
.old-articles-page h3,
.old-articles-page .manifesto blockquote {
  font-family: Georgia, "Times New Roman", serif;
  font-weight: 400;
  margin: 0;
}

.old-articles-page h1 {
  font-size: clamp(67px, 8.1vw, 122px);
  line-height: 0.87;
  letter-spacing: -0.07em;
  margin: 38px 0;
}

.old-articles-page .hero em,
.old-articles-page .featured em,
.old-articles-page .library em,
.old-articles-page .closing em {
  font-weight: 400;
  color: #779c00;
}

.old-articles-page .intro {
  max-width: 720px;
  font-size: 19px;
  line-height: 1.58;
  color: #565a50;
}

.old-articles-page .manifesto {
  border-top: 1px solid #151712;
  padding-top: 18px;
  margin-bottom: 14px;
}

.old-articles-page .manifesto > span,
.old-articles-page .manifesto > p {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.13em;
  font-weight: 750;
}

.old-articles-page .manifesto blockquote {
  font-size: 28px;
  line-height: 1.2;
  letter-spacing: -0.03em;
  margin: 68px 0 30px;
}

.old-articles-page .manifesto > p {
  color: #777a70;
  line-height: 1.6;
}

.old-articles-page .index-strip {
  border-top: 1px solid #cecbc2;
  border-bottom: 1px solid #cecbc2;
}

.old-articles-page .stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

.old-articles-page .stats div {
  padding: 25px 0;
  display: flex;
  align-items: center;
  gap: 18px;
}

.old-articles-page .stats div + div {
  border-left: 1px solid #cecbc2;
  padding-left: 35px;
}

.old-articles-page .stats strong {
  font-family: Georgia, serif;
  font-size: 35px;
  font-weight: 400;
}

.old-articles-page .stats span {
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #6e7168;
  max-width: 150px;
}

.old-articles-page .featured {
  padding: 145px 0;
}

.old-articles-page .section-label {
  display: flex;
  align-items: center;
  gap: 16px;
  margin-bottom: 55px;
}

.old-articles-page .section-label span {
  width: 34px;
  height: 34px;
  border: 1px solid #a7aaa0;
  border-radius: 50%;
  display: grid;
  place-items: center;
  font: 11px/1 Inter, sans-serif;
}

.old-articles-page .section-label p {
  margin: 0;
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.16em;
  font-weight: 750;
}

.old-articles-page .featured h2,
.old-articles-page .library h2,
.old-articles-page .closing h2 {
  font-size: clamp(50px, 7vw, 94px);
  letter-spacing: -0.065em;
  line-height: 0.93;
}

.old-articles-page .featured-grid {
  display: grid;
  grid-template-columns: 1.4fr 1fr 1fr;
  gap: 14px;
  margin-top: 60px;
}

.old-articles-page .feature-card {
  min-height: 420px;
  background: #e5e1d6;
  padding: 30px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  transition: transform 0.25s, background 0.25s;
}

.old-articles-page .feature-card:hover {
  transform: translateY(-5px);
  background: #dbd7cb;
}

.old-articles-page .feature-card.primary {
  background: #d9ff52;
}

.old-articles-page .feature-card.primary:hover {
  background: #cded50;
}

.old-articles-page .card-meta {
  display: flex;
  justify-content: space-between;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  font-size: 10px;
  font-weight: 750;
}

.old-articles-page .feature-card small {
  font-size: 11px;
}

.old-articles-page .feature-card h3 {
  font-size: 34px;
  letter-spacing: -0.045em;
  line-height: 1.04;
  margin: 16px 0;
}

.old-articles-page .feature-card p {
  font-size: 14px;
  line-height: 1.55;
  color: #55584f;
}

.old-articles-page .feature-card b {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 12px;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

.old-articles-page .feature-card b span {
  font-size: 19px;
}

.old-articles-page .library {
  background: #171914;
  color: #f2efe6;
  padding: 130px 0;
}

.old-articles-page .library-head {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 80px;
}

.old-articles-page .section-label.light span {
  border-color: #5c5f56;
}

.old-articles-page .library .library-title em {
  color: #d9ff52;
}

.old-articles-page .library-title p {
  max-width: 610px;
  color: #a9aca2;
  font-size: 16px;
  line-height: 1.65;
  margin-top: 24px;
}

.old-articles-page .tools {
  margin-top: 90px;
  border-top: 1px solid #42443e;
  border-bottom: 1px solid #42443e;
  padding: 28px 0;
  display: grid;
  grid-template-columns: 1fr 1.6fr;
  gap: 60px;
  align-items: end;
}

.old-articles-page .search > span {
  display: block;
  font-size: 10px;
  text-transform: uppercase;
  letter-spacing: 0.15em;
  color: #92958b;
  margin-bottom: 12px;
}

.old-articles-page .search div {
  display: flex;
  align-items: center;
  gap: 12px;
}

.old-articles-page .search svg {
  width: 20px;
  fill: none;
  stroke: currentColor;
  stroke-width: 1.5;
}

.old-articles-page .search input {
  width: 100%;
  background: none;
  border: 0;
  outline: 0;
  color: white;
  font-size: 15px;
}

.old-articles-page .search input::placeholder {
  color: #696c63;
}

.old-articles-page .filters {
  display: flex;
  justify-content: flex-end;
  gap: 8px;
  flex-wrap: wrap;
}

.old-articles-page .filters button {
  color: #aeb0a8;
  background: none;
  border: 1px solid #50534b;
  border-radius: 100px;
  padding: 9px 13px;
  font-size: 11px;
  cursor: pointer;
  transition: 0.2s;
}

.old-articles-page .filters button:hover,
.old-articles-page .filters button.active {
  background: #d9ff52;
  border-color: #d9ff52;
  color: #151712;
}

.old-articles-page .result-line {
  display: flex;
  align-items: center;
  gap: 18px;
  padding-top: 24px;
}

.old-articles-page .result-line span {
  font-size: 10px;
  text-transform: uppercase;
  letter-spacing: 0.15em;
  color: #8e9188;
}

.old-articles-page .result-line i {
  height: 1px;
  background: #343631;
  flex: 1;
}

.old-articles-page .article {
  border-bottom: 1px solid #42443e;
}

.old-articles-page .article summary {
  list-style: none;
  cursor: pointer;
  display: grid;
  grid-template-columns: 70px 1fr 70px;
  gap: 30px;
  padding: 53px 0;
  align-items: start;
}

.old-articles-page .article summary::-webkit-details-marker {
  display: none;
}

.old-articles-page .article-number {
  font: 21px Georgia, serif;
  color: #767970;
}

.old-articles-page .article-meta {
  display: flex;
  gap: 24px;
  text-transform: uppercase;
  letter-spacing: 0.11em;
  font-size: 9px;
  color: #9a9d94;
  font-weight: 750;
}

.old-articles-page .article-summary h3 {
  font-size: clamp(34px, 4.5vw, 62px);
  letter-spacing: -0.05em;
  line-height: 1;
  margin: 19px 0 18px;
  transition: color 0.2s;
}

.old-articles-page .article summary:hover h3 {
  color: #d9ff52;
}

.old-articles-page .article-summary > p {
  max-width: 750px;
  color: #aeb0a8;
  font-size: 15px;
  line-height: 1.6;
  margin: 0;
}

.old-articles-page .toggle {
  text-align: center;
  font-size: 9px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #a9aba4;
}

.old-articles-page .toggle b {
  display: grid;
  place-items: center;
  width: 45px;
  height: 45px;
  border: 1px solid #55584f;
  border-radius: 50%;
  font: 24px/1 Inter, sans-serif;
  margin: 12px auto 0;
  transition: 0.25s;
}

.old-articles-page .close-label {
  display: none;
}

.old-articles-page .article[open] .open-label {
  display: none;
}

.old-articles-page .article[open] .close-label {
  display: inline;
}

.old-articles-page .article[open] .toggle b {
  transform: rotate(45deg);
  background: #d9ff52;
  color: #151712;
  border-color: #d9ff52;
}

.old-articles-page .article-body {
  display: grid;
  grid-template-columns: 170px minmax(0, 760px);
  gap: 70px;
  padding: 10px 100px 100px;
}

.old-articles-page .article-rail {
  font-size: 10px;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: #85887e;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.old-articles-page .article-rail strong {
  color: #f2efe6;
  font-size: 11px;
}

.old-articles-page .article-rail i {
  height: 1px;
  width: 100%;
  background: #464842;
  margin: 14px 0;
}

.old-articles-page .prose {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 18px;
  line-height: 1.84;
  color: #d4d2cb;
}

.old-articles-page .prose blockquote {
  font-size: 34px;
  line-height: 1.3;
  letter-spacing: -0.025em;
  color: #d9ff52;
  margin: 0 0 68px;
  padding-left: 30px;
  border-left: 2px solid #d9ff52;
}

.old-articles-page .prose section {
  margin: 0 0 48px;
}

.old-articles-page .prose h4 {
  font-size: 26px;
  line-height: 1.2;
  color: white;
  margin: 0 0 18px;
}

.old-articles-page .prose p {
  margin: 0 0 18px;
}

.old-articles-page .prose ul {
  list-style: none;
  padding: 0;
  margin: 25px 0;
}

.old-articles-page .prose li {
  padding: 11px 0 11px 24px;
  border-top: 1px solid #3f413b;
  position: relative;
}

.old-articles-page .prose li:before {
  content: "↳";
  position: absolute;
  left: 0;
  color: #d9ff52;
}

.old-articles-page .references {
  border-top: 1px solid #4a4c46;
  border-bottom: 1px solid #4a4c46;
  padding: 20px 0;
  margin-top: 65px;
  display: flex;
  gap: 18px;
  flex-wrap: wrap;
  font-family: Inter, sans-serif;
  font-size: 11px;
}

.old-articles-page .references > span {
  color: #7f8278;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  margin-right: auto;
}

.old-articles-page .references a {
  color: #d9ff52;
}

.old-articles-page .back {
  font: 10px Inter, sans-serif;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  display: inline-block;
  margin-top: 35px;
  color: #9da097;
}

.old-articles-page .empty {
  padding: 100px 0;
  text-align: center;
}

.old-articles-page .empty h3 {
  font-size: 50px;
  margin: 15px;
}

.old-articles-page .empty p {
  color: #999c93;
}

.old-articles-page .empty button {
  border: 1px solid #d9ff52;
  color: #d9ff52;
  background: none;
  border-radius: 100px;
  padding: 11px 17px;
  cursor: pointer;
}

.old-articles-page .closing {
  padding: 150px 0;
}

.old-articles-page .closing h2 {
  margin: 42px 0 65px;
}

.old-articles-page .closing > div {
  margin-left: 40%;
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 60px;
  align-items: end;
}

.old-articles-page .closing > div p {
  margin: 0;
  font-size: 17px;
  line-height: 1.65;
  color: #565a50;
}

.old-articles-page .closing > div a {
  font-size: 12px;
  font-weight: 750;
  text-transform: uppercase;
  letter-spacing: 0.09em;
  border-bottom: 1px solid #151712;
  padding-bottom: 8px;
  white-space: nowrap;
}

.old-articles-page .closing > div a span {
  margin-left: 20px;
}

.old-articles-page footer {
  background: #0d0e0b;
  color: white;
  padding: 56px 0;
}

.old-articles-page .footer-inner {
  display: grid;
  grid-template-columns: 0.6fr 1.2fr 1fr auto;
  align-items: end;
  gap: 40px;
}

.old-articles-page .footer-inner p {
  margin: 0;
  font-family: Georgia, serif;
  font-size: 20px;
  line-height: 1.25;
  color: #c4c6bf;
}

.old-articles-page .footer-inner > div {
  display: flex;
  gap: 25px;
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 0.1em;
}

.old-articles-page .footer-inner small {
  color: #6f716b;
  font-size: 10px;
}

@media (max-width: 900px) {
  .old-articles-page .nav nav {
    display: none;
  }
  .old-articles-page .hero {
    grid-template-columns: 1fr;
    gap: 30px;
    min-height: auto;
  }
  .old-articles-page .manifesto {
    max-width: 440px;
  }
  .old-articles-page .manifesto blockquote {
    margin: 35px 0 20px;
  }
  .old-articles-page .featured-grid {
    grid-template-columns: 1fr 1fr;
  }
  .old-articles-page .feature-card.primary {
    grid-column: 1 / -1;
  }
  .old-articles-page .library-head {
    grid-template-columns: 1fr;
  }
  .old-articles-page .tools {
    grid-template-columns: 1fr;
  }
  .old-articles-page .filters {
    justify-content: flex-start;
  }
  .old-articles-page .article-body {
    grid-template-columns: 1fr;
    padding-left: 70px;
  }
  .old-articles-page .article-rail {
    display: none;
  }
  .old-articles-page .closing > div {
    margin-left: 20%;
    grid-template-columns: 1fr;
  }
  .old-articles-page .footer-inner {
    grid-template-columns: 1fr 1fr;
  }
  .old-articles-page .footer-inner small {
    text-align: right;
  }
}

@media (max-width: 620px) {
  .old-articles-page .wrap {
    width: min(100% - 28px, 1180px);
  }
  .old-articles-page .nav {
    height: 68px;
    padding: 0 14px;
  }
  .old-articles-page .nav-cta {
    padding: 9px 12px;
  }
  .old-articles-page .hero {
    padding: 78px 0 60px;
  }
  .old-articles-page h1 {
    font-size: 56px;
  }
  .old-articles-page .intro {
    font-size: 16px;
  }
  .old-articles-page .stats {
    grid-template-columns: 1fr;
  }
  .old-articles-page .stats div {
    padding: 18px 0;
  }
  .old-articles-page .stats div + div {
    border-left: 0;
    border-top: 1px solid #cecbc2;
    padding-left: 0;
  }
  .old-articles-page .featured {
    padding: 90px 0;
  }
  .old-articles-page .featured h2,
  .old-articles-page .library h2,
  .old-articles-page .closing h2 {
    font-size: 49px;
  }
  .old-articles-page .featured-grid {
    grid-template-columns: 1fr;
  }
  .old-articles-page .feature-card.primary {
    grid-column: auto;
  }
  .old-articles-page .feature-card {
    min-height: 340px;
  }
  .old-articles-page .library {
    padding: 85px 0;
  }
  .old-articles-page .library-head {
    gap: 10px;
  }
  .old-articles-page .tools {
    margin-top: 60px;
    gap: 30px;
  }
  .old-articles-page .article summary {
    grid-template-columns: 36px 1fr;
    padding: 36px 0;
    gap: 10px;
  }
  .old-articles-page .article-number {
    font-size: 15px;
  }
  .old-articles-page .article-meta {
    gap: 10px;
    flex-wrap: wrap;
  }
  .old-articles-page .article-summary h3 {
    font-size: 36px;
  }
  .old-articles-page .toggle {
    grid-column: 2;
    margin-top: 15px;
    display: flex;
    align-items: center;
    gap: 10px;
    text-align: left;
  }
  .old-articles-page .toggle b {
    margin: 0;
    width: 34px;
    height: 34px;
  }
  .old-articles-page .article-body {
    padding: 5px 0 70px;
  }
  .old-articles-page .prose {
    font-size: 17px;
  }
  .old-articles-page .prose blockquote {
    font-size: 27px;
    padding-left: 18px;
    margin-bottom: 50px;
  }
  .old-articles-page .closing {
    padding: 100px 0;
  }
  .old-articles-page .closing > div {
    margin-left: 0;
  }
  .old-articles-page .footer-inner {
    grid-template-columns: 1fr;
  }
  .old-articles-page .footer-inner small {
    text-align: left;
  }
}

```

---

## components/ui/ProfileCard.css

**File Path**: `components/ui/ProfileCard.css` | **Lines**: 574

```css
:root {
  --pointer-x: 50%;
  --pointer-y: 50%;
  --pointer-from-center: 0;
  --pointer-from-top: 0.5;
  --pointer-from-left: 0.5;
  --card-opacity: 0;
  --rotate-x: 0deg;
  --rotate-y: 0deg;
  --background-x: 50%;
  --background-y: 50%;
  --grain: none;
  --icon: none;
  --behind-gradient: none;
  --behind-glow-color: rgba(125, 190, 255, 0.67);
  --behind-glow-size: 25%;
  --inner-gradient: none;
  --sunpillar-1: hsl(2, 100%, 73%);
  --sunpillar-2: hsl(53, 100%, 69%);
  --sunpillar-3: hsl(93, 100%, 69%);
  --sunpillar-4: hsl(176, 100%, 76%);
  --sunpillar-5: hsl(228, 100%, 74%);
  --sunpillar-6: hsl(283, 100%, 73%);
  --sunpillar-clr-1: var(--sunpillar-1);
  --sunpillar-clr-2: var(--sunpillar-2);
  --sunpillar-clr-3: var(--sunpillar-3);
  --sunpillar-clr-4: var(--sunpillar-4);
  --sunpillar-clr-5: var(--sunpillar-5);
  --sunpillar-clr-6: var(--sunpillar-6);
  --card-radius: 30px;
}

.pc-card-wrapper {
  perspective: 500px;
  transform: translate3d(0, 0, 0.1px);
  position: relative;
  touch-action: none;
  contain: layout;
}

.pc-behind {
  position: absolute;
  inset: 0;
  z-index: 0;
  pointer-events: none;
  background: radial-gradient(
    circle at var(--pointer-x) var(--pointer-y),
    var(--behind-glow-color) 0%,
    transparent var(--behind-glow-size)
  );
  filter: blur(50px) saturate(1.1);
  opacity: calc(0.8 * var(--card-opacity));
  transition: opacity 200ms ease;
}

.pc-card-wrapper:hover,
.pc-card-wrapper.active {
  --card-opacity: 1;
}

.pc-card {
  height: 80svh;
  max-height: 540px;
  display: grid;
  aspect-ratio: 0.718;
  border-radius: var(--card-radius);
  position: relative;
  background-blend-mode: color-dodge, normal, normal, normal;
  animation: glow-bg 12s linear infinite;
  animation-play-state: paused;
  box-shadow: rgba(0, 0, 0, 0.8) calc((var(--pointer-from-left) * 10px) - 3px)
    calc((var(--pointer-from-top) * 20px) - 6px) 20px -5px;
  transition: transform 1s ease;
  transform: translateZ(0) rotateX(0deg) rotateY(0deg);
  background: rgba(0, 0, 0, 0.9);
  backface-visibility: hidden;
  overflow: hidden;
  will-change: transform;
}

.pc-card-wrapper.in-view .pc-card {
  animation-play-state: running;
}

.pc-card:hover,
.pc-card.active {
  transition: none;
  transform: translateZ(0) rotateX(var(--rotate-y)) rotateY(var(--rotate-x));
}

.pc-card-shell.entering .pc-card {
  transition: transform 180ms ease-out;
}

.pc-card-shell {
  position: relative;
  z-index: 1;
  will-change: transform;
}

.pc-card * {
  display: grid;
  grid-area: 1/-1;
  border-radius: var(--card-radius);
  pointer-events: none;
}

.pc-inside {
  inset: 0;
  position: absolute;
  background-image: var(--inner-gradient);
  background-color: rgba(0, 0, 0, 0.9);
  transform: none;
}

.pc-shine {
  mask-image: var(--icon);
  mask-mode: luminance;
  mask-repeat: repeat;
  mask-size: 150%;
  mask-position: top calc(200% - (var(--background-y) * 5)) left calc(100% - var(--background-x));
  transition: filter 0.8s ease;
  filter: brightness(0.66) contrast(1.33) saturate(0.33) opacity(0.5);
  animation: holo-bg 18s linear infinite;
  animation-play-state: paused;
  mix-blend-mode: color-dodge;
}

.pc-card-wrapper.in-view .pc-shine {
  animation-play-state: running;
}

.pc-shine,
.pc-shine::after {
  --space: 5%;
  --angle: -45deg;
  transform: translate3d(0, 0, 1px);
  overflow: hidden;
  z-index: 3;
  background: transparent;
  background-size: cover;
  background-position: center;
  background-image:
    repeating-linear-gradient(
      0deg,
      var(--sunpillar-clr-1) calc(var(--space) * 1),
      var(--sunpillar-clr-2) calc(var(--space) * 2),
      var(--sunpillar-clr-3) calc(var(--space) * 3),
      var(--sunpillar-clr-4) calc(var(--space) * 4),
      var(--sunpillar-clr-5) calc(var(--space) * 5),
      var(--sunpillar-clr-6) calc(var(--space) * 6),
      var(--sunpillar-clr-1) calc(var(--space) * 7)
    ),
    repeating-linear-gradient(
      var(--angle),
      #0e152e 0%,
      hsl(180, 10%, 60%) 3.8%,
      hsl(180, 29%, 66%) 4.5%,
      hsl(180, 10%, 60%) 5.2%,
      #0e152e 10%,
      #0e152e 12%
    ),
    radial-gradient(
      farthest-corner circle at var(--pointer-x) var(--pointer-y),
      hsla(0, 0%, 0%, 0.1) 12%,
      hsla(0, 0%, 0%, 0.15) 20%,
      hsla(0, 0%, 0%, 0.25) 120%
    );
  background-position:
    0 var(--background-y),
    var(--background-x) var(--background-y),
    center;
  background-blend-mode: color, hard-light;
  background-size:
    500% 500%,
    300% 300%,
    200% 200%;
  background-repeat: repeat;
}

.pc-shine::before,
.pc-shine::after {
  content: '';
  background-position: center;
  background-size: cover;
  grid-area: 1/1;
  opacity: 0;
  transition: opacity 0.8s ease;
}

.pc-card:hover .pc-shine,
.pc-card.active .pc-shine {
  filter: brightness(0.85) contrast(1.5) saturate(0.5);
  animation-play-state: paused;
}

.pc-card:hover .pc-shine::before,
.pc-card.active .pc-shine::before,
.pc-card:hover .pc-shine::after,
.pc-card.active .pc-shine::after {
  opacity: 1;
}

.pc-shine::before {
  background-image:
    linear-gradient(
      45deg,
      var(--sunpillar-4),
      var(--sunpillar-5),
      var(--sunpillar-6),
      var(--sunpillar-1),
      var(--sunpillar-2),
      var(--sunpillar-3)
    ),
    radial-gradient(circle at var(--pointer-x) var(--pointer-y), hsl(0, 0%, 70%) 0%, hsla(0, 0%, 30%, 0.2) 90%),
    var(--grain);
  background-size:
    250% 250%,
    100% 100%,
    220px 220px;
  background-position:
    var(--pointer-x) var(--pointer-y),
    center,
    calc(var(--pointer-x) * 0.01) calc(var(--pointer-y) * 0.01);
  background-blend-mode: color-dodge;
  filter: brightness(1.15) contrast(1.35) saturate(1.15);
  mix-blend-mode: luminosity;
}

.pc-shine::after {
  background-position:
    0 var(--background-y),
    calc(var(--background-x) * 0.4) calc(var(--background-y) * 0.5),
    center;
  background-size:
    200% 300%,
    700% 700%,
    100% 100%;
  mix-blend-mode: difference;
  filter: brightness(0.8) contrast(1.5);
}

.pc-glare {
  transform: translate3d(0, 0, 1.1px);
  overflow: hidden;
  background-image: radial-gradient(
    farthest-corner circle at var(--pointer-x) var(--pointer-y),
    hsl(248, 25%, 80%) 12%,
    hsla(207, 40%, 30%, 0.8) 90%
  );
  mix-blend-mode: overlay;
  filter: brightness(0.8) contrast(1.2);
  z-index: 4;
}

.pc-avatar-content {
  mix-blend-mode: luminosity;
  overflow: visible;
  transform: translateZ(2);
  backface-visibility: hidden;
}

.pc-avatar-content .avatar {
  width: 82%;
  position: absolute;
  left: 50%;
  transform-origin: 50% 100%;
  transform: translateX(calc(-50% + (var(--pointer-from-left) - 0.5) * 6px)) translateZ(0)
    scaleY(calc(1 + (var(--pointer-from-top) - 0.5) * 0.02)) scaleX(calc(1 + (var(--pointer-from-left) - 0.5) * 0.01));
  bottom: -50px;
  backface-visibility: hidden;
  will-change: transform;
  transition: transform 120ms ease-out;
}

.pc-avatar-content::before {
  content: '';
  position: absolute;
  inset: 0;
  z-index: 1;
  backdrop-filter: none;
  pointer-events: none;
}

.pc-user-info {
  position: absolute;
  --ui-inset: 20px;
  --ui-radius-bias: 6px;
  bottom: var(--ui-inset);
  left: var(--ui-inset);
  right: var(--ui-inset);
  z-index: 2;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(16px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: calc(max(0px, var(--card-radius) - var(--ui-inset) + var(--ui-radius-bias)));
  padding: 12px 14px;
  pointer-events: auto;
}

.pc-user-details {
  display: flex;
  align-items: center;
  gap: 12px;
}

.pc-mini-avatar {
  width: 48px;
  height: 48px;
  border-radius: 50%;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.1);
  flex-shrink: 0;
}

.pc-mini-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
}

.pc-user-text {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  gap: 6px;
}

.pc-handle {
  font-size: 14px;
  font-weight: 500;
  color: rgba(255, 255, 255, 0.9);
  line-height: 1;
}

.pc-status {
  font-size: 14px;
  color: rgba(255, 255, 255, 0.7);
  line-height: 1;
}

.pc-contact-btn {
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 8px;
  padding: 12px 16px;
  font-size: 12px;
  font-weight: 600;
  color: rgba(255, 255, 255, 0.9);
  cursor: pointer;
  transition: all 0.2s ease;
  backdrop-filter: blur(8px);
}

.pc-contact-btn:hover {
  border-color: rgba(255, 255, 255, 0.4);
  transform: translateY(-1px);
  transition: all 0.2s ease;
}

.pc-content:not(.pc-avatar-content) {
  max-height: 100%;
  overflow: hidden;
  text-align: center;
  position: relative;
  transform: translate3d(
    calc(var(--pointer-from-left) * -6px + 3px),
    calc(var(--pointer-from-top) * -6px + 3px),
    0.1px
  );
  z-index: 5;
  mix-blend-mode: luminosity;
}

.pc-details {
  width: 100%;
  position: absolute;
  top: 3em;
  display: flex;
  flex-direction: column;
}

.pc-details h3 {
  font-weight: 600;
  margin: 0;
  font-size: min(5svh, 3em);
  margin: 0;
  background-image: linear-gradient(to bottom, #fff, #6f6fbe);
  background-size: 1em 1.5em;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
}

.pc-details p {
  font-weight: 600;
  position: relative;
  top: -12px;
  white-space: nowrap;
  font-size: 16px;
  margin: 0 auto;
  width: min-content;
  background-image: linear-gradient(to bottom, #fff, #4a4ac0);
  background-size: 1em 1.5em;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  -webkit-background-clip: text;
}

@keyframes glow-bg {
  0% {
    --bgrotate: 0deg;
  }

  100% {
    --bgrotate: 360deg;
  }
}

@keyframes holo-bg {
  0% {
    background-position:
      0 var(--background-y),
      0 0,
      center;
  }

  100% {
    background-position:
      0 var(--background-y),
      90% 90%,
      center;
  }
}

@media (max-width: 768px) {
  .pc-card {
    height: 70svh;
    max-height: 450px;
  }

  .pc-details {
    top: 2em;
  }

  .pc-details h3 {
    font-size: min(4svh, 2.5em);
  }

  .pc-details p {
    font-size: 14px;
  }

  .pc-user-info {
    --ui-inset: 15px;
    padding: 10px 12px;
  }

  .pc-mini-avatar {
    width: 28px;
    height: 28px;
  }

  .pc-user-details {
    gap: 10px;
  }

  .pc-handle {
    font-size: 13px;
  }

  .pc-status {
    font-size: 10px;
  }

  .pc-contact-btn {
    padding: 6px 12px;
    font-size: 11px;
  }
}

@media (max-width: 480px) {
  .pc-card {
    height: 60svh;
    max-height: 380px;
  }

  .pc-details {
    top: 1.5em;
  }

  .pc-details h3 {
    font-size: min(3.5svh, 2em);
  }

  .pc-details p {
    font-size: 12px;
    top: -8px;
  }

  .pc-user-info {
    --ui-inset: 12px;
    padding: 8px 10px;
  }

  .pc-mini-avatar {
    width: 24px;
    height: 24px;
  }

  .pc-user-details {
    gap: 8px;
  }

  .pc-handle {
    font-size: 12px;
  }

  .pc-status {
    font-size: 9px;
  }

  .pc-contact-btn {
    padding: 5px 10px;
    font-size: 10px;
    border-radius: 50px;
  }
}

@media (max-width: 320px) {
  .pc-card {
    height: 55svh;
    max-height: 320px;
  }

  .pc-details h3 {
    font-size: min(3svh, 1.5em);
  }

  .pc-details p {
    font-size: 11px;
  }

  .pc-user-info {
    padding: 6px 8px;
  }

  .pc-mini-avatar {
    width: 20px;
    height: 20px;
  }

  .pc-user-details {
    gap: 6px;
  }

  .pc-handle {
    font-size: 11px;
  }

  .pc-status {
    font-size: 8px;
  }

  .pc-contact-btn {
    padding: 4px 8px;
    font-size: 9px;
    border-radius: 50px;
  }
}
```

---

## components/ui/ProfileCard.tsx

**File Path**: `components/ui/ProfileCard.tsx` | **Lines**: 445

```tsx
"use client";
import React, { useEffect, useRef, useCallback, useMemo } from 'react';
import './ProfileCard.css';

const DEFAULT_INNER_GRADIENT = 'linear-gradient(145deg,#60496e8c 0%,#71C4FF44 100%)';

const ANIMATION_CONFIG = {
  INITIAL_DURATION: 1200,
  INITIAL_X_OFFSET: 70,
  INITIAL_Y_OFFSET: 60,
  DEVICE_BETA_OFFSET: 20,
  ENTER_TRANSITION_MS: 180,
};

const clamp = (v: number, min = 0, max = 100) => Math.min(Math.max(v, min), max);
const round = (v: number, precision = 3) => parseFloat(v.toFixed(precision));
const adjust = (v: number, fMin: number, fMax: number, tMin: number, tMax: number) =>
  round(tMin + ((tMax - tMin) * (v - fMin)) / (fMax - fMin));

export interface ProfileCardProps {
  avatarUrl?: string;
  iconUrl?: string;
  grainUrl?: string;
  innerGradient?: string;
  behindGlowEnabled?: boolean;
  behindGlowColor?: string;
  behindGlowSize?: string;
  className?: string;
  enableTilt?: boolean;
  enableMobileTilt?: boolean;
  mobileTiltSensitivity?: number;
  miniAvatarUrl?: string;
  name?: string;
  title?: string;
  handle?: string;
  status?: string;
  contactText?: string;
  contactHref?: string;
  showUserInfo?: boolean;
  onContactClick?: () => void;
}

const ProfileCardComponent: React.FC<ProfileCardProps> = ({
  avatarUrl = '<Placeholder for avatar URL>',
  iconUrl = '<Placeholder for icon URL>',
  grainUrl = '<Placeholder for grain URL>',
  innerGradient,
  behindGlowEnabled = true,
  behindGlowColor,
  behindGlowSize,
  className = '',
  enableTilt = true,
  enableMobileTilt = false,
  mobileTiltSensitivity = 5,
  miniAvatarUrl,
  name = 'Javi A. Torres',
  title = 'Software Engineer',
  handle = 'javicodes',
  status = 'Online',
  contactText = 'Contact',
  contactHref,
  showUserInfo = true,
  onContactClick,
}) => {
  const wrapRef = useRef<HTMLDivElement | null>(null);
  const shellRef = useRef<HTMLDivElement | null>(null);

  const enterTimerRef = useRef<number | null>(null);
  const leaveRafRef = useRef<number | null>(null);

  const tiltEngine = useMemo(() => {
    if (!enableTilt) return null;

    let rafId: number | null = null;
    let running = false;
    let lastTs = 0;

    let currentX = 0;
    let currentY = 0;
    let targetX = 0;
    let targetY = 0;

    const DEFAULT_TAU = 0.14;
    const INITIAL_TAU = 0.6;
    let initialUntil = 0;

    const setVarsFromXY = (x: number, y: number) => {
      const shell = shellRef.current;
      const wrap = wrapRef.current;
      if (!shell || !wrap) return;

      const width = shell.clientWidth || 1;
      const height = shell.clientHeight || 1;

      const percentX = clamp((100 / width) * x);
      const percentY = clamp((100 / height) * y);

      const centerX = percentX - 50;
      const centerY = percentY - 50;

      const properties: Record<string, string> = {
        '--pointer-x': `${percentX}%`,
        '--pointer-y': `${percentY}%`,
        '--background-x': `${adjust(percentX, 0, 100, 35, 65)}%`,
        '--background-y': `${adjust(percentY, 0, 100, 35, 65)}%`,
        '--pointer-from-center': `${clamp(Math.hypot(percentY - 50, percentX - 50) / 50, 0, 1)}`,
        '--pointer-from-top': `${percentY / 100}`,
        '--pointer-from-left': `${percentX / 100}`,
        '--rotate-x': `${round(-(centerX / 5))}deg`,
        '--rotate-y': `${round(centerY / 4)}deg`,
      };

      for (const [k, v] of Object.entries(properties)) wrap.style.setProperty(k, v);
    };

    const step = (ts: number) => {
      if (!running) return;
      if (lastTs === 0) lastTs = ts;
      const dt = (ts - lastTs) / 1000;
      lastTs = ts;

      const tau = ts < initialUntil ? INITIAL_TAU : DEFAULT_TAU;
      const k = 1 - Math.exp(-dt / tau);

      currentX += (targetX - currentX) * k;
      currentY += (targetY - currentY) * k;

      setVarsFromXY(currentX, currentY);

      const stillFar = Math.abs(targetX - currentX) > 0.05 || Math.abs(targetY - currentY) > 0.05;

      if (stillFar || document.hasFocus()) {
        rafId = requestAnimationFrame(step);
      } else {
        running = false;
        lastTs = 0;
        if (rafId) {
          cancelAnimationFrame(rafId);
          rafId = null;
        }
      }
    };

    const start = () => {
      if (running) return;
      running = true;
      lastTs = 0;
      rafId = requestAnimationFrame(step);
    };

    return {
      setImmediate(x: number, y: number) {
        currentX = x;
        currentY = y;
        setVarsFromXY(currentX, currentY);
      },
      setTarget(x: number, y: number) {
        targetX = x;
        targetY = y;
        start();
      },
      toCenter() {
        const shell = shellRef.current;
        if (!shell) return;
        this.setTarget(shell.clientWidth / 2, shell.clientHeight / 2);
      },
      beginInitial(durationMs: number) {
        initialUntil = performance.now() + durationMs;
        start();
      },
      getCurrent() {
        return { x: currentX, y: currentY, tx: targetX, ty: targetY };
      },
      cancel() {
        if (rafId) cancelAnimationFrame(rafId);
        rafId = null;
        running = false;
        lastTs = 0;
      },
    };
  }, [enableTilt]);

  const getOffsets = (evt: PointerEvent, el: HTMLElement) => {
    const rect = el.getBoundingClientRect();
    return { x: evt.clientX - rect.left, y: evt.clientY - rect.top };
  };

  const handlePointerMove = useCallback(
    (event: PointerEvent) => {
      const shell = shellRef.current;
      if (!shell || !tiltEngine) return;
      const { x, y } = getOffsets(event, shell);
      tiltEngine.setTarget(x, y);
    },
    [tiltEngine]
  );

  const handlePointerEnter = useCallback(
    (event: PointerEvent) => {
      const shell = shellRef.current;
      if (!shell || !tiltEngine) return;

      shell.classList.add('active');
      shell.classList.add('entering');
      if (enterTimerRef.current) window.clearTimeout(enterTimerRef.current);
      enterTimerRef.current = window.setTimeout(() => {
        shell.classList.remove('entering');
      }, ANIMATION_CONFIG.ENTER_TRANSITION_MS);

      const { x, y } = getOffsets(event, shell);
      tiltEngine.setTarget(x, y);
    },
    [tiltEngine]
  );

  const handlePointerLeave = useCallback(() => {
    const shell = shellRef.current;
    if (!shell || !tiltEngine) return;

    tiltEngine.toCenter();

    const checkSettle = () => {
      const { x, y, tx, ty } = tiltEngine.getCurrent();
      const settled = Math.hypot(tx - x, ty - y) < 0.6;
      if (settled) {
        shell.classList.remove('active');
        leaveRafRef.current = null;
      } else {
        leaveRafRef.current = requestAnimationFrame(checkSettle);
      }
    };
    if (leaveRafRef.current) cancelAnimationFrame(leaveRafRef.current);
    leaveRafRef.current = requestAnimationFrame(checkSettle);
  }, [tiltEngine]);

  const handleDeviceOrientation = useCallback(
    (event: DeviceOrientationEvent) => {
      const shell = shellRef.current;
      if (!shell || !tiltEngine) return;

      const { beta, gamma } = event;
      if (beta == null || gamma == null) return;

      const centerX = shell.clientWidth / 2;
      const centerY = shell.clientHeight / 2;
      const x = clamp(centerX + gamma * mobileTiltSensitivity, 0, shell.clientWidth);
      const y = clamp(
        centerY + (beta - ANIMATION_CONFIG.DEVICE_BETA_OFFSET) * mobileTiltSensitivity,
        0,
        shell.clientHeight
      );

      tiltEngine.setTarget(x, y);
    },
    [tiltEngine, mobileTiltSensitivity]
  );

  useEffect(() => {
    if (!enableTilt || !tiltEngine) return;

    const shell = shellRef.current;
    const wrap = wrapRef.current;
    if (!shell || !wrap) return;

    const pointerMoveHandler = handlePointerMove;
    const pointerEnterHandler = handlePointerEnter;
    const pointerLeaveHandler = handlePointerLeave;
    const deviceOrientationHandler = handleDeviceOrientation;

    shell.addEventListener('pointerenter', pointerEnterHandler as EventListener);
    shell.addEventListener('pointermove', pointerMoveHandler as EventListener);
    shell.addEventListener('pointerleave', pointerLeaveHandler as EventListener);

    const handleClick = () => {
      if (!enableMobileTilt || location.protocol !== 'https:') return;
      const anyMotion = (window as unknown as { DeviceMotionEvent?: { requestPermission?: () => Promise<string> } })
        .DeviceMotionEvent;
      if (anyMotion && typeof anyMotion.requestPermission === 'function') {
        anyMotion
          .requestPermission()
          .then((state) => {
            if (state === 'granted') {
              window.addEventListener('deviceorientation', deviceOrientationHandler);
            }
          })
          .catch(console.error);
      } else {
        window.addEventListener('deviceorientation', deviceOrientationHandler);
      }
    };
    shell.addEventListener('click', handleClick);

    // Defer tilt initial animation + CSS animations until card is in viewport
    let initialStarted = false;
    const observer = new IntersectionObserver(
      (entries) => {
        for (const entry of entries) {
          if (entry.isIntersecting) {
            wrap.classList.add('in-view');
            if (!initialStarted) {
              initialStarted = true;
              const initialX = (shell.clientWidth || 0) - ANIMATION_CONFIG.INITIAL_X_OFFSET;
              const initialY = ANIMATION_CONFIG.INITIAL_Y_OFFSET;
              tiltEngine.setImmediate(initialX, initialY);
              tiltEngine.toCenter();
              tiltEngine.beginInitial(ANIMATION_CONFIG.INITIAL_DURATION);
            }
          } else {
            wrap.classList.remove('in-view');
            tiltEngine.cancel();
            initialStarted = false;
          }
        }
      },
      { threshold: 0.1 }
    );
    observer.observe(wrap);

    return () => {
      observer.disconnect();
      shell.removeEventListener('pointerenter', pointerEnterHandler as EventListener);
      shell.removeEventListener('pointermove', pointerMoveHandler as EventListener);
      shell.removeEventListener('pointerleave', pointerLeaveHandler as EventListener);
      shell.removeEventListener('click', handleClick);
      window.removeEventListener('deviceorientation', deviceOrientationHandler);
      if (enterTimerRef.current) window.clearTimeout(enterTimerRef.current);
      if (leaveRafRef.current) cancelAnimationFrame(leaveRafRef.current);
      tiltEngine.cancel();
      shell.classList.remove('entering');
    };
  }, [
    enableTilt,
    enableMobileTilt,
    tiltEngine,
    handlePointerMove,
    handlePointerEnter,
    handlePointerLeave,
    handleDeviceOrientation,
  ]);

  const cardStyle = useMemo(
    () =>
      ({
        '--icon': iconUrl ? `url(${iconUrl})` : 'none',
        '--grain': grainUrl ? `url(${grainUrl})` : 'none',
        '--inner-gradient': innerGradient ?? DEFAULT_INNER_GRADIENT,
        '--behind-glow-color': behindGlowColor ?? 'rgba(125, 190, 255, 0.67)',
        '--behind-glow-size': behindGlowSize ?? '50%',
      }) as React.CSSProperties,
    [iconUrl, grainUrl, innerGradient, behindGlowColor, behindGlowSize]
  );

  const handleContactClick = useCallback(() => {
    onContactClick?.();
  }, [onContactClick]);

  return (
    <div ref={wrapRef} className={`pc-card-wrapper ${className}`.trim()} style={cardStyle}>
      {behindGlowEnabled && <div className="pc-behind" />}
      <div ref={shellRef} className="pc-card-shell">
        <section className="pc-card">
          <div className="pc-inside">
            <div className="pc-shine" />
            <div className="pc-glare" />
            <div className="pc-content pc-avatar-content">
              {/* eslint-disable-next-line @next/next/no-img-element */}
              <img
                className="avatar"
                src={avatarUrl}
                alt={`${name || 'User'} avatar`}
                loading="lazy"
                decoding="async"
                width={500}
                height={500}
                onError={(e) => {
                  const t = e.target as HTMLImageElement;
                  t.style.display = 'none';
                }}
              />
              {showUserInfo && (
                <div className="pc-user-info">
                  <div className="pc-user-details">
                    <div className="pc-mini-avatar">
                      {/* eslint-disable-next-line @next/next/no-img-element */}
                      <img
                        src={miniAvatarUrl || avatarUrl}
                        alt={`${name || 'User'} mini avatar`}
                        loading="lazy"
                        decoding="async"
                        width={48}
                        height={48}
                        onError={(e) => {
                          const t = e.target as HTMLImageElement;
                          t.style.opacity = '0.5';
                          t.src = avatarUrl;
                        }}
                      />
                    </div>
                    <div className="pc-user-text">
                      <div className="pc-handle">@{handle}</div>
                      <div className="pc-status">{status}</div>
                    </div>
                  </div>
                  {contactHref ? (
                    <a
                      className="pc-contact-btn"
                      href={contactHref}
                      target="_blank"
                      rel="noopener noreferrer"
                      onClick={handleContactClick}
                      style={{ pointerEvents: 'auto', display: 'inline-flex', alignItems: 'center', textDecoration: 'none' }}
                      aria-label={`Contact ${name || 'user'}`}
                    >
                      {contactText}
                    </a>
                  ) : (
                    <button
                      className="pc-contact-btn"
                      onClick={handleContactClick}
                      style={{ pointerEvents: 'auto' }}
                      type="button"
                      aria-label={`Contact ${name || 'user'}`}
                    >
                      {contactText}
                    </button>
                  )}
                </div>
              )}
            </div>
            <div className="pc-content">
              <div className="pc-details">
                <h3>{name}</h3>
                <p>{title}</p>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>
  );
};

const ProfileCard = React.memo(ProfileCardComponent);
export default ProfileCard;
```

---

## components/ui/project-modal.tsx

**File Path**: `components/ui/project-modal.tsx` | **Lines**: 507

```tsx
"use client";
import React from "react";
import { motion, AnimatePresence } from "framer-motion";

export type Project = {
  title: string;
  year: string;
  tag: string;
  featured: boolean;
  desc: string;
  stack: string[];
  artwork: string;
  image?: string;
  overview?: string;
  features?: string[];
  links?: { github?: string; linkedin?: string; live?: string };
};

const CloseIcon = (p: React.SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 16 16" fill="none" {...p}>
    <path d="M4 4l8 8M12 4l-8 8" stroke="currentColor" strokeWidth="1.4" strokeLinecap="round" />
  </svg>
);

const ArrowIcon = (p: React.SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 16 16" fill="none" {...p}>
    <path d="M5 11L11 5M6 5h5v5" stroke="currentColor" strokeWidth="1.4" strokeLinecap="round" strokeLinejoin="round" />
  </svg>
);

const GithubIcon = (p: React.SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 24 24" fill="currentColor" {...p}>
    <path d="M12 .5a12 12 0 0 0-3.79 23.39c.6.11.82-.26.82-.58v-2.04c-3.34.72-4.04-1.61-4.04-1.61-.54-1.39-1.33-1.76-1.33-1.76-1.09-.74.08-.73.08-.73 1.21.09 1.84 1.24 1.84 1.24 1.07 1.83 2.81 1.3 3.5.99.11-.78.42-1.3.76-1.6-2.66-.3-5.47-1.33-5.47-5.93 0-1.31.47-2.38 1.24-3.22-.13-.31-.54-1.53.11-3.19 0 0 1.01-.32 3.3 1.23a11.5 11.5 0 0 1 6 0c2.29-1.55 3.3-1.23 3.3-1.23.66 1.66.24 2.88.12 3.19.77.84 1.23 1.91 1.23 3.22 0 4.61-2.81 5.62-5.49 5.92.43.37.81 1.1.81 2.22v3.29c0 .32.22.7.83.58A12 12 0 0 0 12 .5Z" />
  </svg>
);

const LinkedinIcon = (p: React.SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 24 24" fill="currentColor" {...p}>
    <path d="M20.45 20.45h-3.55v-5.57c0-1.33-.03-3.04-1.85-3.04-1.86 0-2.14 1.45-2.14 2.95v5.66H9.36V9h3.41v1.56h.05c.48-.9 1.64-1.85 3.38-1.85 3.61 0 4.28 2.38 4.28 5.47v6.27ZM5.34 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12ZM7.12 20.45H3.56V9h3.56v11.45ZM22.22 0H1.77C.79 0 0 .77 0 1.72v20.55C0 23.23.79 24 1.77 24h20.45c.98 0 1.78-.77 1.78-1.73V1.72C24 .77 23.2 0 22.22 0Z" />
  </svg>
);

const CheckIcon = (p: React.SVGProps<SVGSVGElement>) => (
  <svg viewBox="0 0 16 16" fill="none" {...p}>
    <path d="M3 8.5l3 3 7-7" stroke="currentColor" strokeWidth="1.6" strokeLinecap="round" strokeLinejoin="round" />
  </svg>
);

const containerVariants = {
  hidden: { opacity: 0 },
  visible: {
    opacity: 1,
    transition: { staggerChildren: 0.06, delayChildren: 0.12 },
  },
};

const itemVariants = {
  hidden: { opacity: 0, y: 18 },
  visible: { opacity: 1, y: 0, transition: { duration: 0.55, ease: [0.22, 1, 0.36, 1] as const } },
};

export const ProjectModal = ({
  project,
  onClose,
}: {
  project: Project | null;
  onClose: () => void;
}) => {
  React.useEffect(() => {
    if (!project) return;
    const onKey = (e: KeyboardEvent) => {
      if (e.key === "Escape") onClose();
    };
    window.addEventListener("keydown", onKey);
    const prev = document.body.style.overflow;
    document.body.style.overflow = "hidden";
    return () => {
      window.removeEventListener("keydown", onKey);
      document.body.style.overflow = prev;
    };
  }, [project, onClose]);

  return (
    <AnimatePresence>
      {project && (
        <motion.div
          key="project-modal"
          className="fixed inset-0 z-[120] flex items-center justify-center px-4 sm:px-8 py-8"
          initial={{ opacity: 0 }}
          animate={{ opacity: 1 }}
          exit={{ opacity: 0 }}
          transition={{ duration: 0.35 }}
        >
          {/* Backdrop */}
          <motion.button
            aria-label="Close"
            onClick={onClose}
            className="absolute inset-0 cursor-default"
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            transition={{ duration: 0.4 }}
            style={{
              background:
                "radial-gradient(ellipse at center, rgba(20,14,38,0.78) 0%, rgba(4,2,10,0.92) 80%)",
              backdropFilter: "blur(22px)",
              WebkitBackdropFilter: "blur(22px)",
            }}
          />

          {/* Panel */}
          <motion.div
            role="dialog"
            aria-modal="true"
            aria-labelledby="project-modal-title"
            className="relative w-full max-w-[880px] max-h-[92vh] overflow-y-auto rounded-[20px] [scrollbar-width:none] [&::-webkit-scrollbar]:hidden"
            style={{
              background:
                "linear-gradient(180deg, rgba(22,17,40,0.96) 0%, rgba(10,7,20,0.98) 100%)",
              border: "1px solid rgba(167,139,250,0.18)",
              boxShadow:
                "0 50px 120px -30px rgba(0,0,0,0.95), 0 0 0 1px rgba(167,139,250,0.06), inset 0 1px 0 rgba(255,255,255,0.07)",
            }}
            initial={{ opacity: 0, scale: 0.94, y: 28 }}
            animate={{ opacity: 1, scale: 1, y: 0 }}
            exit={{ opacity: 0, scale: 0.96, y: 14 }}
            transition={{ type: "spring", damping: 28, stiffness: 260, mass: 0.9 }}
          >
            {/* Decorative inner glow rings */}
            <div
              aria-hidden
              className="pointer-events-none absolute inset-0 rounded-[24px]"
              style={{
                background:
                  "radial-gradient(80% 60% at 50% 0%, rgba(167,139,250,0.18), transparent 60%), radial-gradient(50% 40% at 100% 100%, rgba(236,72,153,0.10), transparent 65%)",
              }}
            />

            <motion.div
              variants={containerVariants}
              initial="hidden"
              animate="visible"
              className="relative"
            >
              {/* Hero artwork */}
              <motion.div
                variants={itemVariants}
                className="relative w-full overflow-hidden"
                style={{
                  height: "200px",
                  background: project.artwork,
                  borderBottom: "1px solid rgba(167,139,250,0.10)",
                }}
              >
                {project.image && (
                  <motion.img
                    src={project.image}
                    alt={project.title}
                    className="absolute inset-0 w-full h-full object-cover pointer-events-none select-none"
                    style={{ objectPosition: "center top" }}
                    draggable={false}
                    initial={{ scale: 1.08 }}
                    animate={{ scale: 1 }}
                    transition={{ duration: 1.4, ease: [0.22, 1, 0.36, 1] }}
                  />
                )}
                {/* Image overlays */}
                <div
                  aria-hidden
                  className="absolute inset-0 pointer-events-none"
                  style={{
                    background:
                      "linear-gradient(180deg, rgba(8,6,18,0) 40%, rgba(8,6,18,0.85) 100%)",
                  }}
                />
                <div
                  aria-hidden
                  className="absolute inset-0 pointer-events-none mix-blend-screen opacity-60"
                  style={{
                    background:
                      "radial-gradient(60% 80% at 20% 0%, rgba(167,139,250,0.35), transparent 60%)",
                  }}
                />

                {/* Top-left tag */}
                <span
                  className="absolute top-5 left-5 text-[10px] font-mono uppercase tracking-[0.22em] text-white/90 rounded-full px-3 py-[5px]"
                  style={{
                    background: "rgba(0,0,0,0.45)",
                    border: "1px solid rgba(255,255,255,0.14)",
                    backdropFilter: "blur(8px)",
                  }}
                >
                  {project.tag}
                </span>
                {project.featured && (
                  <span
                    className="absolute top-5 right-20 text-[10px] font-mono uppercase tracking-[0.22em] text-[#d8c9ff] rounded-full px-3 py-[5px]"
                    style={{
                      background:
                        "linear-gradient(180deg, rgba(58,38,108,0.85) 0%, rgba(31,18,58,0.85) 100%)",
                      border: "1px solid rgba(167,139,250,0.45)",
                      backdropFilter: "blur(8px)",
                    }}
                  >
                    ★ Featured
                  </span>
                )}

                {/* Animated shimmer line */}
                <motion.span
                  aria-hidden
                  className="absolute left-0 right-0 bottom-0 h-px"
                  style={{
                    background:
                      "linear-gradient(90deg, transparent 0%, rgba(167,139,250,0.9) 50%, transparent 100%)",
                  }}
                  initial={{ scaleX: 0, opacity: 0 }}
                  animate={{ scaleX: 1, opacity: 1 }}
                  transition={{ duration: 1, delay: 0.4, ease: [0.22, 1, 0.36, 1] }}
                />
              </motion.div>

              {/* Body */}
              <div style={{ padding: "22px 36px 28px" }}>
                {/* Year + meta line */}
                <motion.div
                  variants={itemVariants}
                  className="flex items-center text-[9.5px] font-mono uppercase text-[#8a86a0]"
                  style={{ gap: "10px", marginBottom: "8px", letterSpacing: "0.26em" }}
                >
                  <span>{project.year}</span>
                  <span aria-hidden style={{ width: "3px", height: "3px", borderRadius: "9999px", background: "#a78bfa" }} />
                  <span>Project Detail</span>
                </motion.div>

                {/* Title */}
                <motion.h2
                  id="project-modal-title"
                  variants={itemVariants}
                  className="font-bold tracking-tight"
                  style={{
                    fontSize: "clamp(1.5rem, 3vw, 2.1rem)",
                    lineHeight: 1.05,
                    marginBottom: "10px",
                    backgroundImage:
                      "linear-gradient(92deg, #ffffff 0%, #d8c9ff 55%, #a78bfa 100%)",
                    WebkitBackgroundClip: "text",
                    backgroundClip: "text",
                    color: "transparent",
                  }}
                >
                  {project.title}
                </motion.h2>

                {/* Hairline */}
                <motion.div
                  variants={itemVariants}
                  aria-hidden
                  style={{
                    width: "60px",
                    height: "1px",
                    marginBottom: "14px",
                    background:
                      "linear-gradient(90deg, rgba(167,139,250,0.6), transparent)",
                  }}
                />

                {/* Description */}
                <motion.p
                  variants={itemVariants}
                  style={{
                    maxWidth: "70ch",
                    fontSize: "0.88rem",
                    lineHeight: 1.55,
                    color: "rgba(232,230,245,0.88)",
                    marginBottom: "18px",
                  }}
                >
                  {project.overview || project.desc}
                </motion.p>

                {/* Features */}
                {project.features && project.features.length > 0 && (
                  <motion.section variants={itemVariants} style={{ marginBottom: "18px" }}>
                    <SectionLabel>Key Features</SectionLabel>
                    <ul style={{ display: "grid", gridTemplateColumns: "repeat(2, minmax(0, 1fr))", gap: "6px 20px", marginTop: "10px" }}>
                      {project.features.map((f) => (
                        <li
                          key={f}
                          style={{
                            display: "flex",
                            alignItems: "flex-start",
                            gap: "8px",
                            fontSize: "0.8rem",
                            lineHeight: 1.4,
                            color: "rgba(220,217,238,0.85)",
                          }}
                        >
                          <span
                            style={{
                              width: "16px",
                              height: "16px",
                              borderRadius: "9999px",
                              flexShrink: 0,
                              marginTop: "1px",
                              background:
                                "linear-gradient(135deg, rgba(167,139,250,0.25), rgba(167,139,250,0.05))",
                              border: "1px solid rgba(167,139,250,0.35)",
                              display: "inline-flex",
                              alignItems: "center",
                              justifyContent: "center",
                              color: "#c4b5fd",
                            }}
                          >
                            <CheckIcon style={{ width: "8px", height: "8px" }} />
                          </span>
                          {f}
                        </li>
                      ))}
                    </ul>
                  </motion.section>
                )}

                {/* Tech stack */}
                <motion.section variants={itemVariants} style={{ marginBottom: "18px" }}>
                  <SectionLabel>Tech Stack</SectionLabel>
                  <div style={{ display: "flex", flexWrap: "wrap", gap: "6px", marginTop: "10px" }}>
                    {project.stack.map((tech) => (
                      <span
                        key={tech}
                        style={{
                          fontSize: "11px",
                          fontWeight: 500,
                          letterSpacing: "0.04em",
                          color: "#e8e6f5",
                          padding: "5px 11px",
                          borderRadius: "9999px",
                          background:
                            "linear-gradient(180deg, rgba(34,26,62,0.85) 0%, rgba(20,15,40,0.85) 100%)",
                          border: "1px solid rgba(167,139,250,0.25)",
                          boxShadow:
                            "inset 0 1px 0 rgba(255,255,255,0.06), 0 4px 12px -6px rgba(0,0,0,0.4)",
                        }}
                      >
                        {tech}
                      </span>
                    ))}
                  </div>
                </motion.section>

                {/* Links */}
                {project.links && (project.links.live || project.links.github || project.links.linkedin) && (
                  <motion.div
                    variants={itemVariants}
                    style={{ display: "flex", flexWrap: "wrap", gap: "12px", marginTop: "8px" }}
                  >
                    {project.links.live && (
                      <a
                        href={project.links.live}
                        target="_blank"
                        rel="noopener noreferrer"
                        style={{
                          display: "inline-flex",
                          alignItems: "center",
                          gap: "10px",
                          padding: "9px 16px",
                          borderRadius: "9999px",
                          fontSize: "13px",
                          fontWeight: 600,
                          letterSpacing: "0.04em",
                          color: "#0a0814",
                          background:
                            "linear-gradient(180deg, #fef3c7 0%, #fbbf24 100%)",
                          boxShadow:
                            "0 10px 30px -10px rgba(251,191,36,0.55), inset 0 1px 0 rgba(255,255,255,0.7)",
                          transition: "transform 0.25s ease",
                        }}
                        onMouseEnter={(e) => {
                          e.currentTarget.style.transform = "translateY(-2px)";
                        }}
                        onMouseLeave={(e) => {
                          e.currentTarget.style.transform = "translateY(0)";
                        }}
                      >
                        <span
                          aria-hidden
                          style={{
                            width: "7px",
                            height: "7px",
                            borderRadius: "9999px",
                            background: "#0a0814",
                            boxShadow: "0 0 0 3px rgba(10,8,20,0.18)",
                          }}
                        />
                        Visit Live
                        <ArrowIcon style={{ width: "12px", height: "12px" }} />
                      </a>
                    )}
                    {project.links.github && (
                      <a
                        href={project.links.github}
                        target="_blank"
                        rel="noopener noreferrer"
                        className="group"
                        style={{
                          display: "inline-flex",
                          alignItems: "center",
                          gap: "10px",
                          padding: "9px 16px",
                          borderRadius: "9999px",
                          fontSize: "13px",
                          fontWeight: 600,
                          letterSpacing: "0.04em",
                          color: "#0a0814",
                          background:
                            "linear-gradient(180deg, #f5f0ff 0%, #c4b5fd 100%)",
                          boxShadow:
                            "0 10px 30px -10px rgba(167,139,250,0.6), inset 0 1px 0 rgba(255,255,255,0.7)",
                          transition: "transform 0.25s ease",
                        }}
                        onMouseEnter={(e) => {
                          e.currentTarget.style.transform = "translateY(-2px)";
                        }}
                        onMouseLeave={(e) => {
                          e.currentTarget.style.transform = "translateY(0)";
                        }}
                      >
                        <GithubIcon style={{ width: "14px", height: "14px" }} />
                        View on GitHub
                        <ArrowIcon style={{ width: "12px", height: "12px" }} />
                      </a>
                    )}
                    {project.links.linkedin && (
                      <a
                        href={project.links.linkedin}
                        target="_blank"
                        rel="noopener noreferrer"
                        style={{
                          display: "inline-flex",
                          alignItems: "center",
                          gap: "10px",
                          padding: "9px 16px",
                          borderRadius: "9999px",
                          fontSize: "13px",
                          fontWeight: 600,
                          letterSpacing: "0.04em",
                          color: "#e8e6f5",
                          background:
                            "linear-gradient(180deg, rgba(34,26,62,0.7) 0%, rgba(16,12,30,0.7) 100%)",
                          border: "1px solid rgba(167,139,250,0.28)",
                          transition: "border-color 0.25s ease, background 0.25s ease",
                        }}
                        onMouseEnter={(e) => {
                          e.currentTarget.style.borderColor = "rgba(167,139,250,0.55)";
                          e.currentTarget.style.background =
                            "linear-gradient(180deg, rgba(42,32,76,0.85) 0%, rgba(22,16,42,0.85) 100%)";
                        }}
                        onMouseLeave={(e) => {
                          e.currentTarget.style.borderColor = "rgba(167,139,250,0.28)";
                          e.currentTarget.style.background =
                            "linear-gradient(180deg, rgba(34,26,62,0.7) 0%, rgba(16,12,30,0.7) 100%)";
                        }}
                      >
                        <LinkedinIcon style={{ width: "14px", height: "14px", color: "#7bb6ff" }} />
                        Read on LinkedIn
                        <ArrowIcon style={{ width: "12px", height: "12px" }} />
                      </a>
                    )}
                  </motion.div>
                )}
              </div>
            </motion.div>
          </motion.div>
        </motion.div>
      )}
    </AnimatePresence>
  );
};

const SectionLabel = ({ children }: { children: React.ReactNode }) => (
  <div style={{ display: "flex", alignItems: "center", gap: "12px" }}>
    <span
      aria-hidden
      style={{
        display: "inline-block",
        width: "24px",
        height: "1px",
        background: "rgba(167,139,250,0.6)",
      }}
    />
    <span
      style={{
        fontSize: "10px",
        fontWeight: 600,
        letterSpacing: "0.32em",
        textTransform: "uppercase",
        color: "#8a86a0",
      }}
    >
      {children}
    </span>
  </div>
);

export default ProjectModal;
```

---

## components/ui/project-showcase.tsx

**File Path**: `components/ui/project-showcase.tsx` | **Lines**: 239

```tsx
"use client";

import type React from "react";

import Image from "next/image";
import { useState, useRef, useEffect } from "react";
import { ArrowUpRight } from "lucide-react";

interface Project {
  title: string;
  description: string;
  year: string;
  link: string;
  image: string;
}

const projects: Project[] = [
  {
    title: "ShikshaShakti.AI",
    description:
      "Offline-first adaptive learning platform mapping 233 chapters & 157 prerequisite links (₹2L DST-NIDHI grant, TRL 4).",
    year: "2025",
    link: "https://drive.google.com/file/d/1KB5ZEOAgdl6hEC4cCXVQ1u9I0FcxkGHx/view",
    image: "/assets/carousel/carousel-33.webp",
  },
  {
    title: "PackEdge",
    description:
      "PKD packaging redesign for Godrej Interio modeling ₹47.5L annual savings, 33% freight cut & 1st place at IIT Bombay.",
    year: "2025",
    link: "https://drive.google.com/file/d/198jU7tjaPgLchEVKDLTQ7UO2OzyOkM91/view",
    image: "/assets/carousel/carousel-25.webp",
  },
  {
    title: "NextGenAML",
    description:
      "Real-time GNN + XGBoost + FATF AML screening at <12ms latency & 0.78 ROC-AUC (TCS Foundation Winner, NIT Trichy).",
    year: "2025",
    link: "https://github.com/jay2532006",
    image: "/assets/carousel/carousel-35.webp",
  },
  {
    title: "FDR-Setu",
    description:
      "RegTech infrastructure for security deposits — 55 REST endpoints, 26-table model & two-phase settlement (SIH 2026 AICTE).",
    year: "2026",
    link: "https://github.com/jay2532006",
    image: "/assets/carousel/carousel-32.webp",
  },
  {
    title: "CryptoTrace LEA",
    description:
      "Multi-chain crypto forensics & 7-component risk workspace for law enforcement — 129/129 tests passing (MHA PS 26183).",
    year: "2026",
    link: "https://github.com/jay2532006",
    image: "/assets/carousel/carousel-10.webp",
  },
  {
    title: "Real-time Fraud Alerts",
    description:
      "Transaction defence system pausing risky payments & triggering multilingual Sarvam AI voice verification calls (2× Finalist).",
    year: "2026",
    link: "https://www.linkedin.com/in/jay-parmar-ai",
    image: "/assets/carousel/carousel-24.webp",
  },
];

export function ProjectShowcase() {
  const [hoveredIndex, setHoveredIndex] = useState<number | null>(null);
  const [mousePosition, setMousePosition] = useState({ x: 0, y: 0 });
  const [smoothPosition, setSmoothPosition] = useState({ x: 0, y: 0 });
  const [isVisible, setIsVisible] = useState(false);
  const containerRef = useRef<HTMLDivElement>(null);
  const animationRef = useRef<number | null>(null);

  useEffect(() => {
    const lerp = (start: number, end: number, factor: number) => {
      return start + (end - start) * factor;
    };

    const animate = () => {
      setSmoothPosition((prev) => ({
        x: lerp(prev.x, mousePosition.x, 0.15),
        y: lerp(prev.y, mousePosition.y, 0.15),
      }));
      animationRef.current = requestAnimationFrame(animate);
    };

    animationRef.current = requestAnimationFrame(animate);

    return () => {
      if (animationRef.current) {
        cancelAnimationFrame(animationRef.current);
      }
    };
  }, [mousePosition]);

  const handleMouseMove = (e: React.MouseEvent) => {
    if (containerRef.current) {
      const rect = containerRef.current.getBoundingClientRect();
      setMousePosition({
        x: e.clientX - rect.left,
        y: e.clientY - rect.top,
      });
    }
  };

  const handleMouseEnter = (index: number) => {
    setHoveredIndex(index);
    setIsVisible(true);
  };

  const handleMouseLeave = () => {
    setHoveredIndex(null);
    setIsVisible(false);
  };

  return (
    <section
      id="flagship"
      ref={containerRef}
      onMouseMove={handleMouseMove}
      className="relative w-full mx-auto px-8 py-24 flex flex-col items-center justify-center scroll-mt-12"
    >
      <h2 className="text-muted-foreground text-sm font-medium tracking-[0.3em] uppercase mb-16 text-center">
        Flagship Projects
      </h2>

      <div
        className="pointer-events-none fixed z-50 overflow-hidden rounded-xl shadow-2xl"
        style={{
          left: containerRef.current?.getBoundingClientRect().left ?? 0,
          top: containerRef.current?.getBoundingClientRect().top ?? 0,
          transform: `translate3d(${smoothPosition.x + 20}px, ${smoothPosition.y - 100}px, 0)`,
          opacity: isVisible ? 1 : 0,
          scale: isVisible ? 1 : 0.8,
          transition:
            "opacity 0.3s cubic-bezier(0.4, 0, 0.2, 1), scale 0.3s cubic-bezier(0.4, 0, 0.2, 1)",
        }}
      >
        <div className="relative w-[280px] h-[180px] bg-secondary rounded-xl overflow-hidden">
          {projects.map((project, index) => (
            <Image
              key={project.title}
              src={project.image || "/placeholder.svg"}
              alt={project.title}
              fill
              sizes="280px"
              loading="lazy"
              className="absolute inset-0 w-full h-full object-cover transition-all duration-500 ease-out"
              style={{
                opacity: hoveredIndex === index ? 1 : 0,
                scale: hoveredIndex === index ? 1 : 1.1,
                filter: hoveredIndex === index ? "none" : "blur(10px)",
              }}
            />
          ))}
          <div className="absolute inset-0 bg-gradient-to-t from-background/20 to-transparent" />
        </div>
      </div>

      <div className="w-full max-w-2xl mx-auto flex flex-col gap-10">
        {projects.map((project, index) => (
          <a
            key={project.title}
            href={project.link}
            target="_blank"
            rel="noopener noreferrer"
            className="group block w-full"
            onMouseEnter={() => handleMouseEnter(index)}
            onMouseLeave={handleMouseLeave}
          >
            <div className="relative py-6 px-6 rounded-xl transition-all duration-300 ease-out">
              <div
                className={`
                  absolute inset-0 bg-secondary/50 rounded-xl
                  transition-all duration-300 ease-out
                  ${hoveredIndex === index ? "opacity-100 scale-100" : "opacity-0 scale-95"}
                `}
              />

              <div className="relative flex items-center justify-between gap-12">
                <div className="flex-1 min-w-0">
                  <div className="inline-flex items-center gap-3">
                    <h3 className="text-foreground font-medium text-3xl md:text-4xl tracking-tight">
                      <span className="relative">
                        {project.title}
                        <span
                          className={`
                            absolute left-0 -bottom-0.5 h-px bg-foreground
                            transition-all duration-300 ease-out
                            ${hoveredIndex === index ? "w-full" : "w-0"}
                          `}
                        />
                      </span>
                    </h3>

                    <ArrowUpRight
                      className={`
                        w-6 h-6 text-muted-foreground
                        transition-all duration-300 ease-out
                        ${
                          hoveredIndex === index
                            ? "opacity-100 translate-x-0 translate-y-0"
                            : "opacity-0 -translate-x-2 translate-y-2"
                        }
                      `}
                    />
                  </div>

                  <p
                    className={`
                      text-muted-foreground text-base mt-3 leading-relaxed
                      transition-all duration-300 ease-out
                      ${hoveredIndex === index ? "text-foreground/70" : "text-muted-foreground"}
                    `}
                  >
                    {project.description}
                  </p>
                </div>

                <span
                  className={`
                    text-sm font-mono text-muted-foreground tabular-nums shrink-0
                    transition-all duration-300 ease-out
                    ${hoveredIndex === index ? "text-foreground/60" : ""}
                  `}
                >
                  {project.year}
                </span>
              </div>
            </div>
          </a>
        ))}
      </div>
    </section>
  );
}
```

---

## components/ui/quick-connect-hero.tsx

**File Path**: `components/ui/quick-connect-hero.tsx` | **Lines**: 234

```tsx
"use client";

import React from "react";
import Image from "next/image";
import { ArrowUpRight, Sparkles, FileText, MapPin, ExternalLink } from "lucide-react";
import { SITE } from "@/constants";

export default function QuickConnectHero() {
  const channels = [
    {
      id: "linkedin",
      name: "LinkedIn",
      href: SITE.linkedin,
      target: "_blank",
      rel: "noopener noreferrer",
      logoSrc: "/assets/icons/linkedin-icon-hires.png",
      logoAlt: "LinkedIn",
      haloGradient: "radial-gradient(circle, rgba(0,119,181,0.4) 0%, rgba(10,102,194,0.1) 70%, transparent 100%)",
      borderHover: "hover:border-[#0077b5]/70",
      shadowHover: "hover:shadow-[0_20px_60px_-10px_rgba(0,119,181,0.45)]",
      textColor: "group-hover:text-[#79c5f2]",
      badge: "Network",
    },
    {
      id: "gmail",
      name: "Gmail",
      href: `mailto:${SITE.email}`,
      target: undefined,
      rel: undefined,
      logoSrc: "/assets/icons/gmail-icon-clean.png",
      logoAlt: "Gmail",
      haloGradient: "radial-gradient(circle, rgba(234,67,53,0.35) 0%, rgba(66,133,244,0.2) 50%, transparent 100%)",
      borderHover: "hover:border-[#ea4335]/70",
      shadowHover: "hover:shadow-[0_20px_60px_-10px_rgba(234,67,53,0.4)]",
      textColor: "group-hover:text-[#ff8a80]",
      badge: "Email",
    },
    {
      id: "whatsapp",
      name: "WhatsApp",
      href: `https://wa.me/917773060203?text=${encodeURIComponent(
        "Hi Jay, saw your portfolio and would love to connect!"
      )}`,
      target: "_blank",
      rel: "noopener noreferrer",
      logoSrc: "/assets/icons/whatsapp-icon-clean.png",
      logoAlt: "WhatsApp",
      haloGradient: "radial-gradient(circle, rgba(37,211,102,0.4) 0%, rgba(18,140,126,0.15) 70%, transparent 100%)",
      borderHover: "hover:border-[#25D366]/70",
      shadowHover: "hover:shadow-[0_20px_60px_-10px_rgba(37,211,102,0.45)]",
      textColor: "group-hover:text-[#69f0ae]",
      badge: "Chat",
    },
    {
      id: "resume",
      name: "Résumé PDF",
      href: SITE.resumeUrl,
      target: "_blank",
      rel: "noopener noreferrer",
      logoSrc: null, // Custom gold emblem below
      logoAlt: "Verified Résumé",
      haloGradient: "radial-gradient(circle, rgba(200,168,130,0.45) 0%, rgba(160,130,95,0.15) 70%, transparent 100%)",
      borderHover: "hover:border-[#c8a882]",
      shadowHover: "hover:shadow-[0_20px_60px_-10px_rgba(200,168,130,0.5)]",
      textColor: "group-hover:text-[#f0e2d3]",
      badge: "Dossier",
    },
  ];

  return (
    <section
      id="quick-contact"
      aria-label="Direct Channels"
      className="relative z-30 w-full bg-[#050508] border-y border-white/[0.08] px-4 sm:px-8 md:px-14 lg:px-20 py-20 sm:py-28 text-[#f5f1e8] overflow-hidden"
    >
      {/* Top & Bottom Hairline Gold Accents */}
      <div
        aria-hidden
        className="pointer-events-none absolute inset-x-0 top-0 h-px bg-gradient-to-r from-transparent via-[#c8a882]/45 to-transparent"
      />
      <div
        aria-hidden
        className="pointer-events-none absolute inset-x-0 bottom-0 h-px bg-gradient-to-r from-transparent via-white/[0.08] to-transparent"
      />

      {/* Volumetric Radial Glows */}
      <div
        aria-hidden
        className="pointer-events-none absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[850px] h-[500px] opacity-20 blur-[160px]"
        style={{
          background:
            "radial-gradient(ellipse at center, rgba(200,168,130,0.35), transparent 70%)",
        }}
      />

      <div className="relative z-10 mx-auto max-w-6xl space-y-12 sm:space-y-16">
        {/* Cinematic Minimalist Header */}
        <div className="flex flex-col md:flex-row md:items-end justify-between gap-6 pb-8 border-b border-white/[0.08]">
          <div className="space-y-3">
            <div className="flex items-center gap-3">
              <div className="inline-flex items-center gap-2 rounded-full border border-[#c8a882]/40 bg-[#c8a882]/[0.08] backdrop-blur-md px-3.5 py-1 text-[11px] font-mono uppercase tracking-[0.24em] text-[#e8d5c0] shadow-[0_0_20px_rgba(200,168,130,0.15)]">
                <Sparkles className="h-3 w-3 text-[#c8a882]" />
                <span>Executive Channels · 1-Click Direct Access</span>
              </div>
              <span className="hidden sm:inline-block h-px w-12 bg-gradient-to-r from-[#c8a882]/40 to-transparent" />
            </div>

            <h2
              className="text-3xl sm:text-4xl md:text-5xl lg:text-6xl font-normal tracking-tight text-white leading-[1.08]"
              style={{ fontFamily: "var(--font-display), Georgia, serif" }}
            >
              Connect with{" "}
              <span className="italic font-light text-transparent bg-clip-text bg-gradient-to-r from-[#ffffff] via-[#f0e2d3] to-[#c8a882]">
                Jay Parmar
              </span>
            </h2>

            <p className="text-sm sm:text-base text-[#a8a398] font-light max-w-xl">
              Tap any official channel below for instant direct communication.
            </p>
          </div>

          {/* Live Availability Pill */}
          <div className="inline-flex items-center gap-2.5 self-start md:self-auto rounded-full border border-emerald-500/35 bg-emerald-500/[0.08] backdrop-blur-md px-4 py-2 text-xs font-mono text-emerald-300 shadow-[0_0_24px_-4px_rgba(16,185,129,0.3)]">
            <span className="relative flex h-2 w-2">
              <span className="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span>
              <span className="relative inline-flex rounded-full h-2 w-2 bg-emerald-400"></span>
            </span>
            <span>Live &amp; Available for Inquiries</span>
          </div>
        </div>

        {/* 4 Majestic Visual Monoliths (Enlarged Logos Only · Edge-to-Edge Clickable) */}
        <div className="grid grid-cols-2 md:grid-cols-4 gap-4 sm:gap-6 lg:gap-8">
          {channels.map((ch) => (
            <a
              key={ch.id}
              href={ch.href}
              target={ch.target}
              rel={ch.rel}
              aria-label={`Open ${ch.name}`}
              className={`group relative rounded-3xl border border-white/[0.12] ${ch.borderHover} bg-gradient-to-b from-white/[0.05] via-white/[0.015] to-black/75 backdrop-blur-2xl p-6 sm:p-8 flex flex-col items-center justify-center min-h-[200px] sm:min-h-[240px] md:min-h-[270px] transition-all duration-300 hover:-translate-y-3 hover:scale-[1.04] ${ch.shadowHover} active:scale-95 cursor-pointer overflow-hidden`}
            >
              {/* Top specular reflection sweep */}
              <div
                aria-hidden
                className="pointer-events-none absolute inset-x-0 top-0 h-px bg-gradient-to-r from-transparent via-white/40 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"
              />

              {/* Bespoke Volumetric Brand Glow behind the logo */}
              <div
                aria-hidden
                className="pointer-events-none absolute inset-0 flex items-center justify-center"
              >
                <div
                  className="w-36 h-36 sm:w-44 sm:h-44 rounded-full blur-2xl opacity-40 group-hover:opacity-90 group-hover:scale-125 transition-all duration-500"
                  style={{ background: ch.haloGradient }}
                />
              </div>

              {/* Centered Enlarged Logo */}
              <div className="relative z-10 flex flex-col items-center justify-center space-y-4 sm:space-y-5">
                {ch.logoSrc ? (
                  <div className="relative w-20 h-20 sm:w-24 sm:h-24 md:w-28 md:h-28 flex items-center justify-center transition-transform duration-300 group-hover:scale-110">
                    <Image
                      src={ch.logoSrc}
                      alt={ch.logoAlt}
                      width={112}
                      height={112}
                      className="object-contain filter drop-shadow-[0_8px_24px_rgba(0,0,0,0.6)]"
                      priority
                    />
                  </div>
                ) : (
                  /* Luxury 24K Gold Dossier Seal for Résumé */
                  <div className="relative w-20 h-20 sm:w-24 sm:h-24 md:w-28 md:h-28 rounded-2xl bg-gradient-to-br from-[#e0cfb8] via-[#c8a882] to-[#8c6d48] p-0.5 shadow-[0_8px_30px_rgba(200,168,130,0.35)] transition-transform duration-300 group-hover:scale-110">
                    <div className="w-full h-full rounded-[14px] bg-[#0c0c0e] flex flex-col items-center justify-center text-[#c8a882] group-hover:text-white transition-colors">
                      <FileText className="h-10 w-10 sm:h-12 sm:w-12 drop-shadow-[0_0_12px_rgba(200,168,130,0.6)]" />
                      <span className="mt-1 text-[10px] font-mono font-bold tracking-widest uppercase text-[#c8a882]">
                        PDF
                      </span>
                    </div>
                  </div>
                )}

                {/* Minimalist Brand Name with redirect arrow */}
                <div className="flex items-center gap-1.5 text-xs sm:text-sm font-mono tracking-wider uppercase text-neutral-400 transition-colors">
                  <span className={`${ch.textColor} font-semibold transition-colors`}>
                    {ch.name}
                  </span>
                  <ArrowUpRight className="h-3.5 w-3.5 opacity-60 group-hover:opacity-100 group-hover:translate-x-0.5 group-hover:-translate-y-0.5 transition-all" />
                </div>
              </div>
            </a>
          ))}
        </div>

        {/* Micro-Telemetry Strip */}
        <div className="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 pt-6 border-t border-white/[0.08] text-xs font-mono text-[#9c978e]">
          <div className="flex items-center gap-2">
            <MapPin className="h-3.5 w-3.5 text-[#c8a882] shrink-0" />
            <span>Bhilai, Chhattisgarh, India · Indian Institute of Management Bangalore (DBE)</span>
          </div>

          <div className="flex flex-wrap items-center gap-5 sm:gap-6">
            <a
              href={SITE.github}
              target="_blank"
              rel="noopener noreferrer"
              className="hover:text-white transition-colors flex items-center gap-1"
            >
              <span>GitHub</span>
              <ExternalLink className="h-3 w-3 opacity-60" />
            </a>
            <a
              href="/articles"
              className="text-[#c8a882] hover:text-white transition-colors flex items-center gap-1 font-semibold"
            >
              <span>13 Field Essays</span>
              <ExternalLink className="h-3 w-3 opacity-80" />
            </a>
            <a
              href="#dossier-overview"
              className="hover:text-white transition-colors flex items-center gap-1"
            >
              <span>Executive Dossier ↓</span>
            </a>
          </div>
        </div>
      </div>
    </section>
  );
}
```

---

## components/ui/resume-dossier.tsx

**File Path**: `components/ui/resume-dossier.tsx` | **Lines**: 708

```tsx
"use client";

import React from "react";
import Link from "next/link";
import Image from "next/image";
import {
  ArrowUpRight,
  Award,
  BookOpen,
  Briefcase,
  CheckCircle2,
  ChevronRight,
  ExternalLink,
  FileText,
  GraduationCap,
  Layers,
  Mail,
  MapPin,
  Phone,
  Sparkles,
  TrendingUp,
  ShieldCheck,
  Cpu,
} from "lucide-react";
import {
  ACHIEVEMENTS,
  AIMS,
  CERTIFICATES,
  EDUCATION,
  EXPERIENCE,
  PROJECTS,
  SITE,
  SKILL_CATEGORIES,
} from "@/constants";

export default function ResumeDossier() {
  return (
    <div
      id="dossier"
      className="relative w-full bg-[#070709] text-[#f5f1e8] selection:bg-[#c8a882] selection:text-black overflow-hidden"
    >
      {/* Ambient Atmospheric Lighting - Expansive across full monitor width */}
      <div
        aria-hidden
        className="pointer-events-none absolute top-0 left-1/2 -translate-x-1/2 w-full max-w-[1920px] h-[800px] opacity-25 blur-[180px]"
        style={{
          background:
            "radial-gradient(ellipse at top, rgba(200,168,130,0.3), transparent 70%)",
        }}
      />
      <div
        aria-hidden
        className="pointer-events-none absolute top-[30%] -left-48 w-[800px] h-[800px] opacity-15 blur-[220px]"
        style={{
          background:
            "radial-gradient(circle, rgba(167,139,250,0.25), transparent 70%)",
        }}
      />
      <div
        aria-hidden
        className="pointer-events-none absolute top-[65%] -right-48 w-[800px] h-[800px] opacity-20 blur-[220px]"
        style={{
          background:
            "radial-gradient(circle, rgba(200,168,130,0.25), transparent 70%)",
        }}
      />

      {/* Floating Chapter Index Nav - Desktop */}
      <nav
        aria-label="Dossier section navigation"
        className="sticky top-6 z-40 mx-auto max-w-max hidden md:flex items-center gap-2 rounded-full border border-white/15 bg-[#0d0d12]/90 backdrop-blur-2xl px-6 py-3 shadow-[0_20px_50px_rgba(0,0,0,0.8)]"
      >
        <span className="text-[11px] font-mono uppercase tracking-[0.25em] text-[#c8a882] pr-3 border-r border-white/10 font-bold">
          Dossier Index
        </span>
        <a
          href="#dossier-overview"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Overview
        </a>
        <a
          href="#dossier-education"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Academics
        </a>
        <a
          href="#dossier-experience"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Experience (4)
        </a>
        <a
          href="#dossier-builds"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Systems (6)
        </a>
        <a
          href="#dossier-honors"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Honors
        </a>
        <a
          href="#dossier-credentials"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Certificates
        </a>
        <a
          href="#dossier-skills"
          className="text-xs font-mono text-neutral-400 hover:text-white px-3 py-1 rounded-full transition-colors"
        >
          Capabilities
        </a>
      </nav>

      {/* Floating Chapter Index Nav - Mobile Scrollable Strip */}
      <nav
        aria-label="Dossier mobile navigation"
        className="sticky top-4 z-40 mx-3 flex md:hidden items-center gap-2 rounded-full border border-white/15 bg-[#0d0d12]/95 backdrop-blur-2xl px-3 py-2 overflow-x-auto [scrollbar-width:none] [&::-webkit-scrollbar]:hidden shadow-2xl"
      >
        <span className="text-[10px] font-mono uppercase tracking-[0.18em] text-[#c8a882] shrink-0 font-bold pl-1 pr-2 border-r border-white/10">
          Index
        </span>
        <a href="#dossier-overview" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Overview
        </a>
        <a href="#dossier-education" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Academics
        </a>
        <a href="#dossier-experience" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Experience
        </a>
        <a href="#dossier-builds" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Systems
        </a>
        <a href="#dossier-honors" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Honors
        </a>
        <a href="#dossier-credentials" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Certs
        </a>
        <a href="#dossier-skills" className="text-[11px] font-mono text-neutral-300 hover:text-white active:scale-95 active:bg-white/15 px-2.5 py-1 rounded-full bg-white/[0.04] shrink-0 transition-all duration-150">
          Skills
        </a>
      </nav>

      {/* Main Container - EXPANDED to full monitor width (up to 1920px fluid) with phone-friendly padding */}
      <div className="relative z-10 w-full max-w-[1880px] mx-auto px-4 sm:px-8 md:px-14 lg:px-16 xl:px-24 2xl:px-32 py-16 sm:py-24 md:py-40 space-y-24 sm:space-y-36 md:space-y-56">

        {/* =====================================================================
            CHAPTER 01: EXECUTIVE PROFILE & HERO (LEFT + RIGHT FULL-WIDTH)
        ===================================================================== */}
        <section id="dossier-overview" className="scroll-mt-32 space-y-16">
          <div className="grid grid-cols-1 lg:grid-cols-12 gap-12 xl:gap-20 items-center">
            
            {/* Left Column: Headline, Bio, Stats, and Contact Links */}
            <div className="lg:col-span-7 xl:col-span-7 space-y-8">
              <div className="inline-flex items-center gap-3 rounded-full border border-[#c8a882]/40 bg-[#c8a882]/10 px-5 py-2 text-xs font-mono uppercase tracking-[0.26em] text-[#f2e1ce]">
                <Sparkles className="h-3.5 w-3.5 text-[#c8a882]" />
                Curriculum Vitae · Executive Dossier
              </div>

              <h1 className="text-4xl sm:text-6xl lg:text-7xl xl:text-8xl font-bold tracking-tight text-white leading-[1.02]">
                Turning complex data into{" "}
                <span className="text-transparent bg-clip-text bg-gradient-to-r from-white via-[#f0e2d3] to-[#c8a882]">
                  decisions that move.
                </span>
              </h1>

              <div className="space-y-5 text-lg sm:text-xl text-[#d8d3c8] leading-relaxed font-light">
                <p>
                  I’m <strong className="text-white font-medium">Jay Parmar</strong> — an AI/ML builder, quantitative finance analyst, and product leader pursuing BBA in Digital Business &amp; Entrepreneurship at <span className="text-white font-medium">IIM Bangalore</span>.
                </p>
                <p>
                  I build useful systems, rally ambitious teams around high-rigor engineering, and stay with the work until it creates verifiable outcomes — from &lt;12ms anti-money laundering screening to offline diagnostic education engines and ₹47.5L supply chain redesigns.
                </p>
              </div>

              {/* Verified Contact & Location Row */}
              <div className="flex flex-wrap items-center gap-x-8 gap-y-3 pt-2 text-sm font-mono text-[#b8b3a8]">
                <span className="inline-flex items-center gap-2">
                  <MapPin className="h-4 w-4 text-[#c8a882]" />
                  {SITE.location}
                </span>
                <a
                  href={`mailto:${SITE.email}`}
                  className="inline-flex items-center gap-2 hover:text-white transition-colors"
                >
                  <Mail className="h-4 w-4 text-[#c8a882]" />
                  {SITE.email}
                </a>
                <a
                  href="tel:+917773060203"
                  className="inline-flex items-center gap-2 hover:text-white transition-colors"
                >
                  <Phone className="h-4 w-4 text-[#c8a882]" />
                  {SITE.phone}
                </a>
              </div>

              {/* Direct Action Links */}
              <div className="flex flex-col sm:flex-row items-stretch sm:items-center gap-4 sm:gap-5 pt-3">
                <a
                  href={SITE.resumeUrl}
                  target="_blank"
                  rel="noopener noreferrer"
                  className="w-full sm:w-auto inline-flex items-center justify-center gap-3 rounded-full bg-[#c8a882] px-6 sm:px-8 py-3.5 sm:py-4 text-xs font-mono font-bold uppercase tracking-[0.18em] text-[#0a0a0c] hover:bg-white shadow-[0_15px_35px_-10px_rgba(200,168,130,0.5)] transition-all hover:scale-[1.02]"
                >
                  <FileText className="h-4 w-4" />
                  Download Complete Resume (PDF)
                  <ArrowUpRight className="h-4 w-4" />
                </a>
                <Link
                  href="/articles"
                  className="w-full sm:w-auto inline-flex items-center justify-center gap-3 rounded-full border border-white/20 bg-white/[0.04] px-6 sm:px-8 py-3.5 sm:py-4 text-xs font-mono uppercase tracking-[0.18em] text-white hover:border-[#c8a882] hover:bg-white/[0.08] transition-all hover:scale-[1.02]"
                >
                  <BookOpen className="h-4 w-4 text-[#c8a882]" />
                  Read 13 Field Essays
                  <ArrowUpRight className="h-4 w-4" />
                </Link>
              </div>

              {/* 4 Quantitative Impact Highlights */}
              <div className="grid grid-cols-2 sm:grid-cols-4 gap-4 pt-6 border-t border-white/10">
                <div className="p-4 rounded-2xl bg-white/[0.03] border border-white/10">
                  <p className="text-2xl sm:text-3xl font-mono font-bold text-white">₹47.5L</p>
                  <p className="text-xs font-mono text-[#c8a882] uppercase tracking-wider mt-1">Projected Savings</p>
                </div>
                <div className="p-4 rounded-2xl bg-white/[0.03] border border-white/10">
                  <p className="text-2xl sm:text-3xl font-mono font-bold text-white">233</p>
                  <p className="text-xs font-mono text-[#c8a882] uppercase tracking-wider mt-1">Chapters Mapped</p>
                </div>
                <div className="p-4 rounded-2xl bg-white/[0.03] border border-white/10">
                  <p className="text-2xl sm:text-3xl font-mono font-bold text-white">&lt;12ms</p>
                  <p className="text-xs font-mono text-[#c8a882] uppercase tracking-wider mt-1">AML Latency</p>
                </div>
                <div className="p-4 rounded-2xl bg-white/[0.03] border border-white/10">
                  <p className="text-2xl sm:text-3xl font-mono font-bold text-white">3×</p>
                  <p className="text-xs font-mono text-[#c8a882] uppercase tracking-wider mt-1">National Podiums</p>
                </div>
              </div>
            </div>

            {/* Right Column: Full-Width Executive Showcase utilizing the entire right space */}
            <div className="lg:col-span-5 xl:col-span-5 flex flex-col items-center lg:items-end justify-center w-full">
              <figure className="relative w-full max-w-[540px] rounded-3xl overflow-hidden border border-white/15 bg-gradient-to-b from-[#18181c] to-[#0c0c10] shadow-[0_30px_90px_-20px_rgba(0,0,0,0.9)] group">
                <div className="relative aspect-[4/5] w-full">
                  <Image
                    src={SITE.portraitUrl}
                    alt="Jay Parmar · Indian Institute of Management Bangalore"
                    fill
                    loading="lazy"
                    sizes="(max-width: 1024px) 100vw, 540px"
                    className="object-cover object-center transition-transform duration-700 group-hover:scale-105"
                  />
                  <div className="absolute inset-0 bg-gradient-to-t from-[#0c0c10] via-transparent to-transparent opacity-85" />
                </div>
                
                {/* Executive Details Strip */}
                <figcaption className="p-8 border-t border-white/10 space-y-4 bg-[#0e0e13]">
                  <div className="flex items-center justify-between">
                    <div>
                      <p className="text-xl font-bold text-white">Jay Parmar</p>
                      <p className="text-xs font-mono text-[#c8a882] tracking-wider uppercase mt-0.5">
                        IIM Bangalore · BBA DBE (2026—2029)
                      </p>
                    </div>
                    <span className="text-xs font-mono tracking-widest uppercase bg-[#c8a882]/15 text-[#f0e2d3] px-3.5 py-1.5 rounded-full border border-[#c8a882]/40 font-semibold">
                      Verified
                    </span>
                  </div>

                  <div className="grid grid-cols-2 gap-3 pt-2 text-xs font-mono text-[#b0aba0] border-t border-white/10">
                    <div>
                      <span className="text-[#8c877e] block">Selectivity:</span>
                      <strong className="text-white">Top 20 / 70,000+</strong>
                    </div>
                    <div>
                      <span className="text-[#8c877e] block">Research:</span>
                      <strong className="text-white">IIT Guwahati AI Intern</strong>
                    </div>
                    <div>
                      <span className="text-[#8c877e] block">Venture:</span>
                      <strong className="text-white">₹2L DST-NIDHI Grant</strong>
                    </div>
                    <div>
                      <span className="text-[#8c877e] block">Hackathons:</span>
                      <strong className="text-white">IIT Bombay, TCS Win</strong>
                    </div>
                  </div>
                </figcaption>
              </figure>
            </div>

          </div>
        </section>


        {/* =====================================================================
            CHAPTER 02: ACADEMIC RIGOR & PHILOSOPHY (LEFT + RIGHT FULL SPREAD)
        ===================================================================== */}
        <section id="dossier-education" className="scroll-mt-32 space-y-16">
          <div className="space-y-4">
            <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
              01 / Academic Rigor &amp; Philosophy
            </span>
            <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
              Institutional Foundations &amp; Guiding Aims
            </h2>
            <p className="text-base sm:text-xl text-[#b8b3a8] max-w-4xl leading-relaxed font-light">
              Grounding technology in institutional discipline, quantitative finance, and high-impact public service.
            </p>
          </div>

          <div className="grid grid-cols-1 lg:grid-cols-12 gap-8 xl:gap-12 items-stretch">
            
            {/* Left: IIM Bangalore Dedicated Feature Card */}
            {EDUCATION.map((edu) => (
              <div
                key={edu.degree}
                className="lg:col-span-5 rounded-3xl border border-white/15 bg-gradient-to-br from-[#16161a] via-[#111114] to-[#0a0a0d] p-10 md:p-14 flex flex-col justify-between shadow-2xl space-y-10"
              >
                <div className="space-y-8">
                  <div className="flex items-center justify-between">
                    <span className="inline-flex items-center gap-2.5 text-xs font-mono uppercase tracking-[0.2em] text-[#c8a882] font-semibold">
                      <GraduationCap className="h-4 w-4" />
                      Higher Education
                    </span>
                    <span className="rounded-full bg-white/[0.06] border border-white/10 px-4 py-1.5 text-xs font-mono text-[#e5e0d8]">
                      {edu.period}
                    </span>
                  </div>

                  <div>
                    <h3 className="text-2xl sm:text-3xl lg:text-4xl font-bold text-white leading-tight">
                      {edu.degree}
                    </h3>
                    <p className="text-base sm:text-lg text-[#c8a882] font-mono mt-3">
                      {edu.institution}
                    </p>
                  </div>
                </div>

                <div className="border-t border-white/10 pt-8 space-y-5">
                  <p className="text-xs font-mono uppercase tracking-[0.22em] text-[#9c978e]">
                    Selectivity &amp; Distinctions:
                  </p>
                  <ul className="space-y-4 text-sm sm:text-base text-[#e5e0d8] leading-relaxed">
                    {edu.highlights.map((h) => (
                      <li key={h} className="flex items-start gap-3.5">
                        <CheckCircle2 className="h-5 w-5 text-[#c8a882] shrink-0 mt-0.5" />
                        <span>{h}</span>
                      </li>
                    ))}
                  </ul>
                </div>
              </div>
            ))}

            {/* Right: Three Guiding Aims Spanning across the Right Space */}
            <div className="lg:col-span-7 grid grid-cols-1 gap-6 xl:gap-8">
              {AIMS.map((aim) => (
                <div
                  key={aim.index}
                  className="rounded-3xl border border-white/12 bg-[#101014] p-8 md:p-12 flex flex-col sm:flex-row sm:items-start gap-8 hover:border-[#c8a882]/50 transition-all shadow-xl"
                >
                  <span className="text-4xl sm:text-5xl font-mono font-bold text-[#c8a882] shrink-0">
                    {aim.index}
                  </span>
                  <div className="space-y-3">
                    <h4 className="text-xl sm:text-2xl font-bold text-white">
                      {aim.title}
                    </h4>
                    <p className="text-base text-[#b8b3a8] leading-relaxed font-light">
                      {aim.description}
                    </p>
                  </div>
                </div>
              ))}
            </div>

          </div>
        </section>


        {/* =====================================================================
            CHAPTER 03: PROFESSIONAL EXPERIENCE (4 EXPANSIVE TIMELINE CARDS ACROSS FULL WIDTH)
        ===================================================================== */}
        <section id="dossier-experience" className="scroll-mt-32 space-y-16">
          <div className="flex flex-col md:flex-row md:items-end justify-between gap-6 border-b border-white/10 pb-8">
            <div className="space-y-4">
              <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
                02 / Proven Track Record
              </span>
              <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
                Professional Experience &amp; Leadership
              </h2>
              <p className="text-base sm:text-xl text-[#b8b3a8] max-w-3xl leading-relaxed font-light">
                4 verified institutional and founder engagements with verified budgets, data pipelines, and corporate stakeholders.
              </p>
            </div>
            <span className="text-xs font-mono uppercase tracking-widest text-[#8e897f]">
              2024 — Present
            </span>
          </div>

          <div className="grid grid-cols-1 lg:grid-cols-2 gap-8 xl:gap-12">
            {EXPERIENCE.map((exp) => (
              <article
                key={`${exp.role}-${exp.organization}`}
                className="rounded-3xl border border-white/12 bg-gradient-to-b from-[#131318] to-[#0a0a0e] p-8 sm:p-12 md:p-14 flex flex-col justify-between hover:border-[#c8a882]/50 transition-all shadow-2xl space-y-8"
              >
                <div className="space-y-6">
                  <div className="flex flex-wrap items-center justify-between gap-3">
                    <span className="rounded-full bg-[#c8a882]/15 border border-[#c8a882]/40 px-4 py-1.5 text-xs font-mono uppercase tracking-wider text-[#f0e2d3] font-medium">
                      {exp.period}
                    </span>
                    <span className="text-xs font-mono text-[#9c978e]">
                      {exp.location}
                    </span>
                  </div>

                  <div>
                    <h3 className="text-2xl sm:text-3xl font-bold text-white leading-tight">
                      {exp.role}
                    </h3>
                    <p className="text-base sm:text-lg font-mono text-[#c8a882] mt-2">
                      {exp.organization}
                    </p>
                  </div>

                  <p className="text-base sm:text-lg text-[#d4cfc5] leading-relaxed pt-2 font-light">
                    {exp.summary}
                  </p>
                </div>

                <div className="border-t border-white/10 pt-6 space-y-3.5">
                  {exp.bullets.map((bullet) => (
                    <div key={bullet} className="flex items-start gap-3.5 text-sm sm:text-base text-[#b8b3a8] leading-relaxed">
                      <span className="text-[#c8a882] text-lg leading-none mt-0.5">•</span>
                      <span>{bullet}</span>
                    </div>
                  ))}
                </div>
              </article>
            ))}
          </div>
        </section>


        {/* =====================================================================
            CHAPTER 04: SHIPPED SYSTEMS & CASE MODELS (3-COLUMN FULL-WIDTH SPREAD)
        ===================================================================== */}
        <section id="dossier-builds" className="scroll-mt-32 space-y-16">
          <div className="flex flex-col md:flex-row md:items-end justify-between gap-6 border-b border-white/10 pb-8">
            <div className="space-y-4">
              <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
                03 / Engineering &amp; Products
              </span>
              <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
                6 Shipped Systems &amp; Case Studies
              </h2>
              <p className="text-base sm:text-xl text-[#b8b3a8] max-w-4xl leading-relaxed font-light">
                Quantitative supply chain redesigns, anti-money laundering graphs, adaptive EdTech, and regulatory infrastructure.
              </p>
            </div>
            <span className="text-xs font-mono uppercase tracking-widest text-[#8e897f]">
              Validated Proof
            </span>
          </div>

          {/* 3 Columns across monitor to utilize full width with NO right blank space */}
          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 xl:gap-10">
            {PROJECTS.map((project) => (
              <div
                key={project.id}
                className="rounded-3xl border border-white/12 bg-gradient-to-b from-[#131317] to-[#09090c] p-8 sm:p-10 flex flex-col justify-between hover:border-[#c8a882]/50 transition-all shadow-2xl space-y-8"
              >
                <div className="space-y-6">
                  <div className="flex flex-wrap items-center justify-between gap-3">
                    <span className="text-xs font-mono uppercase tracking-widest text-[#c8a882] font-semibold">
                      {project.category}
                    </span>
                    <span className="text-xs font-mono text-[#8e897f]">
                      {project.year}
                    </span>
                  </div>

                  <div className="space-y-3">
                    <h3 className="text-2xl sm:text-3xl font-bold text-white tracking-tight leading-snug">
                      {project.title}
                    </h3>
                    <div className="inline-block rounded-xl border border-[#c8a882]/40 bg-[#c8a882]/15 px-4 py-2 text-xs sm:text-sm font-mono font-medium text-[#f5e6d6]">
                      {project.headlineMetric}
                    </div>
                  </div>

                  <p className="text-sm sm:text-base text-[#d4cfc5] leading-relaxed font-light">
                    {project.summary}
                  </p>

                  <div className="space-y-3 border-t border-white/10 pt-5">
                    <p className="text-xs font-mono uppercase tracking-wider text-[#9c978e]">
                      Key Evidence:
                    </p>
                    <ul className="space-y-2.5 text-xs sm:text-sm text-[#b8b3a8]">
                      {project.metrics.map((m) => (
                        <li key={m} className="flex items-center gap-2.5">
                          <span className="h-1.5 w-1.5 rounded-full bg-[#c8a882] shrink-0" />
                          <span>{m}</span>
                        </li>
                      ))}
                    </ul>
                  </div>
                </div>

                <div className="space-y-5 border-t border-white/10 pt-5">
                  <div className="flex flex-wrap gap-2">
                    {project.stack.map((t) => (
                      <span
                        key={t}
                        className="rounded-lg border border-white/10 bg-white/[0.04] px-3 py-1 text-xs font-mono text-[#d4cfc5]"
                      >
                        {t}
                      </span>
                    ))}
                  </div>

                  <div className="flex items-center justify-between pt-2">
                    {project.caseDeckUrl ? (
                      <a
                        href={project.caseDeckUrl}
                        target="_blank"
                        rel="noopener noreferrer"
                        className="inline-flex items-center gap-2 text-xs font-mono font-bold uppercase tracking-[0.16em] text-[#c8a882] hover:text-white transition-colors"
                      >
                        Open Case Deck
                        <ExternalLink className="h-3.5 w-3.5" />
                      </a>
                    ) : (
                      <span className="text-xs font-mono uppercase tracking-[0.12em] text-[#8e897f]">
                        {project.badge}
                      </span>
                    )}

                    <span className="text-xs font-mono text-[#8e897f]">
                      {project.year}
                    </span>
                  </div>
                </div>
              </div>
            ))}
          </div>
        </section>


        {/* =====================================================================
            CHAPTER 05: NATIONAL HONORS & RANKINGS (3-COLUMN FULL-WIDTH)
        ===================================================================== */}
        <section id="dossier-honors" className="scroll-mt-32 space-y-16">
          <div className="space-y-4">
            <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
              04 / Recognition
            </span>
            <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
              National Honors &amp; Rankings
            </h2>
            <p className="text-base sm:text-xl text-[#b8b3a8] max-w-3xl leading-relaxed font-light">
              Competitive victories and national selections across premier institutions.
            </p>
          </div>

          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 xl:gap-10">
            {ACHIEVEMENTS.map((ach) => (
              <div
                key={ach.index}
                className="rounded-3xl border border-white/12 bg-[#111116] p-8 sm:p-10 flex flex-col justify-between hover:border-[#c8a882]/45 transition-all shadow-xl space-y-6"
              >
                <div className="space-y-4">
                  <span className="text-3xl sm:text-4xl font-mono font-bold text-[#c8a882]">
                    {ach.index}
                  </span>
                  <h3 className="text-xl font-bold text-white leading-snug">
                    {ach.title}
                  </h3>
                  <p className="text-xs font-mono text-[#c8a882]">
                    {ach.venue}
                  </p>
                </div>
                <p className="text-sm sm:text-base text-[#b8b3a8] leading-relaxed border-t border-white/10 pt-5 font-light">
                  {ach.detail}
                </p>
              </div>
            ))}
          </div>
        </section>


        {/* =====================================================================
            CHAPTER 06: VERIFIED CREDENTIALS & CERTIFICATES (3-COLUMN FULL SPREAD)
        ===================================================================== */}
        <section id="dossier-credentials" className="scroll-mt-32 space-y-16">
          <div className="flex flex-col md:flex-row md:items-end justify-between gap-6 border-b border-white/10 pb-8">
            <div className="space-y-4">
              <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
                05 / Verified Credentials
              </span>
              <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
                Certifications &amp; Licenses
              </h2>
              <p className="text-base sm:text-xl text-[#b8b3a8] max-w-3xl leading-relaxed font-light">
                Click any certificate to view the full verified document.
              </p>
            </div>
            <span className="text-xs font-mono uppercase tracking-widest text-[#8e897f]">
              IIT Bombay · TCS · MSME · IIT Bhilai
            </span>
          </div>

          <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 xl:gap-10">
            {CERTIFICATES.map((cert) => (
              <a
                key={cert.id}
                href={cert.image}
                target="_blank"
                rel="noopener noreferrer"
                className="group rounded-3xl overflow-hidden border border-white/15 bg-[#101014] transition-all hover:border-[#c8a882]/70 hover:-translate-y-1.5 shadow-xl"
              >
                <div className="relative aspect-[16/11] w-full overflow-hidden bg-black/50">
                  <Image
                    src={cert.image}
                    alt={cert.title}
                    fill
                    loading="lazy"
                    sizes="(max-width: 768px) 100vw, (max-width: 1200px) 50vw, 33vw"
                    className="object-cover object-center transition-transform duration-700 group-hover:scale-105"
                  />
                  <div className="absolute inset-0 bg-black/20 group-hover:bg-transparent transition-colors" />
                </div>
                <div className="p-8 space-y-2.5">
                  <h3 className="text-base sm:text-lg font-semibold text-white group-hover:text-[#c8a882] transition-colors leading-snug">
                    {cert.title}
                  </h3>
                  <div className="flex items-center justify-between text-xs font-mono text-[#9c978e] pt-1">
                    <span>{cert.issuer}</span>
                    <span>{cert.year}</span>
                  </div>
                </div>
              </a>
            ))}
          </div>
        </section>


        {/* =====================================================================
            CHAPTER 07: COMPREHENSIVE SKILLS & CAPABILITIES MATRIX
        ===================================================================== */}
        <section id="dossier-skills" className="scroll-mt-32 space-y-16 border-t border-white/10 pt-28">
          <div className="space-y-4">
            <span className="text-xs font-mono uppercase tracking-[0.3em] text-[#c8a882] font-semibold">
              06 / Tooling &amp; Stack
            </span>
            <h2 className="text-3xl sm:text-5xl md:text-6xl font-bold text-white tracking-tight">
              Comprehensive Capabilities Matrix
            </h2>
            <p className="text-base sm:text-xl text-[#b8b3a8] max-w-3xl leading-relaxed font-light">
              Structured across data modeling, financial analysis, AI architectures, engineering, and execution.
            </p>
          </div>

          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-5 gap-6 xl:gap-8">
            {SKILL_CATEGORIES.map((group) => (
              <div
                key={group.category}
                className="rounded-3xl border border-white/12 bg-[#101014] p-8 space-y-5 flex flex-col justify-between"
              >
                <div className="space-y-4">
                  <div className="flex items-center gap-3">
                    <Layers className="h-5 w-5 text-[#c8a882]" />
                    <h3 className="text-sm font-mono uppercase tracking-widest text-white font-bold">
                      {group.category}
                    </h3>
                  </div>
                  <div className="flex flex-wrap gap-2 pt-1">
                    {group.items.map((skill) => (
                      <span
                        key={skill}
                        className="rounded-lg border border-white/10 bg-white/[0.04] px-3 py-1.5 text-xs font-mono text-[#e5e0d8]"
                      >
                        {skill}
                      </span>
                    ))}
                  </div>
                </div>
              </div>
            ))}
          </div>
        </section>

      </div>
    </div>
  );
}
```

---

## components/ui/ruler-carousel.tsx

**File Path**: `components/ui/ruler-carousel.tsx` | **Lines**: 257

```tsx
"use client";

import { useState, useRef, useEffect } from "react";
import { motion } from "framer-motion";
import { Rewind, FastForward } from "lucide-react";

export interface CarouselItem {
  id: number;
  title: string;
}

interface InfiniteItem {
  id: string;
  title: string;
  originalIndex: number;
}

const createInfiniteItems = (originalItems: CarouselItem[]): InfiniteItem[] => {
  const items: InfiniteItem[] = [];
  for (let i = 0; i < 3; i++) {
    originalItems.forEach((item, index) => {
      items.push({
        id: `${i}-${item.id}`,
        title: item.title,
        originalIndex: index,
      });
    });
  }
  return items;
};

const RulerLines = ({
  top = true,
  totalLines = 100,
}: {
  top?: boolean;
  totalLines?: number;
}) => {
  const lines = [];
  const lineSpacing = 100 / (totalLines - 1);

  for (let i = 0; i < totalLines; i++) {
    const isFifth = i % 5 === 0;
    const isCenter = i === Math.floor(totalLines / 2);

    let height = "h-3";
    let color = "bg-gray-500 dark:bg-gray-400";

    if (isCenter) {
      height = "h-8";
      color = "bg-primary dark:bg-white";
    } else if (isFifth) {
      height = "h-4";
      color = "bg-primary dark:bg-white";
    }

    const positionClass = top ? "" : "bottom-0";

    lines.push(
      <div
        key={i}
        className={`absolute w-0.5 ${height} ${color} ${positionClass}`}
        style={{ left: `${i * lineSpacing}%` }}
      />
    );
  }

  return <div className="relative w-full h-8 px-4">{lines}</div>;
};

export function RulerCarousel({
  originalItems,
}: {
  originalItems: CarouselItem[];
}) {
  const infiniteItems = createInfiniteItems(originalItems);
  const itemsPerSet = originalItems.length;

  const [activeIndex, setActiveIndex] = useState(itemsPerSet + 4);
  const [isResetting, setIsResetting] = useState(false);
  const previousIndexRef = useRef(itemsPerSet + 4);

  const handleItemClick = (newIndex: number) => {
    if (isResetting) return;

    const targetOriginalIndex = newIndex % itemsPerSet;
    const possibleIndices = [
      targetOriginalIndex,
      targetOriginalIndex + itemsPerSet,
      targetOriginalIndex + itemsPerSet * 2,
    ];

    let closestIndex = possibleIndices[0];
    let smallestDistance = Math.abs(possibleIndices[0] - activeIndex);

    for (const index of possibleIndices) {
      const distance = Math.abs(index - activeIndex);
      if (distance < smallestDistance) {
        smallestDistance = distance;
        closestIndex = index;
      }
    }

    previousIndexRef.current = activeIndex;
    setActiveIndex(closestIndex);
  };

  const handlePrevious = () => {
    if (isResetting) return;
    setActiveIndex((prev) => prev - 1);
  };

  const handleNext = () => {
    if (isResetting) return;
    setActiveIndex((prev) => prev + 1);
  };

  useEffect(() => {
    if (isResetting) return;

    if (activeIndex < itemsPerSet) {
      setIsResetting(true);
      setTimeout(() => {
        setActiveIndex(activeIndex + itemsPerSet);
        setIsResetting(false);
      }, 0);
    } else if (activeIndex >= itemsPerSet * 2) {
      setIsResetting(true);
      setTimeout(() => {
        setActiveIndex(activeIndex - itemsPerSet);
        setIsResetting(false);
      }, 0);
    }
  }, [activeIndex, itemsPerSet, isResetting]);

  useEffect(() => {
    const handleKeyDown = (event: KeyboardEvent) => {
      if (isResetting) return;

      if (event.key === "ArrowLeft") {
        event.preventDefault();
        setActiveIndex((prev) => prev - 1);
      } else if (event.key === "ArrowRight") {
        event.preventDefault();
        setActiveIndex((prev) => prev + 1);
      }
    };

    window.addEventListener("keydown", handleKeyDown);
    return () => window.removeEventListener("keydown", handleKeyDown);
  }, [isResetting]);

  const centerPosition = 5;
  const targetX = -500 + (centerPosition - (activeIndex % itemsPerSet)) * 500;

  const currentPage = (activeIndex % itemsPerSet) + 1;
  const totalPages = itemsPerSet;

  return (
    <div className="w-full h-screen flex flex-col items-center justify-center bg-background dark:bg-black">
      <div className="w-full h-[200px] flex flex-col justify-center relative">
        <div className="flex items-center justify-center">
          <RulerLines top />
        </div>
        <div className="flex items-center justify-center w-full h-full relative overflow-hidden">
          <motion.div
            className="flex items-center gap-[100px]"
            animate={{
              x: isResetting ? targetX : targetX,
            }}
            transition={
              isResetting
                ? { duration: 0 }
                : {
                    type: "spring",
                    stiffness: 260,
                    damping: 20,
                    mass: 1,
                  }
            }
          >
            {infiniteItems.map((item, index) => {
              const isActive = index === activeIndex;

              return (
                <motion.button
                  key={item.id}
                  onClick={() => handleItemClick(index)}
                  className={`text-4xl md:text-6xl font-bold whitespace-nowrap cursor-pointer flex items-center justify-center ${
                    isActive
                      ? "text-primary dark:text-white"
                      : "text-muted-foreground dark:text-gray-500 hover:text-foreground dark:hover:text-gray-400"
                  }`}
                  animate={{
                    scale: isActive ? 1 : 0.75,
                    opacity: isActive ? 1 : 0.4,
                  }}
                  transition={
                    isResetting
                      ? { duration: 0 }
                      : {
                          type: "spring",
                          stiffness: 400,
                          damping: 25,
                        }
                  }
                  style={{
                    width: "400px",
                  }}
                >
                  {item.title}
                </motion.button>
              );
            })}
          </motion.div>
        </div>

        <div className="flex items-center justify-center">
          <RulerLines top={false} />
        </div>
      </div>

      <div className="flex items-center justify-center gap-4 mt-10">
        <button
          onClick={handlePrevious}
          disabled={isResetting}
          className="flex items-center justify-center cursor-pointer"
          aria-label="Previous item"
        >
          <Rewind className="w-5 h-5 text-primary/80" />
        </button>

        <div className="flex items-center gap-2">
          <span className="text-sm font-medium text-muted-foreground dark:text-gray-400">
            {currentPage}
          </span>
          <span className="text-sm text-muted-foreground dark:text-gray-500">
            /
          </span>
          <span className="text-sm font-medium text-muted-foreground dark:text-gray-400">
            {totalPages}
          </span>
        </div>

        <button
          onClick={handleNext}
          disabled={isResetting}
          className="flex items-center justify-center cursor-pointer"
          aria-label="Next item"
        >
          <FastForward className="w-5 h-5 text-primary/80" />
        </button>
      </div>
    </div>
  );
}
```

---

## components/ui/safari-01.tsx

**File Path**: `components/ui/safari-01.tsx` | **Lines**: 126

```tsx
"use client";

import Image, { StaticImageData } from "next/image";
import React from "react";
import { cn } from "@/lib/utils";

interface Safari_01Props {
  image?: StaticImageData | string;
  url?: string;
  children?: React.ReactNode;
  className?: string;
  bodyClassName?: string;
  style?: React.CSSProperties;
}

const Safari_01: React.FC<Safari_01Props> = ({
  image,
  url,
  children,
  className,
  bodyClassName,
  style,
}) => {
  return (
    <div
      className={cn(
        "rounded-[12px] border border-[#1c1c1c] bg-[#070707] shadow-[0_18px_60px_-24px_rgba(0,0,0,0.7),0_0_0_1px_rgba(167,139,250,0.04)] overflow-hidden",
        className
      )}
      style={style}
    >
      {/* Safari top bar */}
      <div
        className="relative flex items-center bg-[#0d0d0d] border-b border-[#1c1c1c]"
        style={{ paddingLeft: "28px", paddingRight: "28px", paddingTop: "18px", paddingBottom: "18px" }}
      >
        {/* Traffic lights */}
        <div className="flex items-center shrink-0" style={{ gap: "10px" }}>
          <span
            className="rounded-full"
            style={{ width: "14px", height: "14px", backgroundColor: "#ff5f57", boxShadow: "inset 0 0 0 1px rgba(0,0,0,0.25)" }}
          />
          <span
            className="rounded-full"
            style={{ width: "14px", height: "14px", backgroundColor: "#febc2e", boxShadow: "inset 0 0 0 1px rgba(0,0,0,0.25)" }}
          />
          <span
            className="rounded-full"
            style={{ width: "14px", height: "14px", backgroundColor: "#28c840", boxShadow: "inset 0 0 0 1px rgba(0,0,0,0.25)" }}
          />
        </div>

        {/* Centered URL pill */}
        <div
          className="absolute left-1/2 -translate-x-1/2 w-full"
          style={{ maxWidth: "440px", paddingLeft: "72px", paddingRight: "72px" }}
        >
          <div
            className="rounded-md bg-[#161616] border border-[#1f1f1f] flex items-center justify-center text-[#9a9a9a] font-mono"
            style={{ height: "30px", gap: "8px", fontSize: "12.5px", letterSpacing: "0.02em" }}
          >
            <svg viewBox="0 0 16 16" className="w-3 h-3 text-[#a78bfa]" fill="none">
              <path
                d="M11 7a3 3 0 0 0-3-3H6a3 3 0 1 0 0 6h1"
                stroke="currentColor"
                strokeWidth="1.3"
                strokeLinecap="round"
              />
              <path
                d="M5 9a3 3 0 0 0 3 3h2a3 3 0 1 0 0-6H9"
                stroke="currentColor"
                strokeWidth="1.3"
                strokeLinecap="round"
              />
            </svg>
            <span className="truncate">{url ?? "portfolio.local"}</span>
          </div>
        </div>

        {/* Right-side spacer (matches traffic-light width for symmetry) */}
        <div className="ml-auto flex items-center gap-2 text-[#5a5a5a] shrink-0">
          <svg viewBox="0 0 16 16" className="w-3.5 h-3.5" fill="none">
            <path
              d="M3 8h10M9 4l4 4-4 4"
              stroke="currentColor"
              strokeWidth="1.3"
              strokeLinecap="round"
              strokeLinejoin="round"
            />
          </svg>
          <svg viewBox="0 0 16 16" className="w-3.5 h-3.5" fill="none">
            <path
              d="M5 2h6a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z"
              stroke="currentColor"
              strokeWidth="1.2"
            />
          </svg>
        </div>
      </div>

      {/* Body */}
      <div className={cn("bg-[#070707]", bodyClassName)}>
        {children ? (
          children
        ) : image ? (
          <div className="aspect-video flex items-center justify-center bg-[#0a0a0a]">
            <Image
              src={image}
              alt="Preview"
              width={800}
              height={450}
              className="object-contain max-h-full max-w-full"
            />
          </div>
        ) : (
          <div className="aspect-video flex items-center justify-center bg-[#0a0a0a] text-sm text-[#5a5a5a] font-mono">
            No preview
          </div>
        )}
      </div>
    </div>
  );
};

export default Safari_01;
```

---

## components/ui/scroll-morph-hero.tsx

**File Path**: `components/ui/scroll-morph-hero.tsx` | **Lines**: 430

```tsx
"use client";

import React, { useState, useEffect, useMemo, useRef } from "react";
import Image from "next/image";
import { useRouter } from "next/navigation";
import { motion, useTransform, useSpring, useMotionValue, MotionValue } from "framer-motion";

export type AnimationPhase = "scatter" | "line" | "circle" | "bottom-strip";

interface FlipCardProps {
    src: string;
    objectPosition?: string;
    link?: string;
    index: number;
    total: number;
    phase: AnimationPhase;
    target: { x: number; y: number; rotation: number; scale: number; opacity: number };
}

const IMG_WIDTH = 60;
const IMG_HEIGHT = 85;

function FlipCard({
    src,
    objectPosition,
    link,
    index,
    target,
}: FlipCardProps) {
    const router = useRouter();

    return (
        <motion.div
            animate={{
                x: target.x,
                y: target.y,
                rotate: target.rotation,
                scale: target.scale,
                opacity: target.opacity,
            }}
            transition={{
                type: "spring",
                stiffness: 40,
                damping: 15,
            }}
            style={{
                position: "absolute",
                width: IMG_WIDTH,
                height: IMG_HEIGHT,
                transformStyle: "preserve-3d",
                perspective: "1000px",
            }}
            className="cursor-pointer group"
            onClick={() => {
                router.push(link || "/articles");
            }}
        >
            <motion.div
                className="relative h-full w-full"
                style={{ transformStyle: "preserve-3d" }}
                transition={{ duration: 0.6, type: "spring", stiffness: 260, damping: 20 }}
                whileHover={{ rotateY: 180 }}
            >
                <div
                    className="absolute inset-0 h-full w-full overflow-hidden rounded-xl shadow-lg bg-gray-200"
                    style={{ backfaceVisibility: "hidden" }}
                >
                    <Image
                        src={src}
                        alt={`hero-${index}`}
                        fill
                        // Card box is 60 px, but during the bottom-strip arc
                        // Framer Motion scales it up to 1.8× (1.4× on mobile),
                        // so the on-screen footprint reaches ~108 px CSS / 216 px
                        // physical on a retina display. Asking the optimizer for
                        // a 256-wide source covers DPR 3 at peak scale without
                        // wasting bytes on the tiny scatter phase.
                        sizes="256px"
                        quality={85}
                        loading="lazy"
                        className="h-full w-full object-cover"
                        style={{ objectPosition: objectPosition ?? "center" }}
                    />
                    <div className="absolute inset-0 bg-black/10 transition-colors group-hover:bg-transparent" />
                </div>
                <div
                    className="absolute inset-0 h-full w-full overflow-hidden rounded-xl shadow-lg bg-gray-900 flex flex-col items-center justify-center p-4 border border-gray-700"
                    style={{ backfaceVisibility: "hidden", transform: "rotateY(180deg)" }}
                >
                    <div className="text-center">
                        <p className="text-[8px] font-bold text-blue-400 uppercase tracking-widest mb-1">Read</p>
                        <p className="text-xs font-medium text-white">Articles</p>
                    </div>
                </div>
            </motion.div>
        </motion.div>
    );
}

const TOTAL_IMAGES = 20;
const MAX_SCROLL = 3000;

const PROJECT_THUMBS: { src: string; objectPosition: string; link: string }[] = [
    { src: "/assets/carousel/carousel-33.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-25.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-35.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-09.webp", objectPosition: "center top", link: "/articles" },
    { src: "/assets/carousel/carousel-32.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-10.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-24.webp", objectPosition: "center top", link: "/articles" },
    { src: "/assets/carousel/carousel-05.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-19.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-15.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-28.webp", objectPosition: "center", link: "/articles" },
    { src: "/assets/carousel/carousel-37.webp", objectPosition: "center", link: "/articles" },
];

// 12 real projects + 8 duplicates (cycled) to fill TOTAL_IMAGES = 20 slots
const IMAGES = Array.from({ length: TOTAL_IMAGES }, (_, i) => PROJECT_THUMBS[i % PROJECT_THUMBS.length]);

const lerp = (start: number, end: number, t: number) => start * (1 - t) + end * t;

interface IntroAnimationProps {
    scrollProgress?: MotionValue<number>;
}

export default function IntroAnimation({ scrollProgress }: IntroAnimationProps = {}) {
    const [introPhase, setIntroPhase] = useState<AnimationPhase>("scatter");
    const [containerSize, setContainerSize] = useState({ width: 0, height: 0 });
    const containerRef = useRef<HTMLDivElement>(null);

    useEffect(() => {
        if (!containerRef.current) return;

        const handleResize = (entries: ResizeObserverEntry[]) => {
            for (const entry of entries) {
                setContainerSize({
                    width: entry.contentRect.width,
                    height: entry.contentRect.height,
                });
            }
        };

        const observer = new ResizeObserver(handleResize);
        observer.observe(containerRef.current);

        setContainerSize({
            width: containerRef.current.offsetWidth,
            height: containerRef.current.offsetHeight,
        });

        return () => observer.disconnect();
    }, []);

    const virtualScroll = useMotionValue(0);
    const scrollRef = useRef(0);

    useEffect(() => {
        if (!scrollProgress) return;
        const unsub = scrollProgress.on("change", (v) => {
            const clamped = Math.min(Math.max(v, 0), 1);
            scrollRef.current = clamped * MAX_SCROLL;
            virtualScroll.set(scrollRef.current);
        });
        return () => unsub();
    }, [scrollProgress, virtualScroll]);

    useEffect(() => {
        if (scrollProgress) return;
        const container = containerRef.current;
        if (!container) return;

        const handleWheel = (e: WheelEvent) => {
            const atStart = scrollRef.current <= 0 && e.deltaY < 0;
            const atEnd = scrollRef.current >= MAX_SCROLL && e.deltaY > 0;
            if (atStart || atEnd) return;

            e.preventDefault();
            const newScroll = Math.min(Math.max(scrollRef.current + e.deltaY, 0), MAX_SCROLL);
            scrollRef.current = newScroll;
            virtualScroll.set(newScroll);
        };

        let touchStartY = 0;
        const handleTouchStart = (e: TouchEvent) => {
            touchStartY = e.touches[0].clientY;
        };
        const handleTouchMove = (e: TouchEvent) => {
            const touchY = e.touches[0].clientY;
            const deltaY = touchStartY - touchY;
            touchStartY = touchY;

            const newScroll = Math.min(Math.max(scrollRef.current + deltaY, 0), MAX_SCROLL);
            scrollRef.current = newScroll;
            virtualScroll.set(newScroll);
        };

        container.addEventListener("wheel", handleWheel, { passive: false });
        container.addEventListener("touchstart", handleTouchStart, { passive: false });
        container.addEventListener("touchmove", handleTouchMove, { passive: false });

        return () => {
            container.removeEventListener("wheel", handleWheel);
            container.removeEventListener("touchstart", handleTouchStart);
            container.removeEventListener("touchmove", handleTouchMove);
        };
    }, [virtualScroll, scrollProgress]);

    const morphProgress = useTransform(virtualScroll, [0, 600], [0, 1]);
    const smoothMorph = useSpring(morphProgress, { stiffness: 40, damping: 20 });

    const scrollRotate = useTransform(virtualScroll, [600, 3000], [0, 360]);
    const smoothScrollRotate = useSpring(scrollRotate, { stiffness: 40, damping: 20 });

    const mouseX = useMotionValue(0);
    const smoothMouseX = useSpring(mouseX, { stiffness: 30, damping: 20 });

    useEffect(() => {
        const container = containerRef.current;
        if (!container) return;

        const handleMouseMove = (e: MouseEvent) => {
            const rect = container.getBoundingClientRect();
            const relativeX = e.clientX - rect.left;

            const normalizedX = (relativeX / rect.width) * 2 - 1;
            mouseX.set(normalizedX * 100);
        };
        container.addEventListener("mousemove", handleMouseMove);
        return () => container.removeEventListener("mousemove", handleMouseMove);
    }, [mouseX]);

    useEffect(() => {
        const timer1 = setTimeout(() => setIntroPhase("line"), 500);
        const timer2 = setTimeout(() => setIntroPhase("circle"), 2500);
        return () => { clearTimeout(timer1); clearTimeout(timer2); };
    }, []);

    const scatterPositions = useMemo(() => {
        return IMAGES.map(() => ({
            x: (Math.random() - 0.5) * 1500,
            y: (Math.random() - 0.5) * 1000,
            rotation: (Math.random() - 0.5) * 180,
            scale: 0.6,
            opacity: 0,
        }));
    }, []);

    const [morphValue, setMorphValue] = useState(0);
    const [rotateValue, setRotateValue] = useState(0);
    const [parallaxValue, setParallaxValue] = useState(0);
    const [autoRotate, setAutoRotate] = useState(0);
    const morphValueRef = useRef(0);
    const autoRotateRef = useRef(0);
    const isPausedRef = useRef(false);

    useEffect(() => {
        morphValueRef.current = morphValue;
    }, [morphValue]);

    useEffect(() => {
        const container = containerRef.current;
        if (!container) return;
        const onEnter = () => { isPausedRef.current = true; };
        const onLeave = () => { isPausedRef.current = false; };
        container.addEventListener("mouseenter", onEnter);
        container.addEventListener("mouseleave", onLeave);
        return () => {
            container.removeEventListener("mouseenter", onEnter);
            container.removeEventListener("mouseleave", onLeave);
        };
    }, []);

    useEffect(() => {
        let rafId: number;
        let lastTime = performance.now();
        const tick = (time: number) => {
            const dt = time - lastTime;
            lastTime = time;
            if (morphValueRef.current >= 0.95 && !isPausedRef.current) {
                autoRotateRef.current += dt * 0.004;
                setAutoRotate(autoRotateRef.current);
            }
            rafId = requestAnimationFrame(tick);
        };
        rafId = requestAnimationFrame(tick);
        return () => cancelAnimationFrame(rafId);
    }, []);

    useEffect(() => {
        const unsubscribeMorph = smoothMorph.on("change", setMorphValue);
        const unsubscribeRotate = smoothScrollRotate.on("change", setRotateValue);
        const unsubscribeParallax = smoothMouseX.on("change", setParallaxValue);
        return () => {
            unsubscribeMorph();
            unsubscribeRotate();
            unsubscribeParallax();
        };
    }, [smoothMorph, smoothScrollRotate, smoothMouseX]);

    const contentOpacity = useTransform(smoothMorph, [0.8, 1], [0, 1]);
    const contentY = useTransform(smoothMorph, [0.8, 1], [20, 0]);

    return (
        <div ref={containerRef} className="relative w-full h-full bg-[#FAFAFA] overflow-hidden">
            <div className="flex h-full w-full flex-col items-center justify-center perspective-1000">

                <div className="absolute z-0 flex flex-col items-center justify-center text-center pointer-events-none top-1/2 -translate-y-1/2">
                    <motion.h1
                        initial={{ opacity: 0, y: 20, filter: "blur(10px)" }}
                        animate={introPhase === "circle" && morphValue < 0.5 ? { opacity: 1 - morphValue * 2, y: 0, filter: "blur(0px)" } : { opacity: 0, filter: "blur(10px)" }}
                        transition={{ duration: 1 }}
                        className="text-2xl font-medium tracking-tight text-gray-800 md:text-4xl"
                    >
                        Every dataset hides a decision.
                    </motion.h1>
                    <motion.p
                        initial={{ opacity: 0 }}
                        animate={introPhase === "circle" && morphValue < 0.5 ? { opacity: 0.5 - morphValue } : { opacity: 0 }}
                        transition={{ duration: 1, delay: 0.2 }}
                        className="mt-4 text-xs font-bold tracking-[0.2em] text-gray-500"
                    >
                        SCROLL TO EXPLORE
                    </motion.p>
                </div>

                <motion.div
                    style={{ opacity: contentOpacity, y: contentY }}
                    className="absolute top-[10%] z-10 flex flex-col items-center justify-center text-center pointer-events-none px-4"
                >
                    <h2
                        className="text-3xl md:text-5xl font-semibold text-gray-900"
                        style={{ letterSpacing: "0.08em", marginBottom: "16px" }}
                    >
                        Selected Work &amp; Field Proof
                    </h2>
                    <p className="text-sm md:text-base text-gray-600 max-w-lg leading-relaxed">
                        Offline EdTech, supply-chain PKD modeling, sub-12ms AML graphs, <br className="hidden md:block" />
                        national podiums, and institutional research across IITs &amp; IIMs.
                    </p>
                </motion.div>

                <div className="relative flex items-center justify-center w-full h-full">
                    {IMAGES.slice(0, TOTAL_IMAGES).map((image, i) => {
                        let target = { x: 0, y: 0, rotation: 0, scale: 1, opacity: 1 };

                        if (introPhase === "scatter") {
                            target = scatterPositions[i];
                        } else if (introPhase === "line") {
                            const lineSpacing = 70;
                            const lineTotalWidth = TOTAL_IMAGES * lineSpacing;
                            const lineX = i * lineSpacing - lineTotalWidth / 2;
                            target = { x: lineX, y: 0, rotation: 0, scale: 1, opacity: 1 };
                        } else {
                            const isMobile = containerSize.width < 768;
                            const minDimension = Math.min(containerSize.width, containerSize.height);

                            const circleRadius = Math.min(minDimension * 0.35, 350);

                            const circleAngle = (i / TOTAL_IMAGES) * 360;
                            const circleRad = (circleAngle * Math.PI) / 180;
                            const circlePos = {
                                x: Math.cos(circleRad) * circleRadius,
                                y: Math.sin(circleRad) * circleRadius,
                                rotation: circleAngle + 90,
                            };

                            const baseRadius = Math.min(containerSize.width, containerSize.height * 1.5);
                            const arcRadius = baseRadius * (isMobile ? 1.4 : 1.1);

                            const arcApexY = containerSize.height * (isMobile ? 0.35 : 0.25);
                            const arcCenterY = arcApexY + arcRadius;

                            const spreadAngle = isMobile ? 100 : 130;
                            const startAngle = -90 - (spreadAngle / 2);
                            const step = spreadAngle / (TOTAL_IMAGES - 1);

                            const scrollProgress = Math.min(Math.max(rotateValue / 360, 0), 1);

                            const maxRotation = spreadAngle * 0.8;
                            const totalShift = -(scrollProgress * maxRotation) - autoRotate;

                            const baseAngle = i * step;
                            const wrappedPos = (((baseAngle + totalShift) % spreadAngle) + spreadAngle) % spreadAngle;
                            const currentArcAngle = startAngle + wrappedPos;
                            const arcRad = (currentArcAngle * Math.PI) / 180;

                            const fadeRange = 10;
                            let edgeOpacity = 1;
                            if (wrappedPos < fadeRange) {
                                edgeOpacity = wrappedPos / fadeRange;
                            } else if (wrappedPos > spreadAngle - fadeRange) {
                                edgeOpacity = (spreadAngle - wrappedPos) / fadeRange;
                            }

                            const arcPos = {
                                x: Math.cos(arcRad) * arcRadius + parallaxValue,
                                y: Math.sin(arcRad) * arcRadius + arcCenterY,
                                rotation: currentArcAngle + 90,
                                scale: isMobile ? 1.4 : 1.8,
                            };

                            target = {
                                x: lerp(circlePos.x, arcPos.x, morphValue),
                                y: lerp(circlePos.y, arcPos.y, morphValue),
                                rotation: lerp(circlePos.rotation, arcPos.rotation, morphValue),
                                scale: lerp(1, arcPos.scale, morphValue),
                                opacity: lerp(1, edgeOpacity, morphValue),
                            };
                        }

                        return (
                            <FlipCard
                                key={i}
                                src={image.src}
                                objectPosition={image.objectPosition}
                                link={image.link}
                                index={i}
                                total={TOTAL_IMAGES}
                                phase={introPhase}
                                target={target}
                            />
                        );
                    })}
                </div>
            </div>
        </div>
    );
}
```

---

## components/ui/scroll-morph-section.tsx

**File Path**: `components/ui/scroll-morph-section.tsx` | **Lines**: 41

```tsx
"use client";

import React, { useEffect, useRef } from "react";
import { useScroll, useTransform, useSpring } from "framer-motion";
import { ScrollTrigger } from "@/lib/gsap";
import IntroAnimation from "./scroll-morph-hero";

export default function ScrollMorphSection() {
  const wrapperRef = useRef<HTMLDivElement>(null);

  const { scrollYProgress } = useScroll({
    target: wrapperRef,
    offset: ["start start", "end end"],
  });

  const smoothProgress = useSpring(scrollYProgress, {
    stiffness: 180,
    damping: 28,
    mass: 0.2,
  });

  const innerProgress = useTransform(smoothProgress, [0.02, 0.9], [0, 1]);

  useEffect(() => {
    const id = setTimeout(() => ScrollTrigger.refresh(), 100);
    return () => clearTimeout(id);
  }, []);

  return (
    <section
      ref={wrapperRef}
      className="relative w-full h-[230vh]"
      style={{ willChange: "transform" }}
    >
      <div className="sticky top-0 w-full h-screen overflow-hidden bg-[#FAFAFA]">
        <IntroAnimation scrollProgress={innerProgress} />
      </div>
    </section>
  );
}
```

---

## components/ui/scroll-stack.css

**File Path**: `components/ui/scroll-stack.css` | **Lines**: 45

```css
.scroll-stack-scroller {
  position: relative;
  width: 100%;
  height: 100%;
  overflow-y: auto;
  overflow-x: visible;
  overscroll-behavior: contain;
  -webkit-overflow-scrolling: touch;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  will-change: scroll-position;
  /* Hide scrollbar for premium look */
  scrollbar-width: none;
}
.scroll-stack-scroller::-webkit-scrollbar {
  display: none;
}

.scroll-stack-inner {
  /* Compact padding for in-panel widget use (vs. the full-viewport default) */
  padding: 8px 0 50%;
  min-height: 100%;
}

.scroll-stack-card-wrapper {
  position: relative;
}

.scroll-stack-card {
  transform-origin: top center;
  will-change: transform, filter;
  backface-visibility: hidden;
  transform-style: preserve-3d;
  box-sizing: border-box;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  position: relative;
  /* No fixed height — let card content size itself */
}

.scroll-stack-end {
  width: 100%;
  height: 1px;
}
```

---

## components/ui/scroll-stack.tsx

**File Path**: `components/ui/scroll-stack.tsx` | **Lines**: 313

```tsx
"use client";
import {
  useLayoutEffect,
  useRef,
  useCallback,
  type ReactNode,
} from "react";
import Lenis from "lenis";
import "./scroll-stack.css";

export const ScrollStackItem = ({
  children,
  itemClassName = "",
}: {
  children: ReactNode;
  itemClassName?: string;
}) => (
  <div className={`scroll-stack-card ${itemClassName}`.trim()}>{children}</div>
);

export interface ScrollStackProps {
  children: ReactNode;
  className?: string;
  itemDistance?: number;
  itemScale?: number;
  itemStackDistance?: number;
  stackPosition?: string;
  scaleEndPosition?: string;
  baseScale?: number;
  scaleDuration?: number;
  rotationAmount?: number;
  blurAmount?: number;
  useWindowScroll?: boolean;
  onStackComplete?: () => void;
}

interface CardTransform {
  translateY: number;
  scale: number;
  rotation: number;
  blur: number;
}

const ScrollStack = ({
  children,
  className = "",
  itemDistance = 100,
  itemScale = 0.03,
  itemStackDistance = 30,
  stackPosition = "20%",
  scaleEndPosition = "10%",
  baseScale = 0.85,
  rotationAmount = 0,
  blurAmount = 0,
  useWindowScroll = false,
  onStackComplete,
}: ScrollStackProps) => {
  const scrollerRef = useRef<HTMLDivElement | null>(null);
  const stackCompletedRef = useRef(false);
  const animationFrameRef = useRef<number | null>(null);
  const lenisRef = useRef<Lenis | null>(null);
  const cardsRef = useRef<HTMLElement[]>([]);
  const lastTransformsRef = useRef<Map<number, CardTransform>>(new Map());
  const isUpdatingRef = useRef(false);

  const calculateProgress = useCallback(
    (scrollTop: number, start: number, end: number) => {
      if (scrollTop < start) return 0;
      if (scrollTop > end) return 1;
      return (scrollTop - start) / (end - start);
    },
    []
  );

  const parsePercentage = useCallback(
    (value: string | number, containerHeight: number) => {
      if (typeof value === "string" && value.includes("%")) {
        return (parseFloat(value) / 100) * containerHeight;
      }
      return parseFloat(String(value));
    },
    []
  );

  const getScrollData = useCallback(() => {
    if (useWindowScroll) {
      return {
        scrollTop: window.scrollY,
        containerHeight: window.innerHeight,
      };
    }
    const scroller = scrollerRef.current!;
    return {
      scrollTop: scroller.scrollTop,
      containerHeight: scroller.clientHeight,
    };
  }, [useWindowScroll]);

  const getElementOffset = useCallback(
    (element: HTMLElement) => {
      if (useWindowScroll) {
        const rect = element.getBoundingClientRect();
        return rect.top + window.scrollY;
      }
      return element.offsetTop;
    },
    [useWindowScroll]
  );

  const updateCardTransforms = useCallback(() => {
    if (!cardsRef.current.length || isUpdatingRef.current) return;
    isUpdatingRef.current = true;

    const { scrollTop, containerHeight } = getScrollData();
    const stackPositionPx = parsePercentage(stackPosition, containerHeight);
    const scaleEndPositionPx = parsePercentage(scaleEndPosition, containerHeight);

    const endElement = useWindowScroll
      ? document.querySelector<HTMLElement>(".scroll-stack-end")
      : scrollerRef.current?.querySelector<HTMLElement>(".scroll-stack-end");

    const endElementTop = endElement ? getElementOffset(endElement) : 0;

    cardsRef.current.forEach((card, i) => {
      if (!card) return;
      const cardTop = getElementOffset(card);
      const triggerStart = cardTop - stackPositionPx - itemStackDistance * i;
      const triggerEnd = cardTop - scaleEndPositionPx;
      const pinStart = cardTop - stackPositionPx - itemStackDistance * i;
      const pinEnd = endElementTop - containerHeight / 2;

      const scaleProgress = calculateProgress(scrollTop, triggerStart, triggerEnd);
      const targetScale = baseScale + i * itemScale;
      const scale = 1 - scaleProgress * (1 - targetScale);
      const rotation = rotationAmount ? i * rotationAmount * scaleProgress : 0;

      let blur = 0;
      if (blurAmount) {
        let topCardIndex = 0;
        for (let j = 0; j < cardsRef.current.length; j++) {
          const jCardTop = getElementOffset(cardsRef.current[j]);
          const jTriggerStart = jCardTop - stackPositionPx - itemStackDistance * j;
          if (scrollTop >= jTriggerStart) topCardIndex = j;
        }
        if (i < topCardIndex) {
          const depthInStack = topCardIndex - i;
          blur = Math.max(0, depthInStack * blurAmount);
        }
      }

      let translateY = 0;
      const isPinned = scrollTop >= pinStart && scrollTop <= pinEnd;
      if (isPinned) {
        translateY = scrollTop - cardTop + stackPositionPx + itemStackDistance * i;
      } else if (scrollTop > pinEnd) {
        translateY = pinEnd - cardTop + stackPositionPx + itemStackDistance * i;
      }

      const newTransform: CardTransform = {
        translateY: Math.round(translateY * 100) / 100,
        scale: Math.round(scale * 1000) / 1000,
        rotation: Math.round(rotation * 100) / 100,
        blur: Math.round(blur * 100) / 100,
      };

      const lastTransform = lastTransformsRef.current.get(i);
      const hasChanged =
        !lastTransform ||
        Math.abs(lastTransform.translateY - newTransform.translateY) > 0.1 ||
        Math.abs(lastTransform.scale - newTransform.scale) > 0.001 ||
        Math.abs(lastTransform.rotation - newTransform.rotation) > 0.1 ||
        Math.abs(lastTransform.blur - newTransform.blur) > 0.1;

      if (hasChanged) {
        card.style.transform = `translate3d(0, ${newTransform.translateY}px, 0) scale(${newTransform.scale}) rotate(${newTransform.rotation}deg)`;
        card.style.filter = newTransform.blur > 0 ? `blur(${newTransform.blur}px)` : "";
        lastTransformsRef.current.set(i, newTransform);
      }

      if (i === cardsRef.current.length - 1) {
        const isInView = scrollTop >= pinStart && scrollTop <= pinEnd;
        if (isInView && !stackCompletedRef.current) {
          stackCompletedRef.current = true;
          onStackComplete?.();
        } else if (!isInView && stackCompletedRef.current) {
          stackCompletedRef.current = false;
        }
      }
    });

    isUpdatingRef.current = false;
  }, [
    itemScale,
    itemStackDistance,
    stackPosition,
    scaleEndPosition,
    baseScale,
    rotationAmount,
    blurAmount,
    useWindowScroll,
    onStackComplete,
    calculateProgress,
    parsePercentage,
    getScrollData,
    getElementOffset,
  ]);

  const handleScroll = useCallback(() => {
    updateCardTransforms();
  }, [updateCardTransforms]);

  const setupLenis = useCallback(() => {
    const baseOptions = {
      duration: 1.2,
      easing: (t: number) => Math.min(1, 1.001 - Math.pow(2, -10 * t)),
      smoothWheel: true,
      touchMultiplier: 2,
      infinite: false,
      wheelMultiplier: 1,
      lerp: 0.1,
      syncTouch: true,
      syncTouchLerp: 0.075,
    };
    if (useWindowScroll) {
      const lenis = new Lenis(baseOptions);
      lenis.on("scroll", handleScroll);
      const raf = (time: number) => {
        lenis.raf(time);
        animationFrameRef.current = requestAnimationFrame(raf);
      };
      animationFrameRef.current = requestAnimationFrame(raf);
      lenisRef.current = lenis;
      return lenis;
    }
    const scroller = scrollerRef.current;
    if (!scroller || scroller.offsetParent === null) return;
    const inner = scroller.querySelector(".scroll-stack-inner") as HTMLElement;
    if (!inner) return;
    const lenis = new Lenis({
      wrapper: scroller,
      content: inner,
      ...baseOptions,
    } as unknown as ConstructorParameters<typeof Lenis>[0]);
    lenis.on("scroll", handleScroll);
    const raf = (time: number) => {
      lenis.raf(time);
      animationFrameRef.current = requestAnimationFrame(raf);
    };
    animationFrameRef.current = requestAnimationFrame(raf);
    lenisRef.current = lenis;
    return lenis;
  }, [handleScroll, useWindowScroll]);

  useLayoutEffect(() => {
    const scroller = scrollerRef.current;
    if (!scroller) return;

    const cards = Array.from(
      useWindowScroll
        ? document.querySelectorAll<HTMLElement>(".scroll-stack-card")
        : scroller.querySelectorAll<HTMLElement>(".scroll-stack-card")
    );

    cardsRef.current = cards;
    const transformsCache = lastTransformsRef.current;

    cards.forEach((card, i) => {
      if (i < cards.length - 1) card.style.marginBottom = `${itemDistance}px`;
      card.style.willChange = "transform, filter";
      card.style.transformOrigin = "top center";
      card.style.backfaceVisibility = "hidden";
      card.style.transform = "translateZ(0)";
      card.style.perspective = "1000px";
    });

    setupLenis();
    updateCardTransforms();

    return () => {
      if (animationFrameRef.current) cancelAnimationFrame(animationFrameRef.current);
      if (lenisRef.current) lenisRef.current.destroy();
      stackCompletedRef.current = false;
      cardsRef.current = [];
      transformsCache.clear();
      isUpdatingRef.current = false;
    };
  }, [
    itemDistance,
    itemScale,
    itemStackDistance,
    stackPosition,
    scaleEndPosition,
    baseScale,
    rotationAmount,
    blurAmount,
    useWindowScroll,
    onStackComplete,
    setupLenis,
    updateCardTransforms,
  ]);

  return (
    <div className={`scroll-stack-scroller ${className}`.trim()} ref={scrollerRef}>
      <div className="scroll-stack-inner">
        {children}
        <div className="scroll-stack-end" />
      </div>
    </div>
  );
};

export default ScrollStack;
```

---

## components/ui/scroll-tilted-grid-demo.tsx

**File Path**: `components/ui/scroll-tilted-grid-demo.tsx` | **Lines**: 292

```tsx
"use client";
import { ScrollTiltedGrid } from "@/components/ui/scroll-tilted-grid";

export default function ScrollTiltedGridDemo() {
  return (
    <div
      style={{
        position: "relative",
        width: "100%",
        overflowX: "hidden",
        background: "#080808",
        color: "#f0ece4",
        display: "flex",
        flexDirection: "column",
        alignItems: "center",
      }}
    >
      <section
        style={{
          position: "relative",
          width: "100%",
          minHeight: "100vh",
          display: "flex",
          flexDirection: "column",
          alignItems: "center",
          justifyContent: "center",
          paddingInline: "1.5rem",
          textAlign: "center",
          overflow: "hidden",
        }}
      >
        {/* Premium minimal backdrop — non-interactive */}
        <div
          aria-hidden
          style={{
            position: "absolute",
            inset: 0,
            pointerEvents: "none",
            overflow: "hidden",
          }}
        >
          {/* Soft gold radial glow centered behind title */}
          <div
            className="stge-glow"
            style={{
              position: "absolute",
              top: "50%",
              left: "50%",
              width: "min(78vw, 920px)",
              height: "min(78vw, 920px)",
              transform: "translate(-50%, -50%)",
              background:
                "radial-gradient(circle at center, rgba(200,168,130,0.10) 0%, rgba(200,168,130,0.04) 40%, transparent 70%)",
              filter: "blur(8px)",
            }}
          />

          {/* Faint dotted grid */}
          <div
            style={{
              position: "absolute",
              inset: 0,
              backgroundImage:
                "radial-gradient(rgba(240,236,228,0.045) 1px, transparent 1px)",
              backgroundSize: "32px 32px",
              maskImage:
                "radial-gradient(ellipse at center, black 30%, transparent 80%)",
              WebkitMaskImage:
                "radial-gradient(ellipse at center, black 30%, transparent 80%)",
            }}
          />

          {/* Vertical hairlines + edge labels */}
          <span
            style={{
              position: "absolute",
              top: "10%",
              bottom: "10%",
              left: "clamp(1.25rem, 4vw, 3rem)",
              width: "1px",
              background:
                "linear-gradient(180deg, transparent 0%, rgba(240,236,228,0.10) 20%, rgba(240,236,228,0.10) 80%, transparent 100%)",
            }}
          />
          <span
            style={{
              position: "absolute",
              top: "50%",
              left: "calc(clamp(1.25rem, 4vw, 3rem) + 12px)",
              transform: "translateY(-50%) rotate(-90deg)",
              transformOrigin: "left center",
              fontSize: "10px",
              letterSpacing: "0.42em",
              textTransform: "uppercase",
              color: "rgba(240,236,228,0.35)",
              fontFamily:
                "ui-monospace, SFMono-Regular, Menlo, Consolas, monospace",
              whiteSpace: "nowrap",
            }}
          >
            Ch · 04 — Field of Stills
          </span>

          {/* Corner brackets */}
          {[
            { top: "1.75rem", left: "1.75rem", rotate: 0 },
            { top: "1.75rem", right: "1.75rem", rotate: 90 },
            { bottom: "1.75rem", right: "1.75rem", rotate: 180 },
            { bottom: "1.75rem", left: "1.75rem", rotate: 270 },
          ].map((pos, i) => (
            <svg
              key={i}
              width="18"
              height="18"
              viewBox="0 0 18 18"
              style={{
                position: "absolute",
                top: pos.top,
                left: pos.left,
                right: pos.right,
                bottom: pos.bottom,
                transform: `rotate(${pos.rotate}deg)`,
                color: "#c8a882",
                opacity: 0.55,
              }}
            >
              <path
                d="M1 7 L1 1 L7 1"
                stroke="currentColor"
                strokeWidth="1"
                fill="none"
                strokeLinecap="square"
              />
            </svg>
          ))}

          {/* Tiny center-top index numeral */}
          <span
            style={{
              position: "absolute",
              top: "2.25rem",
              left: "50%",
              transform: "translateX(-50%)",
              fontSize: "10px",
              letterSpacing: "0.42em",
              textTransform: "uppercase",
              color: "rgba(200,168,130,0.55)",
              fontFamily:
                "ui-monospace, SFMono-Regular, Menlo, Consolas, monospace",
            }}
          >
            04 / 07
          </span>
        </div>

        <h1
          style={{
            position: "relative",
            fontSize: "clamp(1.875rem, 4vw, 3rem)",
            fontWeight: 500,
            letterSpacing: "-0.02em",
          }}
        >
          Where Evidence Speaks for Itself
        </h1>
        <p style={{ position: "relative", marginTop: "1rem", maxWidth: "30rem", fontSize: "0.95rem", lineHeight: 1.6, opacity: 0.92 }}>
          National hackathon podiums, regional press coverage, industry conversations, and verified certificates across IITs &amp; IIMs.
        </p>

        {/* Animated scroll-and-explore cue */}
        <div
          style={{
            position: "relative",
            marginTop: "3rem",
            display: "flex",
            flexDirection: "column",
            alignItems: "center",
            gap: "14px",
          }}
        >
          <span
            className="stge-shimmer"
            style={{
              fontSize: "11px",
              fontWeight: 600,
              letterSpacing: "0.42em",
              textTransform: "uppercase",
            }}
          >
            Scroll &amp; Explore
          </span>

          <span
            aria-hidden
            style={{
              position: "relative",
              width: "1px",
              height: "48px",
              overflow: "hidden",
              background: "rgba(240,236,228,0.12)",
            }}
          >
            <span
              className="stge-line-pulse"
              style={{
                position: "absolute",
                top: 0,
                left: 0,
                width: "100%",
                height: "40%",
                background:
                  "linear-gradient(180deg, transparent 0%, #c8a882 50%, transparent 100%)",
              }}
            />
          </span>

          <svg
            aria-hidden
            viewBox="0 0 16 16"
            className="stge-bounce"
            style={{ width: "14px", height: "14px", color: "#c8a882" }}
          >
            <path
              d="M4 6l4 4 4-4"
              stroke="currentColor"
              strokeWidth="1.4"
              strokeLinecap="round"
              strokeLinejoin="round"
              fill="none"
            />
          </svg>
        </div>

        <style jsx>{`
          .stge-shimmer {
            background: linear-gradient(
              90deg,
              rgba(240, 236, 228, 0.35) 0%,
              rgba(240, 236, 228, 0.95) 40%,
              #c8a882 50%,
              rgba(240, 236, 228, 0.95) 60%,
              rgba(240, 236, 228, 0.35) 100%
            );
            background-size: 220% 100%;
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            animation: stge-shimmer 3.6s ease-in-out infinite;
          }
          @keyframes stge-shimmer {
            0% { background-position: 200% 0; }
            100% { background-position: -200% 0; }
          }

          .stge-line-pulse {
            animation: stge-line 2.2s cubic-bezier(0.65, 0, 0.35, 1) infinite;
          }
          @keyframes stge-line {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(250%); }
          }

          .stge-bounce {
            animation: stge-bounce 1.8s ease-in-out infinite;
          }
          @keyframes stge-bounce {
            0%, 100% { transform: translateY(0); opacity: 0.55; }
            50% { transform: translateY(4px); opacity: 1; }
          }
        `}</style>
      </section>

      <ScrollTiltedGrid initialCycles={1} gap={10} />

      {/* Fade the starfield section smoothly into the card carousel below */}
      <div
        aria-hidden
        style={{
          position: "absolute",
          bottom: 0,
          left: 0,
          right: 0,
          height: "22vh",
          background: "linear-gradient(to bottom, transparent 0%, #060606 100%)",
          pointerEvents: "none",
          zIndex: 10,
        }}
      />
    </div>
  );
}
```

---

## components/ui/scroll-tilted-grid.tsx

**File Path**: `components/ui/scroll-tilted-grid.tsx` | **Lines**: 367

```tsx
"use client";

import {
  motion,
  useScroll,
  useTransform,
  useMotionTemplate,
  useReducedMotion,
  cubicBezier,
} from "framer-motion";
import { useEffect, useMemo, useRef, useState } from "react"; // useEffect+useState used by ScrollTiltedGrid loop sentinel

export const DEFAULT_GRID_IMAGES: readonly string[] = [
  "/assets/carousel/carousel-09.webp",
  "/assets/carousel/carousel-25.webp",
  "/assets/carousel/carousel-33.webp",
  "/assets/carousel/carousel-16.webp",
  "/assets/carousel/carousel-26.webp",
  "/assets/carousel/carousel-10.webp",
  "/assets/carousel/carousel-05.webp",
  "/assets/carousel/carousel-15.webp",
  "/assets/carousel/carousel-19.webp",
  "/assets/carousel/carousel-24.webp",
  "/assets/portfolio/certificates/cert-01.jpg",
  "/assets/portfolio/certificates/cert-02.jpg",
];

const CONTAIN_KEYS = ["cert-", "carousel-16", "carousel-20", "carousel-21", "carousel-23", "carousel-26"];
const isContain = (src: string) => CONTAIN_KEYS.some((k) => src.includes(k));

const easeIntoFocus = cubicBezier(0.22, 1, 0.36, 1);
const easeOutOfFocus = cubicBezier(0, 0, 0.58, 1);
const focusEase: [typeof easeIntoFocus, typeof easeOutOfFocus] = [
  easeIntoFocus,
  easeOutOfFocus,
];

export type GapToken = 4 | 6 | 8 | 10 | 12 | 14;


// Deterministic hash so server/client positions match (no hydration drift)
function seeded(i: number) {
  const x = Math.sin(i * 12.9898) * 43758.5453;
  return x - Math.floor(x);
}

type StarSpec = {
  top: string;
  left: string;
  size: number;
  delay: string;
  duration: string;
  color: string;
  kind: "dot" | "sparkle";
};

// 70 stars created 70 always-animating CSS-keyframe layers — each with its
// own composite, paint, and opacity tween. 28 still reads as a starfield
// (every other star reuses the same seed slots, so density looks identical
// to a casual scroll) and roughly halves the section's GPU load.
const STARFIELD: StarSpec[] = Array.from({ length: 28 }, (_, i) => {
  const r1 = seeded(i + 1);
  const r2 = seeded(i + 101);
  const r3 = seeded(i + 211);
  const r4 = seeded(i + 313);
  const r5 = seeded(i + 419);
  const isSparkle = r5 > 0.88;
  const rawSize = isSparkle ? 6 + r3 * 4 : 1 + r3 * 1.6;
  const size = Number(rawSize.toFixed(2));
  return {
    top: `${(r1 * 100).toFixed(2)}%`,
    left: `${(r2 * 100).toFixed(2)}%`,
    size,
    delay: `${(r4 * 5).toFixed(2)}s`,
    duration: `${(2.4 + r3 * 3.6).toFixed(2)}s`,
    color: r5 > 0.6 ? "rgba(200,168,130,0.8)" : "rgba(240,236,228,0.7)",
    kind: isSparkle ? "sparkle" : "dot",
  };
});

function Starfield() {
  return (
    <div
      aria-hidden
      style={{
        position: "absolute",
        inset: 0,
        pointerEvents: "none",
        overflow: "hidden",
        zIndex: 0,
        contain: "layout style",
      }}
    >
      {STARFIELD.map((s, i) =>
        s.kind === "dot" ? (
          <span
            key={i}
            className="stg-star-twinkle"
            style={{
              position: "absolute",
              top: s.top,
              left: s.left,
              width: `${s.size}px`,
              height: `${s.size}px`,
              borderRadius: "9999px",
              background: s.color,
              boxShadow: `0 0 ${(s.size * 2).toFixed(2)}px ${s.color}`,
              animationDelay: s.delay,
              animationDuration: s.duration,
            }}
          />
        ) : (
          <svg
            key={i}
            className="stg-star-twinkle"
            viewBox="0 0 12 12"
            style={{
              position: "absolute",
              top: s.top,
              left: s.left,
              width: `${s.size}px`,
              height: `${s.size}px`,
              color: s.color,
              animationDelay: s.delay,
              animationDuration: s.duration,
              filter: `drop-shadow(0 0 4px ${s.color})`,
            }}
          >
            <path
              d="M6 0 L6.6 5.4 L12 6 L6.6 6.6 L6 12 L5.4 6.6 L0 6 L5.4 5.4 Z"
              fill="currentColor"
            />
          </svg>
        )
      )}
      <style>{`
        @keyframes stg-twinkle {
          0%, 100% { opacity: 0.15; transform: scale(0.85); }
          50% { opacity: 1; transform: scale(1.05); }
        }
        .stg-star-twinkle {
          animation-name: stg-twinkle;
          animation-iteration-count: infinite;
          animation-timing-function: ease-in-out;
          will-change: opacity;
        }
        @media (prefers-reduced-motion: reduce) {
          .stg-star-twinkle { animation: none; opacity: 0.5; }
        }
      `}</style>
    </div>
  );
}

type Side = "L" | "R";

type TileConfig = {
  aspectRatio: string;
  perspective: number;
  maxTilt: number;
  maxBlur: number;
  rounded: string;
};

function Tile({
  src,
  side,
  config,
}: {
  src: string;
  side: Side;
  config: TileConfig;
}) {
  const ref = useRef<HTMLElement>(null);
  const { scrollYProgress: p } = useScroll({
    target: ref,
    offset: ["start end", "end start"],
  });

  const reduce = useReducedMotion();
  const sign = side === "L" ? -1 : 1;
  const { aspectRatio, perspective, maxTilt, maxBlur, rounded } = config;

  const blur = useTransform(p, [0, 0.5, 1], [maxBlur, 0, maxBlur], { ease: focusEase });
  const bright = useTransform(p, [0, 0.5, 1], [0, 1, 0], { ease: focusEase });
  const contrast = useTransform(p, [0, 0.5, 1], [4, 1, 4], { ease: focusEase });

  const ty = useTransform(p, [0, 0.5, 1], ["100%", "0%", "-100%"], { ease: focusEase });
  const tz = useTransform(p, [0, 0.5, 1], [300, 0, 300], { ease: focusEase });
  const rx = useTransform(p, [0, 0.5, 1], [maxTilt, 0, -maxTilt], { ease: focusEase });

  const tx = useTransform(p, [0, 0.5, 1],
    [`${sign * 40}%`, "0%", `${sign * 40}%`], { ease: focusEase });
  const rot = useTransform(p, [0, 0.5, 1], [-sign * 5, 0, sign * 5], { ease: focusEase });
  const sk = useTransform(p, [0, 0.5, 1], [sign * 20, 0, -sign * 20], { ease: focusEase });

  const innerSY = useTransform(p, [0, 0.5, 1], [1.8, 1, 1.8], { ease: focusEase });

  const filter = useMotionTemplate`blur(${blur}px) brightness(${bright}) contrast(${contrast})`;

  const topAlign = isContain(src);
  const bgPosition = topAlign ? "center top" : "center";
  const bgImage = `url("${src}")`;

  if (reduce) {
    return (
      <figure ref={ref} className="relative z-10 m-0">
        <div
          className="relative w-full overflow-hidden"
          style={{ aspectRatio, borderRadius: rounded }}
        >
          <div
            className="absolute inset-0 bg-cover bg-no-repeat"
            style={{ backgroundImage: bgImage, backgroundPosition: bgPosition }}
          />
        </div>
      </figure>
    );
  }

  return (
    <motion.figure
      ref={ref}
      className="relative z-10 m-0"
      style={{ perspective, willChange: "transform" }}
    >
      <motion.div
        className="relative w-full overflow-hidden will-change-[filter,transform]"
        style={{
          aspectRatio,
          borderRadius: rounded,
          filter,
          x: tx,
          y: ty,
          z: tz,
          rotate: rot,
          rotateX: rx,
          skewX: sk,
        }}
      >
        <motion.div
          className="absolute inset-0 bg-cover bg-no-repeat will-change-transform"
          style={{
            backgroundImage: bgImage,
            backgroundPosition: bgPosition,
            scaleY: innerSY,
            backfaceVisibility: "hidden",
          }}
        />
      </motion.div>
    </motion.figure>
  );
}

export type ScrollTiltedGridProps = {
  images?: readonly string[];
  loop?: boolean;
  initialCycles?: number;
  aspectRatio?: string;
  gap?: GapToken;
  perspective?: number;
  maxTilt?: number;
  maxBlur?: number;
  rounded?: string;
  className?: string;
};

export function ScrollTiltedGrid({
  images = DEFAULT_GRID_IMAGES,
  loop = false,
  initialCycles = 2,
  aspectRatio = "3/4",
  gap = 10,
  perspective = 900,
  maxTilt = 70,
  maxBlur = 8,
  rounded = "0.375rem",
  className,
}: ScrollTiltedGridProps = {}) {
  const [cycles, setCycles] = useState(initialCycles);
  const sentinelRef = useRef<HTMLDivElement>(null);

  useEffect(() => {
    if (typeof window !== "undefined" && window.innerWidth < 768) {
      setCycles(1);
    }
  }, []);

  useEffect(() => {
    if (!loop) return;
    const el = sentinelRef.current;
    if (!el) return;
    const obs = new IntersectionObserver(
      (entries) => {
        if (entries.some((e) => e.isIntersecting)) {
          setCycles((c) => c + 2);
        }
      },
      { rootMargin: "1500px 0px 1500px 0px" },
    );
    obs.observe(el);
    return () => obs.disconnect();
  }, [loop]);

  const items = useMemo(
    () => Array.from({ length: cycles }, () => images).flat(),
    [cycles, images],
  );

  const config = useMemo<TileConfig>(
    () => ({ aspectRatio, perspective, maxTilt, maxBlur, rounded }),
    [aspectRatio, perspective, maxTilt, maxBlur, rounded],
  );

  const GAP_REM: Record<GapToken, string> = {
    4: "1rem",
    6: "1.5rem",
    8: "2rem",
    10: "2.5rem",
    12: "3rem",
    14: "3.5rem",
  };

  return (
    <section
      className={className}
      style={{
        position: "relative",
        width: "100%",
        boxSizing: "border-box",
        paddingBlockStart: "20vh",
        paddingBlockEnd: "6vh",
        marginTop: "20vh",
        marginBottom: 0,
      }}
    >
      <Starfield />
      <div
        style={{
          position: "relative",
          zIndex: 1,
          display: "grid",
          gridTemplateColumns: "repeat(2, minmax(0, 1fr))",
          gap: GAP_REM[gap],
          boxSizing: "border-box",
          width: "calc(100% - 3rem)",
          maxWidth: "40rem",
          marginLeft: "auto",
          marginRight: "auto",
        }}
      >
        {items.map((src, i) => (
          <Tile
            key={`${i}-${src}`}
            src={src}
            side={i % 2 === 0 ? "L" : "R"}
            config={config}
          />
        ))}
      </div>
      {loop ? (
        <div ref={sentinelRef} aria-hidden className="h-px w-full" />
      ) : null}
    </section>
  );
}
```

---

## components/ui/ScrollProgressBar.tsx

**File Path**: `components/ui/ScrollProgressBar.tsx` | **Lines**: 16

```tsx
"use client";

import { motion, useScroll, useSpring } from "framer-motion";

export function ScrollProgressBar() {
  const { scrollYProgress } = useScroll();
  const scaleX = useSpring(scrollYProgress, { stiffness: 100, damping: 30 });

  return (
    <motion.div
      className="fixed top-0 left-0 right-0 h-[2px] bg-[var(--gold)] z-[200] origin-left"
      style={{ scaleX }}
    />
  );
}
```

---

## components/ui/sheet.tsx

**File Path**: `components/ui/sheet.tsx` | **Lines**: 139

```tsx
"use client"

import * as React from "react"
import { Dialog as SheetPrimitive } from "@base-ui/react/dialog"

import { cn } from "@/lib/utils"
import { Button } from "@/components/ui/button"
import { XIcon } from "lucide-react"

function Sheet({ ...props }: SheetPrimitive.Root.Props) {
  return <SheetPrimitive.Root data-slot="sheet" {...props} />
}

function SheetTrigger({ ...props }: SheetPrimitive.Trigger.Props) {
  return <SheetPrimitive.Trigger data-slot="sheet-trigger" {...props} />
}

function SheetClose({ ...props }: SheetPrimitive.Close.Props) {
  return <SheetPrimitive.Close data-slot="sheet-close" {...props} />
}

function SheetPortal({ ...props }: SheetPrimitive.Portal.Props) {
  return <SheetPrimitive.Portal data-slot="sheet-portal" {...props} />
}

function SheetOverlay({ className, ...props }: SheetPrimitive.Backdrop.Props) {
  return (
    <SheetPrimitive.Backdrop
      data-slot="sheet-overlay"
      className={cn(
        "fixed inset-0 z-50 bg-black/10 transition-opacity duration-150 data-ending-style:opacity-0 data-starting-style:opacity-0 supports-backdrop-filter:backdrop-blur-xs",
        className
      )}
      {...props}
    />
  )
}

function SheetContent({
  className,
  children,
  side = "right",
  showCloseButton = true,
  ...props
}: SheetPrimitive.Popup.Props & {
  side?: "top" | "right" | "bottom" | "left"
  showCloseButton?: boolean
}) {
  return (
    <SheetPortal>
      <SheetOverlay />
      <SheetPrimitive.Popup
        data-slot="sheet-content"
        data-side={side}
        className={cn(
          "fixed z-50 flex flex-col gap-4 bg-popover bg-clip-padding text-sm text-popover-foreground shadow-lg transition duration-200 ease-in-out data-ending-style:opacity-0 data-starting-style:opacity-0 data-[side=bottom]:inset-x-0 data-[side=bottom]:bottom-0 data-[side=bottom]:h-auto data-[side=bottom]:border-t data-[side=bottom]:data-ending-style:translate-y-[2.5rem] data-[side=bottom]:data-starting-style:translate-y-[2.5rem] data-[side=left]:inset-y-0 data-[side=left]:left-0 data-[side=left]:h-full data-[side=left]:w-3/4 data-[side=left]:border-r data-[side=left]:data-ending-style:translate-x-[-2.5rem] data-[side=left]:data-starting-style:translate-x-[-2.5rem] data-[side=right]:inset-y-0 data-[side=right]:right-0 data-[side=right]:h-full data-[side=right]:w-3/4 data-[side=right]:border-l data-[side=right]:data-ending-style:translate-x-[2.5rem] data-[side=right]:data-starting-style:translate-x-[2.5rem] data-[side=top]:inset-x-0 data-[side=top]:top-0 data-[side=top]:h-auto data-[side=top]:border-b data-[side=top]:data-ending-style:translate-y-[-2.5rem] data-[side=top]:data-starting-style:translate-y-[-2.5rem] data-[side=left]:sm:max-w-sm data-[side=right]:sm:max-w-sm",
          className
        )}
        {...props}
      >
        {children}
        {showCloseButton && (
          <SheetPrimitive.Close
            data-slot="sheet-close"
            render={
              <Button
                variant="ghost"
                className="absolute top-3 right-3"
                size="icon-sm"
              />
            }
          >
            <XIcon
            />
            <span className="sr-only">Close</span>
          </SheetPrimitive.Close>
        )}
      </SheetPrimitive.Popup>
    </SheetPortal>
  )
}

function SheetHeader({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="sheet-header"
      className={cn("flex flex-col gap-0.5 p-4", className)}
      {...props}
    />
  )
}

function SheetFooter({ className, ...props }: React.ComponentProps<"div">) {
  return (
    <div
      data-slot="sheet-footer"
      className={cn("mt-auto flex flex-col gap-2 p-4", className)}
      {...props}
    />
  )
}

function SheetTitle({ className, ...props }: SheetPrimitive.Title.Props) {
  return (
    <SheetPrimitive.Title
      data-slot="sheet-title"
      className={cn(
        "font-heading text-base font-medium text-foreground",
        className
      )}
      {...props}
    />
  )
}

function SheetDescription({
  className,
  ...props
}: SheetPrimitive.Description.Props) {
  return (
    <SheetPrimitive.Description
      data-slot="sheet-description"
      className={cn("text-sm text-muted-foreground", className)}
      {...props}
    />
  )
}

export {
  Sheet,
  SheetTrigger,
  SheetClose,
  SheetContent,
  SheetHeader,
  SheetFooter,
  SheetTitle,
  SheetDescription,
}
```

---

## components/ui/spline-scene-basic.tsx

**File Path**: `components/ui/spline-scene-basic.tsx` | **Lines**: 74

```tsx
'use client';

import { useEffect, useRef, useState } from "react";
import { SplineScene } from "@/components/ui/splite";
import { Card } from "@/components/ui/card";
import { Spotlight } from "@/components/ui/spotlight";

export function SplineSceneBasic() {
  const cardRef = useRef<HTMLDivElement>(null);
  const [spotlightArmed, setSpotlightArmed] = useState(false);
  const [loadScene, setLoadScene] = useState(false);

  useEffect(() => {
    // Only load the heavy 3D Spline scene when the user approaches this section (rootMargin: 350px)
    // This frees 100% of network & CPU bandwidth for the Hero, transitions, and photos on mobile.
    if (!cardRef.current) return;
    const el = cardRef.current;
    const io = new IntersectionObserver(
      (entries) => {
        for (const entry of entries) {
          if (entry.isIntersecting) {
            setSpotlightArmed(true);
            setLoadScene(true);
            io.disconnect();
            break;
          }
        }
      },
      { rootMargin: "350px 0px" }
    );
    io.observe(el);

    return () => {
      io.disconnect();
    };
  }, []);

  return (
    <Card ref={cardRef} className="w-full h-full rounded-none border-0 bg-black/[0.96] relative overflow-hidden">
      {spotlightArmed && (
        <Spotlight
          key="spotlight-armed"
          className="-top-40 left-0 md:left-60 md:-top-20"
          fill="white"
        />
      )}

      <div className="flex flex-col md:flex-row h-full">
        <div className="flex-1 py-12 md:py-16 relative z-10 flex flex-col justify-center items-center md:items-end px-6 sm:px-10 md:pr-12 pointer-events-none text-center md:text-right">
          <div className="max-w-lg w-full">
          <h1 className="text-4xl sm:text-5xl md:text-7xl font-bold bg-clip-text text-transparent bg-gradient-to-b from-neutral-50 to-neutral-400">
            Decisions That Move.
          </h1>
          <p className="mt-4 md:mt-6 text-base md:text-lg text-neutral-300">
            I’m Jay Parmar — an AI/ML builder, finance analyst, and product leader at IIM Bangalore. I build useful systems, rally people around ambitious ideas, and stay with the work until it creates a real outcome.
          </p>
          </div>
        </div>

        <div className="flex-1 relative pointer-events-auto min-h-[350px] md:min-h-0">
          {loadScene && (
            <SplineScene
              scene="https://prod.spline.design/kZDDjO5HuC9GJUM2/scene.splinecode"
              className="w-full h-full"
            />
          )}
        </div>
      </div>
    </Card>
  );
}

export default SplineSceneBasic;
```

---

## components/ui/splite.tsx

**File Path**: `components/ui/splite.tsx` | **Lines**: 27

```tsx
'use client';

import { Suspense, lazy } from 'react';

const Spline = lazy(() => import('@splinetool/react-spline'));

interface SplineSceneProps {
  scene: string;
  className?: string;
}

export function SplineScene({ scene, className }: SplineSceneProps) {
  return (
    <Suspense
      fallback={
        <div className="w-full h-full flex items-center justify-center">
          <span className="text-xs tracking-[0.18em] text-neutral-500 uppercase animate-pulse">
            Loading scene…
          </span>
        </div>
      }
    >
      <Spline scene={scene} className={className} />
    </Suspense>
  );
}
```

---

## components/ui/spotlight.tsx

**File Path**: `components/ui/spotlight.tsx` | **Lines**: 59

```tsx
import React from "react";
import { cn } from "@/lib/utils";

type SpotlightProps = {
  className?: string;
  fill?: string;
};

export const Spotlight = ({ className, fill }: SpotlightProps) => {
  return (
    <svg
      className={cn(
        "animate-spotlight pointer-events-none absolute z-[1] h-[169%] w-[138%] lg:w-[84%] opacity-0",
        className
      )}
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 3787 2842"
      fill="none"
    >
      <g filter="url(#filter)">
        <ellipse
          cx="1924.71"
          cy="273.501"
          rx="1924.71"
          ry="273.501"
          transform="matrix(-0.822377 -0.568943 -0.568943 0.822377 3631.88 2291.09)"
          fill={fill || "white"}
          fillOpacity="0.21"
        />
      </g>
      <defs>
        <filter
          id="filter"
          x="0.860352"
          y="0.838989"
          width="3785.16"
          height="2840.26"
          filterUnits="userSpaceOnUse"
          colorInterpolationFilters="sRGB"
        >
          <feFlood floodOpacity="0" result="BackgroundImageFix" />
          <feBlend
            mode="normal"
            in="SourceGraphic"
            in2="BackgroundImageFix"
            result="shape"
          />
          <feGaussianBlur
            stdDeviation="151"
            result="effect1_foregroundBlur_1065_8"
          />
        </filter>
      </defs>
    </svg>
  );
};

export default Spotlight;
```

---

## components/ui/story-scroll-demo.tsx

**File Path**: `components/ui/story-scroll-demo.tsx` | **Lines**: 145

```tsx
'use client';

import Image from 'next/image';
import FlowArt, { FlowSection } from '@/components/ui/story-scroll';

export default function StoryScrollDemo() {
  return (
    <FlowArt aria-label="Jay Parmar Story Presentation">
      <FlowSection aria-label="Who I AM" style={{ backgroundColor: '#fd5200', color: '#fff' }}>
        <div className="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-12 items-center w-full my-auto">
          {/* Left: Portrait Picture */}
          <div className="lg:col-span-5 w-full flex justify-center lg:justify-start">
            <div className="relative aspect-[3/4] w-full max-w-[400px] rounded-2xl md:rounded-3xl overflow-hidden border-2 border-black/80 shadow-[0_24px_60px_rgba(0,0,0,0.35)] bg-black/15">
              <Image
                src="/assets/portfolio/gallery/gallery-03.jpg"
                alt="Jay Parmar · BBA, IIM Bangalore"
                fill
                priority
                sizes="(max-width: 1024px) 100vw, 400px"
                className="object-cover object-center"
              />
              <div className="absolute inset-x-0 bottom-0 bg-gradient-to-t from-black/90 via-black/45 to-transparent p-4 sm:p-5 text-white">
                <p className="text-xs sm:text-sm font-bold uppercase tracking-[0.2em]">Jay Parmar</p>
                <p className="text-[11px] sm:text-xs text-white/80 font-mono tracking-wider">BBA · IIM Bangalore</p>
              </div>
            </div>
          </div>

          {/* Right: Heading & Bio */}
          <div className="lg:col-span-7 flex flex-col justify-between min-w-0">
            <p className="text-xs font-bold uppercase tracking-[0.2em]">01 — WHO I AM</p>
            <hr className="my-[1.5vw] border-none border-t border-black opacity-100" />
            <div>
              <h1 className="text-[clamp(2.5rem,6vw,7rem)] font-bold leading-[0.9] uppercase tracking-tight">
                STRATEGY
                <br />
                MEETS
                <br />
                SYSTEMS
              </h1>
            </div>
            <hr className="my-[1.5vw] border-none border-t border-black opacity-100" />
            <p className="mt-auto max-w-[48ch] text-[clamp(1rem,1.7vw,1.5rem)] font-normal leading-relaxed">
              I’m Jay Parmar — pursuing BBA in Digital Business &amp; Entrepreneurship at IIM Bangalore, interning in AI &amp; Disaster Analytics at IIT Guwahati, and founding ShikshaShakti.AI from Bhilai, India.
            </p>
          </div>
        </div>
      </FlowSection>

      <FlowSection aria-label="Three Aims" style={{ backgroundColor: '#000', color: '#fff' }}>
        <p className="text-xs font-bold uppercase tracking-[0.2em]">02 — THREE AIMS</p>
        <hr className="my-[2vw] border-none border-t border-white/60" />
        <div>
          <h2 className="text-[clamp(2.5rem,8.5vw,9rem)] font-bold leading-[0.9] uppercase tracking-tight">
            OUTCOME
            <br />
            OVER
            <br />
            HYPE
          </h2>
        </div>
        <hr className="my-[2vw] border-none border-t border-white/60" />
        <p className="max-w-[54ch] text-[clamp(1rem,2.3vw,1.9rem)] font-normal leading-relaxed">
          Most energised when an ambitious idea has to survive contact with the real world — classrooms, supply chains, compliance desks, and disaster response teams.
        </p>
        <hr className="my-[2vw] border-none border-t border-white/60" />
        <div className="flex flex-wrap gap-[3vw]">
          <div className="min-w-45 flex-1">
            <p className="mb-2 text-sm font-bold uppercase tracking-wider">01 BUILD USEFUL INTELLIGENCE</p>
            <p className="text-[clamp(0.95rem,1.35vw,1.1rem)] leading-relaxed text-neutral-200">
              From &lt;12ms GNN+XGBoost AML screening to 233 chapters of offline adaptive learning backed by a ₹2L DST-NIDHI grant.
            </p>
          </div>
          <div className="min-w-45 flex-1">
            <p className="mb-2 text-sm font-bold uppercase tracking-wider">02 CREATE FROM INDIA, FOR THE WORLD</p>
            <p className="text-[clamp(0.95rem,1.35vw,1.1rem)] leading-relaxed text-neutral-200">
              Proof that rigorous product engineering, ₹47.5L unit-economics modeling, and national wins start right where you stand.
            </p>
          </div>
          <div className="min-w-45 flex-1">
            <p className="mb-2 text-sm font-bold uppercase tracking-wider">03 GROW THROUGH SERVICE</p>
            <p className="text-[clamp(0.95rem,1.35vw,1.1rem)] leading-relaxed text-neutral-200">
              Coordinating corporate outreach at CSVTU T&amp;P Cell, incubation budgets at CSVTU-FORTE i-TBI, and disaster telemetry at IIT Guwahati.
            </p>
          </div>
        </div>
      </FlowSection>

      <FlowSection aria-label="How it works" style={{ backgroundColor: '#F5F0E8', color: '#000' }}>
        <p className="text-xs font-bold uppercase tracking-[0.2em]">03 — HOW I WORK</p>
        <hr className="my-[2vw] border-none border-t border-black/60" />
        <div>
          <h2 className="text-[clamp(2.5rem,8.5vw,9rem)] font-bold leading-[0.9] uppercase tracking-tight">
            MODEL.
            <br />
            BUILD.
            <br />
            PROVE.
          </h2>
        </div>
        <hr className="my-[2vw] border-none border-t border-black/60" />
        <p className="max-w-[54ch] text-[clamp(1rem,2.3vw,1.9rem)] font-normal leading-relaxed">
          Combine quantitative ROI modeling with production Python, FastAPI, Claude API, and React execution — then validate until the numbers hold up.
        </p>
      </FlowSection>

      <FlowSection aria-label="Track Record" style={{ backgroundColor: '#1A3DE8', color: '#fff' }}>
        <p className="text-xs font-bold uppercase tracking-[0.2em]">04 — TRACK RECORD</p>
        <hr className="my-[2vw] border-none border-t border-white/50" />
        <div>
          <h2 className="text-[clamp(2.5rem,8.5vw,9rem)] font-bold leading-[0.9] uppercase tracking-tight">
            BUILT
            <br />
            UNDER
            <br />
            PRESSURE.
          </h2>
        </div>
        <hr className="my-[2vw] border-none border-t border-white/50" />
        <p className="max-w-[54ch] text-[clamp(1rem,2.3vw,1.9rem)] font-normal leading-relaxed">
          National winner at TCS Foundation × NIT Trichy, 1st Position at PackEdge (IIT Bombay Techfest), Hack-LLM winner at IIIT Delhi, and Top 20 at IIM Bangalore YLS (70,000+ applicants).
        </p>
      </FlowSection>

      <FlowSection aria-label="Let's Talk" style={{ backgroundColor: '#000', color: '#fff' }}>
        <p className="text-xs font-bold uppercase tracking-[0.2em]">05 — LET&apos;S TALK</p>
        <hr className="my-[2vw] border-none border-t border-white/60" />
        <div>
          <h2 className="text-[clamp(2.5rem,8.5vw,9rem)] font-bold leading-[0.9] uppercase tracking-tight">
            COMPLEX
            <br />
            PROBLEM?
            <br />
            LET&apos;S SOLVE IT.
          </h2>
        </div>
        <hr className="my-[2vw] border-none border-t border-white/60" />
        <p className="mt-auto max-w-[54ch] text-[clamp(1rem,2.3vw,1.9rem)] font-normal leading-relaxed">
          Open to AI/ML engineering, finance &amp; strategy analysis, and high-ownership product roles. Reach me at jaydeepak2532006@gmail.com.
        </p>
      </FlowSection>
    </FlowArt>
  );
}
```

---

## components/ui/story-scroll.tsx

**File Path**: `components/ui/story-scroll.tsx` | **Lines**: 143

```tsx
'use client';

import React, { useEffect, useRef, useState } from 'react';
import { gsap } from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import { useGSAP } from '@gsap/react';

gsap.registerPlugin(ScrollTrigger);

function cx(...parts: Array<string | undefined | false | null>): string {
  return parts.filter(Boolean).join(' ');
}

export interface FlowSectionProps {
  className?: string;
  style?: React.CSSProperties;
  children: React.ReactNode;
  'aria-label'?: string;
}

export const FlowSection: React.FC<FlowSectionProps> = ({
  className,
  style = {},
  children,
  'aria-label': ariaLabel,
}) => (
  <section
    data-flow-section
    aria-label={ariaLabel}
    className={cx('relative min-h-screen w-full overflow-hidden', className)}
  >
    <div
      data-flow-inner
      className={cx(
        'flow-art-container relative flex min-h-screen w-full flex-col justify-between',
        'will-change-transform',
      )}
      style={{
        transformOrigin: 'bottom left',
        paddingLeft: 'clamp(2.5rem, 12vw, 12rem)',
        paddingRight: 'clamp(2.5rem, 12vw, 12rem)',
        paddingTop: 'clamp(3.5rem, 10vw, 8rem)',
        paddingBottom: 'clamp(3.5rem, 8vw, 7rem)',
        rowGap: 'clamp(1.5rem, 3vw, 3rem)',
        ...style,
      }}
    >
      {children}
    </div>
  </section>
);

export interface FlowArtProps {
  children: React.ReactNode;
  className?: string;
  'aria-label'?: string;
}

const childCount = (children: React.ReactNode) => React.Children.count(children);

const FlowArt: React.FC<FlowArtProps> = ({
  children,
  className,
  'aria-label': ariaLabel = 'Story scroll',
}) => {
  const containerRef = useRef<HTMLElement>(null);
  const [reducedMotion, setReducedMotion] = useState(false);

  useEffect(() => {
    const mq = window.matchMedia('(prefers-reduced-motion: reduce)');
    const update = () => setReducedMotion(mq.matches);
    update();
    mq.addEventListener('change', update);
    return () => mq.removeEventListener('change', update);
  }, []);

  useGSAP(
    () => {
      if (!containerRef.current || reducedMotion) return;

      const sections = Array.from(
        containerRef.current.querySelectorAll<HTMLElement>('[data-flow-section]'),
      );
      if (sections.length === 0) return;

      const triggers: ScrollTrigger[] = [];

      sections.forEach((section, i) => {
        gsap.set(section, { zIndex: i + 1 });

        const inner = section.querySelector<HTMLElement>('.flow-art-container');
        if (!inner) return;

        if (i > 0) {
          gsap.set(inner, { rotation: 30, transformOrigin: 'bottom left' });
          const tween = gsap.to(inner, {
            rotation: 0,
            ease: 'none',
            scrollTrigger: {
              trigger: section,
              start: 'top bottom',
              end: 'top 25%',
              scrub: true,
            },
          });
          if (tween.scrollTrigger) triggers.push(tween.scrollTrigger);
        }

        if (i < sections.length - 1) {
          triggers.push(
            ScrollTrigger.create({
              trigger: section,
              start: 'bottom bottom',
              end: 'bottom top',
              pin: true,
              pinSpacing: false,
            }),
          );
        }
      });

      ScrollTrigger.refresh();

      return () => {
        triggers.forEach((t) => t.kill());
      };
    },
    { scope: containerRef, dependencies: [childCount(children), reducedMotion] },
  );

  return (
    <main
      ref={containerRef}
      aria-label={ariaLabel}
      className={cx('w-full overflow-x-hidden', className)}
    >
      {children}
    </main>
  );
};

export default FlowArt;
```

---

## components/ui/tabs.tsx

**File Path**: `components/ui/tabs.tsx` | **Lines**: 83

```tsx
"use client"

import { Tabs as TabsPrimitive } from "@base-ui/react/tabs"
import { cva, type VariantProps } from "class-variance-authority"

import { cn } from "@/lib/utils"

function Tabs({
  className,
  orientation = "horizontal",
  ...props
}: TabsPrimitive.Root.Props) {
  return (
    <TabsPrimitive.Root
      data-slot="tabs"
      data-orientation={orientation}
      className={cn(
        "group/tabs flex gap-2 data-horizontal:flex-col",
        className
      )}
      {...props}
    />
  )
}

const tabsListVariants = cva(
  "group/tabs-list inline-flex w-fit items-center justify-center rounded-lg p-[3px] text-muted-foreground group-data-horizontal/tabs:h-8 group-data-vertical/tabs:h-fit group-data-vertical/tabs:flex-col data-[variant=line]:rounded-none",
  {
    variants: {
      variant: {
        default: "bg-muted",
        line: "gap-1 bg-transparent",
      },
    },
    defaultVariants: {
      variant: "default",
    },
  }
)

function TabsList({
  className,
  variant = "default",
  ...props
}: TabsPrimitive.List.Props & VariantProps<typeof tabsListVariants>) {
  return (
    <TabsPrimitive.List
      data-slot="tabs-list"
      data-variant={variant}
      className={cn(tabsListVariants({ variant }), className)}
      {...props}
    />
  )
}

function TabsTrigger({ className, ...props }: TabsPrimitive.Tab.Props) {
  return (
    <TabsPrimitive.Tab
      data-slot="tabs-trigger"
      className={cn(
        "relative inline-flex h-[calc(100%-1px)] flex-1 items-center justify-center gap-1.5 rounded-md border border-transparent px-1.5 py-0.5 text-sm font-medium whitespace-nowrap text-foreground/60 transition-all group-data-vertical/tabs:w-full group-data-vertical/tabs:justify-start hover:text-foreground focus-visible:border-ring focus-visible:ring-[3px] focus-visible:ring-ring/50 focus-visible:outline-1 focus-visible:outline-ring disabled:pointer-events-none disabled:opacity-50 has-data-[icon=inline-end]:pr-1 has-data-[icon=inline-start]:pl-1 aria-disabled:pointer-events-none aria-disabled:opacity-50 dark:text-muted-foreground dark:hover:text-foreground group-data-[variant=default]/tabs-list:data-active:shadow-sm group-data-[variant=line]/tabs-list:data-active:shadow-none [&_svg]:pointer-events-none [&_svg]:shrink-0 [&_svg:not([class*='size-'])]:size-4",
        "group-data-[variant=line]/tabs-list:bg-transparent group-data-[variant=line]/tabs-list:data-active:bg-transparent dark:group-data-[variant=line]/tabs-list:data-active:border-transparent dark:group-data-[variant=line]/tabs-list:data-active:bg-transparent",
        "data-active:bg-background data-active:text-foreground dark:data-active:border-input dark:data-active:bg-input/30 dark:data-active:text-foreground",
        "after:absolute after:bg-foreground after:opacity-0 after:transition-opacity group-data-horizontal/tabs:after:inset-x-0 group-data-horizontal/tabs:after:bottom-[-5px] group-data-horizontal/tabs:after:h-0.5 group-data-vertical/tabs:after:inset-y-0 group-data-vertical/tabs:after:-right-1 group-data-vertical/tabs:after:w-0.5 group-data-[variant=line]/tabs-list:data-active:after:opacity-100",
        className
      )}
      {...props}
    />
  )
}

function TabsContent({ className, ...props }: TabsPrimitive.Panel.Props) {
  return (
    <TabsPrimitive.Panel
      data-slot="tabs-content"
      className={cn("flex-1 text-sm outline-none", className)}
      {...props}
    />
  )
}

export { Tabs, TabsList, TabsTrigger, TabsContent, tabsListVariants }
```

---

## components/ui/text-type.css

**File Path**: `components/ui/text-type.css` | **Lines**: 15

```css
.text-type {
  display: inline-block;
  white-space: pre-wrap;
}

.text-type__cursor {
  margin-left: 0.25rem;
  display: inline-block;
  opacity: 1;
}

.text-type__cursor--hidden {
  display: none;
}
```

---

## components/ui/text-type.tsx

**File Path**: `components/ui/text-type.tsx` | **Lines**: 204

```tsx
"use client";
import {
  useEffect,
  useRef,
  useState,
  createElement,
  useMemo,
  useCallback,
  type ElementType,
  type ReactNode,
  type CSSProperties,
} from "react";
import { gsap } from "gsap";
import "./text-type.css";

export interface TextTypeProps {
  text: string | string[];
  as?: ElementType;
  typingSpeed?: number;
  initialDelay?: number;
  pauseDuration?: number;
  deletingSpeed?: number;
  loop?: boolean;
  className?: string;
  showCursor?: boolean;
  hideCursorWhileTyping?: boolean;
  cursorCharacter?: string | ReactNode;
  cursorClassName?: string;
  cursorBlinkDuration?: number;
  textColors?: string[];
  variableSpeed?: { min: number; max: number };
  onSentenceComplete?: (sentence: string, index: number) => void;
  startOnVisible?: boolean;
  reverseMode?: boolean;
  style?: CSSProperties;
}

const TextType = ({
  text,
  as: Component = "div",
  typingSpeed = 50,
  initialDelay = 0,
  pauseDuration = 2000,
  deletingSpeed = 30,
  loop = true,
  className = "",
  showCursor = true,
  hideCursorWhileTyping = false,
  cursorCharacter = "|",
  cursorClassName = "",
  cursorBlinkDuration = 0.5,
  textColors = [],
  variableSpeed,
  onSentenceComplete,
  startOnVisible = false,
  reverseMode = false,
  ...props
}: TextTypeProps) => {
  const [displayedText, setDisplayedText] = useState("");
  const [currentCharIndex, setCurrentCharIndex] = useState(0);
  const [isDeleting, setIsDeleting] = useState(false);
  const [currentTextIndex, setCurrentTextIndex] = useState(0);
  const [isVisible, setIsVisible] = useState(!startOnVisible);
  const cursorRef = useRef<HTMLSpanElement | null>(null);
  const containerRef = useRef<HTMLElement | null>(null);

  const textArray = useMemo(
    () => (Array.isArray(text) ? text : [text]),
    [text]
  );

  const getRandomSpeed = useCallback(() => {
    if (!variableSpeed) return typingSpeed;
    const { min, max } = variableSpeed;
    return Math.random() * (max - min) + min;
  }, [variableSpeed, typingSpeed]);

  const getCurrentTextColor = () => {
    if (textColors.length === 0) return "inherit";
    return textColors[currentTextIndex % textColors.length];
  };

  useEffect(() => {
    if (!startOnVisible || !containerRef.current) return;
    const observer = new IntersectionObserver(
      (entries) => {
        entries.forEach((entry) => {
          if (entry.isIntersecting) setIsVisible(true);
        });
      },
      { threshold: 0.1 }
    );
    observer.observe(containerRef.current);
    return () => observer.disconnect();
  }, [startOnVisible]);

  useEffect(() => {
    if (showCursor && cursorRef.current) {
      gsap.set(cursorRef.current, { opacity: 1 });
      gsap.to(cursorRef.current, {
        opacity: 0,
        duration: cursorBlinkDuration,
        repeat: -1,
        yoyo: true,
        ease: "power2.inOut",
      });
    }
  }, [showCursor, cursorBlinkDuration]);

  useEffect(() => {
    if (!isVisible) return;
    let timeout: ReturnType<typeof setTimeout> | undefined;
    const currentText = textArray[currentTextIndex];
    const processedText = reverseMode
      ? currentText.split("").reverse().join("")
      : currentText;

    const executeTypingAnimation = () => {
      if (isDeleting) {
        if (displayedText === "") {
          setIsDeleting(false);
          if (currentTextIndex === textArray.length - 1 && !loop) return;
          if (onSentenceComplete)
            onSentenceComplete(textArray[currentTextIndex], currentTextIndex);
          setCurrentTextIndex((prev) => (prev + 1) % textArray.length);
          setCurrentCharIndex(0);
          timeout = setTimeout(() => {}, pauseDuration);
        } else {
          timeout = setTimeout(() => {
            setDisplayedText((prev) => prev.slice(0, -1));
          }, deletingSpeed);
        }
      } else {
        if (currentCharIndex < processedText.length) {
          timeout = setTimeout(
            () => {
              setDisplayedText((prev) => prev + processedText[currentCharIndex]);
              setCurrentCharIndex((prev) => prev + 1);
            },
            variableSpeed ? getRandomSpeed() : typingSpeed
          );
        } else if (textArray.length >= 1) {
          if (!loop && currentTextIndex === textArray.length - 1) return;
          timeout = setTimeout(() => setIsDeleting(true), pauseDuration);
        }
      }
    };

    if (currentCharIndex === 0 && !isDeleting && displayedText === "") {
      timeout = setTimeout(executeTypingAnimation, initialDelay);
    } else {
      executeTypingAnimation();
    }
    return () => {
      if (timeout) clearTimeout(timeout);
    };
    // eslint-disable-next-line react-hooks/exhaustive-deps
  }, [
    currentCharIndex,
    displayedText,
    isDeleting,
    typingSpeed,
    deletingSpeed,
    pauseDuration,
    textArray,
    currentTextIndex,
    loop,
    initialDelay,
    isVisible,
    reverseMode,
    variableSpeed,
    onSentenceComplete,
  ]);

  const shouldHideCursor =
    hideCursorWhileTyping &&
    (currentCharIndex < textArray[currentTextIndex].length || isDeleting);

  return createElement(
    Component,
    {
      ref: containerRef,
      className: `text-type ${className}`,
      ...props,
    },
    <span
      className="text-type__content"
      style={{ color: getCurrentTextColor() || "inherit" }}
    >
      {displayedText}
    </span>,
    showCursor && (
      <span
        ref={cursorRef}
        className={`text-type__cursor ${cursorClassName} ${shouldHideCursor ? "text-type__cursor--hidden" : ""}`}
      >
        {cursorCharacter}
      </span>
    )
  );
};

export default TextType;
```

---

## components/ui/vscode-portfolio.tsx

**File Path**: `components/ui/vscode-portfolio.tsx` | **Lines**: 1110

```tsx
"use client";
import React from "react";
import Image from "next/image";
import { FileTree, type FileNode } from "@/components/ui/file-tree";
import { SpotlightSearch } from "@/components/ui/apple-spotlight";
import MacOSMenuBar from "@/components/ui/mac-os-menu-bar";
import { getLenis } from "@/hooks/useLenis";
import Safari_01 from "@/components/ui/safari-01";
import { ButtonCta } from "@/components/ui/button-shiny";
import LogoLoop from "@/components/ui/logo-loop";
import ScrollStack, { ScrollStackItem } from "@/components/ui/scroll-stack";
import TextType from "@/components/ui/text-type";
import { ProjectModal, type Project } from "@/components/ui/project-modal";

/* ---------- Tiny icon set (inline SVG) ---------- */
const I = {
  files: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M14 4.5V14a1 1 0 0 1-1 1H5v-1h8V5h-2.5L9 3.5H5V8H4V3a1 1 0 0 1 1-1h4.5L14 4.5Z" fill="currentColor"/>
      <path d="M3 6h7v9H3a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Z" fill="currentColor" fillOpacity=".55"/>
    </svg>
  ),
  search: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M11.5 7a4.5 4.5 0 1 1-9 0 4.5 4.5 0 0 1 9 0Zm-.82 4.39A6 6 0 1 1 11.39 10.68l3.46 3.46-.7.71-3.47-3.46Z" fill="currentColor"/>
    </svg>
  ),
  git: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M11.5 5a1.5 1.5 0 1 0-2.62 1l-2.05 3.46a1.5 1.5 0 1 0 .86.5L9.74 6.5A1.5 1.5 0 0 0 11.5 5Zm-7 5a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3Z" fill="currentColor"/>
    </svg>
  ),
  debug: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M11 5V3.5L12.5 2l.7.7L12 4h1v1h-1.05A4 4 0 0 1 12 6v1h2v1h-2v1h2v1h-2.05A4 4 0 0 1 4.05 10H2V9h2V8H2V7h2V6h-.05A4 4 0 0 1 4 5H3V4h1L2.8 2.7l.7-.7L5 3.5V5h6Z" fill="currentColor"/>
    </svg>
  ),
  ext: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M7 2H3a1 1 0 0 0-1 1v4h1V3h4V2Zm6 6h-1V4h-4V3h5v5ZM3 9H2v4a1 1 0 0 0 1 1h4v-1H3V9Zm10 0h-1v4H8v1h5v-5Z" fill="currentColor"/>
    </svg>
  ),
  warn: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M8 2 1.5 13.5h13L8 2Zm.5 8.5h-1v-4h1v4Zm0 2h-1v-1h1v1Z" fill="currentColor"/>
    </svg>
  ),
  beaker: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M6 2v4.2L2.4 12.5A1.5 1.5 0 0 0 3.7 14.7h8.6a1.5 1.5 0 0 0 1.3-2.2L10 6.2V2H6Zm1 1h2v3.5l1.4 2.5H5.6L7 6.5V3Z" fill="currentColor"/>
    </svg>
  ),
  cube: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M8 1.5 2 4.5v7L8 14.5l6-3v-7L8 1.5Zm0 1.1 4.6 2.3L8 7.2 3.4 4.9 8 2.6ZM3 6l4.5 2.3v5L3 11V6Zm5.5 7.3v-5L13 6v5l-4.5 2.3Z" fill="currentColor"/>
    </svg>
  ),
  chev: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="m6 4 4 4-4 4" stroke="currentColor" strokeWidth="1.2" strokeLinecap="round" strokeLinejoin="round"/>
    </svg>
  ),
  arrow: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M3 8h10m0 0L9 4m4 4-4 4" stroke="currentColor" strokeWidth="1.3" strokeLinecap="round" strokeLinejoin="round"/>
    </svg>
  ),
  copy: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <rect x="5" y="5" width="8" height="8" rx="1.2" stroke="currentColor" strokeWidth="1.1"/>
      <path d="M3 11V3.6A.6.6 0 0 1 3.6 3H11" stroke="currentColor" strokeWidth="1.1"/>
    </svg>
  ),
  ext_arrow: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M6 4h6v6m0-6L5 11" stroke="currentColor" strokeWidth="1.4" strokeLinecap="round"/>
    </svg>
  ),
  mouse: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <rect x="4" y="2" width="8" height="12" rx="4" stroke="currentColor" strokeWidth="1.2"/>
      <path d="M8 5v2.5" stroke="currentColor" strokeWidth="1.2" strokeLinecap="round"/>
    </svg>
  ),
  clock: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <circle cx="8" cy="8" r="5.5" stroke="currentColor" strokeWidth="1.2"/>
      <path d="M8 5v3l2 1.5" stroke="currentColor" strokeWidth="1.2" strokeLinecap="round"/>
    </svg>
  ),
  chat: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M2.5 3.5h11v7h-5l-3 2.5v-2.5h-3v-7Z" stroke="currentColor" strokeWidth="1.2" strokeLinejoin="round"/>
    </svg>
  ),
  stack: (p: any) => (
    <svg viewBox="0 0 16 16" fill="none" {...p}>
      <path d="M8 2 2 5l6 3 6-3-6-3Zm-6 6 6 3 6-3M2 11l6 3 6-3" stroke="currentColor" strokeWidth="1.2" strokeLinejoin="round"/>
    </svg>
  ),
};

/* ---------- File tree data ---------- */
const fileStructure: FileNode[] = [
  {
    name: "profile",
    type: "folder",
    children: [
      { name: "jay-parmar.ts", type: "file", extension: "ts" },
      { name: "iim-bangalore.md", type: "file", extension: "md" },
      { name: "iit-guwahati.ts", type: "file", extension: "ts" },
      { name: "experience.tsx", type: "file", extension: "tsx" },
    ],
  },
  {
    name: "ventures",
    type: "folder",
    children: [
      { name: "ShikshaShakti.tsx", type: "file", extension: "tsx" },
      { name: "PackEdge.ts", type: "file", extension: "ts" },
      { name: "NextGenAML.tsx", type: "file", extension: "tsx" },
      { name: "FDR-Setu.ts", type: "file", extension: "ts" },
      { name: "CryptoTrace.ts", type: "file", extension: "ts" },
    ],
  },
  {
    name: "intelligence",
    type: "folder",
    children: [
      { name: "claude-pipeline.ts", type: "file", extension: "ts" },
      { name: "gnn-xgboost.ts", type: "file", extension: "ts" },
      { name: "roi-model.ts", type: "file", extension: "ts" },
    ],
  },
  {
    name: "credentials",
    type: "folder",
    children: [
      { name: "achievements.json", type: "file", extension: "json" },
      { name: "certificates.json", type: "file", extension: "json" },
      { name: "skills-matrix.ts", type: "file", extension: "ts" },
    ],
  },
  {
    name: "articles",
    type: "folder",
    children: [
      { name: "essays-13.md", type: "file", extension: "md" },
    ],
  },
  { name: "Jay-Parmar-Resume.json", type: "file", extension: "json" },
  { name: "README.md", type: "file", extension: "md" },
];

/* ---------- Section label ---------- */
const SectionLabel: React.FC<{ children: React.ReactNode }> = ({ children }) => (
  <div className="flex items-center" style={{ gap: "10px", marginBottom: "16px" }}>
    <span className="text-[10px] tracking-[0.22em] text-[#7a7a7a] font-mono uppercase">{children}</span>
    <span
      aria-hidden
      className="flex-1 h-px"
      style={{ background: "linear-gradient(90deg, rgba(167,139,250,0.18), transparent)" }}
    />
  </div>
);

/* ---------- Tech stack icons ---------- */
const TechIcon = ({ kind }: { kind: string }) => {
  const base = "w-full h-full flex items-center justify-center";
  if (kind === "react")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="none">
          <circle cx="12" cy="12" r="2" fill="#61dafb"/>
          <g stroke="#61dafb" strokeWidth="1" fill="none">
            <ellipse cx="12" cy="12" rx="10" ry="4"/>
            <ellipse cx="12" cy="12" rx="10" ry="4" transform="rotate(60 12 12)"/>
            <ellipse cx="12" cy="12" rx="10" ry="4" transform="rotate(120 12 12)"/>
          </g>
        </svg>
      </div>
    );
  if (kind === "next")
    return (
      <div className={base}>
        <div className="w-7 h-7 rounded-full bg-white text-black font-bold flex items-center justify-center text-[14px]" style={{ fontFamily: "serif" }}>N</div>
      </div>
    );
  if (kind === "ts")
    return (
      <div className={base}>
        <div className="w-7 h-7 rounded-[5px] bg-[#3178c6] text-white font-bold flex items-center justify-center text-[12px]">TS</div>
      </div>
    );
  if (kind === "tw")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="#38bdf8">
          <path d="M12 6c-2.7 0-4.4 1.35-5 4 .9-1.2 1.95-1.65 3.15-1.35.685.17 1.174.668 1.716 1.218C12.728 10.764 13.74 11.85 16 11.85c2.7 0 4.4-1.35 5-4-.9 1.2-1.95 1.65-3.15 1.35-.685-.17-1.174-.668-1.716-1.218C15.272 7.086 14.26 6 12 6Zm-5 6c-2.7 0-4.4 1.35-5 4 .9-1.2 1.95-1.65 3.15-1.35.685.17 1.174.668 1.716 1.218C7.728 16.764 8.74 17.85 11 17.85c2.7 0 4.4-1.35 5-4-.9 1.2-1.95 1.65-3.15 1.35-.685-.17-1.174-.668-1.716-1.218C10.272 13.086 9.26 12 7 12Z"/>
        </svg>
      </div>
    );
  if (kind === "js")
    return (
      <div className={base}>
        <div className="w-7 h-7 rounded-[5px] bg-[#5cb85c] text-white font-bold flex items-center justify-center text-[10px]">JS</div>
      </div>
    );
  if (kind === "aws")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="none">
          <path d="M6.7 11.2c0 .3 0 .55.08.74.1.2.22.4.38.62a.38.38 0 0 1 .06.2c0 .08-.05.17-.16.26l-.54.36a.4.4 0 0 1-.22.07c-.08 0-.17-.04-.25-.12a2.6 2.6 0 0 1-.3-.4 6.4 6.4 0 0 1-.26-.5c-.67.79-1.5 1.18-2.5 1.18-.7 0-1.27-.2-1.7-.6-.41-.4-.62-.94-.62-1.6 0-.71.25-1.29.76-1.72.5-.43 1.19-.65 2.05-.65.28 0 .58.03.89.07.3.04.62.1.95.18v-.6c0-.64-.13-1.08-.4-1.34-.27-.26-.73-.39-1.38-.39-.3 0-.6.04-.92.11-.31.07-.62.16-.92.27a2.45 2.45 0 0 1-.3.11.52.52 0 0 1-.13.02c-.12 0-.18-.08-.18-.26v-.41c0-.14.02-.24.06-.3.04-.06.12-.12.24-.18.3-.15.65-.28 1.07-.38.42-.1.86-.16 1.33-.16 1.01 0 1.75.23 2.23.69.47.45.71 1.15.71 2.08v2.75ZM3.27 12.5c.28 0 .57-.05.87-.15.3-.1.57-.28.8-.53.13-.16.23-.34.28-.55.04-.2.07-.45.07-.74v-.36a7 7 0 0 0-.76-.14 6.3 6.3 0 0 0-.78-.05c-.55 0-.96.11-1.23.33-.27.22-.4.54-.4.95 0 .39.1.68.3.88.2.2.49.36.85.36Zm6.79.93a.46.46 0 0 1-.32-.08c-.07-.07-.14-.21-.2-.4l-2.2-7.24a1.8 1.8 0 0 1-.1-.41c0-.16.08-.25.25-.25h.86c.15 0 .26.03.32.08.07.07.13.21.19.4l1.57 6.2 1.46-6.2c.05-.2.11-.33.18-.4a.6.6 0 0 1 .33-.08h.7c.16 0 .27.03.34.08.06.07.13.21.17.4l1.48 6.28 1.62-6.28c.06-.2.13-.33.19-.4a.55.55 0 0 1 .32-.08h.81c.17 0 .26.09.26.25 0 .05-.01.1-.02.16a1.4 1.4 0 0 1-.08.25l-2.25 7.24c-.06.2-.13.32-.2.4a.6.6 0 0 1-.32.07h-.75c-.15 0-.26-.02-.33-.08-.07-.07-.13-.2-.17-.4l-1.45-6.05-1.44 6.04c-.04.2-.1.34-.17.41-.07.06-.19.08-.33.08h-.75ZM20.95 13.61c-.44 0-.88-.05-1.3-.15-.42-.1-.75-.21-.97-.34-.13-.07-.22-.15-.26-.23a.6.6 0 0 1-.05-.24v-.43c0-.18.06-.26.2-.26.05 0 .1.01.16.03.06.02.14.06.23.1.3.13.62.23.96.3.35.07.69.11 1.04.11.55 0 .98-.1 1.27-.29.3-.19.45-.47.45-.83 0-.24-.08-.45-.23-.62-.16-.16-.46-.32-.88-.46l-1.27-.4c-.64-.2-1.11-.5-1.4-.9a2.1 2.1 0 0 1-.45-1.27c0-.36.08-.69.23-.97.16-.28.37-.52.63-.71.27-.2.57-.35.92-.45.36-.1.73-.15 1.12-.15.19 0 .39.02.58.04.2.04.39.07.57.12.18.05.34.1.5.16.16.06.28.13.36.19.12.07.2.14.25.22.04.07.07.16.07.28v.4c0 .19-.07.28-.2.28a.92.92 0 0 1-.34-.1 4.1 4.1 0 0 0-1.73-.36c-.5 0-.89.08-1.16.25-.27.16-.41.42-.41.76 0 .24.1.45.27.62.18.16.5.33.96.48l1.24.4c.64.2 1.09.49 1.36.86.27.36.4.78.4 1.25 0 .37-.07.7-.22.99-.16.3-.37.55-.64.75-.28.21-.61.36-.99.47-.4.12-.81.18-1.26.18ZM21.95 17.5c-2.71 2-6.65 3.07-10.04 3.07-4.74 0-9.02-1.75-12.25-4.66-.26-.23-.03-.55.27-.37 3.5 2.03 7.81 3.26 12.27 3.26 3.02 0 6.32-.63 9.37-1.92.46-.2.85.3.38.62Z" fill="#ff9900"/>
          <path d="M23.08 16.27c-.35-.45-2.3-.22-3.18-.1-.27.03-.31-.2-.07-.37 1.56-1.1 4.12-.78 4.42-.41.3.38-.08 2.94-1.55 4.16-.22.19-.43.09-.34-.16.32-.83 1.03-2.68.72-3.12Z" fill="#ff9900"/>
        </svg>
      </div>
    );
  if (kind === "tf")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="none">
          <path d="M11 2 2 7v10l4 2v-9l5-3v15l4 2V8l5 3V7l-9-5Z" fill="#ff6f00"/>
          <path d="M11 2v17l4 2V8l5 3V7l-9-5Z" fill="#ffa726"/>
        </svg>
      </div>
    );
  if (kind === "hf")
    return (
      <div className={base}>
        <div className="w-7 h-7 rounded-full bg-[#ffd21e] flex items-center justify-center text-[14px]">🤗</div>
      </div>
    );
  if (kind === "lg")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="none">
          <circle cx="6" cy="6" r="2.4" stroke="#a78bfa" strokeWidth="1.3" fill="#1a1330"/>
          <circle cx="18" cy="6" r="2.4" stroke="#f0abfc" strokeWidth="1.3" fill="#1a1330"/>
          <circle cx="12" cy="18" r="2.4" stroke="#c4b5fd" strokeWidth="1.3" fill="#1a1330"/>
          <path d="M6 8.4v3a2 2 0 0 0 2 2h8a2 2 0 0 1 2 2v0M6 8.4a2 2 0 0 0 2 2h2.5M18 8.4a2 2 0 0 1-2 2h-2.5M10.5 10.4l1.5 5M13.5 10.4 12 15.4" stroke="#c4b5fd" strokeWidth="1.1" strokeLinecap="round"/>
        </svg>
      </div>
    );
  if (kind === "claude")
    return (
      <div className={base}>
        <svg viewBox="0 -0.01 39.5 39.53" className="w-7 h-7" fill="none">
          <path d="m7.75 26.27 7.77-4.36.13-.38-.13-.21h-.38l-1.3-.08-4.44-.12-3.85-.16-3.73-.2-.94-.2-.88-1.16.09-.58.79-.53 1.13.1 2.5.17 3.75.26 2.72.16 4.03.42h.64l.09-.26-.22-.16-.17-.16-3.88-2.63-4.2-2.78-2.2-1.6-1.19-.81-.6-.76-.26-1.66 1.08-1.19 1.45.1.37.1 1.47 1.13 3.14 2.43 4.1 3.02.6.5.24-.17.03-.12-.27-.45-2.23-4.03-2.38-4.1-1.06-1.7-.28-1.02c-.1-.42-.17-.77-.17-1.2l1.23-1.67.68-.22 1.64.22.69.6 1.02 2.33 1.65 3.67 2.56 4.99.75 1.48.4 1.37.15.42h.26v-.24l.21-2.81.39-3.45.38-4.44.13-1.25.62-1.5 1.23-.81.96.46.79 1.13-.11.73-.47 3.05-.92 4.78-.6 3.2h.35l.4-.4 1.62-2.15 2.72-3.4 1.2-1.35 1.4-1.49.9-.71h1.7l1.25 1.86-.56 1.92-1.75 2.22-1.45 1.88-2.08 2.8-1.3 2.24.12.18.31-.03 4.7-1 2.54-.46 3.03-.52 1.37.64.15.65-.54 1.33-3.24.8-3.8.76-5.66 1.34-.07.05.08.1 2.55.24 1.09.06h2.67l4.97.37 1.3.86.78 1.05-.13.8-2 1.02-2.7-.64-6.3-1.5-2.16-.54h-.3v.18l1.8 1.76 3.3 2.98 4.13 3.84.21.95-.53.75-.56-.08-3.63-2.73-1.4-1.23-3.17-2.67h-.21v.28l.73 1.07 3.86 5.8.2 1.78-.28.58-1 .35-1.1-.2-2.26-3.17-2.33-3.57-1.88-3.2-.23.13-1.11 11.95-.52.61-1.2.46-1-.76-.53-1.23.53-2.43.64-3.17.52-2.52.47-3.13.28-1.04-.02-.07-.23.03-2.36 3.24-3.59 4.85-2.84 3.04-.68.27-1.18-.61.11-1.09.66-.97 3.93-5 2.37-3.1 1.53-1.79-.01-.26h-.09l-10.44 6.78-1.86.24-.8-.75.1-1.23.38-.4 3.14-2.16z" fill="#d97757"/>
        </svg>
      </div>
    );
  if (kind === "flutter")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="none">
          <path d="M14.3 2 4 12.3l3.2 3.2L20.7 2h-6.4Z" fill="#42a5f5"/>
          <path d="M14.3 13.4 9.2 18.5l3.2 3.2 5.1-5.1-3.2-3.2Z" fill="#0d47a1"/>
          <path d="M9.2 18.5 12.4 21.7h6.4L12.4 15.3 9.2 18.5Z" fill="#42a5f5"/>
          <path d="m12.4 15.3 3.2 3.2-1.3 1.3-3.2-3.2 1.3-1.3Z" fill="#1976d2"/>
        </svg>
      </div>
    );
  if (kind === "github")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="#f0f6fc">
          <path d="M12 2a10 10 0 0 0-3.16 19.49c.5.09.68-.22.68-.48v-1.7c-2.78.6-3.37-1.34-3.37-1.34-.45-1.16-1.11-1.47-1.11-1.47-.91-.62.07-.6.07-.6 1 .07 1.53 1.03 1.53 1.03.9 1.52 2.34 1.08 2.91.83.09-.65.35-1.09.63-1.34-2.22-.25-4.55-1.11-4.55-4.94 0-1.09.39-1.98 1.03-2.68-.1-.25-.45-1.27.1-2.64 0 0 .84-.27 2.75 1.02a9.6 9.6 0 0 1 5 0c1.91-1.29 2.75-1.02 2.75-1.02.55 1.37.2 2.39.1 2.64.64.7 1.03 1.59 1.03 2.68 0 3.84-2.34 4.68-4.57 4.93.36.31.68.92.68 1.85v2.74c0 .27.18.58.69.48A10 10 0 0 0 12 2Z"/>
        </svg>
      </div>
    );
  if (kind === "docker")
    return (
      <div className={base}>
        <svg viewBox="0 0 24 24" className="w-7 h-7" fill="#2496ed">
          <path d="M22.5 9.4c-.06-.05-.6-.46-1.74-.46-.3 0-.6.03-.9.08-.22-1.51-1.47-2.24-1.53-2.27l-.3-.18-.2.28c-.26.4-.45.86-.55 1.34-.2.86-.08 1.66.34 2.34-.5.28-1.32.35-1.5.36H1.6a.6.6 0 0 0-.6.6 8.96 8.96 0 0 0 .56 3.26c.42 1.1 1.04 1.9 1.86 2.39 1.85 1.1 4.04 1.34 5.84 1.34.81 0 1.6-.07 2.32-.2 1-.18 1.96-.5 2.83-.96a8.05 8.05 0 0 0 1.97-1.55c1.07-1.2 1.7-2.53 2.16-3.72.06.01.13.01.2.01 1.21 0 1.95-.49 2.36-.89.27-.26.49-.58.63-.95l.09-.27-.21-.16ZM2.85 10h2.04c.1 0 .18-.08.18-.18V8a.18.18 0 0 0-.18-.18H2.85a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.81 0H7.7c.1 0 .18-.08.18-.18V8a.18.18 0 0 0-.18-.18H5.66a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.85 0h2.04c.1 0 .18-.08.18-.18V8a.18.18 0 0 0-.18-.18H8.51a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.81 0h2.04c.1 0 .18-.08.18-.18V8a.18.18 0 0 0-.18-.18h-2.04a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm-5.66-2.6H7.7c.1 0 .18-.08.18-.18V5.4a.18.18 0 0 0-.18-.18H5.66a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.85 0h2.04c.1 0 .18-.08.18-.18V5.4a.18.18 0 0 0-.18-.18H8.51a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.81 0h2.04c.1 0 .18-.08.18-.18V5.4a.18.18 0 0 0-.18-.18h-2.04a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm0-2.6h2.04c.1 0 .18-.08.18-.18V2.8a.18.18 0 0 0-.18-.18h-2.04a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Zm2.83 5.2h2.04c.1 0 .18-.08.18-.18V8a.18.18 0 0 0-.18-.18h-2.04a.18.18 0 0 0-.18.18v1.82c0 .1.08.18.18.18Z"/>
        </svg>
      </div>
    );
  return null;
};

/* ---------- Main component ---------- */
const featuredProjects: Project[] = [
  {
    title: "ShikshaShakti.AI",
    year: "2025",
    tag: "EdTech · Founder",
    featured: true,
    desc: "Offline-first adaptive learning platform mapping prerequisite gaps across 233 chapters and 157 prerequisite links for low-bandwidth classrooms, backed by a ₹2L DST-NIDHI grant (TRL 4).",
    stack: ["Claude API", "Python", "FastAPI"],
    artwork: "linear-gradient(180deg, #1e1b4b 0%, #5b21b6 50%, #ec4899 100%)",
    image: "/assets/carousel/carousel-33.webp",
    overview:
      "ShikshaShakti.AI is an offline-first adaptive learning and prerequisite-mapping platform engineered for classrooms with unreliable connectivity. Powered by a structured knowledge graph spanning 233 chapters and 157 prerequisite relationships alongside a Claude API question-generation engine, it diagnoses conceptual gaps before generating targeted practice — validated to TRL 4 with ₹2L DST-NIDHI ignition funding.",
    features: [
      "233 chapters & 157 prerequisite links mapped",
      "Claude API adaptive question generation engine",
      "Offline-first architecture for low-bandwidth schools",
      "Diagnostic prerequisite gap detection",
      "TRL 4 prototype validated on field cohorts",
      "₹2L DST-NIDHI ignition grant recipient",
    ],
    links: {
      live: "https://drive.google.com/file/d/1KB5ZEOAgdl6hEC4cCXVQ1u9I0FcxkGHx/view",
      linkedin: "https://www.linkedin.com/in/jay-parmar-ai",
    },
  },
  {
    title: "PackEdge",
    year: "2025",
    tag: "Supply Chain · IIT Bombay 1st",
    featured: true,
    desc: "Partial knock-down (PKD) packaging and logistics redesign for Godrej Interio delivering ₹47.5L projected annual savings, 18.5% less volume, and 33% freight reduction — 1st place at IIT Bombay Techfest.",
    stack: ["ROI Modeling", "Excel", "Analytics"],
    artwork: "linear-gradient(180deg, #0c1e3e 0%, #1e3a8a 45%, #7c3aed 100%)",
    image: "/assets/carousel/carousel-25.webp",
    overview:
      "Built for the PackEdge national supply-chain challenge at IIT Bombay Techfest, this partial knock-down (PKD) packaging redesign for Godrej Interio re-engineered carton geometry and pallet utilization. Quantitative unit-economics modeling demonstrated 25% higher truck loadability, 18.5% volume compression, and a 33% drop in freight spend — projecting ₹47.5L in annual cost savings.",
    features: [
      "₹47.5L projected annual supply-chain savings",
      "18.5% packaging volume reduction",
      "33% outbound freight cost reduction",
      "25% improvement in truck loadability",
      "End-to-end financial & ROI sensitivity model",
      "1st Position — Techfest, IIT Bombay",
    ],
    links: {
      live: "https://drive.google.com/file/d/198jU7tjaPgLchEVKDLTQ7UO2OzyOkM91/view",
      linkedin: "https://www.linkedin.com/in/jay-parmar-ai",
    },
  },
  {
    title: "NextGenAML",
    year: "2025",
    tag: "FinTech · TCS National Winner",
    featured: true,
    desc: "Real-time anti-money-laundering screening engine fusing Graph Neural Networks, XGBoost, FATF rules, and LLM-assisted case triage with <12ms latency and 0.78 ROC-AUC.",
    stack: ["GNN", "XGBoost", "Neo4j"],
    artwork: "linear-gradient(180deg, #042f2e 0%, #134e4a 40%, #7c3aed 100%)",
    image: "/assets/carousel/carousel-35.webp",
    overview:
      "Winner of the TCS Foundation 36-hour national hackathon at NIT Tiruchirappalli, NextGenAML pairs low-latency transaction screening (<12ms) with structural ring detection. By combining Graph Neural Networks, XGBoost classification (0.78 ROC-AUC), deterministic FATF rule checks, and LLM-generated investigator narratives, compliance analysts move directly to high-signal cases.",
    features: [
      "<12ms real-time transaction screening latency",
      "0.78 ROC-AUC across hybrid GNN + XGBoost scoring",
      "Automated FATF typology rules engine",
      "Neo4j transaction graph ring visualization",
      "LLM-assisted SAR / case triage briefs",
      "National Winner — TCS Foundation @ NIT Trichy",
    ],
    links: {
      github: "https://github.com/jay2532006",
      linkedin: "https://www.linkedin.com/in/jay-parmar-ai",
    },
  },
];

export const VSCodePortfolio: React.FC = () => {
  const [activeProject, setActiveProject] = React.useState<Project | null>(null);
  return (
    <div className="w-full h-full bg-[#0a0a0a] text-[#cccccc] flex flex-col overflow-hidden rounded-[6px]"
      style={{ fontFamily: "'SF Pro Text', -apple-system, system-ui, sans-serif", fontSize: 12 }}>

      {/* ===== macOS menu bar ===== */}
      <div className="shrink-0">
        <MacOSMenuBar appName="Portfolio" />
      </div>

      {/* ===== Title bar ===== */}
      <div className="flex items-center h-[38px] px-5 bg-[#0a0a0a] border-b border-[#1a1a1a] shrink-0">
        {/* Back / forward */}
        <div className="flex items-center gap-3 text-[#7a7a7a] mr-auto">
          <button className="w-5 h-5 flex items-center justify-center"><svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><path d="M10 4 6 8l4 4" stroke="currentColor" strokeWidth="1.4" fill="none" strokeLinecap="round"/></svg></button>
          <button className="w-5 h-5 flex items-center justify-center"><svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><path d="M6 4l4 4-4 4" stroke="currentColor" strokeWidth="1.4" fill="none" strokeLinecap="round"/></svg></button>
        </div>
        {/* Spotlight search (⌘K) */}
        <div className="flex-1 max-w-[420px] -ml-10 h-[22px] flex items-center">
          <SpotlightSearch triggerClassName="w-full h-[22px]" />
        </div>
        {/* Right cluster */}
        <div className="ml-auto flex items-center gap-3 text-[#7a7a7a]">
          <span className="flex items-center gap-1 text-[10px] text-[#bdbdbd]"><span className="w-2 h-2 rounded-full bg-[#3b82f6]"></span>2</span>
          <I.chev className="w-3 h-3 -ml-1" />
          <div className="flex items-center gap-2 ml-2">
            <svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><rect x="2" y="3" width="12" height="10" rx="1" stroke="currentColor" fill="none"/><path d="M9 3v10" stroke="currentColor"/></svg>
            <svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><rect x="2" y="3" width="12" height="10" rx="1" stroke="currentColor" fill="none"/><path d="M2 8h12" stroke="currentColor"/></svg>
            <svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><rect x="2" y="3" width="12" height="10" rx="1" stroke="currentColor" fill="none"/><rect x="9" y="3" width="5" height="10" fill="currentColor" opacity=".4"/></svg>
            <svg viewBox="0 0 16 16" className="w-3.5 h-3.5"><rect x="2" y="3" width="12" height="10" rx="1" stroke="currentColor" fill="none"/><rect x="11" y="3" width="3" height="10" fill="currentColor" opacity=".4"/></svg>
          </div>
        </div>
      </div>

      {/* ===== Body ===== */}
      <div className="flex flex-1 min-h-0">
        {/* Activity bar */}
        <div className="w-[44px] bg-[#0a0a0a] border-r border-[#1a1a1a] flex flex-col items-center py-2 shrink-0 text-[#6f6f6f]">
          <div className="relative w-full flex justify-center py-2 text-white">
            <span className="absolute left-0 top-0 h-full w-[2px] bg-white"></span>
            <I.files className="w-5 h-5" />
          </div>
          <div className="py-2.5"><I.cube className="w-5 h-5" /></div>
          <div className="py-2.5"><I.beaker className="w-5 h-5" /></div>
          <div className="py-2.5"><I.search className="w-5 h-5" /></div>
          <div className="py-2.5"><I.git className="w-5 h-5" /></div>
          <div className="py-2.5"><I.debug className="w-5 h-5" /></div>
          <div className="py-2.5"><I.ext className="w-5 h-5" /></div>
          <div className="py-2.5 text-[#f59e0b]"><I.warn className="w-5 h-5" /></div>
          <div className="py-2.5"><I.beaker className="w-5 h-5" /></div>
          <div className="py-2.5"><I.cube className="w-5 h-5" /></div>
          <div className="py-2.5"><I.stack className="w-5 h-5" /></div>
          <div className="mt-auto flex flex-col items-center gap-3 pb-1">
            <div className="relative">
              <div className="relative w-6 h-6 rounded-full overflow-hidden border border-[#a78bfa]/60 bg-[#1a1625]">
                <Image
                  src="/assets/portfolio/gallery/gallery-03.jpg"
                  alt="Jay Parmar"
                  fill
                  sizes="24px"
                  className="object-cover object-[50%_54%] scale-[2]"
                />
              </div>
              <span className="absolute -bottom-0.5 -right-0.5 w-2.5 h-2.5 rounded-full bg-[#3b82f6] text-white text-[8px] flex items-center justify-center">1</span>
            </div>
            <svg viewBox="0 0 16 16" className="w-5 h-5" fill="none" stroke="currentColor"><circle cx="8" cy="8" r="2.2"/><path d="M8 1v2M8 13v2M1 8h2M13 8h2M3 3l1.4 1.4M11.6 11.6 13 13M3 13l1.4-1.4M11.6 4.4 13 3" strokeWidth="1.1"/></svg>
          </div>
        </div>

        {/* Explorer */}
        <div className="hidden md:flex w-[210px] bg-[#0a0a0a] border-r border-[#1a1a1a] shrink-0 flex-col">
          <div className="flex items-center justify-between px-3 pt-3 pb-2">
            <span className="text-[11px] tracking-[0.12em] text-[#9a9a9a]">EXPLORER</span>
            <span className="text-[#6f6f6f]">⋯</span>
          </div>
          <div className="px-2 flex-1 overflow-y-auto [scrollbar-width:none] [&::-webkit-scrollbar]:hidden">
            <div className="flex items-center px-1 py-[3px] text-[11px] text-[#cfcfcf] font-medium">
              <I.chev className="w-3 h-3 mr-1 rotate-90 text-[#9a9a9a]" />
              <span>JAY-PARMAR.FOLIO</span>
            </div>
            <FileTree
              data={fileStructure}
              defaultOpen={true}
              initialActive="profile/jay-parmar.ts"
              className="mt-1 pb-2"
            />
          </div>
          <div className="px-3 py-2 border-t border-[#161616] text-[11px] tracking-[0.12em] text-[#9a9a9a] flex items-center">
            <I.chev className="w-3 h-3 mr-1" /> OUTLINE
          </div>
          <div className="px-3 py-2 border-t border-[#161616] text-[11px] tracking-[0.12em] text-[#9a9a9a] flex items-center">
            <I.chev className="w-3 h-3 mr-1" /> TIMELINE
          </div>
        </div>

        {/* Editor + Right panel */}
        <div className="flex-1 flex min-w-0 bg-[#0d0d0d]">
          {/* Editor */}
          <div className="flex-1 flex flex-col min-w-0">
            {/* Tab bar */}
            <div className="h-[30px] bg-[#0a0a0a] border-b border-[#1a1a1a] flex items-center text-[11px] shrink-0">
              <div className="h-full flex items-center gap-2 px-3 bg-[#0d0d0d] border-r border-[#1a1a1a] text-white">
                <svg viewBox="0 0 16 16" className="w-3 h-3 text-[#519aba]" fill="currentColor"><path d="M2 2h12v12H2z" opacity=".15"/><path d="M3 8h2v1H3v2h3v1H2V8Zm5 0h5v1h-2v4h-1V9H8V8Z"/></svg>
                Welcome
                <span className="ml-2 text-[#7a7a7a] hover:text-white">×</span>
              </div>
            </div>

            {/* Editor body */}
            <div className="flex-1 overflow-auto px-4 sm:px-10 md:px-16 lg:px-20 pt-6 sm:pt-12 md:pt-20 pb-16 min-w-0 [scrollbar-width:none] [&::-webkit-scrollbar]:hidden">
              <p className="text-base sm:text-[22px] text-[#cfcfcf]" style={{ marginTop: "12px", marginLeft: "clamp(8px, 2vw, 24px)", marginBottom: "4px" }}>Hi, I&apos;m</p>
              <h1 className="text-4xl sm:text-6xl md:text-8xl lg:text-[104px] leading-[1.05] font-bold tracking-tight" style={{ marginBottom: "16px", marginLeft: "clamp(8px, 2vw, 24px)" }}>
                <TextType
                  as="span"
                  text="Jay Parmar"
                  loop={false}
                  typingSpeed={160}
                  initialDelay={500}
                  variableSpeed={{ min: 120, max: 220 }}
                  showCursor
                  cursorBlinkDuration={0.65}
                  className="bg-clip-text text-transparent"
                  style={{
                    backgroundImage:
                      "linear-gradient(90deg, #a78bfa 0%, #c4b5fd 50%, #f0abfc 100%)",
                  }}
                  cursorCharacter={
                    <span
                      aria-hidden
                      className="inline-block align-middle"
                      style={{
                        width: "4px",
                        height: "0.78em",
                        marginLeft: "8px",
                        marginBottom: "-0.08em",
                        borderRadius: "2px",
                        background:
                          "linear-gradient(180deg, #f5f0ff 0%, #a78bfa 60%, #7c3aed 100%)",
                        boxShadow:
                          "0 0 18px rgba(167,139,250,0.7), 0 0 38px rgba(167,139,250,0.3)",
                      }}
                    />
                  }
                />
              </h1>
              <div className="flex flex-wrap items-center gap-y-1 text-[13px] sm:text-[15px] text-[#cfcfcf]" style={{ marginBottom: "0px" , marginLeft: "clamp(8px, 2vw, 24px)"}}>
                <svg viewBox="0 0 16 16" className="w-4 h-4 mr-1.5 text-[#a78bfa] shrink-0" fill="currentColor"><path d="M4 1h6l3 3v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1Z"/></svg>
                <span className="text-[#a78bfa]">AI/ML Builder · Finance Analyst · Product Leader</span>
                <span className="text-[#6f6f6f] mx-2 hidden sm:inline">•</span>
                <span className="block sm:inline">BBA, IIM Bangalore</span>
              </div>
              <p className="text-sm sm:text-[15px] text-[#cbd5e1] max-w-[640px]" style={{ marginBottom: "40px", marginLeft: "clamp(8px, 2vw, 24px)"}}>turning complex data into decisions that move.</p>

              {/* Code block — Safari-framed */}
              <Safari_01
                url="jayparmar.in/profile.ts"
                className="mb-12 max-w-[820px] w-full"
                style={{ marginInline: "clamp(8px, 2vw, 24px)", marginBottom: "24px" }}
              >
                <pre className="px-5 sm:px-10 py-6 sm:py-9 leading-[2] sm:leading-[2.1] tracking-[0.01em] overflow-x-auto font-mono text-[11px] sm:text-[13.5px]">
{[
"const builder = {",
'  name: "Jay Parmar",',
'  role: "AI/ML Builder · Finance Analyst · Product Leader",',
'  skills: ["Python", "Claude API", "FastAPI", "React", "Neo4j", "XGBoost", "Power BI"],',
'  focus: "Adaptive EdTech, AML Graph Forensics & Supply-Chain ROI Systems",',
'  passion: "Strategy × Technology — outcomes that survive contact with reality",',
"};",
"",
"// IIM Bangalore (DBE 2026–29) · Bhilai, India",
].map((line, i) => (
  <CodeLine key={i} n={i+1} line={line} />
))}
                </pre>
              </Safari_01>

              {/* Buttons */}
              <div
                className="flex flex-col sm:flex-row items-center justify-center gap-4 sm:gap-7"
                style={{ marginBottom: "96px", marginTop: "8px" }}
              >
                <ButtonCta
                  className="min-w-[200px]"
                  onClick={() => {
                    const lenis = getLenis();
                    if (lenis) {
                      lenis.scrollTo("#showcase", { duration: 1.05 });
                      return;
                    }
                    document.getElementById("showcase")?.scrollIntoView({ behavior: "smooth" });
                  }}
                >
                  <span className="flex items-center gap-2">
                    Explore My Work <I.arrow className="w-3.5 h-3.5 text-[#D69DDE]" />
                  </span>
                </ButtonCta>
                <ButtonCta
                  label="About Me"
                  className="min-w-[200px]"
                  onClick={() => {
                    const lenis = getLenis();
                    if (lenis) {
                      lenis.scrollTo("#about", { duration: 0.95 });
                      return;
                    }
                    document.getElementById("about")?.scrollIntoView({ behavior: "smooth" });
                  }}
                />
              </div>

              {/* Scroll to explore cue */}
              <div
                className="flex flex-col items-center"
                style={{ gap: "10px", marginTop: "-72px" }}
              >
                <span
                  className="vp-scroll-shimmer"
                  style={{
                    fontSize: "10px",
                    fontWeight: 600,
                    letterSpacing: "0.42em",
                    textTransform: "uppercase",
                  }}
                >
                  Scroll to Explore
                </span>
                <span
                  aria-hidden
                  style={{
                    position: "relative",
                    width: "1px",
                    height: "36px",
                    overflow: "hidden",
                    background: "rgba(167,139,250,0.12)",
                  }}
                >
                  <span
                    className="vp-scroll-beam"
                    style={{
                      position: "absolute",
                      top: 0,
                      left: 0,
                      width: "100%",
                      height: "40%",
                      background:
                        "linear-gradient(180deg, transparent 0%, #a78bfa 50%, transparent 100%)",
                    }}
                  />
                </span>
                <svg
                  aria-hidden
                  viewBox="0 0 16 16"
                  className="vp-scroll-chevron"
                  style={{ width: "12px", height: "12px", color: "#c4b5fd" }}
                >
                  <path
                    d="M4 6l4 4 4-4"
                    stroke="currentColor"
                    strokeWidth="1.4"
                    strokeLinecap="round"
                    strokeLinejoin="round"
                    fill="none"
                  />
                </svg>
              </div>

              <style jsx>{`
                .vp-scroll-shimmer {
                  background: linear-gradient(
                    90deg,
                    rgba(167, 139, 250, 0.35) 0%,
                    rgba(245, 240, 255, 0.95) 40%,
                    #c4b5fd 50%,
                    rgba(245, 240, 255, 0.95) 60%,
                    rgba(167, 139, 250, 0.35) 100%
                  );
                  background-size: 220% 100%;
                  -webkit-background-clip: text;
                  background-clip: text;
                  color: transparent;
                  animation: vp-shimmer 3.6s ease-in-out infinite;
                }
                @keyframes vp-shimmer {
                  0% { background-position: 200% 0; }
                  100% { background-position: -200% 0; }
                }

                .vp-scroll-beam {
                  animation: vp-beam 2.2s cubic-bezier(0.65, 0, 0.35, 1) infinite;
                }
                @keyframes vp-beam {
                  0% { transform: translateY(-100%); }
                  100% { transform: translateY(250%); }
                }

                .vp-scroll-chevron {
                  animation: vp-bounce 1.8s ease-in-out infinite;
                }
                @keyframes vp-bounce {
                  0%, 100% { transform: translateY(0); opacity: 0.55; }
                  50% { transform: translateY(3px); opacity: 1; }
                }
              `}</style>
            </div>
          </div>

          {/* Right panel — hidden on mobile and tablets to let editor take full width */}
          <aside
            className="hidden xl:flex flex-col w-[380px] bg-[#0a0a0a] border-l border-[#1a1a1a] shrink-0 overflow-y-auto [scrollbar-width:none] [&::-webkit-scrollbar]:hidden p-8"
          >
            <div style={{ display: "flex", flexDirection: "column", gap: "44px" }}>

              {/* ===== Current status ===== */}
              <section>
                <SectionLabel>CURRENT STATUS</SectionLabel>
                <a
                  href="https://www.linkedin.com/in/jay-parmar-ai"
                  target="_blank"
                  rel="noopener noreferrer"
                  className="group relative block overflow-hidden rounded-[16px] border border-[#1a1a1a] transition-all duration-500 hover:border-[#a78bfa]/30 cursor-pointer"
                  style={{
                    background: "linear-gradient(180deg, rgba(20,17,30,0.7) 0%, rgba(10,8,16,0.85) 100%)",
                    boxShadow: "inset 0 1px 0 rgba(255,255,255,0.04), 0 12px 32px -16px rgba(0,0,0,0.6)",
                    padding: "22px 24px",
                  }}
                >
                  <div className="flex items-center justify-between mb-3">
                    <div className="flex items-center" style={{ gap: "10px" }}>
                      <span className="relative flex w-2 h-2">
                        <span className="absolute inline-flex h-full w-full rounded-full bg-[#22c55e] opacity-60 animate-ping" />
                        <span className="relative inline-flex w-2 h-2 rounded-full bg-[#22c55e] shadow-[0_0_10px_rgba(34,197,94,0.6)]" />
                      </span>
                      <span className="text-[13px] text-white font-medium tracking-tight">Strategy × Technology</span>
                    </div>
                    <span className="text-[9px] tracking-[0.18em] text-[#5a5a5a] uppercase">IIM-B · IIT-G</span>
                  </div>
                  <p className="text-[11.5px] text-[#9a9a9a] leading-[1.55]" style={{ marginBottom: "16px" }}>
                    Building ShikshaShakti.AI &amp; disaster analytics pipelines. Open to high-impact AI, finance &amp; product roles.
                  </p>
                  <div className="flex items-center justify-between pt-3 border-t border-white/[0.04]">
                    <span className="text-[10px] text-[#6a6a6a] tracking-[0.05em]">jaydeepak2532006@gmail.com</span>
                    <span className="text-[10px] text-[#a78bfa] tracking-[0.05em] flex items-center gap-1 group-hover:gap-1.5 transition-all">
                      Connect <I.ext_arrow className="w-2.5 h-2.5" />
                    </span>
                  </div>
                  {/* Decorative orb */}
                  <div
                    aria-hidden
                    className="pointer-events-none absolute -right-6 -top-6 w-[110px] h-[110px] rounded-full opacity-80 group-hover:opacity-100 transition-opacity duration-700"
                    style={{
                      background: "radial-gradient(circle at 30% 30%, rgba(167,139,250,0.55), rgba(30,27,75,0) 65%)",
                      filter: "blur(2px)",
                    }}
                  />
                </a>
              </section>

              {/* ===== Tech stack ===== */}
              <section>
                <SectionLabel>CORE TOOLING</SectionLabel>
                <div
                  className="relative rounded-[16px] overflow-hidden"
                  style={{
                    background: "linear-gradient(180deg, rgba(20,17,30,0.7) 0%, rgba(10,8,16,0.85) 100%)",
                    border: "1px solid rgba(255,255,255,0.04)",
                    boxShadow: "inset 0 1px 0 rgba(255,255,255,0.04), 0 10px 28px -16px rgba(0,0,0,0.55)",
                    padding: "18px 0",
                  }}
                >
                  <LogoLoop
                    logos={[
                      { node: <TechIcon kind="claude" />, title: "Claude API", ariaLabel: "Claude API", href: "https://claude.ai" },
                      { node: <TechIcon kind="react" />, title: "React", ariaLabel: "React", href: "https://react.dev" },
                      { node: <TechIcon kind="tf" />, title: "Python & ML / GNN", ariaLabel: "Python & ML / GNN" },
                      { node: <TechIcon kind="lg" />, title: "Neo4j & Graph Analytics", ariaLabel: "Neo4j & Graph Analytics" },
                      { node: <TechIcon kind="hf" />, title: "NLP & XGBoost", ariaLabel: "NLP & XGBoost" },
                      { node: <TechIcon kind="next" />, title: "FastAPI & REST APIs", ariaLabel: "FastAPI" },
                      { node: <TechIcon kind="ts" />, title: "Power BI & Dashboards", ariaLabel: "Power BI" },
                      { node: <TechIcon kind="js" />, title: "Excel & ROI Modeling", ariaLabel: "Excel & ROI Modeling" },
                      { node: <TechIcon kind="github" />, title: "GitHub (jay2532006)", ariaLabel: "GitHub", href: "https://github.com/jay2532006" },
                    ]}
                    speed={32}
                    direction="left"
                    logoHeight={30}
                    gap={36}
                    hoverSpeed={8}
                    scaleOnHover
                    fadeOut
                    fadeOutColor="#0e0b18"
                    ariaLabel="Technology stack"
                  />
                  {/* Top + bottom hairlines for premium framing */}
                  <span
                    aria-hidden
                    className="absolute inset-x-6 top-0 h-px pointer-events-none"
                    style={{ background: "linear-gradient(90deg, transparent, rgba(167,139,250,0.25), transparent)" }}
                  />
                  <span
                    aria-hidden
                    className="absolute inset-x-6 bottom-0 h-px pointer-events-none"
                    style={{ background: "linear-gradient(90deg, transparent, rgba(167,139,250,0.18), transparent)" }}
                  />
                </div>
                {/* Caption row */}
                <div
                  className="flex items-center justify-between"
                  style={{ paddingLeft: "4px", paddingRight: "4px", marginTop: "12px" }}
                >
                  <span className="text-[10px] text-[#6a6a6a] tracking-[0.12em] uppercase">Daily Drivers</span>
                  <span className="flex items-center gap-1.5 text-[10px] text-[#a78bfa] tracking-[0.05em]">
                    <span className="relative flex w-1.5 h-1.5">
                      <span className="absolute inline-flex h-full w-full rounded-full bg-[#a78bfa] opacity-60 animate-ping" />
                      <span className="relative inline-flex w-1.5 h-1.5 rounded-full bg-[#a78bfa]" />
                    </span>
                    auto-scroll
                  </span>
                </div>
              </section>

              {/* ===== Featured projects (scroll stack) ===== */}
              <section>
                <div
                  className="flex items-center"
                  style={{ marginBottom: "14px", gap: "12px" }}
                >
                  <span className="text-[10px] tracking-[0.22em] text-[#7a7a7a] font-mono uppercase shrink-0">
                    FEATURED WORK
                  </span>
                  <span
                    aria-hidden
                    className="flex-1 h-px"
                    style={{
                      background:
                        "linear-gradient(90deg, rgba(167,139,250,0.18), transparent)",
                    }}
                  />
                  <span
                    className="relative flex items-center font-mono uppercase rounded-full shrink-0"
                    style={{
                      padding: "5px 11px",
                      gap: "7px",
                      fontSize: "8.5px",
                      letterSpacing: "0.18em",
                      background:
                        "linear-gradient(180deg, rgba(24,20,38,0.85) 0%, rgba(12,10,22,0.75) 100%)",
                      border: "1px solid rgba(167,139,250,0.24)",
                      boxShadow:
                        "0 4px 12px -6px rgba(0,0,0,0.55), 0 0 14px -6px rgba(167,139,250,0.3), inset 0 1px 0 rgba(255,255,255,0.05)",
                    }}
                  >
                    <I.mouse
                      className="w-2.5 h-2.5 text-[#c4b5fd]"
                      style={{
                        filter: "drop-shadow(0 0 4px rgba(167,139,250,0.45))",
                      }}
                    />
                    <span
                      className="bg-clip-text text-transparent"
                      style={{
                        backgroundImage:
                          "linear-gradient(180deg, #F5F0FF 0%, #C4B5FD 100%)",
                      }}
                    >
                      Scroll to explore
                    </span>
                  </span>
                </div>
                <div
                  className="relative rounded-[18px] overflow-hidden"
                  style={{
                    height: "420px",
                    background: "linear-gradient(180deg, rgba(20,17,30,0.55) 0%, rgba(10,8,16,0.85) 100%)",
                    border: "1px solid rgba(255,255,255,0.04)",
                    boxShadow: "inset 0 1px 0 rgba(255,255,255,0.04), 0 14px 36px -18px rgba(0,0,0,0.7)",
                  }}
                >
                  {/* Subtle top + bottom fades — softer now so card top reads clearly */}
                  <span
                    aria-hidden
                    className="absolute inset-x-0 top-0 h-6 z-10 pointer-events-none"
                    style={{ background: "linear-gradient(180deg, rgba(10,8,16,0.85) 0%, rgba(10,8,16,0) 100%)" }}
                  />

                  <span
                    aria-hidden
                    className="absolute inset-x-0 bottom-0 h-12 z-10 pointer-events-none"
                    style={{ background: "linear-gradient(0deg, rgba(10,8,16,1) 0%, rgba(10,8,16,0) 100%)" }}
                  />
                  <ScrollStack
                    itemDistance={28}
                    itemScale={0.03}
                    itemStackDistance={12}
                    stackPosition="10%"
                    scaleEndPosition="5%"
                    baseScale={0.94}
                    blurAmount={1.2}
                  >
                    {featuredProjects.map((p, i) => (
                      <ScrollStackItem key={i}>
                        <div
                          role="button"
                          tabIndex={0}
                          onClick={() => setActiveProject(p)}
                          onKeyDown={(e) => {
                            if (e.key === "Enter" || e.key === " ") {
                              e.preventDefault();
                              setActiveProject(p);
                            }
                          }}
                          className="group relative overflow-hidden rounded-[18px] cursor-pointer"
                          style={{
                            background: "linear-gradient(180deg, rgba(22,18,34,0.95) 0%, rgba(10,8,16,0.98) 100%)",
                            border: "1px solid rgba(167,139,250,0.10)",
                            boxShadow: "inset 0 1px 0 rgba(255,255,255,0.05), 0 24px 48px -20px rgba(0,0,0,0.8), 0 0 0 1px rgba(167,139,250,0.04)",
                            transition: "border-color 0.35s ease, box-shadow 0.35s ease, background 0.35s ease",
                          }}
                          onMouseEnter={(e) => {
                            e.currentTarget.style.borderColor = "rgba(167,139,250,0.42)";
                            e.currentTarget.style.boxShadow =
                              "inset 0 1px 0 rgba(255,255,255,0.08), 0 30px 64px -16px rgba(0,0,0,0.85), 0 0 0 1px rgba(167,139,250,0.18), 0 0 40px -10px rgba(167,139,250,0.35)";
                            e.currentTarget.style.background =
                              "linear-gradient(180deg, rgba(30,24,48,0.97) 0%, rgba(14,11,24,0.99) 100%)";
                          }}
                          onMouseLeave={(e) => {
                            e.currentTarget.style.borderColor = "rgba(167,139,250,0.10)";
                            e.currentTarget.style.boxShadow =
                              "inset 0 1px 0 rgba(255,255,255,0.05), 0 24px 48px -20px rgba(0,0,0,0.8), 0 0 0 1px rgba(167,139,250,0.04)";
                            e.currentTarget.style.background =
                              "linear-gradient(180deg, rgba(22,18,34,0.95) 0%, rgba(10,8,16,0.98) 100%)";
                          }}
                        >
                          {/* Hero artwork */}
                          <div
                            className="relative h-[120px] overflow-hidden"
                            style={{ background: p.artwork }}
                          >
                            {p.image && (
                              <Image
                                src={p.image}
                                alt={p.title}
                                fill
                                sizes="(max-width: 768px) 100vw, 820px"
                                // The first card is visible the moment the
                                // VSCode frame mounts (right rail, top of the
                                // stack) — mark it priority so the browser
                                // doesn't lazy-defer it. Everything else is
                                // pre-warmed by AssetPreloader during idle.
                                priority={i === 0}
                                loading={i === 0 ? "eager" : "lazy"}
                                fetchPriority={i === 0 ? "high" : "low"}
                                className="absolute inset-0 w-full h-full object-cover pointer-events-none select-none transition-transform duration-700 ease-[cubic-bezier(0.22,1,0.36,1)] group-hover:scale-[1.08]"
                                style={{ objectPosition: "center top" }}
                                draggable={false}
                              />
                            )}
                            <div
                              className="absolute inset-0"
                              style={{ background: "radial-gradient(circle at 30% 25%, rgba(255,255,255,0.35), transparent 55%)", opacity: p.image ? 0 : 1 }}
                            />
                            <div
                              className="absolute inset-x-0 top-0 h-1/2 mix-blend-screen opacity-75"
                              style={{ background: "radial-gradient(60% 100% at 50% 0%, rgba(167,139,250,0.4), transparent 70%)" }}
                            />
                            <span
                              className="absolute top-4 left-4 text-[9.5px] font-mono tracking-[0.18em] text-white/90 backdrop-blur-md rounded-full uppercase"
                              style={{
                                background: "rgba(0,0,0,0.5)",
                                border: "1px solid rgba(255,255,255,0.14)",
                                padding: "6px 12px",
                                letterSpacing: "0.18em",
                              }}
                            >
                              {p.tag}
                            </span>
                            {p.featured && (
                              <span
                                className="absolute top-4 right-4 text-[9.5px] font-mono tracking-[0.18em] text-[#d8c9ff] backdrop-blur-md rounded-full"
                                style={{
                                  background:
                                    "linear-gradient(180deg, rgba(58,38,108,0.85) 0%, rgba(31,18,58,0.85) 100%)",
                                  border: "1px solid rgba(167,139,250,0.4)",
                                  padding: "6px 12px",
                                  letterSpacing: "0.18em",
                                }}
                              >
                                ★ FEATURED
                              </span>
                            )}
                          </div>

                          <div style={{ padding: "18px 20px 18px" }}>
                            <div className="flex items-baseline justify-between" style={{ marginBottom: "8px" }}>
                              <span className="text-[15px] text-white font-semibold tracking-tight">{p.title}</span>
                              <span className="text-[10px] text-[#6a6a6a] tracking-[0.08em] font-mono">{p.year}</span>
                            </div>
                            <p className="text-[12px] text-[#9a9a9a] leading-[1.55]" style={{ marginBottom: "14px" }}>
                              {p.desc}
                            </p>
                            <div className="flex items-center justify-between">
                              <div className="flex items-center flex-wrap" style={{ gap: "5px" }}>
                                {p.stack.map((tech) => (
                                  <span
                                    key={tech}
                                    className="text-[9px] text-[#7a7a7a] tracking-[0.05em] px-2 py-[3px] rounded-full"
                                    style={{ background: "rgba(255,255,255,0.03)", border: "1px solid rgba(255,255,255,0.05)" }}
                                  >
                                    {tech}
                                  </span>
                                ))}
                              </div>
                              <span className="flex items-center gap-1 text-[11px] text-[#a78bfa] group-hover:gap-2 transition-all">
                                View <I.ext_arrow className="w-2.5 h-2.5" />
                              </span>
                            </div>
                          </div>
                        </div>
                      </ScrollStackItem>
                    ))}
                  </ScrollStack>
                </div>
                {/* Caption row */}
                <div
                  className="flex items-center justify-between"
                  style={{ paddingLeft: "4px", paddingRight: "4px", marginTop: "12px" }}
                >
                  <span className="text-[10px] text-[#6a6a6a] tracking-[0.12em] uppercase">3 Flagship</span>
                  <span className="flex items-center gap-1.5 text-[10px] text-[#a78bfa] tracking-[0.05em]">
                    scroll to stack
                    <I.mouse className="w-3 h-3" />
                  </span>
                </div>
              </section>

              {/* ===== Quick stats ===== */}
              <section>
                <SectionLabel>QUICK STATS</SectionLabel>
                <div className="grid grid-cols-3" style={{ gap: "10px" }}>
                  {[
                    { icon: <I.chat className="w-3.5 h-3.5 text-[#c4b5fd]"/>, n: "6", suffix: "", l: "Projects" },
                    { icon: <I.clock className="w-3.5 h-3.5 text-[#c4b5fd]"/>, n: "3", suffix: "×", l: "Nat'l Wins" },
                    { icon: <I.stack className="w-3.5 h-3.5 text-[#c4b5fd]"/>, n: "233", suffix: "", l: "Chapters" },
                  ].map((s, i) => (
                    <div
                      key={i}
                      className="group relative rounded-[14px] cursor-pointer transition-all duration-500 hover:-translate-y-1 overflow-hidden"
                      style={{
                        background: "linear-gradient(180deg, rgba(20,17,30,0.6) 0%, rgba(10,8,16,0.85) 100%)",
                        border: "1px solid rgba(255,255,255,0.04)",
                        boxShadow: "inset 0 1px 0 rgba(255,255,255,0.04)",
                        padding: "16px 14px",
                      }}
                    >
                      <div
                        className="w-7 h-7 rounded-[8px] flex items-center justify-center mb-3"
                        style={{
                          background: "linear-gradient(135deg, rgba(167,139,250,0.18), rgba(167,139,250,0.04))",
                          border: "1px solid rgba(167,139,250,0.18)",
                        }}
                      >
                        {s.icon}
                      </div>
                      <div className="flex items-baseline gap-0.5">
                        <span
                          className="text-[22px] font-semibold leading-none bg-clip-text text-transparent tracking-tight"
                          style={{ backgroundImage: "linear-gradient(180deg, #ffffff 0%, #c4b5fd 100%)" }}
                        >
                          {s.n}
                        </span>
                        <span className="text-[12px] text-[#7a7a7a] font-medium">{s.suffix}</span>
                      </div>
                      <div className="text-[10px] text-[#cbd5e1] tracking-[0.06em] mt-2 uppercase">{s.l}</div>
                      {/* Hover ring */}
                      <div
                        aria-hidden
                        className="absolute inset-0 rounded-[14px] opacity-0 group-hover:opacity-100 transition-opacity duration-500 pointer-events-none"
                        style={{ boxShadow: "inset 0 0 0 1px rgba(167,139,250,0.30)" }}
                      />
                    </div>
                  ))}
                </div>
              </section>

              {/* ===== Footer signature ===== */}
              <section className="pt-2 border-t border-white/[0.04]">
                <div className="flex items-center justify-between" style={{ paddingTop: "16px" }}>
                  <span className="text-[10px] text-[#5a5a5a] tracking-[0.18em] uppercase">Based in</span>
                  <span className="text-[10px] text-[#9a9a9a] tracking-[0.08em] font-mono">Bhilai · IIM-B · IST</span>
                </div>
              </section>
            </div>
          </aside>
        </div>
      </div>

      {/* ===== Status bar ===== */}
      <div className="h-[26px] bg-[#0a0a0a] border-t border-[#1a1a1a] flex items-center text-[11px] text-[#bdbdbd] shrink-0">
        <div className="flex items-center gap-4 px-4">
          <span className="flex items-center gap-1 text-[#9a9a9a]"><svg viewBox="0 0 16 16" className="w-3 h-3" fill="none" stroke="currentColor"><circle cx="8" cy="8" r="6"/><path d="m5 8 2 2 4-4"/></svg> 0</span>
          <span className="flex items-center gap-1 text-[#9a9a9a]"><I.warn className="w-3 h-3"/> 00</span>
          <span className="px-2 py-[1px] rounded-[3px] bg-[#1a1a1a] text-[#cfcfcf]">No Solution</span>
        </div>
        <div className="ml-auto flex items-center gap-5 px-4 text-[#9a9a9a]">
          <span>Ln 1, Col 1</span>
          <span>Spaces: 2</span>
          <span>UTF-8</span>
          <span>LF</span>
          <span className="flex items-center gap-1">{"{ }"} TypeScript JSX</span>
          <span className="flex items-center gap-1 text-[#a78bfa]">⚡ Prettier</span>
        </div>
      </div>

      <ProjectModal project={activeProject} onClose={() => setActiveProject(null)} />
    </div>
  );
};

/* ---------- Code line with syntax tokens ---------- */
function CodeLine({ n, line }: { n: number; line: string }) {
  return (
    <div className="flex items-baseline">
      <span className="inline-block w-10 text-right pr-5 text-[#3a3a3a] select-none tabular-nums">{line ? n : ""}</span>
      <span className="whitespace-pre">{tokenize(line)}</span>
    </div>
  );
}

function tokenize(line: string): React.ReactNode {
  if (!line) return " ";
  if (line.startsWith("//")) return <span className="text-[#6b7d52]">{line}</span>;
  // const developer = {
  const parts: React.ReactNode[] = [];
  const push = (t: React.ReactNode, k: number) => parts.push(<React.Fragment key={k}>{t}</React.Fragment>);
  // simple regex-based highlighter
  const regex = /("[^"]*"|\b(const|name|role|skills|focus|passion)\b|\[|\]|\{|\}|=|,|;|:|\(|\))/g;
  let last = 0; let k = 0; let m: RegExpExecArray | null;
  while ((m = regex.exec(line))) {
    if (m.index > last) push(<span className="text-[#cfcfcf]">{line.slice(last, m.index)}</span>, k++);
    const tok = m[0];
    let cls = "text-[#cfcfcf]";
    if (tok.startsWith('"')) cls = "text-[#ce9178]";
    else if (tok === "const") cls = "text-[#c586c0]";
    else if (["name","role","skills","focus","passion"].includes(tok)) cls = "text-[#9cdcfe]";
    else if ("{}[]".includes(tok)) cls = "text-[#ffd700]";
    else if (",;:=".includes(tok)) cls = "text-[#9a9a9a]";
    push(<span className={cls}>{tok}</span>, k++);
    last = m.index + tok.length;
  }
  if (last < line.length) push(<span className="text-[#cfcfcf]">{line.slice(last)}</span>, k++);
  return parts;
}

export default VSCodePortfolio;
```

---

## components/ui/zoom-parallax-demo.tsx

**File Path**: `components/ui/zoom-parallax-demo.tsx` | **Lines**: 78

```tsx
"use client";
import { ZoomParallax } from "@/components/ui/zoom-parallax";
import { LampDemo } from "@/components/ui/lamp";
import { ProjectShowcase } from "@/components/ui/project-showcase";
import ScrollExpand from "@/components/animations/ScrollExpand";
import { ScrollReveal } from "@/components/animations/ScrollReveal";
import { RulerCarousel, type CarouselItem } from "@/components/ui/ruler-carousel";

const rulerItems: CarouselItem[] = [
  { id: 1, title: "AI / ML BUILDER" },
  { id: 2, title: "FINANCE ANALYST" },
  { id: 3, title: "PRODUCT LEADER" },
  { id: 4, title: "FOUNDER" },
  { id: 5, title: "GNN & XGBOOST" },
  { id: 6, title: "ROI MODELING" },
  { id: 7, title: "CLAUDE API" },
  { id: 8, title: "IIM BANGALORE" },
  { id: 9, title: "3× NATIONAL WINNER" },
];

export default function ZoomParallaxDemo() {
  const images = [
    {
      src: "/assets/portfolio/gallery/gallery-03.jpg",
      alt: "Jay Parmar — BBA, IIM Bangalore",
    },
    {
      src: "/assets/portfolio/certificates/cert-01.jpg",
      alt: "PackEdge 1st Position — IIT Bombay Techfest",
    },
    {
      src: "/assets/portfolio/certificates/cert-02.jpg",
      alt: "TCS Foundation National Hackathon — 1st Place NIT Trichy",
    },
    {
      src: "/assets/carousel/carousel-09.webp",
      alt: "National Recognition with TCS CEO K. Krithivasan",
    },
    {
      src: "/assets/portfolio/certificates/cert-05.jpg",
      alt: "Ministry of MSME — Drone Technology E-SDP",
    },
    {
      src: "/assets/carousel/carousel-33.webp",
      alt: "ShikshaShakti.AI — ₹2L DST-NIDHI Grant",
    },
    {
      src: "/assets/portfolio/certificates/cert-07.jpg",
      alt: "VLSI Workshop — IIT Bhilai",
    },
  ];

  return (
    <section className="w-full">
      <div className="relative flex h-[50vh] items-center justify-center px-6">
        <h1 className="text-center text-4xl font-bold">
          Built to Survive Real-World Scale.
        </h1>
      </div>
      <ZoomParallax
        images={images}
        portalIndex={0}
        portalContent={<LampDemo />}
      />
      <ScrollExpand
        stageBackground="radial-gradient(ellipse 100% 80% at 50% 50%, rgba(99,102,241,0.12) 0%, rgba(139,92,246,0.07) 28%, #08080f 58%, #050508 100%)"
        background="#080808"
      >
        <ProjectShowcase />
      </ScrollExpand>

      <ScrollReveal className="w-full">
        <RulerCarousel originalItems={rulerItems} />
      </ScrollReveal>
    </section>
  );
}
```

---

## components/ui/zoom-parallax.tsx

**File Path**: `components/ui/zoom-parallax.tsx` | **Lines**: 90

```tsx
"use client";

import { useScroll, useTransform, motion } from "framer-motion";
import NextImage from "next/image";
import { useRef } from "react";

interface ParallaxImage {
  src: string;
  alt?: string;
}

interface ZoomParallaxProps {
  images: ParallaxImage[];
  /** Optional node rendered inside one frame instead of an image — acts as a portal/preview */
  portalContent?: React.ReactNode;
  /** Which image index to replace with portalContent (default 0 — centered frame) */
  portalIndex?: number;
}

export function ZoomParallax({ images, portalContent, portalIndex = 0 }: ZoomParallaxProps) {
  const container = useRef(null);
  const { scrollYProgress } = useScroll({
    target: container,
    offset: ["start start", "end end"],
  });

  const scale4 = useTransform(scrollYProgress, [0, 1], [1, 4]);
  const scale5 = useTransform(scrollYProgress, [0, 1], [1, 5]);
  const scale6 = useTransform(scrollYProgress, [0, 1], [1, 6]);
  const scale8 = useTransform(scrollYProgress, [0, 1], [1, 8]);
  const scale9 = useTransform(scrollYProgress, [0, 1], [1, 9]);

  const scales = [scale4, scale5, scale6, scale5, scale6, scale8, scale9];

  return (
    <div ref={container} className="relative h-[190vh]">
      <div className="sticky top-0 h-screen overflow-hidden">
        {images.map(({ src, alt }, index) => {
          const scale = scales[index % scales.length];

          return (
            <motion.div
              key={index}
              style={{ scale }}
              className={`absolute top-0 flex h-full w-full items-center justify-center ${index === 1 ? "[&>div]:!-top-[30vh] [&>div]:!left-[5vw] [&>div]:!h-[30vh] [&>div]:!w-[35vw]" : ""} ${index === 2 ? "[&>div]:!-top-[10vh] [&>div]:!-left-[25vw] [&>div]:!h-[45vh] [&>div]:!w-[20vw]" : ""} ${index === 3 ? "[&>div]:!left-[27.5vw] [&>div]:!h-[25vh] [&>div]:!w-[25vw]" : ""} ${index === 4 ? "[&>div]:!top-[27.5vh] [&>div]:!left-[5vw] [&>div]:!h-[25vh] [&>div]:!w-[20vw]" : ""} ${index === 5 ? "[&>div]:!top-[27.5vh] [&>div]:!-left-[22.5vw] [&>div]:!h-[25vh] [&>div]:!w-[30vw]" : ""} ${index === 6 ? "[&>div]:!top-[22.5vh] [&>div]:!left-[25vw] [&>div]:!h-[15vh] [&>div]:!w-[15vw]" : ""} `}
            >
              <div className="relative h-[25vh] w-[25vw] overflow-hidden">
                {index === portalIndex && portalContent ? (
                  <div
                    className="absolute inset-0 overflow-hidden bg-slate-950"
                    style={{
                      border: "1px solid rgba(255,255,255,0.12)",
                      boxShadow:
                        "0 10px 40px rgba(0,0,0,0.5), inset 0 0 0 1px rgba(255,255,255,0.04)",
                    }}
                  >
                    <div
                      style={{
                        width: "100vw",
                        height: "100vh",
                        transform: "scale(0.25)",
                        transformOrigin: "top left",
                        pointerEvents: "none",
                      }}
                    >
                      {portalContent}
                    </div>
                  </div>
                ) : (
                  <NextImage
                    src={src || "/placeholder.svg"}
                    alt={alt || `Parallax image ${index + 1}`}
                    fill
                    sizes="(max-width: 768px) 60vw, 25vw"
                    loading="lazy"
                    className="h-full w-full object-cover"
                    style={{
                      objectPosition: "center top",
                    }}
                  />
                )}
              </div>
            </motion.div>
          );
        })}
      </div>
    </div>
  );
}
```

---

## constants/index.ts

**File Path**: `constants/index.ts` | **Lines**: 393

```typescript
export const SITE = {
  name: "Jay Parmar",
  shortName: "Jay",
  role: "AI/ML Builder · Finance Analyst · Product Leader",
  headline: "I turn complex data into decisions that move.",
  subheadline:
    "I’m an AI/ML builder, finance analyst and product leader. I build useful systems, bring people around ambitious ideas and stay with the work until it creates a real outcome.",
  email: "jaydeepak2532006@gmail.com",
  phone: "+91 77730 60203",
  location: "Bhilai, Chhattisgarh, India",
  timezone: "IST (UTC+5:30)",
  educationShort: "BBA, IIM Bangalore",
  github: "https://github.com/jay2532006",
  linkedin: "https://www.linkedin.com/in/jay-parmar-ai",
  resumeUrl: "/assets/portfolio/resume/Jay-Parmar-Resume.pdf",
  portraitUrl: "/assets/portfolio/gallery/gallery-03.jpg",
  brandMarkUrl: "/assets/brand/jay-parmar-mark.webp",
  brandBannerUrl: "/assets/brand/jay-parmar-brand-banner.webp",
  badge: "Strategy × Technology",
};

export const NAV_LINKS = [
  { label: "Projects", href: "#showcase" },
  { label: "Experience", href: "#experience" },
  { label: "Dossier", href: "#dossier" },
  { label: "Gallery", href: "#gallery" },
  { label: "Articles", href: "/articles" },
  { label: "Contact", href: "#contact" },
];

export const EDUCATION = [
  {
    degree: "BBA, Digital Business & Entrepreneurship (DBE)",
    institution: "Indian Institute of Management Bangalore (IIMB)",
    period: "2026 – 2029",
    highlights: [
      "Top 20 — Young Leadership Summit, IIM Bangalore (selected from 70,000+ applicants)",
      "National Finalist — SIPS 2026 (IIM Bangalore) & AVANT B-Plan (IIM Indore)",
    ],
  },
];

export const EXPERIENCE = [
  {
    period: "2025 — Present",
    role: "AI & Disaster Analytics Intern",
    organization: "Center for Disaster Management, IIT Guwahati",
    location: "Remote / Guwahati",
    summary:
      "Built automated data pipelines consolidating social media streams, government advisories, and public-source datasets into real-time risk-monitoring dashboards.",
    bullets: [
      "Designed automated ETL pipelines ingesting social, government, and open public feeds into live risk-monitoring dashboards.",
      "Curated and structured NLP-ready pre-disaster preparedness datasets for early-warning and situational analysis.",
    ],
  },
  {
    period: "2025 — Present",
    role: "Founder & Product Lead",
    organization: "ShikshaShakti.AI",
    location: "Bhilai, India",
    summary:
      "Built an offline-first adaptive learning platform and prerequisite diagnostic engine funded by a ₹2L DST-NIDHI ignition grant.",
    bullets: [
      "Architected a question-generation and diagnostic engine powered by the Claude API spanning 233 chapters and 157 prerequisite relationships.",
      "Engineered an offline-first delivery model tailored for low-bandwidth classrooms, reaching TRL 4 with ₹2L DST-NIDHI grant backing.",
    ],
  },
  {
    period: "2024 — 2025",
    role: "Core Coordinator, Event & Logistics Management (Internship)",
    organization: "CSVTU-FORTE DST-NIDHI i-TBI",
    location: "Bhilai, India",
    summary:
      "Led vendor coordination and budget-conscious execution across startup incubation cohorts and mentoring programs.",
    bullets: [
      "Managed vendor negotiations, procurement timelines, and end-to-end event logistics across incubation and mentoring programs.",
      "Tracked budgets against financial plan, flagged cost variances early, and maintained stakeholder reporting.",
    ],
  },
  {
    period: "2024 — 2025",
    role: "Company Outreach Lead & Event Management Core Coordinator",
    organization: "Training & Placement Cell, CSVTU Bhilai",
    location: "Bhilai, India",
    summary:
      "Coordinated corporate outreach, vocational training allocations, and placement drive operations across students, faculty, and hiring partners.",
    bullets: [
      "Spearheaded company outreach and onboarding for campus placement and vocational training drives.",
      "Synchronized scheduling, logistics, and communication between student cohorts, faculty coordinators, and corporate recruiters.",
    ],
  },
];

export interface PortfolioProject {
  id: string;
  title: string;
  category: string;
  year: string;
  badge: string;
  summary: string;
  headlineMetric: string;
  metrics: string[];
  stack: string[];
  image: string;
  caseDeckUrl?: string;
  github?: string;
}

export const PROJECTS: PortfolioProject[] = [
  {
    id: "shikshashakti",
    title: "ShikshaShakti.AI",
    category: "EdTech · Founder",
    year: "2025",
    badge: "₹2L DST-NIDHI Grant · TRL 4",
    summary:
      "Offline-first adaptive learning platform that maps prerequisite gaps before generating targeted questions for students in low-bandwidth classrooms.",
    headlineMetric: "233 chapters mapped",
    metrics: [
      "233 chapters mapped",
      "157 prerequisite links",
      "₹2L DST-NIDHI grant",
      "TRL 4 validated",
    ],
    stack: ["Claude API", "Python", "FastAPI", "React", "Knowledge Graph"],
    image: "/assets/carousel/carousel-33.webp",
    caseDeckUrl: "https://drive.google.com/file/d/1KB5ZEOAgdl6hEC4cCXVQ1u9I0FcxkGHx/view",
  },
  {
    id: "packedge",
    title: "PackEdge",
    category: "Supply Chain · 1st Place IIT Bombay",
    year: "2025",
    badge: "1st Position · Techfest IIT Bombay",
    summary:
      "Partial knock-down (PKD) packaging and logistics redesign developed for Godrej Interio to maximize truck loadability and cut freight costs.",
    headlineMetric: "₹47.5L projected annual savings",
    metrics: [
      "₹47.5L projected annual savings",
      "18.5% less volume",
      "33% freight reduction",
      "25% higher loadability",
    ],
    stack: ["ROI Modeling", "Excel", "Supply Chain Analytics", "Unit Economics"],
    image: "/assets/carousel/carousel-25.webp",
    caseDeckUrl: "https://drive.google.com/file/d/198jU7tjaPgLchEVKDLTQ7UO2OzyOkM91/view",
  },
  {
    id: "nextgenaml",
    title: "NextGenAML",
    category: "FinTech · National Winner",
    year: "2025",
    badge: "TCS Foundation Winner · NIT Trichy",
    summary:
      "Real-time anti-money-laundering screening engine combining Graph Neural Networks, XGBoost, FATF typologies, and LLM-assisted case triage.",
    headlineMetric: "<12ms screening latency",
    metrics: [
      "<12ms screening latency",
      "0.78 ROC-AUC",
      "GNN + XGBoost + FATF rules",
      "LLM-assisted case triage",
    ],
    stack: ["Python", "GNN", "XGBoost", "Neo4j", "FastAPI", "Claude API"],
    image: "/assets/carousel/carousel-35.webp",
  },
  {
    id: "fdr-setu",
    title: "FDR-Setu",
    category: "RegTech · SIH 2026 AICTE",
    year: "2026",
    badge: "Smart India Hackathon 2026 · AICTE",
    summary:
      "Regulatory infrastructure layer for the institutional security-deposit lifecycle featuring two-phase settlement and an audit-first architecture.",
    headlineMetric: "55 REST endpoints · 26 tables",
    metrics: [
      "55 REST endpoints",
      "26-table data model",
      "Two-phase settlement",
      "Role-based audit workflows",
    ],
    stack: ["Python", "FastAPI", "SQL", "React", "Audit Architecture"],
    image: "/assets/carousel/carousel-32.webp",
  },
  {
    id: "cryptotrace-lea",
    title: "CryptoTrace LEA",
    category: "Web3 Forensics · MHA PS 26183",
    year: "2026",
    badge: "129/129 Tests Passing · SIH",
    summary:
      "Multi-chain cryptocurrency fraud attribution and investigation workspace built for law enforcement agencies with a 7-component risk scoring engine.",
    headlineMetric: "129/129 tests passing",
    metrics: [
      "129/129 tests passing",
      "7-component risk score",
      "Multi-chain entity attribution",
      "MHA Problem Statement 26183",
    ],
    stack: ["Python", "Graph Analytics", "FastAPI", "React", "Web3 Forensics"],
    image: "/assets/carousel/carousel-10.webp",
  },
  {
    id: "realtime-fraud-alerts",
    title: "Real-time Fraud Alerts",
    category: "Fraud Prevention · 2× Finalist",
    year: "2026",
    badge: "MUJ Hack 4.0 & Fintechstico 2026",
    summary:
      "Active transaction defence layer that pauses suspicious payments in flight and triggers instant multilingual verification voice calls via Sarvam AI.",
    headlineMetric: "2× National Finalist",
    metrics: [
      "Real-time transaction pause",
      "Multilingual Sarvam AI voice alerts",
      "MUJ Hack 4.0 Finalist",
      "Fintechstico 2026, NSUT Delhi",
    ],
    stack: ["Python", "Sarvam AI", "FastAPI", "ML Risk Scoring", "Voice Pipelines"],
    image: "/assets/carousel/carousel-24.webp",
  },
];

export const ACHIEVEMENTS = [
  {
    index: "01",
    title: "National Winner — TCS Foundation 36-Hour Hackathon",
    venue: "NIT Tiruchirappalli",
    detail: "First place nationally for NextGenAML real-time transaction screening.",
  },
  {
    index: "02",
    title: "1st Position — PackEdge Supply Chain Challenge",
    venue: "Techfest, IIT Bombay",
    detail: "Winner for Godrej Interio partial knock-down packaging redesign (₹47.5L projected annual savings).",
  },
  {
    index: "03",
    title: "Hack-LLM Winner",
    venue: "IIIT Delhi",
    detail: "Awarded top honors for applied LLM systems engineering.",
  },
  {
    index: "04",
    title: "Top 100 in India — iDEA 2.0 AML Challenge",
    venue: "Union Bank of India",
    detail: "Selected among the top 100 teams nationwide for anti-money-laundering innovation.",
  },
  {
    index: "05",
    title: "Top 20 — Young Leadership Summit",
    venue: "IIM Bangalore",
    detail: "Selected into the top 20 nationally from over 70,000+ applicants.",
  },
  {
    index: "06",
    title: "5× National Finalist across Flagship Hackathons & B-Plans",
    venue: "IIT BHU · NSUT Delhi · IIM Indore · IIM Bangalore · MUJ",
    detail: "Finalist at SANGYAN (IIT BHU), MUJ Hack 4.0, Fintechstico 2026 (NSUT Delhi), AVANT B-Plan (IIM Indore), and SIPS 2026 (IIM Bangalore).",
  },
];

export const CERTIFICATES = [
  {
    id: "cert-01",
    title: "PackEdge — 1st Position",
    issuer: "Techfest, IIT Bombay",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-01.jpg",
  },
  {
    id: "cert-02",
    title: "National Hackathon — First Place",
    issuer: "TCS Foundation × NIT Trichy",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-02.jpg",
  },
  {
    id: "cert-05",
    title: "Drone Technology E-SDP",
    issuer: "Ministry of MSME, Government of India",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-05.jpg",
  },
  {
    id: "cert-03",
    title: "GitHub Dev Days",
    issuer: "Rungta International Skills University",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-03.jpg",
  },
  {
    id: "cert-06",
    title: "Recruitment Drive Appreciation",
    issuer: "Codelent Technologies",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-06.jpg",
  },
  {
    id: "cert-07",
    title: "VLSI Workshop",
    issuer: "Electromos × IIT Bhilai",
    year: "2025",
    image: "/assets/portfolio/certificates/cert-07.jpg",
  },
];

export const SKILL_CATEGORIES = [
  {
    category: "Data & Reporting",
    items: [
      "Power BI",
      "Excel",
      "Data Pipelines",
      "Data Analysis",
      "Financial Analysis",
      "ROI Modeling",
      "KPI Definition",
      "Reporting Automation",
      "Dashboard Design",
    ],
  },
  {
    category: "AI & Tools",
    items: [
      "Claude API",
      "LLM Fine-Tuning",
      "Machine Learning",
      "GNN",
      "NLP",
      "XGBoost",
      "GenAI Applications",
    ],
  },
  {
    category: "Engineering",
    items: ["Python", "FastAPI", "React", "Neo4j"],
  },
  {
    category: "Business",
    items: [
      "Budget Tracking",
      "Vendor Coordination",
      "Stakeholder Management",
      "Cross-Functional Coordination",
    ],
  },
  {
    category: "Office & Productivity",
    items: ["Microsoft Excel", "PowerPoint", "Word", "Outlook"],
  },
];

export const SKILLS = SKILL_CATEGORIES.flatMap((group) => group.items);

export const STACK = [
  "Python",
  "Claude API",
  "FastAPI",
  "React",
  "Neo4j",
  "XGBoost",
  "GNN",
  "Power BI",
  "Excel",
  "NLP",
  "ROI Modeling",
];

export const AIMS = [
  {
    index: "01",
    title: "Build useful intelligence",
    description:
      "Ship AI and analytics systems that solve concrete bottlenecks — from <12ms AML triage to offline prerequisite mapping in rural classrooms.",
  },
  {
    index: "02",
    title: "Create from India, for the world",
    description:
      "Prove that high-rigor product engineering, financial modeling, and institutional-grade software can emerge out of Bhilai and IIM Bangalore.",
  },
  {
    index: "03",
    title: "Grow through service",
    description:
      "Stay accountable to real outcomes — coordinating placement drives, incubation cohorts, and public-interest disaster pipelines alongside technical builds.",
  },
];

export const ABOUT_COPY = {
  lead: "I’m Jay — a builder, organiser and relentlessly curious learner, most energised when an ambitious idea has to survive contact with the real world.",
  bio: "Pursuing BBA in Digital Business & Entrepreneurship at IIM Bangalore while leading product engineering on ShikshaShakti.AI and AI disaster pipelines at IIT Guwahati.",
};
```

---

## eslint.config.mjs

**File Path**: `eslint.config.mjs` | **Lines**: 19

```javascript
import { defineConfig, globalIgnores } from "eslint/config";
import nextVitals from "eslint-config-next/core-web-vitals";
import nextTs from "eslint-config-next/typescript";

const eslintConfig = defineConfig([
  ...nextVitals,
  ...nextTs,
  // Override default ignores of eslint-config-next.
  globalIgnores([
    // Default ignores of eslint-config-next:
    ".next/**",
    "out/**",
    "build/**",
    "next-env.d.ts",
  ]),
]);

export default eslintConfig;
```

---

## hooks/useInView.ts

**File Path**: `hooks/useInView.ts` | **Lines**: 28

```typescript
"use client";

import { useEffect, useRef, useState } from "react";

export function useInView(options?: IntersectionObserverInit) {
  const ref = useRef<HTMLElement>(null);
  const [inView, setInView] = useState(false);

  useEffect(() => {
    if (!ref.current) return;

    const observer = new IntersectionObserver(
      ([entry]) => {
        if (entry.isIntersecting) {
          setInView(true);
          observer.disconnect();
        }
      },
      { threshold: 0.1, rootMargin: "0px 0px -10% 0px", ...options }
    );

    observer.observe(ref.current);
    return () => observer.disconnect();
  }, []);

  return { ref, inView };
}
```

---

## hooks/useLenis.ts

**File Path**: `hooks/useLenis.ts` | **Lines**: 53

```typescript
"use client";

import { useEffect } from "react";
import Lenis from "lenis";
import { gsap } from "@/lib/gsap";
import { ScrollTrigger } from "@/lib/gsap";

let lenisInstance: Lenis | null = null;

export function getLenis() {
  return lenisInstance;
}

export function useLenis() {
  useEffect(() => {
    // Detect touch / mobile devices. Native touch momentum on mobile devices runs
    // on the hardware compositor thread (up to 120Hz). Hijacking touch events with
    // virtual JS interpolation causes "hard scroll" and input lag on phones.
    const isCoarse =
      typeof window !== "undefined" &&
      window.matchMedia("(pointer: coarse)").matches;

    const lenis = new Lenis({
      duration: 1.0,
      easing: (t) => Math.min(1, 1.001 - Math.pow(2, -10 * t)),
      orientation: "vertical",
      smoothWheel: true,
      wheelMultiplier: 1.1,
      // On touch devices, disable JS touch virtualization so phones use 100% fluid native momentum
      touchMultiplier: 1,
      syncTouch: false,
    });

    lenisInstance = lenis;
    lenis.on("scroll", ScrollTrigger.update);

    const tick = (time: number) => {
      lenis.raf(time * 1000);
    };

    gsap.ticker.add(tick);
    // Restore GSAP lag smoothing: smoothly dampen timeline when frames take longer than 33ms
    // (disabling lag smoothing with 0 causes violent frame jumping and visual stutter).
    gsap.ticker.lagSmoothing(500, 33);

    return () => {
      gsap.ticker.remove(tick);
      lenis.destroy();
      lenisInstance = null;
    };
  }, []);
}
```

---

## hooks/useMousePosition.ts

**File Path**: `hooks/useMousePosition.ts` | **Lines**: 27

```typescript
"use client";

import { useState, useEffect } from "react";

export function useMousePosition() {
  const [position, setPosition] = useState({ x: 0, y: 0 });
  const [velocity, setVelocity] = useState({ x: 0, y: 0 });
  const prev = { x: 0, y: 0 };

  useEffect(() => {
    const handleMouseMove = (e: MouseEvent) => {
      setVelocity({
        x: e.clientX - prev.x,
        y: e.clientY - prev.y,
      });
      prev.x = e.clientX;
      prev.y = e.clientY;
      setPosition({ x: e.clientX, y: e.clientY });
    };

    window.addEventListener("mousemove", handleMouseMove);
    return () => window.removeEventListener("mousemove", handleMouseMove);
  }, []);

  return { position, velocity };
}
```

---

## hooks/useScrollProgress.ts

**File Path**: `hooks/useScrollProgress.ts` | **Lines**: 21

```typescript
"use client";

import { useState, useEffect } from "react";

export function useScrollProgress() {
  const [progress, setProgress] = useState(0);

  useEffect(() => {
    const updateProgress = () => {
      const scrollY = window.scrollY;
      const docHeight = document.documentElement.scrollHeight - window.innerHeight;
      setProgress(docHeight > 0 ? scrollY / docHeight : 0);
    };

    window.addEventListener("scroll", updateProgress, { passive: true });
    return () => window.removeEventListener("scroll", updateProgress);
  }, []);

  return progress;
}
```

---

## lib/articles.ts

**File Path**: `lib/articles.ts` | **Lines**: 253

```typescript
export type ArticleSection = { heading?: string; paragraphs: string[]; points?: string[] };

export type Article = {
	id: string;
	number: string;
	title: string;
	dek: string;
	category: "Leadership" | "AI & Strategy" | "Healthcare" | "Economy" | "Career" | "Banking";
	date: string;
	readTime: string;
	featured?: boolean;
	quote?: string;
	sections: ArticleSection[];
	links?: { label: string; url: string }[];
};

export const articles: Article[] = [
	{
		id: "influencing-without-authority",
		number: "01",
		title: "Influencing Without Authority",
		dek: "What Florence Nightingale teaches us about clarity, evidence and moving a room when the title is not yours.",
		category: "Leadership",
		date: "2026",
		readTime: "4 min read",
		featured: true,
		quote: "Nightingale did not out-rank the colonel. She out-clarified him.",
		sections: [
			{ paragraphs: ["She had no title. No budget. No authority. Just a notebook, three coloured pens, and a hospital full of dying soldiers nobody would listen to her about.", "At a session with Prof. Rakesh Godhwani at IIM Bangalore, I learned the deeper story behind Florence Nightingale—not only the lady with the lamp, but a woman who used data visualisation to save lives."] },
			{ heading: "The evidence changed the conversation", paragraphs: ["In 1854, during the Crimean War, Nightingale arrived at a military hospital in Turkey with 25 nurses and almost no formal authority. Soldiers were dying less from battle wounds than from infections spreading through filthy, poorly managed wards. When her requests to improve sanitation were dismissed, she changed her method.", "She collected data for months: injuries, infections and deaths. Then she translated it into a hand-drawn polar-area chart—the form now associated with her famous rose diagrams. The visual made a complex pattern immediately legible. Evidence accomplished what repeated pleading could not."], points: ["Clarity of thought", "Clarity of expression", "Presence", "Connection"] },
			{ heading: "Position is not persuasion", paragraphs: ["Prof. Godhwani framed influence without authority through four pillars: clarity of thought, expression, presence and connection. Nightingale did not need a higher rank to move the system; she needed a clearer case.", "We often assume that an idea needs a title behind it before it can move a room. Nightingale had neither position nor budget, yet her work influenced hospital practice at a national scale. The lesson is simple: when authority is unavailable, make the problem impossible to misunderstand."] }
		],
		links: [{ label: "Prof. Rakesh Godhwani", url: "https://www.linkedin.com/in/rakeshgodhwani/" }]
	},
	{
		id: "digital-sovereignty-ai",
		number: "02",
		title: "Digital Sovereignty in the Age of AI",
		dek: "The invisible dependency that could define the next global power shift—and why resilience matters more than isolation.",
		category: "AI & Strategy",
		date: "16 July 2026",
		readTime: "13 min read",
		featured: true,
		quote: "The goal is not disconnection. It is avoiding total dependence on infrastructure you do not control and cannot replace.",
		sections: [
			{ heading: "The sovereignty we quietly traded away", paragraphs: ["Imagine a ministry unable to open documents, a public-sector bank unable to process transactions, or a hospital locked out of its scheduling system—not because of a cyberattack, but because a foreign provider changed the commercial or geopolitical terms of access. Dramatic? Yes. Impossible? Less so than it sounds.", "Over two decades, governments and businesses moved to global cloud platforms for good reasons: lower costs, faster innovation, strong security and continuous updates. The problem is that better gradually became irreplaceable. Microsoft, Salesforce, Google Workspace, AWS, Azure, GCP and WhatsApp now form part of the operating environment of modern economies." ] },
			{ heading: "Technology is geopolitics", paragraphs: ["Semiconductor export restrictions, GPU-allocation constraints and telecom-equipment bans show that technology supply chains can become foreign-policy instruments. The exposure exists even if an enterprise-software cutoff never occurs. Dependency itself is the vulnerability.", "The strategic question is not whether global platforms are good or bad. It is whether a country can continue governing, banking, treating patients and running businesses if access changes suddenly."] },
			{ heading: "The numbers are hard to ignore", paragraphs: ["Synergy Research Group estimated global cloud-infrastructure spending at roughly $129 billion in Q1 2026, with AWS, Azure and Google Cloud together accounting for about two-thirds of enterprise cloud spending. Gartner forecast Indian public-cloud spending at $17.5 billion in 2026, up 28.1% year on year, with infrastructure-as-a-service growing even faster.", "These figures describe extraordinary capability and equally extraordinary concentration. Most debate about AI sovereignty focuses on domestic language models, but sovereignty spans the full stack: semiconductors, GPUs, cloud, foundation models, enterprise software, identity, storage and cybersecurity. A domestic model running entirely on foreign infrastructure is still structurally dependent."] },
			{ heading: "India is building more than chatbots", paragraphs: ["Krutrim has moved toward cloud services and GPU infrastructure. Sarvam AI is building multilingual models, speech systems and enterprise deployments. Neysa is focusing on domestic AI-cloud infrastructure and GPU-as-a-service. Together they illustrate three different pieces of a sovereign stack: models, interfaces and compute.", "Several quieter players matter too. Yotta is building large domestic GPU clusters through Shakti Cloud. E2E Cloud offers India-resident compute with local pricing. QpiAI is working across quantum hardware and software. Fractal is building reasoning models under the IndiaAI Mission. Tattvam AI is tackling semiconductor physical-design automation. Gnani AI is lowering Indic-language inference costs, while NPCI's work around financial AI could prove strategically significant because it sits close to public payment rails."] },
			{ heading: "What sovereignty actually requires", paragraphs: ["Startups cannot solve this alone. National digital resilience requires coordinated investment across compute, open models, enterprise software, cloud platforms, cybersecurity and semiconductor capacity. This is a decade-long infrastructure project, not a startup sprint.", "The practical near-term goal is resilience: multi-cloud architectures, open-source frameworks, portable data, hybrid deployments and domestic alternatives for sensitive sectors. Global technology will remain essential. The aim is to keep choice, continuity and bargaining power."] },
			{ heading: "The bigger picture", paragraphs: ["Oil, manufacturing and military capacity defined much of 20th-century leverage. The 21st century adds control over the infrastructure through which governments govern, businesses operate and societies communicate.", "India's emerging AI companies are more than valuation stories. They are early chapters in a longer question: will the country build enough of its digital foundations to retain strategic agency, or permanently rent them from others?"] }
		],
		links: [
			{ label: "Gartner", url: "https://www.gartner.com/" },
			{ label: "Synergy Research Group", url: "https://www.srgresearch.com/" },
			{ label: "Sarvam AI", url: "https://www.sarvam.ai/" }
		]
	},
	{
		id: "healthcare-ai-governance",
		number: "03",
		title: "Healthcare AI: Build Fast, Scale Safely",
		dek: "Risk-based regulation, clinical co-creation and designing for the 99%—a field note on trustworthy healthcare AI.",
		category: "Healthcare",
		date: "2026",
		readTime: "8 min read",
		quote: "In healthcare, regulation should be the runway that lets innovation take off safely.",
		sections: [
			{ heading: "Scale requires trust", paragraphs: ["Healthcare is shifting from AI experimentation to deployment at scale. But scale requires trust, and trust requires governance. During a recent panel, Nico Schiettekatte—Counsellor for Health, Welfare and Sport at the Embassy of the Kingdom of the Netherlands in New Delhi—shared how the Netherlands and the European Union approach regulation without suffocating innovation.", "The core idea is proportionality. The EU AI Act categorises systems by risk rather than treating every algorithm as equally dangerous. Clear guardrails can help software-as-a-medical-device teams move faster because safety expectations are visible early, not discovered at the end."] },
			{ heading: "Design for low-resource settings", paragraphs: ["Healthcare AI should not become a collection of shiny objects built only for top-tier hospitals. Its deepest value may emerge in low-resource settings: screening, triage and simple decision support for frontline workers.", "A useful example is AI-assisted X-ray screening for tuberculosis across rural districts. The point is not to replace clinicians. It is to make scarce expertise travel farther and help trained professionals decide where attention is needed first."], points: ["Triage over autonomous treatment", "Simple decision support for frontline workers", "Supervised use by trained professionals", "Compatibility with digital public infrastructure"] },
			{ heading: "Co-create with clinicians", paragraphs: ["A technically brilliant model can fail if it does not fit clinical workflow. Ninety-percent accuracy may sound strong in a pitch deck, but in care delivery it can mean missing one in ten patients. Metrics must reflect real-world clinical consequences.", "Teams should unify useful signals across radiology, pathology and genomics without overwhelming doctors. The winning product is not the one with the most impressive isolated benchmark; it is the one clinicians can safely understand, challenge and use."] },
			{ heading: "The principle", paragraphs: ["Innovation and regulation are not natural enemies. Good governance protects patients, clarifies the path to market and creates the confidence required for adoption. The test is not whether a tool looks advanced—it is whether it works safely in the conditions where care is actually delivered."] }
		],
		links: [
			{ label: "Nico Schiettekatte", url: "https://www.linkedin.com/in/nico-schiettekatte-08b2427/" },
			{ label: "Mahajan Imaging & Labs", url: "https://www.linkedin.com/company/mahajan-imaging-pvt-ltd-/" }
		]
	},
	{
		id: "healthcare-ai-operations",
		number: "04",
		title: "Healthcare AI's First Revolution Is Time",
		dek: "Before robotic surgeons, the operational wins: faster discovery, less administration and more productive diagnostic infrastructure.",
		category: "Healthcare",
		date: "2026",
		readTime: "6 min read",
		quote: "The immediate impact of AI in healthcare will not be science fiction. It will be giving time back to care.",
		sections: [
			{ paragraphs: ["When we think of AI in medicine, we often picture robotic surgeons and futuristic diagnosis. But leaders at a recent healthcare panel focused on a more immediate frontier: operational low-hanging fruit.", "Drug-discovery systems may compress parts of a journey that often takes a decade. Administrative automation can return nurses—who deliver much of day-to-day patient care—to the bedside. Better reconstruction and scheduling can reduce radiation exposure and increase the daily throughput of expensive CT and MRI machines."] },
			{ heading: "Efficiency is a clinical outcome", paragraphs: ["Aman Sharma from the Department of Pharmaceuticals and Dr. Vishnu Panigrahi of Fortis Healthcare highlighted the same economic logic: when hospitals use scarce people, machines and time better, the cost of care can fall.", "Operational gains are not secondary to patient outcomes. A shorter queue, a nurse with more time and a scanner serving more patients are all meaningful improvements in access."] },
			{ heading: "From pilots to systems", paragraphs: ["The industry must also stop building in a vacuum. Hospitals will not adopt tools that create extra clicks, fragment data or fail under real clinical pressure. Developers and clinicians need to define the problem, workflow and safety checks together.", "India has a large economic opportunity in AI, but the more important challenge is execution: move from isolated demos to systems that are monitored, governed and embedded in care. Use AI for speed; keep trained people responsible for judgment."] },
			{ heading: "A question worth asking", paragraphs: ["Are we focusing enough on the operational side of AI—or are we still distracted by the clinical hype? The most transformative product may be the one that quietly gives every shift a little more time."] }
		],
		links: [{ label: "Fortis Healthcare", url: "https://www.linkedin.com/company/fortis-healthcare/" }, { label: "NITI Aayog", url: "https://www.linkedin.com/company/nitiaayog/" }]
	},
	{
		id: "free-ai-subscriptions",
		number: "05",
		title: "The Price of 'Free' AI",
		dek: "India's AI subsidy war is not charity. It is a contest for distribution, habit, data and the next interface layer.",
		category: "AI & Strategy",
		date: "2026",
		readTime: "7 min read",
		featured: true,
		quote: "You are not paying with money. You are paying with habit, context and switching cost.",
		sections: [
			{ heading: "The OS war of 2026", paragraphs: ["Indian users have received premium AI subscriptions bundled through telecom and platform offers: Jio with Gemini, Airtel with Perplexity, and lower-priced access from OpenAI. The strategy resembles the early days of consumer internet expansion—volume first, monetisation later.", "The prize is larger than a chatbot subscription. Whoever becomes the default assistant can sit between users and search, documents, cloud storage, work and eventually commerce. This is an operating-system contest disguised as a giveaway."] },
			{ heading: "The hidden exchange", paragraphs: ["India's code-mixed language and enormous diversity are a powerful product stress test. User feedback reveals where models fail across Hindi-English and regional-language contexts. Telecom bundles also reduce payment friction and give AI companies immediate distribution at national scale.", "Then comes lock-in. Once users store terabytes of files, build personal knowledge bases and embed an assistant into daily workflows, moving becomes costly. The free period acquires a long tail."] },
			{ heading: "Is it over for Indian startups?", paragraphs: ["No. Global firms are fighting for the horizontal consumer interface. Indian companies can win on a different field: domestic compute, voice-first interaction and vertical products designed around local regulation and workflows.", "Krutrim and Sarvam illustrate the opportunity. Sovereign compute can reduce external dependency. Voice interfaces can reach users who will never make typing in English their primary mode. Vertical AI can address legal, agricultural, healthcare and government problems that generic models routinely miss."] },
			{ heading: "The verdict", paragraphs: ["The subsidy war will eventually cool. The innovation war will not. The career question for users is equally important: are these tools only saving minutes, or are they helping us build judgment and durable skill? Convenience compounds—but so does capability."] }
		]
	},
	{
		id: "india-neutral-pole",
		number: "06",
		title: "The World Is Fracturing. India Is Building.",
		dek: "A data-led view of India as a potential neutral pole in a volatile global economy.",
		category: "Economy",
		date: "2026",
		readTime: "5 min read",
		quote: "India is not simply an outlier in the growth story. It is increasingly one of the engines.",
		sections: [
			{ paragraphs: ["Headlines in 2026 are dominated by geopolitical tension, rising defence expenditure, debt concerns and volatile asset markets. Yet a different story emerges when we look at India through growth, investment and strategic positioning.", "Forecast ranges from institutions such as the IMF and UN have placed India's growth well above the global average. Forecasts change and should be read with care, but the structural divergence deserves attention."] },
			{ heading: "Three drivers", paragraphs: ["First, strategic autonomy: India often avoids binary geopolitical alignment in favour of issue-based partnerships and domestic priorities. Second, an investment-led cycle: public capital expenditure in infrastructure can create capacity beyond a single consumption season. Third, resilience: diversified trade relationships across Europe, the Middle East and Asia can reduce dependence on any one market."], points: ["Strategic autonomy", "Investment-led growth", "Diversified economic relationships"] },
			{ heading: "My take", paragraphs: ["Global instability is not automatically good for India. It raises energy, trade and financial risks. But it can also cause capital and companies to search for scale with relative institutional continuity.", "The opportunity is not guaranteed. It depends on execution: jobs, logistics, manufacturing depth, human capital and policy consistency. If those foundations strengthen, India's role can shift from promising outlier to durable growth engine."] }
		]
	},
	{
		id: "deep-work-ai",
		number: "07",
		title: "AI Speeds Up the Surface. Depth Still Takes Work.",
		dek: "Expertise is not disappearing. Its value is moving from production speed to problem selection, context and judgment.",
		category: "Career",
		date: "2026",
		readTime: "7 min read",
		quote: "The skill is no longer only 'can you produce it?' It is 'do you understand what to automate and what to preserve?'",
		sections: [
			{ paragraphs: ["A question raised during Pushparanjan Malajure's session deserves serious attention: is AI making expertise cheap, or democratising access to knowledge? AI can generate code, presentations and strategy drafts quickly. What it cannot reliably supply is years of industry context compressed into judgment."] },
			{ heading: "Large problems are not superficial", paragraphs: ["Improving an engine, restoring soil health or discovering a medicine requires deep causal understanding. AI can accelerate secondary research and help specialists explore more possibilities. It cannot independently decide which observations matter, reconcile every local constraint or own the consequences of a decision.", "The winning formula combines deep industry understanding, AI-assisted research, human synthesis across disciplines and primary evidence from the field. AI shortens parts of the journey; it does not eliminate the need to travel it."] },
			{ heading: "The barrier to entry has fallen", paragraphs: ["The encouraging side is that capable newcomers can now build and learn faster. A person with a handful of serious projects, disciplined experiments and a working grasp of LLMs may demonstrate more ability than a candidate with a longer but passive résumé.", "Build one useful AI project. Document what failed and what changed. Stop waiting for permission to call yourself a practitioner. Expertise is earned through deliberate experimentation—not declared by tenure alone."] },
			{ heading: "Automate friction, preserve judgment", paragraphs: ["Founders can use AI to draft HR documentation, segment prospect lists and prototype product ideas. These are high-friction activities where a fast first draft is valuable. But outputs entering production still require review, testing and governance.", "Use AI for speed. Keep humans accountable for quality, context and decisions. The companies that understand this boundary will move quickly without turning today's convenience into tomorrow's technical debt."] }
		],
		links: [{ label: "Pushparanjan Malajure", url: "https://www.linkedin.com/in/ranjanm/" }, { label: "Marsh McLennan", url: "https://www.linkedin.com/company/marshmclennan/" }]
	},
	{
		id: "human-ingenuity",
		number: "08",
		title: "When Intelligence Becomes Abundant",
		dek: "Human ingenuity, the 3+1 framework and why adaptability may matter more than competing with machines.",
		category: "Leadership",
		date: "2026",
		readTime: "6 min read",
		quote: "Do not compete with AI on raw processing. Compete on adaptability, courage and care.",
		sections: [
			{ heading: "The commoditisation of intelligence", paragraphs: ["A session with Ambarish Kenghe, Group CEO of Angel One, reframed the fear around AI. When intelligence-like capabilities become cheap and accessible, uniquely human value does not vanish—it shifts.", "Humans remain unusually good at adapting to chaos, noticing a problem before it is formally defined and taking hopeful risks with incomplete information. Call it ingenuity or jugaad; it is the ability to create movement without perfect conditions."] },
			{ heading: "A 3+1 framework for satisfaction", paragraphs: ["Sustainable career satisfaction often sits at the intersection of three conditions: excitement about the problem, pride in the work, and enough economic freedom to remove constant financial anxiety. The plus one is recognition—an environment that actually sees your contribution."], points: ["Excitement", "Boasting rights—the healthy pride of meaningful work", "Economic freedom", "+1: Recognition"] },
			{ heading: "Learn—and unlearn", paragraphs: ["Old methods expire faster than they used to. The ability to unlearn can therefore matter as much as the ability to acquire a new skill. Ownership becomes more durable than title; impact becomes a better compass than status alone.", "A regret-minimisation lens helps: which bold, responsible step would your future self wish you had taken while you still had the time, energy and room to recover? Intelligence is becoming abundant. Courage and adaptation remain scarce."] }
		],
		links: [{ label: "Ambarish Kenghe", url: "https://www.linkedin.com/in/ambarish-kenghe/" }, { label: "Angel One", url: "https://www.linkedin.com/company/angelone/" }]
	},
	{
		id: "interview-culture-management",
		number: "09",
		title: "The Work Behind the Interview",
		dek: "Company research, culture fit, psychological safety and a more useful definition of management success.",
		category: "Career",
		date: "2026",
		readTime: "10 min read",
		quote: "A company is choosing you—and you are also choosing the company.",
		sections: [
			{ heading: "Research beyond the product", paragraphs: ["Kushendra Singh shared a revealing interview exercise: candidates who had consumed Coca-Cola products for years often knew very little about the company, its portfolio or its ownership of brands such as Costa Coffee. One candidate even named Mountain Dew—a PepsiCo product—as a favourite Coca-Cola brand.", "The point was not trivia. Strong candidates investigate how an organisation works, what it values and how it makes money. They speak with employees, understand the vision, study the business model and arrive ready to evaluate fit in both directions."] },
			{ heading: "Culture fit is a real constraint", paragraphs: ["Every organisation has a working DNA. Every person brings expectations, energy patterns and values. High pay and prestigious travel cannot permanently compensate for a system that makes someone miserable.", "Some people thrive in intense, long-hour environments; others do their best work with a different rhythm. Neither is inherently weak. The question is compatibility: can you flourish in this system without compromising what matters most to you?"] },
			{ heading: "Management is what happens when you leave the room", paragraphs: ["Promotion and visibility are poor measures of leadership. Better signals are whether a team meets goals, grows in capability and feels safe enough to contribute honestly. Inclusion does not mean forcing every introvert to perform extroversion. A quiet observer may be the team's highest-value contributor.", "Trust grows through consistency. Great managers create psychological safety across personality types, distribute credit and make it possible for people to do good work without pretending to be someone else."] },
			{ heading: "The check-out epidemic", paragraphs: ["Quiet quitting is often less about laziness than a culture that suppresses authenticity. Employees can appear present while mentally disengaging and searching for an exit. Gallup has estimated the global cost of low engagement in the trillions of dollars.", "Freedom with accountability, honest feedback and adult-to-adult trust can reduce that loss. People rarely leave a job description alone; they leave the lived experience created by managers and systems."] },
			{ heading: "Prepare like it matters", paragraphs: ["Practise answers until they sound natural, but do not stop there. Know the organisation well enough to ask intelligent questions about culture, strategy and operating reality. The interview is not only your chance to make a mark. It is your chance to decide whether this is a mark you want the organisation to make on you."] }
		],
		links: [{ label: "Kushendra Singh", url: "https://www.linkedin.com/in/kushendrasingh19/" }, { label: "The Coca-Cola Company", url: "https://www.linkedin.com/company/the-coca-cola-company/" }]
	},
	{
		id: "human-strength-vuca",
		number: "10",
		title: "AI's Weakness Is Humanity's Strength",
		dek: "Why adaptation, sense-making and seven leadership mindsets matter in a volatile world.",
		category: "Leadership",
		date: "2026",
		readTime: "9 min read",
		quote: "When the path is hidden by fog, make sure the next step is higher than the previous one.",
		sections: [
			{ heading: "Pattern matching meets an unpredictable world", paragraphs: ["A session with Prof. Apurva Sanaria challenged a common assumption: AI is powerful, but much of its power comes from patterns in the past. In a volatile, uncertain, complex and ambiguous world, yesterday's pattern is not always tomorrow's answer.", "AI can process financial data but may miss the human signals of manipulation. It can draft a polished email but cannot reliably read a tense room. It can optimise a workflow but cannot replace the care a teammate needs on the worst day of their life."] },
			{ heading: "Collaborate, do not compete", paragraphs: ["Use AI for a first draft, then apply human judgment to find what is wrong, missing or misleading. Our species adapted to smartphones, reinvented industries during the pandemic and is already learning to work with AI. Our superpower is not perfection; it is adaptation."] },
			{ heading: "Seven mindsets for VUCA leadership", paragraphs: ["Prof. Sanaria described a hierarchy: mindset shapes the knowledge we seek, and knowledge enables skill. Skills can be developed in parallel, but mindset determines whether we notice what the situation requires."], points: ["Sense-making: create direction when others see noise", "Agility: experiment, learn and pivot", "Systems thinking: see interdependence", "Growth: treat capability as developable", "Empathy: listen to understand", "Resilience: recover and continue", "Reflection: extract lessons from success and failure"] },
			{ heading: "The risk-return paradox", paragraphs: ["We want better careers, relationships and opportunities while becoming more risk-averse. But exceptional returns rarely arrive with zero exposure. In a VUCA world, refusing to move is itself a decision—and often a risky one.", "The useful version of 'when in doubt, do it' is not recklessness. It is responsible action under uncertainty: take the flight when the destination matters, preserve room to recover and keep choosing the next higher step."] }
		],
		links: [{ label: "Prof. Apurva Sanaria", url: "https://www.linkedin.com/in/apurva-sanaria/" }]
	},
	{
		id: "digital-bank-india",
		number: "11",
		title: "Can a Fully Digital Bank Disrupt India?",
		dek: "Why India's banking future is both/and: digital scale with human trust, public rails with private innovation.",
		category: "Banking",
		date: "2026",
		readTime: "9 min read",
		featured: true,
		quote: "The winners will master duality: digital and physical, efficiency and empathy, scale and trust.",
		sections: [
			{ paragraphs: ["A digital-only bank can disrupt particular niches in India. A universal, deposit-led digital-only bank is less likely under today's regulatory and market conditions. India has chosen a distinctive architecture: keep regulated banks central while allowing fintechs to create, compete and cooperate on common public infrastructure."] },
			{ heading: "The economics of the model", paragraphs: ["Digital acquisition is rising, but high-value deposits still skew toward customers who often expect relationship support alongside convenience. Payments function increasingly like a public good—excellent for citizens, structurally thin-margin for banks—so value moves toward credit, wealth and distribution.", "As incomes rise, sachet buyers become fuller-package consumers. Banks need to design for that migration before it arrives. Money may move into mutual funds and equities, but it still passes through bank accounts and financial distribution systems. Product mix and capture points matter."] },
			{ heading: "AI and employment", paragraphs: ["When I asked K.V.S. Manian, MD and CEO of Federal Bank, about AI and employment, his answer echoed earlier waves of automation: pressure reaches skill-defined mid-level tasks first, while total employment can still grow as roles evolve.", "The career response is not fear but leverage. Use AI to augment risk, operations and service while strengthening human trust where it matters most. Maintain a permanent learning mindset, develop storytelling and empathy alongside analytics, and practise enough humility to let experts lead from wherever they sit."] },
			{ heading: "Leadership without a promoter", paragraphs: ["Leading a widely held bank requires ownership without personal equity and accountability without a dominant shareholder's safety net. The leader must feel the weight of employees, families, customers, regulators and investors.", "Technology is table stakes, not strategy. Keep senior leaders close to branches and frontline relationship managers. Run listening tours. Over-communicate to reduce transmission loss. Consistency beats bursts of intensity."] },
			{ heading: "From mainframes to mobile banking", paragraphs: ["India's financial sector moved from paper ledgers and room-sized mainframes to instant public payment rails within a single career. Four lessons stand out from that journey: timing creates openings, learning keeps them open, adaptability lets experience travel, and culture turns distributed branches into accountable businesses.", "A powerful operating idea comes from Handelsbanken: treat every branch manager like the CEO of the outlet. P&L ownership at the grassroots creates alignment faster than another memo from headquarters."] }
		],
		links: [{ label: "K.V.S. Manian", url: "https://www.linkedin.com/in/manian-kvs-6798b5/" }, { label: "Federal Bank", url: "https://www.linkedin.com/company/federal-bank/" }]
	},
	{
		id: "leadership-meraki",
		number: "12",
		title: "Lead With Meraki",
		dek: "Five lessons on energy, discomfort, mentorship, feedback and leaving real footprints.",
		category: "Leadership",
		date: "2026",
		readTime: "6 min read",
		quote: "Success is not only what you achieve. It is how you achieve it, who you bring along and what you leave behind.",
		sections: [
			{ paragraphs: ["The VENIX programme at IIM Bangalore began with a session by Shyam Unnikrishnan, Managing Partner at Bain & Company India. His lessons were corporate in context but deeply human in application."] },
			{ heading: "1. Be an energy giver", paragraphs: ["Some people lift a room; others leave it tired. Energy comes from what we care about, how we show up and how we make others feel. Ask honestly whether your presence expands a team's capacity or drains it. That awareness is the start of influence."] },
			{ heading: "2. Use discomfort as a compass", paragraphs: ["Comfort rarely produces the fastest growth. New technology, uncertain assignments and unfamiliar responsibility all create friction. Do not waste a disruption. Use it to stretch, learn and lead."] },
			{ heading: "3. Collect mentors, not only titles", paragraphs: ["Promotions are visible; the people who sharpen our judgment are often more consequential. Seek mentors who are smart, kind and honest enough to offer uncomfortable truths. Mentorship is not a one-time request—it is a habit of staying teachable."] },
			{ heading: "4. Know the back of your T-shirt", paragraphs: ["Your achievements are printed on the front. Your real professional brand is what people say when you are not in the room. Collect genuine 360-degree feedback from peers, juniors and seniors. Blind spots only become tools after they become visible."] },
			{ heading: "5. Leave real footprints", paragraphs: ["Meraki is a Greek word associated with putting a piece of your soul into the work. Résumés fade; impact and feeling endure. Leave clients, colleagues and communities better than you found them. Dream big, stay uncomfortable, build a tribe of mentors and pursue the work with integrity and full presence."] }
		],
		links: [{ label: "Shyam Unnikrishnan", url: "https://www.linkedin.com/in/shyamunnikrishnan/" }, { label: "Bain & Company", url: "https://www.linkedin.com/company/bain-and-company/" }]
	},
	{
		id: "india-ai-opportunity",
		number: "13",
		title: "$1.4 Trillion: India's AI Imperative",
		dek: "Why India must create—not merely consume—the systems that may shape its next phase of growth.",
		category: "AI & Strategy",
		date: "2026",
		readTime: "5 min read",
		quote: "If we delay, the gap widens. If we act, we lead.",
		sections: [
			{ paragraphs: ["During a recent session, Dr. V.K. Paul of NITI Aayog framed AI not only as a technology shift but as part of India's development trajectory. Estimates cited in the discussion suggest AI could add about $1.4 trillion to the economy by 2035–36. Forecasts are not guarantees, but they make the scale of the opportunity visible."] },
			{ heading: "Adoption is not enough", paragraphs: ["India cannot remain only a large market for systems created elsewhere. It needs to participate in model development, compute infrastructure, applications, standards and safety. The market will not wait while institutions debate whether the shift is real.", "The opportunity spans research, public services, healthcare, agriculture, finance, education and manufacturing. It also demands workforce transition: domain experts who can use AI, builders who understand local constraints and leaders who can govern deployment responsibly."] },
			{ heading: "India can help define AI", paragraphs: ["The strongest version of the claim is reciprocal: AI will influence India's future, and India's scale, languages and public digital infrastructure can influence how AI develops. That is possible only if the country creates solutions, measures outcomes and shares what works.", "Move quickly, but not carelessly. Lead with ambition, invest in foundations and keep human accountability at the centre. The difference between an AI wave that widens gaps and one that expands capability will be the quality of our choices now."] }
		],
		links: [{ label: "NITI Aayog", url: "https://www.linkedin.com/company/nitiaayog/" }]
	}
];

export const categories = ["All", "AI & Strategy", "Leadership", "Healthcare", "Career", "Banking", "Economy"] as const;
```

---

## lib/gsap.ts

**File Path**: `lib/gsap.ts` | **Lines**: 50

```typescript
import gsap from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";

if (typeof window !== "undefined") {
  gsap.registerPlugin(ScrollTrigger);
}

export { gsap, ScrollTrigger };

export const EASES = {
  smooth: "power3.out",
  snappy: "power4.out",
  elastic: "elastic.out(1, 0.3)",
  back: "back.out(1.7)",
  expo: "expo.out",
  circ: "circ.out",
};

export const DURATIONS = {
  fast: 0.3,
  normal: 0.6,
  slow: 1.0,
  cinematic: 1.4,
};

export function createScrollReveal(
  target: gsap.TweenTarget,
  options: gsap.TweenVars = {},
  scrollOptions: ScrollTrigger.Vars = {}
) {
  return gsap.fromTo(
    target,
    { y: 60, opacity: 0, ...options },
    {
      y: 0,
      opacity: 1,
      duration: DURATIONS.cinematic,
      ease: EASES.smooth,
      scrollTrigger: {
        trigger: target as Element,
        start: "top 85%",
        end: "bottom 20%",
        toggleActions: "play none none reverse",
        ...scrollOptions,
      },
      ...options,
    }
  );
}
```

---

## lib/motion.ts

**File Path**: `lib/motion.ts` | **Lines**: 99

```typescript
import { Variants } from "framer-motion";

export const fadeUp: Variants = {
  hidden: { opacity: 0, y: 40 },
  visible: {
    opacity: 1,
    y: 0,
    transition: { duration: 0.8, ease: [0.16, 1, 0.3, 1] },
  },
};

export const fadeIn: Variants = {
  hidden: { opacity: 0 },
  visible: {
    opacity: 1,
    transition: { duration: 0.8, ease: "easeOut" },
  },
};

export const staggerContainer: Variants = {
  hidden: {},
  visible: {
    transition: {
      staggerChildren: 0.08,
      delayChildren: 0.1,
    },
  },
};

export const staggerItem: Variants = {
  hidden: { opacity: 0, y: 30 },
  visible: {
    opacity: 1,
    y: 0,
    transition: { duration: 0.7, ease: [0.16, 1, 0.3, 1] },
  },
};

export const maskReveal: Variants = {
  hidden: { clipPath: "inset(0 100% 0 0)" },
  visible: {
    clipPath: "inset(0 0% 0 0)",
    transition: { duration: 1, ease: [0.76, 0, 0.24, 1] },
  },
};

export const slideInLeft: Variants = {
  hidden: { x: -60, opacity: 0 },
  visible: {
    x: 0,
    opacity: 1,
    transition: { duration: 0.8, ease: [0.16, 1, 0.3, 1] },
  },
};

export const slideInRight: Variants = {
  hidden: { x: 60, opacity: 0 },
  visible: {
    x: 0,
    opacity: 1,
    transition: { duration: 0.8, ease: [0.16, 1, 0.3, 1] },
  },
};

export const scaleIn: Variants = {
  hidden: { scale: 0.85, opacity: 0 },
  visible: {
    scale: 1,
    opacity: 1,
    transition: { duration: 0.8, ease: [0.16, 1, 0.3, 1] },
  },
};

export const pageTransition: Variants = {
  initial: { opacity: 0, y: 20 },
  animate: {
    opacity: 1,
    y: 0,
    transition: { duration: 0.6, ease: [0.16, 1, 0.3, 1] },
  },
  exit: {
    opacity: 0,
    y: -20,
    transition: { duration: 0.4, ease: "easeIn" },
  },
};

export const SPRING = {
  gentle: { type: "spring", stiffness: 100, damping: 20 },
  snappy: { type: "spring", stiffness: 400, damping: 30 },
  wobbly: { type: "spring", stiffness: 200, damping: 10 },
};

export const EASE = {
  smooth: [0.16, 1, 0.3, 1] as [number, number, number, number],
  snappy: [0.76, 0, 0.24, 1] as [number, number, number, number],
  cinematic: [0.25, 0.46, 0.45, 0.94] as [number, number, number, number],
};
```

---

## lib/utils.ts

**File Path**: `lib/utils.ts` | **Lines**: 33

```typescript
import { clsx, type ClassValue } from "clsx";
import { twMerge } from "tailwind-merge";

export function cn(...inputs: ClassValue[]) {
  return twMerge(clsx(inputs));
}

export function lerp(start: number, end: number, t: number): number {
  return start * (1 - t) + end * t;
}

export function clamp(value: number, min: number, max: number): number {
  return Math.min(Math.max(value, min), max);
}

export function mapRange(
  value: number,
  inMin: number,
  inMax: number,
  outMin: number,
  outMax: number
): number {
  return ((value - inMin) * (outMax - outMin)) / (inMax - inMin) + outMin;
}

export function splitTextToWords(text: string): string[] {
  return text.split(" ");
}

export function splitTextToChars(text: string): string[] {
  return text.split("");
}
```

---

## next-env.d.ts

**File Path**: `next-env.d.ts` | **Lines**: 7

```typescript
/// <reference types="next" />
/// <reference types="next/image-types/global" />
import "./.next/types/routes.d.ts";

// NOTE: This file should not be edited
// see https://nextjs.org/docs/app/api-reference/config/typescript for more information.
```

---

## next.config.ts

**File Path**: `next.config.ts` | **Lines**: 99

```typescript
import type { NextConfig } from "next";

const nextConfig: NextConfig = {
  reactStrictMode: true,
  poweredByHeader: false,
  compress: true,
  productionBrowserSourceMaps: false,
  images: {
    formats: ["image/avif", "image/webp"],
    minimumCacheTTL: 60 * 60 * 24 * 30,
    deviceSizes: [360, 640, 750, 828, 1080, 1200, 1440, 1920, 2560],
    imageSizes: [16, 32, 48, 64, 96, 128, 256, 384, 512, 768],
    remotePatterns: [
      { protocol: "https", hostname: "ui.aceternity.com" },
      { protocol: "https", hostname: "aceternity.com" },
      { protocol: "https", hostname: "i.pinimg.com" },
      { protocol: "https", hostname: "picsum.photos" },
      { protocol: "https", hostname: "images.unsplash.com" },
      { protocol: "https", hostname: "plus.unsplash.com" },
    ],
  },
  experimental: {
    optimizePackageImports: [
      "framer-motion",
      "gsap",
      "lucide-react",
      "@radix-ui/react-label",
      "@radix-ui/react-switch",
      "@react-three/drei",
      "lenis",
    ],
  },
  webpack: (config, { isServer }) => {
    if (!isServer) {
      // Group fragmented vendor node_modules into unified chunks to make fewer HTTP requests
      config.optimization.splitChunks = {
        ...config.optimization.splitChunks,
        cacheGroups: {
          default: false,
          vendors: false,
          // Group key framework modules
          frameworks: {
            name: "frameworks",
            chunks: "all",
            test: /[\\/]node_modules[\\/](react|react-dom|next|scheduler)[\\/]/,
            priority: 40,
            enforce: true,
          },
          // Aggregate heavy UI and animation libraries into a single chunk
          libs: {
            test: /[\\/]node_modules[\\/](gsap|framer-motion|lenis|swiper|ogl|lucide-react)[\\/]/,
            name: "libs",
            chunks: "all",
            priority: 30,
            enforce: true,
          },
          // Shared modules
          commons: {
            name: "commons",
            chunks: "all",
            minChunks: 2,
            priority: 20,
            reuseExistingChunk: true,
          },
        },
      };
    }
    return config;
  },
  turbopack: {
    root: process.cwd(),
  },
  async headers() {
    const longCache = "public, max-age=31536000, immutable";
    return [
      {
        source: "/:all*(woff2|woff|ttf|otf)",
        headers: [{ key: "Cache-Control", value: longCache }],
      },
      {
        source: "/:all*(png|jpg|jpeg|webp|avif|svg|gif|ico)",
        headers: [{ key: "Cache-Control", value: longCache }],
      },
      {
        source: "/(.*)",
        headers: [
          { key: "Cache-Control", value: "no-cache, no-store, must-revalidate" },
          { key: "X-Content-Type-Options", value: "nosniff" },
          { key: "X-Frame-Options", value: "SAMEORIGIN" },
          { key: "Referrer-Policy", value: "strict-origin-when-cross-origin" },
          { key: "X-DNS-Prefetch-Control", value: "on" },
        ],
      },
    ];
  },
};

export default nextConfig;
```

---

## package.json

**File Path**: `package.json` | **Lines**: 51

```json
{
  "name": "portfoliodraft05",
  "version": "0.1.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "eslint"
  },
  "dependencies": {
    "@base-ui/react": "^1.4.1",
    "@gsap/react": "^2.1.2",
    "@radix-ui/react-label": "^2.1.8",
    "@radix-ui/react-switch": "^1.2.6",
    "@react-three/drei": "^10.7.7",
    "@react-three/fiber": "^9.6.1",
    "@splinetool/react-spline": "^4.1.0",
    "@splinetool/runtime": "^1.12.94",
    "@studio-freight/lenis": "^1.0.42",
    "@vercel/speed-insights": "^2.1.0",
    "class-variance-authority": "^0.7.1",
    "clsx": "^2.1.1",
    "framer-motion": "^12.38.0",
    "gsap": "^3.15.0",
    "lenis": "^1.3.23",
    "lucide-react": "^1.16.0",
    "next": "16.2.6",
    "ogl": "^1.0.11",
    "react": "19.2.4",
    "react-dom": "19.2.4",
    "shadcn": "^4.7.0",
    "sharp": "^0.35.5",
    "swiper": "^12.1.4",
    "tailwind-merge": "^3.6.0",
    "three": "^0.184.0",
    "tw-animate-css": "^1.4.0"
  },
  "devDependencies": {
    "@tailwindcss/postcss": "^4",
    "@types/node": "^20",
    "@types/react": "^19",
    "@types/react-dom": "^19",
    "@types/three": "^0.184.1",
    "eslint": "^9",
    "eslint-config-next": "16.2.6",
    "tailwindcss": "^4",
    "typescript": "^5"
  }
}
```

---

## postcss.config.mjs

**File Path**: `postcss.config.mjs` | **Lines**: 8

```javascript
const config = {
  plugins: {
    "@tailwindcss/postcss": {},
  },
};

export default config;
```

---

## README.md

**File Path**: `README.md` | **Lines**: 327

```markdown
# Jay Parmar — AI/ML Builder, Finance Analyst & Product Leader

A cinematic, scroll-driven personal portfolio built on Next.js 16 (App Router), React 19, Tailwind CSS v4, GSAP ScrollTrigger, Framer Motion, Lenis smooth-scroll, Three.js / Spline, and custom WebGL shaders. Designed to read like an executive dossier and editorial spread across desktop and mobile, with every section choreographed against a single scroll timeline.

The site is deliberately heavy on motion and light on chrome: there is no navigation bar, no fold; the experience is the scroll. Each "chapter" introduces itself with a full-bleed curtain, plays a dedicated micro-scene, and hands the user off to the next chapter via a custom transition (warp portal, fold, zoom-parallax, tilted grid).

---

## Live deploy

Deployed on Vercel from the `main` branch. Push-to-deploy. Static prerendering for the single route (`/`) plus on-demand image optimization through `next/image`.

---

## Tech stack

| Layer | Library / Tool | Version | Why it's here |
|---|---|---|---|
| Framework | Next.js | 16.2.6 (App Router, Turbopack) | Static prerender of the single page, image optimization pipeline, font subsetting, route-level code splitting |
| UI runtime | React | 19.2.4 | Server Components for the root page; Client Components for every scroll-driven scene |
| Language | TypeScript | 5.x (strict) | All app code is `.tsx` / `.ts` under `strict: true` |
| Styling | Tailwind CSS | 4.x | Utility-first; theming via `@theme` tokens in `globals.css` |
| Component primitives | shadcn/ui, Radix | — | Buttons, dialog, tabs, sheet, switch, label |
| Scroll engine | Lenis | 1.3.23 | RAF-driven smooth scroll piped into GSAP's ticker so every ScrollTrigger reads from the same time source |
| Macro animation | GSAP + ScrollTrigger | 3.15 | Pinning, scrub, timeline choreography (FrameToFullscreen, ScrollWarpPortal, ScrollFoldTransition, ScrollRevealCurtain) |
| Micro animation | Framer Motion | 12.38 | Component-level enter/exit, cursor spring, hero parallax, modals |
| 3D scene | Spline (@splinetool/react-spline) | 4.1 | The "Built Different" hero scene |
| WebGL shader | ogl | 1.0.11 | Custom light-rays fragment shader behind the design carousel |
| 3D primitives | three, @react-three/fiber, @react-three/drei | 0.184 / 9.6 / 10.7 | Available for future scenes |
| Carousel | Swiper | 12.1 | Design carousel slider |
| Fonts | `next/font/google` — Cormorant Garamond, DM Sans | — | Two weights of Cormorant for display, three of DM Sans for body, all served via the Vercel font CDN |

---

## What's on the page

The single route at `/` is composed of these scenes, in order, all rendered as static HTML on first paint and progressively hydrated:

1. **`FrameToFullscreen` → `VSCodePortfolio`**
   GSAP pin + perspective tilt that lifts a miniature VS Code window from the page and flattens it into the viewport. The IDE is a full replica — Mac OS menu bar, activity bar, explorer with a working `FileTree`, tabs, editor, right rail with `ProjectModal` cards driven by real project data, an animated `TextType` headline, and an embedded Apple-style `SpotlightSearch` (`⌘K`).

2. **`ScrollRevealCurtain` → `SplineSceneBasic`**
   A black curtain peels away to reveal a Spline 3D scene with a `Spotlight` sweep. The Spline runtime is lazy-loaded behind an `IntersectionObserver` so the ~2 MB WebAssembly bundle never ships until the section is scrolled into view.

3. **`StoryScrollDemo`**
   "About" chapter — long-form copy revealed through scroll-pinned typographic panels (`story-scroll.tsx`) with a `prefers-reduced-motion` opt-out.

4. **`ScrollWarpPortal`** (Chapter 02 — The Showcase)
   Pinned section where text warps through a portal effect.

5. **`HeroParallaxDemo` → `HeroParallax`**
   Three horizontally-translating rows of project cards driven by `useScroll` + `useSpring`. Real project thumbnails (KodaiRateIQ, ProofStack, CyberShield India, etc.) link out to live deploys.

6. **`ScrollMorphSection` → `ScrollMorphHero`**
   Scatter → line → circle → bottom-strip flip-card morph animation cycling through every project image.

7. **`ScrollFoldTransition`** (Chapter 03 — Designed with Intent)
   Origami-style fold transition between sections.

8. **`ScrollTiltedGridDemo` → `ScrollTiltedGrid`**
   Each tile is a `motion` element with its own `useScroll`-driven blur, brightness, contrast, and 3D tilt. Backed by a starfield + dotted-grid + radial gold glow backdrop.

9. **`CardCarouselDemo`** with `LightRays` backdrop
   Design portfolio carousel with a custom ogl-based fragment shader projecting low-saturation gold rays from the top of the section.

10. **`ZoomParallaxDemo` → `ZoomParallax`**
    Sticky 300vh container where seven images zoom independently into the viewport on a single scroll arc.

11. **`ProfileCard`** (Contact)
    Tilted holographic business card with pointer-tracked shine, mini avatar, status pill, and a LinkedIn CTA.

12. **`FooterDemo` → `Footer`**
    Brand mark, social grid (LinkedIn, Resume, GitHub, Mail), nav row, and a giant blurred wordmark backdrop.

A global `MouseFollower` (dual-spring cursor) and a `PageReveal` curtain animate over the whole experience, and a `SmoothScrollProvider` (Lenis) drives the page's scroll.

---

## Project structure

```
.
├─ app/
│  ├─ layout.tsx              Root layout — fonts, viewport, metadata, providers
│  ├─ page.tsx                Single route, composed of every scene in order
│  ├─ globals.css             Tailwind v4 theme tokens, scrollbar hide, noise overlay
│  └─ favicon.ico
│
├─ components/
│  ├─ animations/             Scroll choreography + page-wide motion primitives
│  │  ├─ FrameToFullscreen.tsx          GSAP pin + perspective unfold (IDE intro)
│  │  ├─ ScrollRevealCurtain.tsx        Color curtain peel
│  │  ├─ ScrollWarpPortal.tsx           Warp-through-portal transition
│  │  ├─ ScrollFoldTransition.tsx       Origami fold between sections
│  │  ├─ ScrollReveal.tsx               Drop-in reveal-on-scroll wrapper
│  │  ├─ ScrollFloat.tsx + .css         Per-character staggered float
│  │  ├─ ScrollExpand.tsx               Width/height expand on scroll
│  │  ├─ ParallaxSection.tsx            Y-translate parallax helper
│  │  ├─ MaskRevealText.tsx             Clip-path masked text reveal
│  │  ├─ StaggerTextReveal.tsx          Word-by-word stagger
│  │  ├─ VelocityScroll.tsx             Scroll-velocity skew
│  │  ├─ MagneticButton.tsx             Pointer-attractive button
│  │  ├─ HoverDistortionCard.tsx        Pointer-driven RGB-split card
│  │  ├─ MouseFollower.tsx              Dual-spring cursor (mix-blend-difference)
│  │  ├─ PageTransition.tsx             Page reveal + AnimatePresence route fade
│  │  ├─ SmoothScrollProvider.tsx       Lenis + GSAP ticker hookup
│  │  └─ SectionWrapper.tsx             Standardized section padding/layout
│  │
│  └─ ui/                     Scene components, shadcn primitives, and one-offs
│     ├─ vscode-portfolio.tsx           VS Code window replica (1119 LOC)
│     ├─ apple-spotlight.tsx            ⌘K spotlight with shortcuts + search
│     ├─ mac-os-menu-bar.tsx            Top menu bar, clock, weather
│     ├─ file-tree.tsx                  Animated file tree
│     ├─ project-modal.tsx              Project detail modal
│     ├─ project-showcase.tsx           Cursor-tracked project hover preview
│     ├─ hero-parallax.tsx              Three-row horizontal parallax
│     ├─ scroll-morph-hero.tsx          Scatter → line → circle morph
│     ├─ scroll-tilted-grid.tsx         Per-tile scroll-driven 3D tilt
│     ├─ zoom-parallax.tsx              Seven-image zoom-into-viewport
│     ├─ story-scroll.tsx               Pinned chapter typography
│     ├─ scroll-stack.tsx + .css        Sticky stacked cards
│     ├─ card-carousel.tsx              Design portfolio carousel
│     ├─ LightRays.tsx + .css           ogl-based fragment shader
│     ├─ ProfileCard.tsx + .css         Tilted holographic card
│     ├─ spline-scene-basic.tsx         Spline scene + Spotlight sweep
│     ├─ splite.tsx                     Lazy Suspense wrapper for Spline
│     ├─ spotlight.tsx                  SVG radial spotlight
│     ├─ lamp.tsx                       Conic-gradient lamp glow
│     ├─ logo-loop.tsx + .css           Infinite logo marquee
│     ├─ modem-animated-footer.tsx      Footer chrome
│     ├─ footer-demo.tsx                Footer composition
│     ├─ text-type.tsx + .css           Typewriter effect
│     ├─ ruler-carousel.tsx             Ruler-style carousel
│     ├─ container-scroll-animation.tsx Shared context for FrameToFullscreen
│     ├─ safari-01.tsx                  Safari-window chrome
│     ├─ ScrollProgressBar.tsx          Top scroll-progress bar
│     └─ shadcn primitives              badge, button, card, dialog, input, sheet,
│                                       tabs, button-shiny
│
├─ hooks/
│  ├─ useLenis.ts             Lenis RAF + GSAP ticker glue + global accessor
│  ├─ useInView.ts            IntersectionObserver hook
│  ├─ useMousePosition.ts     Pointer tracking
│  └─ useScrollProgress.ts    Scroll progress in [0,1]
│
├─ lib/
│  ├─ gsap.ts                 GSAP + ScrollTrigger registration, ease/duration tokens, createScrollReveal
│  ├─ motion.ts               Framer Motion variants and timing tokens
│  └─ utils.ts                cn() class merger
│
├─ constants/
│  └─ index.ts                Site metadata, nav links, project / skill / experience seed data
│
├─ public/                    Project thumbnails, design carousel images, profile assets, fonts
├─ next.config.ts             Image pipeline, package import optimization, cache + security headers
├─ tsconfig.json              strict TS, ES2017 target, `@/*` path alias
├─ eslint.config.mjs          Flat config layering eslint-config-next core-web-vitals + TS rules
├─ postcss.config.mjs         Tailwind v4 PostCSS plugin
├─ components.json            shadcn config
├─ package.json               Dependencies, scripts
├─ AGENTS.md / CLAUDE.md      Agent guard-rails (Next.js 16 has breaking changes — read node_modules/next/dist/docs)
└─ README.md                  You are here
```

---

## Getting started

### Prerequisites

- Node.js 20+ (Next.js 16 dropped Node 18)
- pnpm 9+ (the repo ships a `pnpm-lock.yaml` and a `pnpm-workspace.yaml`)

### Install

```bash
pnpm install
```

### Local development

```bash
pnpm dev
```

Open <http://localhost:3000>. Turbopack is the default in Next.js 16; HMR is wired through `next dev`. Edit `app/page.tsx` and any imported scene to iterate live.

### Production build

```bash
pnpm build
pnpm start
```

`pnpm build` runs Turbopack-powered production compilation, type-checks the project with `tsc --noEmit` (via Next), collects route data, and prerenders the single `/` route to static HTML. The output is in `.next/`.

### Lint

```bash
pnpm lint
```

ESLint flat config layers `eslint-config-next/core-web-vitals` and `eslint-config-next/typescript`. Lint is decoupled from `next build` (so an in-flight stylistic warning does not block deploys), but the type checker still runs during build and will fail the build on any TS error.

---

## Architecture decisions

### Single scroll timeline

The whole experience is driven by one source of truth for time:

- `useLenis` ([`hooks/useLenis.ts`](hooks/useLenis.ts)) instantiates Lenis with `duration: 1.2`, an exponential-ease wheel, and pipes its `scroll` event straight into `ScrollTrigger.update`.
- The Lenis RAF loop is registered with `gsap.ticker.add(tick)` — *the same `tick` reference is removed in cleanup* (early commits had a leak here where `gsap.ticker.add` and `gsap.ticker.remove` were given different inline closures, so the RAF survived hot-reloads).
- Every animated section uses GSAP ScrollTrigger or Framer Motion's `useScroll`, both reading from `window.scrollY`, which Lenis now owns. There is no second scroll loop anywhere.

### Code splitting

- The root `app/page.tsx` is a **Server Component**. Every interactive scene is a Client Component (`"use client"`) imported into it. Next.js automatically code-splits each client component into its own chunk.
- The Spline runtime (~2 MB compressed, includes WebAssembly for physics + opentype) is wrapped in [`splite.tsx`](components/ui/splite.tsx) with `React.lazy()` + `<Suspense>`. The Spline scene component then guards its render behind an `IntersectionObserver` so the runtime is not even *fetched* until the user scrolls to it.
- `next.config.ts` declares `experimental.optimizePackageImports` for `framer-motion`, `gsap`, `lucide-react`, `@radix-ui/*`, `@react-three/drei`, and `lenis` — only the named exports actually used get bundled.

### Image pipeline

- `next/image` is used for every non-decorative image, with explicit `sizes` matched to the actual visual width.
- `next.config.ts` declares `formats: ['image/avif', 'image/webp']` and tuned `deviceSizes` / `imageSizes` arrays, so the heavy PNGs (`oldportfolio-1.png` at 4.5 MB, `profilecard.png` at 4.1 MB) stream as AVIF/WebP at viewport size rather than as raw PNG.
- A response-header rule applies `Cache-Control: public, max-age=31536000, immutable` to fonts and images.

### Fonts

- Two `next/font/google` families: Cormorant Garamond (display, weights 400/500) and DM Sans (body, weights 400/500/600). Both with `display: 'swap'`.
- Cormorant has `preload: false` because it appears only in a handful of card titles — eagerly preloading every weight blocks the critical font request for DM Sans.

### Cursor & input

- `MouseFollower` ([`components/animations/MouseFollower.tsx`](components/animations/MouseFollower.tsx)) uses Framer Motion springs for the outer ring and an inner dot at different stiffness, blended with `mix-blend-difference`.
- It detects coarse pointers via `matchMedia('(pointer: coarse)')` in a `useEffect` (no SSR mismatches) and short-circuits the whole component on touch devices.
- Hover-state tracking uses **document-level event delegation** (`mouseover` / `mouseout` with `e.target.closest(...)`) rather than per-element listeners, so links and buttons added later in the scroll lifecycle (modals, spotlight results, project cards) get the hover treatment automatically without re-scanning the DOM.
- The `mousemove` listener is registered with `{ passive: true }`.

### Mailto / external links

- The footer and the `⌘K` spotlight detect protocol URLs (`mailto:`, `tel:`, `sms:`) and render plain `<a>` without `target="_blank"`. The earlier behavior — `target="_blank"` on a `mailto:` — opens a blank tab that the OS then tries to redirect, which Safari and some Chromium builds drop silently.

### Security headers

`next.config.ts` sets:

- `X-Content-Type-Options: nosniff`
- `X-Frame-Options: SAMEORIGIN`
- `Referrer-Policy: strict-origin-when-cross-origin`
- `X-DNS-Prefetch-Control: on`
- `poweredByHeader: false`

### Reduced motion

`prefers-reduced-motion: reduce` is honored where motion is critical: `story-scroll.tsx` reads the media query and disables transforms, `scroll-tilted-grid.tsx` swaps to a static layout via Framer's `useReducedMotion`, and the starfield in the tilted grid CSS animation pauses.

---

## Build configuration highlights

```ts
// next.config.ts
reactStrictMode: true
poweredByHeader: false
compress: true
productionBrowserSourceMaps: false  // smaller deploy, no client maps
images: {
  formats: ['image/avif', 'image/webp'],
  minimumCacheTTL: 60 * 60 * 24 * 30,
  deviceSizes: [360, 640, 750, 828, 1080, 1200, 1440, 1920, 2560],
  imageSizes:  [16, 32, 48, 64, 96, 128, 256, 384, 512, 768],
}
experimental.optimizePackageImports: [
  'framer-motion', 'gsap', 'lucide-react',
  '@radix-ui/react-label', '@radix-ui/react-switch',
  '@react-three/drei', 'lenis',
]
```

---

## Deployment (Vercel)

The project is configured to deploy zero-config on Vercel:

1. Connect the GitHub repo (`Rohithpranov07/Portfolio-cinematic`) to a Vercel project.
2. Framework preset: **Next.js** (auto-detected).
3. Install command: `pnpm install` (auto).
4. Build command: `pnpm build` (auto).
5. Output: `.next/` (auto).
6. Set the `metadataBase` in `app/layout.tsx` to your final deploy URL for correct OG image resolution.

Static pages prerender at build time; `next/image` requests are served via Vercel's edge image optimizer.

---

## Conventions

- All scene components use a `"use client"` directive at the top.
- Server-only logic stays in `app/page.tsx` and `app/layout.tsx`.
- Animations register on `useLayoutEffect` (to avoid flicker) and clean up via `gsap.context()`.
- GSAP ScrollTriggers are created inside `gsap.context()` blocks so they're collected and disposed together on unmount.
- Class-name composition goes through [`lib/utils.ts`](lib/utils.ts) `cn()` (clsx + tailwind-merge).
- Path alias `@/*` resolves to the project root (see `tsconfig.json`).

---

## Known constraints

- The site is desktop-first by design — many scenes (the VS Code IDE, Spline 3D, the horizontal hero parallax) are authored at a 1440-wide canvas. They render on mobile but the design is not flowed for it.
- `metadataBase` in `app/layout.tsx` currently points at a placeholder Vercel URL; update before going to a custom domain so Open Graph image URLs resolve correctly.

---

## Credits

- Smooth scroll — [Lenis](https://github.com/darkroomengineering/lenis) by darkroom.engineering
- Animation engines — [GSAP](https://gsap.com/) and [Framer Motion](https://www.framer.com/motion/)
- 3D scene — [Spline](https://spline.design/)
- WebGL primitives — [ogl](https://github.com/oframe/ogl)
- Component primitives — [shadcn/ui](https://ui.shadcn.com/) on [Radix](https://www.radix-ui.com/)
- Aceternity, motion-primitives, and 21st.dev for several pattern references the scenes were authored against

Built with care by **Rohith Pranov** — [LinkedIn](https://www.linkedin.com/in/rohith-pranov/) · [GitHub](https://github.com/Rohithpranov07) · `rohithpranovv@gmail.com`
```

---

## tsconfig.json

**File Path**: `tsconfig.json` | **Lines**: 35

```json
{
  "compilerOptions": {
    "target": "ES2017",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "strict": true,
    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "moduleResolution": "bundler",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "react-jsx",
    "incremental": true,
    "plugins": [
      {
        "name": "next"
      }
    ],
    "paths": {
      "@/*": ["./*"]
    }
  },
  "include": [
    "next-env.d.ts",
    "**/*.ts",
    "**/*.tsx",
    ".next/types/**/*.ts",
    ".next/dev/types/**/*.ts",
    "**/*.mts"
  ],
  "exclude": ["node_modules"]
}
```

---

