## 🚀 Featured Projects

### 🌐 Orbit — Real-Time Social & Chat Platform

**Live:** https://orbit-one-inky.vercel.app
**Type:** Full-Stack Web Application + PWA
**Tech Stack:** React.js • Node.js • Express.js • MongoDB • Socket.io • JWT • CSS3 • Vite

Orbit is a full-stack social networking and real-time messaging platform designed to provide users with a complete social interaction experience — from account creation and profile management to posts, followers, notifications, and private messaging.

#### 🔹 Core Features

* 🔐 **Authentication & Authorization**

  * User registration and login system.
  * JWT-based authentication.
  * Protected routes and authorization.
  * Secure user session handling.

* 👤 **User Profiles & Social Connections**

  * User profile management.
  * Follow / unfollow functionality.
  * Followers and following system.
  * Profile search.
  * Private-account controls.

* 📝 **Post Management**

  * Create, update and delete posts.
  * Like and unlike posts.
  * Comment system.
  * Complete CRUD operations for social content.

* 💬 **Real-Time Messaging**

  * One-to-one real-time chat.
  * Message delivery and seen status.
  * Inbox management.
  * Real-time communication using Socket.io.

* 🔔 **Notifications**

  * Follow notifications.
  * Post and social interaction notifications.
  * Real-time notification updates.

* 📱 **Responsive PWA**

  * Mobile-responsive interface.
  * Installable as a Progressive Web App.
  * Optimized mobile messaging layout.
  * Dynamic viewport-height handling for mobile devices.

#### ⚙️ Backend & API Architecture

Designed and implemented **35+ RESTful APIs** covering authentication, users, profiles, posts, comments, likes, followers, messaging and notifications.

The backend follows a structured Node.js + Express architecture with MongoDB as the primary database.

#### 🚀 Deployment

* Frontend deployed on **Vercel**
* Backend deployed with production configuration
* MongoDB used as the database
* Git/GitHub used for source-code management

**What I worked on:** Full-stack development, REST API development, authentication, database integration, real-time communication, responsive UI and deployment.

---

### 📍 NearPing — Real-Time Location-Based Alert & Community Platform

**Live Web App:** https://nearping-app.vercel.app
**Platform:** Web + Native Android
**Tech Stack:** React.js (Vite) • Node.js • Express.js • MongoDB Atlas • Socket.io • Capacitor • Vercel • Render

NearPing is a location-based community platform built around the idea of helping people quickly communicate about **Lost & Found items and Urgent Help situations** within their nearby area.

The project was developed end-to-end, including the frontend, backend, database, real-time communication, deployment and native Android packaging.

#### 🔹 Core Features

* 🔐 **Authentication System**

  * User registration and login.
  * JWT-based authentication.
  * Protected user functionality.
  * Profile-based access.

* 📍 **Location-Based Alerts**

  * Users can create location-based Pings.
  * Supports:

    * 🔎 Lost
    * ✅ Found
    * 🚨 Urgent Help
  * Nearby users can discover relevant alerts based on location.

* 📡 **Geospatial Search**

  * MongoDB geospatial capabilities used for location-based matching.
  * Implemented **2dsphere indexing**.
  * Distance-based queries help identify nearby alerts/users.

* 💬 **Real-Time Communication**

  * Implemented Socket.io for real-time updates.
  * Supports real-time community interactions.
  * Backend communicates with connected clients without requiring constant page refreshes.

* ⏳ **Alert Expiry System**

  * Alerts can automatically become expired after their active period.
  * Helps keep the active feed relevant.

* 📱 **Responsive Mobile UI**

  * Built with React + Vite.
  * Designed for mobile-first usage.
  * Responsive interface for both desktop and mobile browsers.

#### ⚙️ Backend Architecture

The backend was developed using **Node.js and Express.js** with MongoDB Atlas.

The backend handles:

* Authentication APIs
* Ping creation and retrieval
* Claim-related functionality
* Location/distance-based matching
* Real-time Socket.io communication
* Alert expiry
* Database operations

#### ☁️ Production Deployment

The complete application is deployed using a GitHub-based workflow:

**GitHub Push → Vercel Frontend Deployment + Render Backend Deployment → MongoDB Atlas**

A `/health` endpoint was also configured for backend health monitoring.

#### 📲 Native Android Application

One of the major parts of NearPing was converting the web application into a native Android application using **Capacitor**.

I handled:

* Capacitor Android integration
* Android project configuration
* Release keystore generation
* APK/AAB release signing
* ADB-based device testing
* Native Android packaging

The project successfully produced a **signed Android APK/AAB**.

#### 🔄 Remote Update System

A remote-update approach was implemented for the Android application.

The Android wrapper loads the live frontend hosted on Vercel through the configured URL. Because of this architecture, frontend UI and feature updates can be deployed to the live web application without rebuilding and redistributing the Android APK for every frontend change.

**What I worked on:** Complete end-to-end development — React frontend, Node/Express backend, MongoDB database, geospatial functionality, Socket.io, authentication, deployment, Android packaging and release configuration.

---

### 🏨 Hotel Management & QR Ordering System

**Type:** Full-Stack MERN Application
**Tech Stack:** React.js • Node.js • Express.js • MongoDB

A hotel management and restaurant ordering platform designed to digitize table ordering and kitchen operations.

#### 🔹 Key Features

* 📱 QR-code based table ordering.
* 🍽️ Customers can place orders directly from their table.
* 👨‍🍳 Real-time order routing to kitchen/waiter dashboards.
* 💳 Online payment integration.
* 🪑 Live table availability tracking.
* 🔄 Backend APIs for orders, tables and related operations.

**My Focus:** Full-stack development, REST APIs, MongoDB integration and real-time order-management workflow.

---

### 🏢 Company Website — Kamarta Robotics Automation

**Type:** Production Company Website
**Tech Stack:** Django • Python • Database Integration

Developed the backend of a company website using Django.

#### 🔹 Key Work

* Developed Django backend functionality.
* Implemented custom URL routing.
* Integrated application logic with the database.
* Worked on backend modules required for production usage.
* Connected frontend components with backend functionality.

This project also provided practical experience working with backend architecture and production-oriented development.

---

### 🍔 Food Website

**Type:** Responsive Frontend Web Application
**Tech Stack:** HTML5 • CSS3 • JavaScript

A responsive food/restaurant-style website focused on creating a clean and mobile-friendly user experience.

#### 🔹 Key Features

* Responsive layout.
* Mobile-friendly navigation.
* Structured landing-page sections.
* Interactive UI using JavaScript.
* Cross-screen layout optimization.

**My Focus:** Frontend development, responsive design and JavaScript-based interactions.
