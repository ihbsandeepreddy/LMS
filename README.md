# LoanOps Cloud

LoanOps Cloud is a no-build loans management platform prototype. It runs as a single static `index.html` file and does not require Node.js, npm, Git, Vite, or admin rights on the laptop.

## Product Surface

- Origination pipeline with KYC, eligibility, and policy exception visibility
- Underwriting cockpit for credit memos, approval queues, and collateral review
- Servicing control room for repayments, mandates, schedules, and reconciliations
- Risk and collections view with SMA, portfolio-at-risk, provisioning, and audit trail signals
- Full-screen carousel-inspired hero interface using CDN-hosted React, Tailwind CSS, and lucide icons
- Borrower and loan intake form
- EMI calculator
- Live loan pipeline table
- Organization, upload, column mapping, configuration, and role workflow cards
- Analytics selection for eligibility, EMI, IRACP, ECL, collections, and audit trail
- Workpaper text file generation from the selected loan configuration

## Run Locally

Open `index.html` directly in a browser.

## Host on GitHub Pages Without Installing Software

1. Create a new GitHub repository from the GitHub website.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the repository root.
3. Go to repository `Settings` > `Pages`.
4. Set source to `Deploy from a branch`.
5. Select branch `main` and folder `/root`.
6. Save. GitHub will show the public Pages URL after deployment.

The page uses public CDNs, so the hosted site needs internet access to load React, Tailwind CSS, fonts, and lucide icons.

## Functional Coverage

The app now covers the requested loan-management journey:

- Sign-in shell
- Organization setup
- Company/product setup
- Data upload and column mapping
- Configuration
- Analytics selection
- Execution
- Workpaper generation
- User management
- GitHub Pages hosting
