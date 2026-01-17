<script>
	import { base } from '$app/paths';
	import logo from '$lib/assets/logo.png';
	import screen1 from '$lib/assets/screen_001.png';
	import screen2 from '$lib/assets/screen_002.png';
	import screen3 from '$lib/assets/screen_003.png';
	import screen4 from '$lib/assets/screen_004.png';
	import screen5 from '$lib/assets/screen_005.png';
	import screen6 from '$lib/assets/screen_006.png';
</script>

<svelte:head>
	<title>PDFImageExtractor - Extract Images from PDFs Locally</title>
	<meta
		name="description"
		content="PDFImageExtractor - A lightweight, native desktop application to extract images from PDF files locally and privately."
	/>
</svelte:head>

<header class="header">
	<nav class="container nav">
		<div class="logo">
			<img src={logo} alt="PDFImageExtractor Logo" />
			<span>PDFImageExtractor</span>
		</div>
		<a href="#features" class="nav-link">Features</a>
	</nav>
</header>

<main>
	<section class="hero">
		<div class="container">
			<h1>
				Extract Images from PDFs<br />
				<span class="highlight">Locally & Privately</span>
			</h1>
			<p class="hero-subtitle">
				A lightweight desktop application that keeps your documents on your computer. No uploads, no
				cloud processing—your files remain entirely yours.
			</p>
			<div class="cta-buttons">
				<a href="#screenshots" class="btn btn-primary">See How It Works</a>
				<a href="#features" class="btn btn-secondary">Learn More</a>
				<a href="mailto:pochonlee@gmail.com" class="btn btn-secondary">Contact Us</a>
			</div>
		</div>
	</section>

	<section id="features" class="features">
		<div class="container">
			<h2 class="section-title">Why PDFImageExtractor?</h2>
			<div class="features-grid">
				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" />
						</svg>
					</div>
					<h3>Local & Private</h3>
					<p>
						All data stays on your computer. No uploads, no cloud processing—your documents remain
						entirely yours.
					</p>
				</div>

				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<rect x="3" y="3" width="18" height="18" rx="2" ry="2" />
							<line x1="9" y1="3" x2="9" y2="21" />
						</svg>
					</div>
					<h3>Native Desktop App</h3>
					<p>Built for performance and smooth integration with your operating system.</p>
				</div>

				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<circle cx="12" cy="12" r="10" />
							<line x1="12" y1="8" x2="12" y2="12" />
							<line x1="12" y1="16" x2="12.01" y2="16" />
						</svg>
					</div>
					<h3>Small & Efficient</h3>
					<p>Minimal footprint, fast operation, and no unnecessary bloat.</p>
				</div>

				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<path
								d="M14.7 6.3a1 1 0 0 0 0 1.4l1.6 1.6a1 1 0 0 0 1.4 0l3.77-3.77a6 6 0 0 1-7.94 7.94l-6.91 6.91a2.12 2.12 0 0 1-3-3l6.91-6.91a6 6 0 0 1 7.94-7.94l-3.76 3.76z"
							/>
						</svg>
					</div>
					<h3>Simple & Intuitive</h3>
					<p>Clean interface that lets you get the job done in just a few clicks.</p>
				</div>

				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<circle cx="12" cy="12" r="5" />
							<line x1="12" y1="1" x2="12" y2="3" />
							<line x1="12" y1="21" x2="12" y2="23" />
							<path d="M4.22 4.22l1.42 1.42" />
							<path d="M18.36 18.36l1.42 1.42" />
							<line x1="1" y1="12" x2="3" y2="12" />
							<line x1="21" y1="12" x2="23" y2="12" />
							<path d="M4.22 19.78l1.42-1.42" />
							<path d="M18.36 5.64l1.42-1.42" />
						</svg>
					</div>
					<h3>Theme Adaptation</h3>
					<p>Automatically adapts to your system's light or dark theme preference.</p>
				</div>

				<div class="feature-card">
					<div class="feature-icon">
						<svg width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
							<circle cx="12" cy="12" r="10" />
							<line x1="2" y1="12" x2="22" y2="12" />
							<path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z" />
						</svg>
					</div>
					<h3>Multi-language Support</h3>
					<p>Available in multiple languages to serve users around the world.</p>
				</div>
			</div>
		</div>
	</section>

	<section id="screenshots" class="screenshots">
		<div class="container">
			<h2 class="section-title">See It In Action</h2>
			<p class="section-subtitle">Clean design, simple operation, powerful features</p>

			<div class="screenshot-grid">
				<div class="screenshot-card">
					<img src={screen1} alt="Clean UI Design" />
					<div class="screenshot-caption">Clean UI Design</div>
				</div>

				<div class="screenshot-card">
					<img src={screen2} alt="Drag and Drop PDF Files" />
					<div class="screenshot-caption">Simple Operation - Drag & Drop PDF Files</div>
				</div>

				<div class="screenshot-card">
					<img src={screen3} alt="Auto Scan All Images" />
					<div class="screenshot-caption">Auto Scan All Images in PDF</div>
				</div>

				<div class="screenshot-card">
					<img src={screen4} alt="Filter by Image Size" />
					<div class="screenshot-caption">Filter Images by Size</div>
				</div>

				<div class="screenshot-card">
					<img src={screen5} alt="Theme Adaptation" />
					<div class="screenshot-caption">Automatic Theme Adaptation</div>
				</div>

				<div class="screenshot-card">
					<img src={screen6} alt="Multi-language Support" />
					<div class="screenshot-caption">Multi-language Support</div>
				</div>
			</div>
		</div>
	</section>

	<section class="use-cases">
		<div class="container">
			<h2 class="section-title">Perfect For</h2>
			<div class="use-cases-list">
				<span class="tag">Designers</span>
				<span class="tag">Researchers</span>
				<span class="tag">Archivists</span>
				<span class="tag">Content Creators</span>
				<span class="tag">Anyone Who Values Privacy</span>
			</div>
		</div>
	</section>

	<section class="cta-section">
		<div class="container">
			<h2>Download PDFImageExtractor</h2>
			<p class="cta-subtitle">Keep it simple. Keep it local.</p>
			<p class="coming-soon">Coming Soon...</p>
		</div>
	</section>
</main>

<footer class="footer">
	<div class="container">
		<p class="footer-email">Contact: <a href="mailto:pochonlee@gmail.com">pochonlee#gmail.com</a></p>
		<p class="footer-links">
			<a href="{base}/privacy">Privacy Policy</a>
		</p>
		<p>&copy; 2025 scrapmind.com All rights reserved.</p>
	</div>
</footer>

<style>
	:global(:root) {
		--bg-primary: #ffffff;
		--bg-secondary: #f8fafc;
		--bg-card: #ffffff;
		--text-primary: #1e293b;
		--text-secondary: #64748b;
		--accent: #6366f1;
		--accent-hover: #4f46e5;
		--border: #e2e8f0;
		--shadow: rgba(0, 0, 0, 0.1);
	}

	@media (prefers-color-scheme: dark) {
		:global(:root) {
			--bg-primary: #0f172a;
			--bg-secondary: #1e293b;
			--bg-card: #1e293b;
			--text-primary: #f1f5f9;
			--text-secondary: #94a3b8;
			--accent: #818cf8;
			--accent-hover: #a5b4fc;
			--border: #334155;
			--shadow: rgba(0, 0, 0, 0.3);
		}
	}

	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}

	:global(body) {
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
		background-color: var(--bg-primary);
		color: var(--text-primary);
		line-height: 1.6;
	}

	.container {
		max-width: 1200px;
		margin: 0 auto;
		padding: 0 20px;
	}

	/* Header */
	.header {
		background-color: var(--bg-primary);
		border-bottom: 1px solid var(--border);
		position: sticky;
		top: 0;
		z-index: 100;
	}

	.nav {
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 1rem 0;
	}

	.logo {
		display: flex;
		align-items: center;
		gap: 12px;
		font-weight: 700;
		font-size: 1.25rem;
	}

	.logo img {
		width: 40px;
		height: 40px;
	}

	.nav-link {
		color: var(--text-secondary);
		text-decoration: none;
		font-weight: 500;
		transition: color 0.2s;
	}

	.nav-link:hover {
		color: var(--accent);
	}

	/* Hero Section */
	.hero {
		padding: 100px 0 80px;
		text-align: center;
		background: linear-gradient(180deg, var(--bg-primary) 0%, var(--bg-secondary) 100%);
	}

	.hero h1 {
		font-size: clamp(2.5rem, 5vw, 4rem);
		font-weight: 800;
		line-height: 1.1;
		margin-bottom: 1.5rem;
	}

	.highlight {
		color: var(--accent);
	}

	.hero-subtitle {
		font-size: 1.25rem;
		color: var(--text-secondary);
		max-width: 700px;
		margin: 0 auto 2.5rem;
	}

	.cta-buttons {
		display: flex;
		gap: 1rem;
		justify-content: center;
		flex-wrap: wrap;
	}

	.btn {
		padding: 14px 28px;
		border-radius: 12px;
		font-weight: 600;
		text-decoration: none;
		transition: all 0.2s;
		display: inline-block;
	}

	.btn-primary {
		background-color: var(--accent);
		color: white;
	}

	.btn-primary:hover {
		background-color: var(--accent-hover);
		transform: translateY(-2px);
	}

	.btn-secondary {
		background-color: var(--bg-card);
		color: var(--text-primary);
		border: 2px solid var(--border);
	}

	.btn-secondary:hover {
		border-color: var(--accent);
		color: var(--accent);
	}

	/* Features Section */
	.features {
		padding: 80px 0;
		background-color: var(--bg-primary);
	}

	.section-title {
		text-align: center;
		font-size: 2.5rem;
		font-weight: 700;
		margin-bottom: 3rem;
	}

	.section-subtitle {
		text-align: center;
		color: var(--text-secondary);
		font-size: 1.125rem;
		margin-bottom: 3rem;
	}

	.features-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
		gap: 2rem;
	}

	.feature-card {
		background-color: var(--bg-card);
		border: 1px solid var(--border);
		border-radius: 16px;
		padding: 2rem;
		transition: all 0.3s;
	}

	.feature-card:hover {
		transform: translateY(-4px);
		box-shadow: 0 20px 40px var(--shadow);
	}

	.feature-icon {
		color: var(--accent);
		margin-bottom: 1rem;
	}

	.feature-card h3 {
		font-size: 1.25rem;
		margin-bottom: 0.75rem;
	}

	.feature-card p {
		color: var(--text-secondary);
		line-height: 1.7;
	}

	/* Screenshots Section */
	.screenshots {
		padding: 80px 0;
		background-color: var(--bg-secondary);
	}

	.screenshot-grid {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
		gap: 2rem;
	}

	.screenshot-card {
		background-color: var(--bg-card);
		border-radius: 16px;
		overflow: hidden;
		box-shadow: 0 10px 30px var(--shadow);
		transition: transform 0.3s;
	}

	.screenshot-card:hover {
		transform: scale(1.02);
	}

	.screenshot-card img {
		width: 100%;
		height: auto;
		display: block;
	}

	.screenshot-caption {
		padding: 1rem;
		text-align: center;
		font-weight: 500;
		color: var(--text-secondary);
	}

	/* Use Cases Section */
	.use-cases {
		padding: 80px 0;
		background-color: var(--bg-primary);
		text-align: center;
	}

	.use-cases-list {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		gap: 1rem;
		margin-top: 2rem;
	}

	.tag {
		background-color: var(--bg-secondary);
		color: var(--text-primary);
		padding: 12px 24px;
		border-radius: 50px;
		font-weight: 500;
		border: 1px solid var(--border);
	}

	/* CTA Section */
	.cta-section {
		padding: 100px 0;
		background: linear-gradient(135deg, var(--accent) 0%, var(--accent-hover) 100%);
		text-align: center;
		color: white;
	}

	.cta-section h2 {
		font-size: 2.5rem;
		margin-bottom: 1rem;
	}

	.cta-subtitle {
		font-size: 1.25rem;
		opacity: 0.9;
		margin-bottom: 2rem;
	}

	.coming-soon {
		font-size: 1.5rem;
		font-weight: 600;
		opacity: 0.8;
	}

	/* Footer */
	.footer {
		padding: 2rem 0;
		background-color: var(--bg-secondary);
		border-top: 1px solid var(--border);
		text-align: center;
		color: var(--text-secondary);
	}

	.footer-email {
		margin-bottom: 0.5rem;
	}

	.footer-email a {
		color: var(--accent);
		text-decoration: none;
	}

	.footer-email a:hover {
		text-decoration: underline;
	}

	.footer-links {
		margin-bottom: 0.5rem;
	}

	.footer-links a {
		color: var(--accent);
		text-decoration: none;
		margin: 0 0.5rem;
	}

	.footer-links a:hover {
		text-decoration: underline;
	}

	/* Responsive */
	@media (max-width: 768px) {
		.hero h1 {
			font-size: 2rem;
		}

		.hero-subtitle {
			font-size: 1rem;
		}

		.section-title {
			font-size: 2rem;
		}

		.cta-section h2 {
			font-size: 2rem;
		}

		.nav {
			flex-direction: column;
			gap: 1rem;
		}
	}
</style>
