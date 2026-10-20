# IOT SIM M2M Demo

Responsive IOT SIM M2M front-end demo inspired by the provided M2M/GPS portal reference. Includes an elevated orange-and-green UI with tactile 3D-style icons.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, and `app.js` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then Save.
6. After deployment, open the GitHub Pages URL shown in Settings → Pages.

## Demo login
- Partner/User: username `partner`, password `demo123`
- Administrator: username `admin`, password `admin123`

You can also use the **Create partner account** form.

## Included front-end modules
- Role-select login and registration
- Separate user and administrator navigation (front-end demo gating)
- Overview dashboard and responsive charts
- SIM inventory, activation/validity status, search and filters
- Customer directory
- Demo orders and checkout workflow
- Safe-custody records and duration selection
- Service tickets and status updates
- Reports and CSV exports
- Local notifications
- Browser localStorage persistence

## Important limitations
This is a static HTML/CSS/JavaScript prototype. It does not connect to a telecom provider, GPS tracking server, real payment gateway, SMS/email service, or secure backend. Accounts and demo records are stored in the current browser's localStorage. The role checks are not production security. Before real deployment, add server-side authentication, authorization, database, audit logs, validation, and provider APIs.

The original app's features and wording are the property of their respective owners. This is an independently styled concept demo, not an official clone or affiliated product.
