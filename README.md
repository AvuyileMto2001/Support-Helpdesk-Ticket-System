# TCM Enterprise IT Support — Service Desk

A responsive IT service desk dashboard prototype built with HTML, CSS and vanilla JavaScript. JavaScript functionality is embedded directly inside `index.html`, so there is no separate JavaScript file or build step.

## Features
- Dashboard with ticket KPIs, recent queue and SLA health overview
- Create support tickets with client details, priority, category, description and agent assignment
- Ticket search and filters for status, priority and category
- Ticket detail page with editable status, priority and assignment
- Comment/activity updates
- SLA countdowns based on demo targets (Urgent 2h, High 4h, Medium 8h, Low 24h)
- Client directory derived from ticket records
- Agent workload overview
- Reports with priority/status breakdown and CSV export
- Knowledge base guides for common IT issues
- Local browser storage persistence and reset demo data option
- Responsive layout for desktop and mobile

## Run locally
Open `index.html` in a modern browser. No install or server is required.

## Deploy using GitHub Pages
1. Create a GitHub repository (or open your existing repository for this project).
2. Upload **`index.html`**, **`style.css`**, and **`README.md`** to the repository root (top-level folder).
3. Open the repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **`main`** and folder **`/(root)`**, then click **Save**.
6. Wait for the Pages deployment to finish. Your site URL will be shown in the Pages settings.

## Important prototype limitations
This is a front-end portfolio demo, not a production ticketing system. Ticket records are stored in local storage in the browser that is being used. They do not sync across users or devices. There is no real authentication, server/database, email delivery, company integration, or access control. Do not enter confidential company or customer information. The SLA values are illustrative.

## Technologies
HTML5 · CSS3 · JavaScript (embedded) · Browser Local Storage
