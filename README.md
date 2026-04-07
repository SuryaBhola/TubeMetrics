# TubeMetrics
**TubeMetrics** is a single-page YouTube analytics dashboard that fetches real-time data for any YouTube video or channel using the **YouTube Data API v3**. Enter a YouTube URL and instantly get deep performance metrics, revenue estimates, engagement analysis, and interactive visualisations — all in a sleek dark/light UI.

This project demonstrates real-world API integration, data transformation, and frontend data visualisation skills.

---

## ✨ Features

### 🎬 Video Analysis
- **Core Stats** — Views, Likes, Comments, video duration and publish date
- **Engagement Rate** — Calculated as `(Likes + Comments) / Views × 100`
- **Revenue Estimates** — Lifetime earnings in USD and INR based on category CPM and YouTube's 55% creator share
- **Authenticity Score** — Flags verified channels
- **Thumbnail Downloader** — Download video thumbnail in one click

### 📺 Channel Analysis
- **Channel Overview** — Total subscribers, total views, total uploads, channel age
- **Calculated Metrics** — Average views/month, average views/year, avg likes/video, avg comments/video
- **Revenue Estimates** — Lifetime and annual earnings (USD / INR) using category-specific CPM
- **Last 20 Videos Charts:**
  - Views per video (bar chart)
  - Likes per video (line chart)
  - Comments per video (bar chart)
  - Views vs channel average benchmark line

### 🎨 UI/UX
- Dark / Light mode toggle
- Custom animated cursor
- Animated hero section with grid background
- Fully responsive layout
- Light/Dark themed Chart.js charts

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 / CSS3 | Structure and styling |
| Vanilla JavaScript (ES6+) | Logic, API calls, DOM manipulation |
| YouTube Data API v3 | Fetching video and channel data |
| Chart.js 4.4 | Interactive bar and line charts |
| Google Fonts | Bebas Neue, DM Sans, Rajdhani |

---

## 📸 Screenshots

https://github.com/SuryaBhola/TubeMetrics/blob/main/Screenshot%202026-04-08%20005157.png

## 📂 Project Structure

```
tubemetrics/
│
├── tubemetrics.html       # Main single-page application
└── README.md              # Project documentation
```

---

## ⚙️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/tubemetrics.git
   ```

2. Get a free **YouTube Data API v3** key from [Google Cloud Console](https://console.cloud.google.com/)

3. Open `tubemetrics.html` and replace the API key variable with your own key

4. Open the file in any browser — no server or installation needed

---

## 📈 Key Metrics & Calculations

| Metric | Formula |
|---|---|
| Engagement Rate | `(Likes + Comments) / Views × 100` |
| Avg Views/Month | `Total Views / Channel Age in Months` |
| Revenue Estimate | `(Total Views / 1000) × Category CPM × 0.55` |
| Authenticity Score | Based on subscriber-to-view ratio benchmarks |

---

## 💡 What I Learned

- Integrating and parsing responses from the **YouTube Data API v3**
- Handling asynchronous JavaScript with `async/await` and `fetch()`
- Transforming raw API data into meaningful KPIs and business metrics
- Building interactive charts with **Chart.js**
- Designing a responsive, themeable UI with pure CSS variables

---

## 🔮 Future Improvements

- [ ] Add competitor channel comparison feature
- [ ] Export analytics report as PDF
- [ ] Add historical trend tracking with local storage
- [ ] Support for YouTube Shorts specific metrics

---

## 👤 Author

**Your Name**
- LinkedIn: [linkedin.com/in/suryabhola-da](https://linkedin.com/in/suryabhola-da)
- GitHub: [github.com/SuryaBhola](https://github.com/SuryaBhola)

---

## ⚠️ Disclaimer

Revenue estimates are approximations based on industry-average CPM rates and are not official YouTube earnings data. Actual earnings vary based on geography, advertiser demand, and content type.

---

⭐ If you found this project helpful, please give it a star!
