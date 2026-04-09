# HomestayHub

> A full-featured homestay and tourism platform connecting travelers with local hosts, guides, and authentic experiences.

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com/)

---

## Features

- **Browse & Book Homestays** — Search, filter, and explore verified homestay listings
- **Tourist Attractions** — Discover local attractions organized by category
- **Local Guides** — Find and connect with certified local guides by location
- **Multi-Role Dashboards** — Separate portals for Tourists, Hosts, Guides, and Admins
- **Booking Management** — End-to-end booking lifecycle tracking
- **Reviews & Ratings** — Authentic guest reviews and rating system
- **Platform Analytics** — Real-time charts and performance metrics
- **Admin Control Panel** — Full platform management and oversight

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- npm v9 or higher

### Installation

```bash
git clone https://github.com/kl2400032185/homestay-1-hgh.git
cd homestay-1-hgh
npm install
npm run dev
```

Open http://localhost:5173 in your browser.

### Build for Production

```bash
npm run build
npm run preview
```

---

## Project Structure

```
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
```

---

## Pages & Portals

| Page | Description |
|------|-------------|
| **Home** | Hero section, featured homestays, highlights |
| **Homestays** | Full listing browser with search and filters |
| **Attractions** | Tourist spots grouped by category |
| **Guides** | Local guide profiles filterable by location |
| **Tourist Portal** | Bookings, wishlist, reviews, profile, messages |
| **Host Portal** | Listings, reservations, earnings, calendar |
| **Guide Portal** | Tours, schedule, clients, reviews, earnings |
| **Admin Portal** | Users, listings, reports, platform settings |
| **Analytics** | Charts, KPIs, and platform performance data |
| **Bookings** | Full booking management with status tracking |
| **Reviews** | Ratings overview and moderation tools |

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Framework | React 18 |
| Build Tool | Vite |
| Routing | React Router |
| Styling | CSS / Tailwind |
| Charts | Recharts / Chart.js |
| Deployment | Vercel |
| Data | Mock Data (JSON) |

---

## Deployment

Configured for seamless deployment on **Vercel**. The `vercel.json` handles SPA routing so all page refreshes resolve correctly.

Push to `main` and Vercel auto-deploys every commit.

---

## Contributing

1. Fork the repository
2. Create your branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push: `git push origin feature/your-feature`
5. Open a Pull Request

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with love by <a href="https://github.com/kl2400032185">kl2400032185</a></p>
