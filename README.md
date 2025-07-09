<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0E75B6&height=120&section=header&text=Sanjay%20Patidar&fontSize=40&fontColor=FFFFFF" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=0E75B6&center=true&vCenter=true&width=1000&lines=Full+Stack+Engineer+%7C+SaaS+Storyteller+%7C+Cloud+Native+Architect;Building+Products+with+SEO+and+Scalability;React.js+%7C+Node.js+%7C+WebRTC+%7C+AWS+Lambda" />
</p>

---

## 👨‍💻 Executive Summary

I’m **Sanjay Patidar**, a full-stack engineer who builds **business-backed, scalable, cloud-native SaaS products**. Each project—from insurance and education to event management and peer-to-peer communication—is a story of addressing a real-world problem with a fully deployed, SEO-optimized solution that scales and delivers impact.

---

## 🚀 Projects Overview

### 1. **LIC Neemuch – Insurance Inquiry Platform**  
**Live:** [licneemuch.space](https://licneemuch.space)  
**Case Study:** [LIC Case Study](https://sanjay-patidar.vercel.app/lic-case-study)  
**Photo:** (Include `lic-full-architecture.png` below section)

#### 🛋 The Pain Point  
LIC Neemuch had no digital presence—leads from pamphlets and word of mouth were slow and untraceable.

#### 🎯 Solution Delivered  
- Full **serverless SSR React site** with SEO optimization  
- AWS Lambda API, MongoDB Atlas data capture, email notifications  
- 3x increase in lead submissions, top-3 Google rankings for local queries

#### ⚙️ Technical Highlights  
- Vite + React Helmet for SEO and metadata  
- CloudFront + S3 hosting, global reach, sub-800 ms Time‑to‑Interactive  
- CloudWatch logs for visibility and lambda cold start tuning

#### 🧩 Lessons Learned  
- Structured metadata leads to faster indexing  
- Serverless cost optimization: reduced infra by 60% vs EC2

---

### 2. **Zedemy – EdTech Platform with Code Playground & Certificates**  
**Live:** [zedemy.vercel.app](https://zedemy.vercel.app)  
**Case Study:** [Zedemy Case Study](https://sanjay-patidar.vercel.app/zedemy-case-study)  
**Photo:** (Include `zedemy-frontend-architecture.png`)

#### 🌐 Why It Matters  
Existing educational platforms focus on content delivery, not on learner verification or interactivity.

#### 💡 Solutions Built  
- `react-markdown` blog posts + progress tracking  
- CodeMirror-powered in-browser IDE with autosave  
- Certificate issuance + certificate verification engine  
- Role-based auth via JWT + OAuth, serverless backend

#### 🏗 Tech Breakdown  
- Lambda + DynamoDB for posting, cert logic, unique hashes  
- Vercel & GitHub Actions for SSR deployment  
- Dashboard features and mobile-first UX

#### 🔍 SEO Work  
- Rewrites for `/post/:slug`, pre-rendered versions via SSR  
- Sitemap.xml updates to improve discoverability

---

### 3. **EventEase – Unified Event Scheduling & Collaboration**  
**Live:** [eventunified.vercel.app](https://eventunified.vercel.app)  
**Case Study:** [EventEase Case Study](https://sanjay-patidar.vercel.app/eventease-case-study)  
**Photo:** (Include `eventease-full-architecture.png`)

#### 📅 The Problem  
Maintaining two event-focused tools caused friction—disorganized design, conflicting UX.

#### ➕ What Was Built  
- Consolidated UI with shared Redux slices  
- Google Calendar sync via FullCalendar  
- Admin & user dashboards with role-level auth  
- Lazy-loading optimized with code-splitting

#### ⚙️ Architecture  
- React + Redux Toolkit, styled components  
- Node/Express + MongoDB API, deployed to Render  
- Vercel hosting for frontend, auto-deployment of updates

#### 🧠 Optimization  
- Split renders to reduce JS by 30%  
- Protected routes and session fallback strategies

---

### 4. **ConnectNow – Peer‑to‑Peer Video + Chat App**  
**Live:** [connectnow.vercel.app](https://connectnow.vercel.app)  
**Case Study:** [ConnectNow Case Study](https://sanjay-patidar.vercel.app/connectnow-case-study)  
**Photo:** (Include `connectnow-backend-architecture.png`)

#### 🎥 Market Gap  
No light-weight, browser-native video chat for small teams—performance-heavy platforms didn’t fit.

#### 🔗 What I Built  
- Raw WebRTC for P2P video, ICE fallback for unstable networks  
- Real-time chat and file transfer in a “commonroom”  
- Custom signaling using Socket.io

#### 🛠 Technical Challenges  
- SDP renegotiation and echo suppression  
- State cleanup on connection end or reload  
- Base64 file streaming via socket

---

## 📊 Impact Metrics

| Metric                        | LIC Neemuch       | Zedemy              | EventEase          | ConnectNow         |
|------------------------------|------------------|---------------------|--------------------|--------------------|
| Unique Users                 | 1K+ / mo          | 20K+ CTRs           | 5K+ active users   | 1K+ downloads      |
| Google Lighthouse Score      | 100/100           | 99+                | 95+                | 90+                |
| PageSpeed TTI                | <800 ms           | <1.2 s             | <1 s               | 1–1.5 s            |
| Lead / Conversion Growth     | +300%             | N/A                | +200% planned      | N/A                |
| Infra Cost Reduction         | -60%              | -40%               | -30%               | N/A                |

---

## 🛠 Engineering Challenges & Insights

- **SSR in serverless architecture**: Achieved full SEO liftoff with React + Helmet + pre-rendered HTML
- **Peer-to-peer media handling**: Received rotary ICE connection via `oniceconnectionstatechange`
- **Unified state in multi-app workflows**: Shared Redux logic reduced redundancy by 50%
- **SSTTT challenges (Searchability, Speed, Traffic, Trust, Transfers)** solved across projects

---

## 💬 Technical FAQs

<details>
  <summary>🔒 How do you secure your backend?</summary>
  <p>JWT-based auth, HTTPS via ACM, API Gateway IAM roles, secure cookies, MFA for admin panels.</p>
</details>

<details>
  <summary>🧩 How do you prevent duplicate blog reads?</summary>
  <p>Deduplicate with MongoDB `$addToSet`, prevent issues via Redis-like storing in frontend.</p>
</details>

<details>
  <summary>🌐 How did you ensure SEO for login-based blog features?</summary>
  <p>Partial SSR, pre-rendered public pages with authenticated SPA enhancements later in app flow.</p>
</details>

<details>
  <summary>🔧 How did you handle ICE failures under 3G?</summary>
  <p>Used fallback STUN servers, custom retry logic, and re-negotiation via call UI state management.</p>
</details>

---

## 🎯 Why These Projects Matter

- **Real-world utility**: Each solves a unique problem with tangible outcomes
- **Solo execution**: You get figuring out every module, code path, deployment, and delivery
- **SEO-centric growth**: From zero to discoverable — all without backlinks or SEO spend
- **Performance-first engineering**: Speed is non-negotiable — every app is fast, secure, and scalable

---

## 📌 Connect With My Full Portfolio

- 📝 [Full Case Study Portfolio](https://sanjay-patidar.vercel.app)
- 🌐 [website](https://sanjay-patidar.vercel.app)
- 🧠 [Resume (ATS‑friendly)](https://sanjay-patidar.vercel.app/resume)
- 🔭 [LinkedIn](https://linkedin.com/in/sanjay-patidar)
- 📧 [sanjaypatidar.engineer@gmail.com](mailto:sanjaypatidar.engineer@gmail.com)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0E75B6&height=120&section=footer" />
</p>
