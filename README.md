# Warehouse QC Management System

A real-time web application built to manage and track 
quality control checks across 4 warehouse production sites, 
replacing a manual WhatsApp-based process with a fully 
automated digital platform.

## 🏭 About the Project

Built independently for a food manufacturing company 
supplying sushi to major UK supermarkets. The system manages 
daily quality checks across 4 sites (Fuji, Koi, Bonsai, Yuzu) 
for 20+ team members.

**Status:** Pending full team rollout following management approval.

## ✨ Features

- **Real-time sync** — all check logs update instantly across 
all devices via Firebase
- **Role-based access** — user registration, admin approval 
workflow, super admin protection
- **Smart scheduling** — custom scheduling engine managing 
7 check types with individual time windows and automatic 
status transitions (Due → Done / Missed / Late)
- **Photo evidence** — mandatory photo uploads per check type 
with automatic client-side compression
- **Automated PDF reports** — app data exported directly onto 
official company compliance documents, eliminating manual 
form filling and paper scanning
- **Check assignment** — assign checks to team members with 
full accountability tracking
- **Audit history** — 30-day history with full drill-down 
by site, time slot and staff member
- **Notifications** — in-app alerts for due and missed checks

## 🛠️ Built With

- **Frontend** — HTML, CSS, JavaScript
- **Database** — Firebase Realtime Database
- **Image Storage** — Cloudinary CDN
- **PDF Generation** — jsPDF
- **Hosting** — GitHub Pages

## 📱 Live App

🔗 [Open App](https://quality-crew.github.io/checks-documents/)

## 💡 Problem Solved

Previously, warehouse teams logged checks manually via 
WhatsApp polls — no accountability, no audit trail, no 
real-time visibility. This system replaced that entirely with:

- Named, locked user accounts
- Time-stamped logs with photo evidence
- Live dashboard visible to all team members
- Automated compliance documentation

## 📊 Scale

- 4 production sites
- 7 check types
- 20+ concurrent users
- Zero operational cost (free tier infrastructure)
