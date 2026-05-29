# 🌐 SupplyChain-ERP-Frontend-React

<!-- Badges Section -->
<p align="left">
  <img src="https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/React%20Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" alt="React Router">
</p>

---

## 📖 Project Overview

This repository contains the **Frontend Application** for an enterprise-grade Supply Chain and ERP system. Built as a Single Page Application (SPA) using **React, TypeScript, and Vite**, it provides a lightning-fast, highly responsive, and intuitive user interface. It seamlessly consumes the underlying ASP.NET Core Web API to handle complex procurement lifecycles, dynamic inventory tracking, and master data management.

*(To view the Backend REST API architecture, please check the interconnected backend repository in my profile).*

---

## 🚀 Key Features & UI Workflows

* 🔑 **Role-Based Dynamic Routing:** Secure routing system that dynamically renders sidebars and pages based on user roles (Admin, Purchase Manager, Store Manager, etc.).
* 📋 **Complex Form Handling:** Multi-step workflows for Employee Requisitions, Purchase Orders (PO), and Goods Receipt Notes (GRN).
* 📊 **Algorithmic Data Visualization:** Interactive implementation of the Comparative Statement (CS) module, comparing multi-vendor bids side-by-side.
* 📦 **State Management:** Efficient global state handling utilizing React Context API and custom hooks.

---

## 📷 UI Showcases (Sneak Peek)

*Click on the dropdowns below to expand the application screenshots:*

<details>
<summary>📊 1. Interactive Dashboard</summary>
<br>
<img src="https://placehold.co/800x450?text=Dashboard+Screenshot+Coming+Soon" alt="Dashboard" width="100%">
</details>

<details>
<summary>⚖️ 2. Comparative Statement (CS)</summary>
<br>
<img src="https://placehold.co/800x450?text=Comparative+Statement+Screenshot+Coming+Soon" alt="Comparative Statement" width="100%">
</details>

<details>
<summary>📝 3. Employee Requisition & PR</summary>
<br>
<img src="https://placehold.co/800x450?text=Requisition+Screenshot+Coming+Soon" alt="Requisition" width="100%">
</details>

<details>
<summary>📦 4. Procurement (RFQ & PO)</summary>
<br>
<img src="https://placehold.co/800x450?text=Procurement+Screenshot+Coming+Soon" alt="Procurement" width="100%">
</details>

---

## 📂 Project Structure Snapshot

```text
src/
├── assets/           # Static media and global styles
├── components/       # Reusable UI components (Buttons, Modals, Tables)
├── context/          # React Context providers for global state
├── hooks/            # Custom React hooks
├── layouts/          # Master layouts (Sidebar, Header, Protected Layout)
├── pages/            # Core application pages (Dashboard, Procurement, Store)
├── services/         # Axios API configuration and endpoint calls
├── utils/            # Helper functions and formatters
├── App.tsx           # Root component and Router configuration
└── main.tsx          # Application entry point