# Public Stats Repository

This project serves as a central, publicly accessible repository for statistics across various projects of mine. These statistics are intended to be fetched and displayed on landing pages, dashboards, and other external locations.

## 📊 Project Statistics

The source of truth for these statistics is [index.json](./index.json).

| Product Name | Description | Users | Rating | URL |
| :--- | :--- | :--- | :--- | :--- |
| **Zen Virtual Piano** | Virtual piano with realistic sound and touch response | 600+ | ⭐ 5/5 | [Link](https://zenpiano.art) |
| **Zen Analytics Pixel Tracker** | Analytics tracking solution | 600+ | ⭐ 5/5 | [Link](https://zenanalytics.online) |
| **Crypto Pulse** | Real-time crypto monitoring | 20+ | ⭐ 5/5 | [Link](https://get-crypto-pulse.web.app) |

## 🚀 How to Use

You can fetch the statistics directly from the GitHub repository using the Raw URL.

### Fetch Example (JavaScript)

```javascript
async function fetchStats() {
  const response = await fetch('https://raw.githubusercontent.com/[USER]/public-stats/main/index.json');
  const data = await response.json();
  console.log(data.product['zen-virtual-piano'].userCount);
}
```

## 🛠️ Project Structure

- `index.json`: The main data store containing all project stats.
- `README.md`: This documentation file.
