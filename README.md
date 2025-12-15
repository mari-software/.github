<style>
  .mari-logo {
    width: 200px;
    background: white;
    padding: 30px;
    border-radius: 30px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    transition: 
      transform 0.4s ease,
      box-shadow 0.4s ease,
      filter 0.4s ease;
  }

  .mari-logo:hover {
    transform: translateY(-8px) scale(1.01);
    box-shadow: 0 20px 45px rgba(0,0,0,0.25);
    filter: brightness(1.05);
  }
</style>

<div align="center">
  <img 
    src="assets/logo.png"
    alt="Mari logo"
    class="mari-logo"
  />
</div>

<br />

<h1 align="center" style="font-weight: 800;">
  Mari Software
</h1>

<p align="center" style="max-width: 600px; margin: auto; color: #555;">
  A modular, multi-platform software ecosystem designed for scalability, 
  clean architecture, and long-term maintainability.
</p>

---

## ✨ Repository Walkthrough

> This repository is organized by **product type** and **platform**,  
> allowing services and applications to evolve independently while remaining interoperable.

### 📦 Products Overview

| Type   | Product  | Description          |
|:------:|:--------:|----------------------|
| record | gateway  | API Gateway Service  |
| web    | account  | Account Website      |

---

## 🧩 Project Types

The **Type** field indicates the role and deployment target of each product:

- **record** – Backend services (APIs, gateways, workers)
- **web** – Web applications
- **android** – Android applications
- **ios** – iOS applications
- **cli** – Command-line tools
- **windows** – Windows desktop apps
- **mac** – macOS desktop apps
- **linux** – Linux desktop apps

---

