# AXASP Broker Exchange

Dashboard-first AXASP broker interface based on the supplied reference design.

## Dashboard changes
- Removed normal user navigation functions from the left sidebar.
- Moved all client functions into the logged-in dashboard.
- Added Portfolio, Trading Charts, Deposit, Withdraw, Transactions, Notifications, Referral, Spin & Win, Profile & KYC, Settings, Support and Sign Out actions.
- Added an admin-only dashboard tools area for administrator accounts.
- Updated the logged-in workspace to AXASP's light mint/teal visual system.
- Added a larger Live Quotes panel plus a moving market ticker.
- Preserved existing authentication, Firebase/Firestore integration, KYC, transactions and admin workflows.

## Files
- `index.html` - main web app
- `www/index.html` - Capacitor web build
- `package.json` - project metadata/dependencies
- `capacitor.config.json` - Capacitor configuration

## GitHub Pages
Use `index.html` at the repository root for GitHub Pages.
