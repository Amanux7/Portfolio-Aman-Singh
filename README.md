Aman Singh | Design-AI Portfolio System
Designing Intelligence, Not Interfaces.
This repository contains the source code for my professional portfolio. It is engineered to bridge the gap between high-fidelity design systems (Figma) and production-ready frontend architecture, with a specific focus on AI-driven user experience (UX) and WCAG 2.2 accessibility.

🛠 Tech Stack
Architecture: Vanilla HTML5, CSS3 (Custom Properties), and ES6+ JavaScript.

Typography: Inter (Interface) & JetBrains Mono (Technical/Data).

Design System: 8px Hard Grid system with 1:1 token mapping from Figma.

AI Integration: Vanilla JS "Context-Aware" Assistant with intent-based knowledge retrieval.

Performance: 0 dependencies, <100ms Largest Contentful Paint (LCP), 60fps interaction target.

🚀 Key Features
1. Figma ↔ CSS Token System
The design follows a strict tokenization strategy. Every CSS variable in :root is mapped to a Figma variable, ensuring that updates in the design tool can be exported and synced with zero visual regression.

2. "Ask Aman" AI Assistant
A built-in floating assistant that acts as a digital twin. It is programmed to handle:

Project Deep-Dives: Explaining the technical hurdles of the Amazon and YONO SBI case studies.

Skill Verification: Instantly retrieving relevant tech-stack proficiencies.

Lead Generation: Directing recruiters to contact channels or meeting booking links.

3. Progressive Disclosure Case Studies
Unlike traditional long-form portfolios, this system uses a "Card-to-Panel" architecture. It prioritizes high-level metrics (Impact) for the initial recruiter scan, while providing technical deep-dives (Architecture) for engineering leads.

💻 Local Development
Clone the repository:

Bash
git clone https://github.com/yourusername/aman-singh-portfolio.git
Open the directory:

Bash
cd aman-singh-portfolio
Run with Live Server:
Open index.html in your browser or use the VS Code "Live Server" extension for hot-reloading.

🌍 Deployment Guide
Option A: Vercel (Recommended)
Push this code to a GitHub repository.

Import the project into Vercel.

Vercel will automatically detect the static HTML and deploy it to a global CDN.

Option B: GitHub Pages
Go to your repository Settings > Pages.

Under Build and deployment, set the source to Deploy from a branch.

Select the main branch and / (root) folder.

Hit Save. Your site will be live at https://yourusername.github.io/repo-name/.

📈 Performance & Accessibility (WCAG 2.2)
This portfolio is optimized for accessibility-first design:

Contrast: All text meets or exceeds WCAG AA standards.

Navigation: Full keyboard accessibility and focus state management.

SEO: Semantic HTML tags for optimal indexing by recruiter search tools and search engines.

📬 Contact & Links
Founder: UXterity

Email: aman@uxterity.com

Role: UX Designer | AI Researcher | Builder
