# AXASP Broker Exchange

GitHub-ready single-page broker client dashboard.

## Run

Open `index.html` in a modern browser or serve the folder with a static web server. The Capacitor web copy is in `www/index.html`.

## Dashboard

After login, users land on an AXASP-style mobile-first dashboard with quick actions for Deposit, Withdraw, Help, Team, Activity, Invite Friends, Agent Program and Messages, plus account balances, withdrawal history and live quote shortcuts.

## Important

The client UI preserves the project's existing Firebase authentication/Firestore integration. Do not treat browser-side state as a secure source of truth for real-money balances, KYC, withdrawals or admin permissions; those operations should be enforced server-side with appropriate security rules.
