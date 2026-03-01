# Website Performance Audit (Google Lighthouse)

This repository contains a detailed Lighthouse performance audit report of a live production website.

## 📊 Audit Overview

- Tool Used: Google Lighthouse (Mobile Simulation)
- Testing Mode: Chrome Incognito
- Performance Score: 58/100
- Key Metrics Analyzed:
  - First Contentful Paint (FCP)
  - Largest Contentful Paint (LCP)
  - Total Blocking Time (TBT)
  - Cumulative Layout Shift (CLS)
  - Speed Index

## 🚨 Key Issues Identified

- High LCP (11.9s)
- Render-blocking CSS & JavaScript
- Font loading delays
- Unoptimized images
- Excess JavaScript execution time

## 🛠 Optimization Recommendations

- Convert images to WebP
- Implement lazy loading
- Use font-display: swap
- Defer non-critical JavaScript
- Implement CDN & compression

## 📄 Full Report

The complete audit report is available in:
`Website_Performance_Audit_Report.pdf`

---


## 👨‍💻 Author

**Aditya Raj Singh**  
B.Tech CSE | Web Development & Performance Optimization Enthusiast  
GitHub: https://github.com/LENGND123
