<script>
	import logo from '$lib/assets/logo.png';
	import { base } from '$app/paths';
</script>

<svelte:head>
	<title>Privacy Policy - PDFImgExtractor</title>
	<meta
		name="description"
		content="Privacy Policy for PDFImgExtractor - Your data stays on your device, we collect nothing."
	/>
</svelte:head>

<header class="header">
	<nav class="container nav">
		<a href="{base}/" class="logo">
			<img src={logo} alt="PDFImgExtractor Logo" />
			<span>PDFImgExtractor</span>
		</a>
		<a href="{base}/" class="nav-link">Back to Home</a>
	</nav>
</header>

<main class="container">
	<div class="privacy-content">
		<h1>Privacy Policy</h1>
		<p class="last-updated">Last updated: January 2025</p>

		<section class="policy-section">
			<h2>No Data Collection</h2>
			<p>
				PDFImgExtractor is a fully local desktop application. We do not collect, store, or transmit
				any of your data. All file processing happens entirely on your computer. Your PDF files,
				extracted images, and usage data never leave your device.
			</p>
			<ul>
				<li>No telemetry or analytics</li>
				<li>No usage tracking</li>
				<li>No file uploads to any server</li>
				<li>No account registration required</li>
			</ul>
		</section>

		<section class="policy-section">
			<h2>No Data Sharing</h2>
			<p>
				Since we collect no data, we have nothing to share. We do not sell, rent, or distribute your
				information to third parties. Your privacy is absolute because your data never leaves your
				possession.
			</p>
		</section>

		<section class="policy-section">
			<h2>Legal Compliance</h2>
			<p>
				PDFImgExtractor operates in full compliance with applicable data protection regulations,
				including but not limited to:
			</p>
			<ul>
				<li><strong>GDPR</strong> (General Data Protection Regulation) - EU/UK</li>
				<li><strong>CCPA</strong> (California Consumer Privacy Act) - California, USA</li>
				<li><strong>PIPL</strong> (Personal Information Protection Law) - China</li>
			</ul>
			<p>
				Because no personal data is collected or processed, the application maintains full compliance
				without requiring additional consent mechanisms or data processing agreements.
			</p>
		</section>

		<section class="policy-section">
			<h2>Contact Information</h2>
			<p>
				If you have any questions, concerns, or suggestions about this privacy policy or our data
				practices, please contact us:
			</p>
			<div class="contact-box">
				<a href="mailto:pochonlee@gmail.com" class="email-link">
					<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
						<path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z" />
						<polyline points="22,6 12,13 2,6" />
					</svg>
					pochonlee@gmail.com
				</a>
			</div>
		</section>

		<section class="policy-section summary">
			<h2>Our Privacy Promise</h2>
			<p>
				<strong>PDFImgExtractor is built on the principle that your data belongs to you.</strong> We
				believe privacy shouldn't be a feature—it should be the foundation. By keeping all processing
				local, we ensure that your documents remain private, secure, and entirely under your control.
			</p>
		</section>
	</div>
</main>

<footer class="footer">
	<div class="container">
		<p class="footer-email">Contact: <a href="mailto:pochonlee@gmail.com">pochonlee@gmail.com</a></p>
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
		line-height: 1.7;
	}

	.container {
		max-width: 900px;
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
		text-decoration: none;
		color: var(--text-primary);
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

	/* Main Content */
	.privacy-content {
		padding: 3rem 0 4rem;
	}

	.privacy-content h1 {
		font-size: 2.5rem;
		font-weight: 800;
		margin-bottom: 0.5rem;
	}

	.last-updated {
		color: var(--text-secondary);
		font-size: 0.9rem;
		margin-bottom: 3rem;
	}

	.policy-section {
		margin-bottom: 3rem;
		padding: 2rem;
		background-color: var(--bg-card);
		border: 1px solid var(--border);
		border-radius: 16px;
	}

	.policy-section h2 {
		font-size: 1.5rem;
		font-weight: 700;
		margin-bottom: 1rem;
		color: var(--accent);
	}

	.policy-section p {
		color: var(--text-secondary);
		margin-bottom: 1rem;
		line-height: 1.8;
	}

	.policy-section ul {
		list-style: none;
		padding-left: 0;
		margin-top: 1rem;
	}

	.policy-section li {
		padding: 0.5rem 0 0.5rem 1.5rem;
		position: relative;
		color: var(--text-secondary);
	}

	.policy-section li::before {
		content: '✓';
		position: absolute;
		left: 0;
		color: var(--accent);
		font-weight: bold;
	}

	.summary {
		background: linear-gradient(135deg, var(--accent) 0%, var(--accent-hover) 100%);
		color: white;
		border: none;
	}

	.summary h2 {
		color: white;
	}

	.summary p {
		color: rgba(255, 255, 255, 0.9);
	}

	.contact-box {
		margin-top: 1rem;
	}

	.email-link {
		display: inline-flex;
		align-items: center;
		gap: 10px;
		padding: 14px 24px;
		background-color: var(--accent);
		color: white;
		text-decoration: none;
		border-radius: 12px;
		font-weight: 600;
		transition: all 0.2s;
	}

	.email-link:hover {
		background-color: var(--accent-hover);
		transform: translateY(-2px);
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

	/* Responsive */
	@media (max-width: 768px) {
		.privacy-content h1 {
			font-size: 2rem;
		}

		.policy-section {
			padding: 1.5rem;
		}

		.nav {
			flex-direction: column;
			gap: 1rem;
		}
	}
</style>
