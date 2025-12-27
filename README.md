# 🚕 CabFlow AI™  
**AI-Driven Cab Booking Automation for Routematic**

> Never miss your cab booking again.  
> HarshCabFlow AI™ is a context-aware, autonomous Android automation system that securely books next-day Routematic cabs within the allowed booking window.

---

## ⬇️ Download (APK)

👉 **[Download Latest APK](https://github.com/Harsh067899/Cab_Automation_Routematic/releases/latest)**

- Platform: **Android**
- Current Version: **v0.1.0-beta**
- Installation: Manual APK install
- Permissions Required: **Accessibility Service**

---

## 📌 Problem Statement

In many colleges and corporate campuses, students and employees rely on **Routematic** for daily transportation.  
However, the system enforces strict rules:

- Cab for **tomorrow must be booked before 12:00 AM today**
- Booking is **manual and multi-step**
- No auto-booking or reminder feature
- Booking is **blocked on holidays**
- Missing the window means **no cab for the next day**

This results in a **real, recurring problem** faced daily by students, interns, and professionals.

---

## 🤖 How HarshCabFlow AI™ Helps

HarshCabFlow AI™ acts as an **autonomous, context-aware agent** that performs booking **exactly like a responsible human user**, but without forgetting.

### What the AI Does
- Observes the app UI in real time
- Detects the current screen (Home, Calendar, Form)
- Identifies the **next valid working day**
- Skips weekends and holidays automatically
- Fills booking details only when required
- Verifies every action before proceeding
- Fails safely if booking is not allowed

### What the AI Does NOT Do
- ❌ No reverse engineering
- ❌ No private or unauthorized APIs
- ❌ No bypassing business rules
- ❌ No booking outside allowed time windows

---

## 🧠 Why This Is AI (Not a Script)

This system is **not a blind click bot**.

It is built as a **finite state machine**, where each step:
1. Observes UI context
2. Makes a decision
3. Performs an action
4. Verifies the outcome
5. Retries or exits safely if needed

This allows the automation to handle:
- Network delays
- UI changes
- Missed clicks
- Holidays
- End-of-month calendar transitions

---

## 🛠️ Technical Overview

- Android **Accessibility Service**
- Event-driven UI detection (no fixed delays)
- State-machine-based control flow
- Read-after-write verification
- Retry limits & safety timeouts
- Notification-based user initiation (Android-compliant)

---

## ⏰ Scheduling & Safety

- Designed to run **before midnight**
- Fully respects Routematic booking rules
- Does **nothing** on holidays or blocked days
- Requires minimal user interaction (notification tap)

---

## 🌍 Real-World Impact

HarshCabFlow AI™ solves a **daily operational pain point**:

- Prevents missed cab bookings
- Reduces stress and cognitive load
- Saves money on last-minute transport
- Improves punctuality and reliability

This is a **real-world AI automation**, not a theoretical demo.

---

## 🔒 Source Code Availability

The **implementation source code is intentionally private**.

This public repository exists to:
- Share the project concept and documentation
- Provide the compiled APK for testing
- Demonstrate real-world AI automation capability

Source code may be released in the future.

---

## ⚠️ Disclaimer

> This project is intended for **personal, educational, and internal use only**.  
> It operates strictly through the official app UI and respects all business rules.  
> The author is **not affiliated with Routematic**.

---

## 🏁 Summary

**HarshCabFlow AI™** demonstrates how AI can be used responsibly to solve a real, everyday problem faced by students and professionals.

By combining:
- Context awareness
- State-based reasoning
- Verification-driven automation

…it delivers a **robust, ethical, and practical AI solution**.

---

**Built with ❤️ to solve a problem we personally faced.**
