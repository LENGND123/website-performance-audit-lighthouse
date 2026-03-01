# 🚀 Website Performance Audit (Google Lighthouse)

A detailed Lighthouse performance audit and optimization strategy for a live production website.

---

## 📌 Project Overview

This project analyzes the performance of a live school website using **Google Lighthouse (Mobile Simulation)** in Chrome Incognito mode.

The goal was to:
- Evaluate real-world mobile performance
- Identify Core Web Vitals issues
- Suggest practical optimization strategies
- Improve overall user experience and SEO readiness

---

## 🛠 Tools & Testing Environment

- Tool: Google Lighthouse
- Mode: Mobile Simulation
- Browser: Google Chrome (Incognito)
- Network: Simulated Slow 4G
- Lighthouse Version: 13+

---

## 📊 Performance Summary

| Metric | Observed | Ideal |
|--------|----------|--------|
| Performance Score | 58/100 | 90+ |
| First Contentful Paint (FCP) | 3.0s | < 1.8s |
| Largest Contentful Paint (LCP) | 11.9s | < 2.5s |
| Total Blocking Time (TBT) | 280ms | < 200ms |
| Cumulative Layout Shift (CLS) | 0.03 | < 0.1 |
| Speed Index | 6.5s | < 3.4s |

---

## 🚨 Key Issues Identified

- High LCP (11.9s)
- Render-blocking CSS & JavaScript
- Font display delays
- Unoptimized images
- Excess JavaScript execution time
- Main-thread blocking tasks

---

## ⚙ Optimization Recommendations

- Convert hero images to WebP
- Implement lazy loading
- Add `font-display: swap`
- Defer non-critical JavaScript
- Remove unused JS & CSS
- Implement CDN & Gzip/Brotli compression
- Configure proper cache headers

---

## 📈 Expected Improvements

If implemented:

- Performance score can improve from **58 → 85+**
- LCP can reduce from **11.9s → < 3s**
- Overall load time can improve by **30–50%**

---

## 📄 Full Report

The complete detailed audit report is available here:

📄 **Full Detailed Report:**  
[Click here to view the PDF](./Website_Performance_Audit_Report.pdf)---

## 👨‍💻 Author

**Aditya Raj Singh**  
B.Tech CSE | Web Development & Performance Optimization Enthusiast  
GitHub: [LENGND123](https://github.com/LENGND123)
