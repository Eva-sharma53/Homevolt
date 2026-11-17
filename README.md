# HomeVolt ⚡

> Smart Home Energy Monitor dashboard application.

HomeVolt provides real-time power tracking, historical usage graphs, breakdown by appliance, bill forecasting, and personalized energy-saving insights.

## 🚀 Live Demo
- [Live Demo](https://eva-sharma53.github.io/Homevolt/) *(accessible once deployed)*

## ✨ Features
- **Real-time Monitoring**: Instant display of current electrical draw (Watts / kW).
- **Consumption Analytics**: Visual historical charts breaking down hourly, daily, and monthly usage.
- **Device Breakdown**: Detailed power usage categorization (HVAC, EV Charger, Water Heater, Kitchen, etc.).
- **Smart Alerts & Recommendations**: Tips and insights to optimize consumption during peak-rate periods.
- **Dark / Light Mode**: Automatically adapts to system color preference.
- **Zero Dependencies**: Lightweight, self-contained single-page application.

## 🛠️ Project Structure
```
Homevolt/
├── .github/
│   └── workflows/
│       └── deploy.yml    # Automated CI/CD pipeline for GitHub Pages
├── index.html            # Main application (HTML, CSS, JavaScript)
└── README.md             # Project documentation
```

## ⚙️ CI/CD Deployment
This repository is configured with GitHub Actions:
- On every push to `main`, `.github/workflows/deploy.yml` triggers.
- The build is validated and automatically published to GitHub Pages.

To enable GitHub Pages in your repo:
1. Go to your repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, choose **GitHub Actions**.

## 💻 Local Development
Simply open `index.html` in any web browser.
