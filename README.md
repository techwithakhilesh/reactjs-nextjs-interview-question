# React.js & Next.js Interview Questions (7+ Years Experience)

A curated list of the most frequently asked React.js and Next.js interview questions for senior frontend developers, frontend architects, and full-stack engineers.

---

# 📚 Table of Contents

- [React.js Interview Questions](#-reactjs-interview-questions)
  - [Core React Internals](#-core-react-internals)
  - [React Hooks](#-react-hooks)
  - [Performance Optimization](#-performance-optimization)
  - [State Management](#-state-management)
  - [React Architecture](#-react-architecture)
  - [Advanced React Topics](#-advanced-react-topics)
  - [Scenario-Based Questions](#-scenario-based-questions)
  - [Coding Questions](#-coding-questions)

- [Next.js Interview Questions](#-nextjs-interview-questions)
  - [Core Next.js Concepts](#-core-nextjs-concepts)
  - [Server Components](#-server-components)
  - [Data Fetching](#-data-fetching)
  - [Performance Optimization](#-performance-optimization-1)
  - [Authentication & Security](#-authentication--security)
  - [Deployment & DevOps](#-deployment--devops)
  - [Architecture & System Design](#-architecture--system-design)
  - [Production Scenario Questions](#-production-scenario-questions)

---

# ⚛️ React.js Interview Questions

## 🔹 Core React Internals

- What happens internally when React re-renders?
- Explain React reconciliation.
- What is React Fiber?
- Difference between Virtual DOM and Real DOM?
- How does React batching work in React 18?
- What causes unnecessary re-renders?
- Difference between `useMemo`, `useCallback`, and `React.memo`?
- When should you NOT use `useMemo`?
- Explain rendering lifecycle in functional components.
- Difference between controlled and uncontrolled components.

---

## 🎣 React Hooks

- Explain `useEffect` lifecycle completely.
- Difference between `useEffect` and `useLayoutEffect`?
- What are stale closures?
- Why is dependency array important?
- What happens if dependency array is missing?
- How do you prevent infinite re-renders?
- Explain custom hooks with real-world use case.
- When to use `useReducer` over `useState`?
- Explain `useRef` practical use cases.
- Can `useRef` trigger re-render?

---

## ⚡ Performance Optimization

- How do you optimize a large React application?
- Explain code splitting.
- Difference between lazy loading and dynamic import?
- How does `React.lazy` work?
- How to optimize large lists?
- Explain virtualization.
- What tools do you use to analyze performance?
- How do you reduce bundle size?
- What is tree shaking?
- Explain debounce and throttle in React.

---

## 🗂️ State Management

- Context API vs Redux?
- Why Redux Toolkit over Redux?
- Zustand vs Redux?
- When Context API becomes bad?
- How do you manage global state in large apps?
- Explain normalized state.
- How do you avoid prop drilling?

---

## 🏗️ React Architecture

- How do you structure a scalable React project?
- Explain Atomic Design.
- Smart vs Dumb components?
- Feature-based folder structure vs type-based?
- How do you manage reusable components?
- How do you design scalable frontend architecture?
- How do you handle permissions and roles?
- How do you implement dynamic forms?

---

## 🚀 Advanced React Topics

- What are Error Boundaries?
- How do Portals work?
- Explain Higher Order Components (HOC).
- Render Props pattern?
- What is hydration?
- Explain concurrent rendering.
- What are transitions in React 18?
- Explain Suspense.
- What are Server Components?
- Difference between Client and Server Components?

---

## 🧠 Scenario-Based Questions

- Why is your component rendering multiple times?
- How would you optimize dashboard with 100+ API calls?
- How would you handle websocket updates?
- How would you manage authentication state?
- How would you build reusable table component?
- How would you implement infinite scrolling?
- How do you prevent memory leaks?
- How do you debug production issues?
- How would you handle API retry mechanism?
- Explain optimistic UI update.

---

## 💻 Coding Questions

- Build debounce search input.
- Build reusable modal component.
- Create custom `useFetch` hook.
- Build dynamic form generator.
- Build pagination component.
- Implement drag-and-drop.
- Build infinite scroll.
- Create theme switcher.
- Implement file upload with preview.
- Build OTP input component.

---

# ▲ Next.js Interview Questions

## 🔹 Core Next.js Concepts

- Why Next.js over React?
- Difference between CSR, SSR, SSG, ISR?
- When to use SSR vs SSG?
- Explain App Router architecture.
- Difference between App Router and Pages Router?
- What is middleware in Next.js?
- Explain routing in Next.js.
- What are dynamic routes?
- Explain nested layouts.
- What is `loading.tsx`?

---

## 📦 Rendering Types

| Rendering Type | Description |
|---|---|
| CSR | Rendering in browser |
| SSR | Rendering on each request |
| SSG | Build-time rendering |
| ISR | Static page regeneration after deployment |

---

## 🖥️ Server Components

- What are React Server Components?
- Benefits of Server Components?
- Difference between Server and Client Components?
- Why use `"use client"`?
- Can hooks run in Server Components?
- How data fetching works in App Router?
- Explain server actions.
- Explain streaming in Next.js.
- What is partial rendering?
- How does hydration work?

---

## 🌐 Data Fetching

- Difference between fetch in client and server?
- Explain caching in Next.js.
- What is `revalidate`?
- Difference between `force-cache` and `no-store`?
- How do you prevent duplicate API calls?
- Explain parallel data fetching.
- Explain sequential fetching.
- What is Route Handler?
- Difference between API Routes and Route Handlers?
- How do you secure APIs?

---

## ⚡ Performance Optimization

- How Next.js improves SEO?
- Explain Image Optimization.
- What is edge runtime?
- What is middleware caching?
- How do you optimize Core Web Vitals?
- How do you reduce hydration cost?
- How do you optimize fonts?
- Explain static export.
- What is Turbopack?
- Explain bundle analysis.

---

## 🔐 Authentication & Security

- How do you implement JWT auth in Next.js?
- Session vs JWT?
- How do you secure cookies?
- What is HTTP-only cookie?
- How do you protect server routes?
- How do you implement RBAC?
- How do you handle refresh tokens?
- CSRF vs XSS?
- How do you secure environment variables?
- Explain middleware auth flow.

---

## 🚢 Deployment & DevOps

- How do you deploy Next.js on AWS EC2?
- Why use Nginx with Next.js?
- PM2 vs Docker?
- How do you scale Next.js app?
- Explain CDN usage.
- How do you configure SSL?
- Explain CI/CD pipeline.
- How do you monitor production errors?
- How do you handle logging?
- Explain Docker setup for Next.js.

---

## 🏛️ Architecture & System Design

- Design scalable frontend architecture.
- How would you build multi-tenant SaaS frontend?
- How would you design reusable design system?
- How do microfrontends work?
- How do you handle feature flags?
- How do you implement caching strategy?
- How do you handle real-time updates?
- Explain frontend scalability issues.
- How do you reduce initial load time?
- How do you manage shared state across apps?

---

## 🧪 Production Scenario Questions

- Tell me about a difficult bug you solved.
- Explain one production incident.
- How do you handle API failures?
- How do you optimize slow page?
- How do you improve Lighthouse score?
- Explain memory leak issue you faced.
- Explain one architecture decision you made.
- How do you handle large forms?
- How do you manage accessibility?
- How do you write scalable reusable code?

---

# ⭐ Recommended Interview Preparation Topics

## Must-Have Topics for Senior Frontend Engineers

### React
- React Fiber
- Reconciliation
- Hooks internals
- Performance optimization
- State management
- Suspense & Concurrent Rendering
- Design patterns

### Next.js
- SSR / SSG / ISR
- App Router
- Server Components
- Caching & Revalidation
- Middleware
- Authentication
- Deployment & Scaling

### System Design
- Frontend scalability
- API architecture
- Caching strategies
- Design systems
- Microfrontends
- Real-time systems

---

# 🛠️ Recommended Tech Stack

- React.js
- Next.js
- TypeScript
- Redux Toolkit / Zustand
- Tailwind CSS
- Node.js
- Docker
- Nginx
- AWS EC2
- CI/CD Pipelines

---

# 📌 Tips for 7+ Years Experience Interviews

✅ Focus on architecture decisions  
✅ Explain real production issues  
✅ Share optimization techniques  
✅ Be strong in performance tuning  
✅ Prepare scenario-based answers  
✅ Understand SSR/CSR deeply  
✅ Practice system design discussions  
✅ Be ready for live coding rounds  

---

# 📖 Source

Prepared from interview question collection. :contentReference[oaicite:0]{index=0}
