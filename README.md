# Portfolio redesign v2 — compact page switching + dark mode

Replacement for `index.html` in the GitHub Pages portfolio:
https://philip1314.github.io/portfolio/

## What's included
- Compact page-switching navigation: Home, Case Studies, Web Apps, AI Evaluation, Background
- Light/dark theme switch; theme preference is saved in the browser when local storage is available
- Restored live app links:
  - Margin Calculator: https://philip1314.github.io/Margin-Calculator/
  - Trading Journal: https://philip1314.github.io/myTradingJournal/
  - Personal Finance Tracker: https://philip1314.github.io/finances/
- Responsive mobile navigation and page layouts
- Reduced-motion support and keyboard focus styling
- Credentials restored from the published portfolio text
- Sample case studies are explicitly labeled as demonstrations / scenarios to avoid implying unverified production results

## Install
1. Unzip the package.
2. Keep your existing `profile.jpg` beside `index.html`.
3. Preview the HTML locally.
4. Verify your email, LinkedIn URL, credentials, skill descriptions, and all three app links.
5. Replace the `index.html` in the `Philip1314/portfolio` GitHub repository and commit.
6. Test the live site on desktop and mobile after GitHub Pages rebuilds.

## Notes
- This is a single HTML file that behaves like a small multi-page site. It does not require a framework or build step.
- The pages switch without a full reload; URLs use hashes such as `#apps` so individual views can be linked.
- Dark mode is implemented with CSS variables and a theme toggle. The browser remembers the preference when local storage is available.
- This package does not deploy changes to GitHub automatically.
