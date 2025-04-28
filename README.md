# Augur Frontend Dashboard

A single-page application (SPA) built with React and TailwindCSS to display key distributor metrics for the Augur system.  
This frontend currently uses mock data for demonstration purposes and will later integrate with a backend.

## 🚀 Live Demo
[View the Augur Dashboard Live](https://augur-frontend.vercel.app)

## ✨ Features
- Distributor metrics including:
  - Name
  - Quantity of goods shipped last month
  - Forecasted quantity for next month
  - Year-to-date average monthly shipments
  - Region, trend, and reliability score
- Modern, responsive design
- Built with best practices using Vite, React 18, and TailwindCSS

## 🛠️ Built With
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [Lucide React](https://lucide.dev/) (icons)

## 📦 Local Setup

```bash
git clone https://github.com/YOUR-USERNAME/augur-frontend.git
cd augur-frontend
npm install
npm run dev


const distributors = [
  {
    id: 1,
    name: "Distributor One",
    shippedLastMonth: 1200,
    forecastedNextMonth: 1300,
    ytdAverage: 1150,
    region: "North America",
    trend: "up",
    reliabilityScore: 95
  },
  {
    id: 2,
    name: "Distributor Two",
    shippedLastMonth: 950,
    forecastedNextMonth: 1100,
    ytdAverage: 980,
    region: "Europe",
    trend: "down",
    reliabilityScore: 88
  }
];
export default distributors;
