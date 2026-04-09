homestay-1-hgh
/README (1).md
kl2400032185
kl2400032185
Add files via upload
c2ce104
 · 
4 minutes ago

Preview

Code

Blame
138 lines (103 loc) · 3.79 KB
HomestayHub
A full-featured homestay and tourism platform connecting travelers with local hosts, guides, and authentic experiences.

React Vite Vercel

Features
Browse & Book Homestays — Search, filter, and explore verified homestay listings
Tourist Attractions — Discover local attractions organized by category
Local Guides — Find and connect with certified local guides by location
Multi-Role Dashboards — Separate portals for Tourists, Hosts, Guides, and Admins
Booking Management — End-to-end booking lifecycle tracking
Reviews & Ratings — Authentic guest reviews and rating system
Platform Analytics — Real-time charts and performance metrics
Admin Control Panel — Full platform management and oversight
Getting Started
Prerequisites
Node.js v18 or higher
npm v9 or higher
Installation
git clone https://github.com/kl2400032185/homestay-1-hgh.git
cd homestay-1-hgh
npm install
npm run dev
Open http://localhost:5173 in your browser.

Build for Production
npm run build
npm run preview
Project Structure
homestay-1-hgh/
├── index.html
├── vite.config.js
├── vercel.json
├── package.json
└── src/
    ├── App.jsx
    ├── main.jsx
    ├── data/
    │   └── mockData.js
    └── components/
        ├── Sidebar.jsx
        └── pages/
            ├── HomePage.jsx
            ├── HomestaysPage.jsx
            ├── AttractionsPage.jsx
            ├── GuidesPage.jsx
            ├── AdminPage.jsx
            ├── HostPage.jsx
            ├── TouristPage.jsx
            ├── GuidePage.jsx
            ├── AnalyticsPage.jsx
            ├── BookingsPage.jsx
            └── ReviewsPage.jsx
Pages & Portals
Page	Description
Home	Hero section, featured homestays, highlights
Homestays	Full listing browser with search and filters
Attractions	Tourist spots grouped by category
Guides	Local guide profiles filterable by location
Tourist Portal	Bookings, wishlist, reviews, profile, messages
Host Portal	Listings, reservations, earnings, calendar
Guide Portal	Tours, schedule, clients, reviews, earnings
Admin Portal	Users, listings, reports, platform settings
Analytics	Charts, KPIs, and platform performance data
Bookings	Full booking management with status tracking
Reviews	Ratings overview and moderation tools
Tech Stack
Layer	Technology
Framework	React 18
Build Tool	Vite
Routing	React Router
Styling	CSS / Tailwind
Charts	Recharts / Chart.js
Deployment	Vercel
Data	Mock Data (JSON)
Deployment
Configured for seamless deployment on Vercel. The vercel.json handles SPA routing so all page refreshes resolve correctly.

Push to main and Vercel auto-deploys every commit.

Contributing
Fork the repository
Create your branch: git checkout -b feature/your-feature
Commit your changes: git commit -m 'Add your feature'
Push: git push origin feature/your-feature
Open a Pull Request
License
This project is open source and available under the MIT License.

