# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
<p><strong>Deployed by:</strong> DMI Cohort 2 | Rahul Sharma | Group 4 | Week 1 | 16-01-2026</p>
```

✅ This proof must be visible in your browser screenshot submission.

## 02/07/2026 Added Dynamic date to Footer in <span id="deployDate">05 Feb 2026</span> — By James Tuttle

```JS
         <script>
          const d = new Date();
          const formattedDate = d.toISOString().split("T")[0];
          document.getElementById("deployDate").textContent = formattedDate;
        </script>
```

<img width="792" height="519" alt="Screenshot 2026-02-06 at 11 01 19 PM" src="https://github.com/user-attachments/assets/290b3b5c-1f77-4e7e-a2d0-da941b328817" />

