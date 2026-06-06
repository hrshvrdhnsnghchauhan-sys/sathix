# sathix
Auto Saathi - An Agentic AI-powered "Digital Employee" for MSMEs. Features zero-UI WhatsApp automation, document OCR, smart payment recovery, and direct-to-sheet bookkeeping. Built with Next.js and Supabase.
# Auto Saathi (Sathix) 🚀
**India's All-in-One Service Automation Platform for Local Businesses**

Auto Saathi is an autonomous "Agentic AI" platform designed to act as a Digital Business Manager for Indian MSMEs (CAs, Doctors, Clinics, Retailers, and Freelancers). It moves beyond passive SaaS tools by utilizing a "Zero-UI" approach, allowing business owners to automate document collection, payment recovery, and bookkeeping entirely via WhatsApp.

## 📌 Core Features

*   **Zero-UI Onboarding:** Fully operational via WhatsApp Business API. No complex dashboards required for the end-user.
*   **AI Payment Recovery Agent:** Automated invoice tracking, dynamic escalation (early-bird discounts), and seamless UPI integration.
*   **Auto Document Collection (OCR):** Automatically requests, parses, and verifies KYC and billing documents via WhatsApp and Email.
*   **Zero-Touch Bookkeeping:** Direct-to-Sheet architecture. Synchronizes WhatsApp transaction data directly into Google Sheets or Excel without manual entry.
*   **Compliance Autopilot:** Automated tracking and filing assistance for GSTIN and Udyog Aadhaar portals.

## 🛠️ Tech Stack

*   **Frontend:** Next.js 14 (App Router), React, TypeScript
*   **Styling:** Tailwind CSS, shadcn/ui
*   **Backend & Database:** Supabase (PostgreSQL, Edge Functions, Auth, RLS)
*   **Integrations:** 
    *   WhatsApp Cloud API (Webhooks)
    *   Google Sheets API
    *   Razorpay / UPI Payment Gateways
    *   OCR Processing Endpoints

## ⚙️ Getting Started

### Prerequisites
*   Node.js (v18 or higher)
*   Supabase Account
*   Meta Developer Account (for WhatsApp Business API)
*   Google Cloud Console Account (for Sheets API)

### Installation

1. **Clone the repository:**
```bash
   git clone [https://github.com/your-username/auto-saathi.git](https://github.com/your-username/auto-saathi.git)
   cd auto-saathi
