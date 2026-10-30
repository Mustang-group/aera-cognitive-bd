# AERA COGNITIVE (SYS-AIS) — VERCEL PHONE DEPLOYMENT & ZERO-MISS OPERATION GUIDE

## 1. How to Deploy Live on Vercel Directly From Your Phone (3 Minutes)
1. **Unzip `AERA_Cognitive_Final_Deployment_Bundle.zip`** on your phone (using Files by Google on Android or the Files app on iPhone).
2. **Upload to GitHub from Mobile Browser**:
   - Open `https://github.com/new` in Chrome/Safari on your phone.
   - Create a repository named `aera-cognitive-bd` and tap **uploading an existing file**.
   - Select the 4 files from the unzipped folder:
     - `index.html` (Public Customer Storefront + Hidden Footer `🔒 Partner Auth`)
     - `cofounder-dashboard.html` (Your Private War Room Dashboard)
     - `vercel.json` (Auto-routes `/warroom` and `/admin` to your dashboard)
     - `PRD_TRD_APP_FLOW_AND_SECURITY_SPEC.md`
   - Tap **Commit changes**.
3. **1-Tap Deploy on Vercel Mobile**:
   - Open `https://vercel.com/new` on your phone, tap **Import** next to `aera-cognitive-bd`, and tap **Deploy** (leave all settings default—no build command needed).
   - In 15 seconds, your live URL is active:
     - **Customer Link (for Meta Ads & Bio):** `https://your-project.vercel.app/`
     - **Your Private War Room Link:** `https://your-project.vercel.app/warroom` (or tap `🔒 Partner Auth` in the footer of the main site and enter passkey **`AIS2026`**).

---

## 2. Exact Inputs Required From You (Checklist of Every Smallest Input)
Everything in the codebase is pre-configured and live. Here are the **only 3 inputs** you ever provide during live operation:

| When / Where | Exact Input You Provide | What the System Does Automatically |
| :--- | :--- | :--- |
| **Input 1: When a customer pays via bKash (`+8801720674268`) or Nagad (`+8801708761298`)** | Copy the customer's WhatsApp verification message (or just the 8–10 character `TrxID` from your bKash/Nagad SMS) and paste it into **`📲 ১-ট্যাপ মোবাইল অর্ডার ইমপোর্টার`** inside `🔒 Partner Auth` (Passkey: `AIS2026`) or `/warroom`. | Automatically extracts and saves the customer's Name, Phone, Email, Package, and Amount into your Data Store, updates your live bKash/Nagad balance, computes their mathematical 6-character Unlock PIN (`AIS-XXXX`), and opens WhatsApp with the pre-filled reply so they unlock all 7 assets + Official Invoice in under 60 seconds. |
| **Input 2: Launching Your Meta Ad (500 BDT Budget)** | In Meta Ads Manager on your phone/browser, paste your new Vercel URL (`https://your-project.vercel.app/`) at the bottom of **FB Post #1** (copied with 1 tap from your dashboard) and set Manual Placements to **FB/IG Feed & Reels only**. | Drives ৳1.50–৳2.50 clicks into the 4 Free Neuro-Tools and converts visitors into ৳99 / ৳499 / ৳4,999 buyers. |
| **Input 3 (Optional): 24/7 Sleeping Automation** | If you want incoming bKash/Nagad SMS messages on your Android phone to verify orders automatically without you touching WhatsApp, paste the 15-line Google Apps Script (from the `⚡ Social & SMS Automation` tab) into a free Google Sheet Web App and paste that URL into the **`Webhook URL`** box in `🔒 Partner Auth`. | Syncs every order to your Google Sheet and auto-verifies matching SMS TrxIDs 24/7. |
