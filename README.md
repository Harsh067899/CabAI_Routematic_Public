# IF SOMEONE WANTS TO CONTRIBUTE OR WANNA ACCESS THE CODE MailME at "mikeross997721@gmail.com" or send a req on github.


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







#HOW IT WORKS

#  AI-Driven Cab Booking Automation for Routematic

## 📌 Problem Statement

In many colleges and corporate campuses, students and employees depend on **Routematic** for daily cab transportation. The booking system has strict constraints:

- Cab for **tomorrow must be booked before 12:00 AM today**
- Booking is done manually through a **multi-step mobile app flow**
- If a user forgets to book on time, **no cab is assigned**
- On holidays or blocked days, booking is not allowed
- There is **no reminder or auto-booking feature**

This creates a **real, recurring problem** faced by many students and working professionals.

---

## 🎯 Why This Is a Real-World Problem

Students and interns often:
- Return late from classes, labs, or projects
- Manage academic work along with internships
- Miss the narrow booking window unintentionally

Missing a booking results in:
- Last-minute expensive transport
- Stress and inconvenience
- Punctuality and attendance issues

This is not an edge case — **it happens daily to many users**.

---

## ❌ Why Existing Solutions Are Insufficient

- Routematic does **not provide any auto-booking option**
- There is **no public API** to integrate with
- Manual booking requires:
  - Navigating the calendar
  - Identifying the next working day
  - Filling multiple dropdowns
  - Saving within a strict time window
- Simple reminders are unreliable because the user still needs to perform every step correctly before midnight

---

## 🤖 How AI Helps Solve This Problem

We designed an **AI-driven, context-aware automation agent** that behaves like a **responsible human user** rather than a simple script.

### The AI Does NOT:
- Reverse engineer the application
- Use private or unauthorized APIs
- Bypass business rules
- Book outside allowed time windows

### The AI DOES:
- Observe the app’s UI in real time
- Understand which screen is currently visible
- Make decisions based on UI state
- Verify every action before proceeding
- Respect booking rules, holidays, and constraints

---

## 🧠 Why This Is AI and Not a Script

This solution is **not a blind click bot**.

It uses **state-based reasoning** and **context awareness**, similar to how a human interacts with the app:

- Detects current screen (Home, Calendar, Form)
- Identifies valid working days
- Skips weekends and holidays
- Reads current field values before changing them
- Verifies that selections were applied successfully
- Retries intelligently if an action fails
- Exits gracefully when booking is not allowed

The system is implemented as a **finite state machine**, where each state:
- Observes UI context
- Decides the next action
- Confirms success before transitioning

---

## 🛠️ Technical Approach

### Core Design
- Android **Accessibility Service**
- **Finite State Machine** based automation
- Event-driven UI detection (no fixed delays)
- Read-after-write verification
- Fail-safe retries and timeouts

### Key Capabilities
- Launches Routematic reliably
- Navigates to the calendar automatically
- Identifies the **next valid working day**
- Skips weekends and holidays
- Fills booking details only when needed
- Confirms booking success visually
- Stops safely when booking is not permitted

---

## ⏰ Scheduling & Safety

- Runs automatically before midnight
- Respects Routematic’s booking window
- Does not attempt booking on holidays
- Requires minimal user interaction (notification-based launch)

---

## 🌍 Real-World Impact

This project addresses a **daily operational pain point**:

- Prevents missed cab bookings
- Reduces stress and mental load
- Saves money on last-minute transport
- Improves punctuality and reliability

It demonstrates how **AI automation can improve everyday life**, not just serve as a theoretical demo.

---

## 🧠 Key Learnings & Innovation

- AI can operate **within strict system constraints**
- Accessibility can be used **ethically and responsibly**
- State-based reasoning significantly improves reliability
- Real-world automation requires verification, not assumptions

---

## 🏁 Summary

We built an **AI-driven, context-aware automation system** to solve a **real, recurring transportation problem** faced by students and professionals.

Instead of bypassing systems, the AI agent is designed to:
- Observe
- Decide
- Act
- Verify
- Fail safely

This makes the solution **robust, ethical, and genuinely useful in real-world scenarios**.


> ⚠️ This project is intended for personal, educational, and internal use only.
> It operates strictly via the official app UI and respects all booking rules.
> The author is not affiliated with Routematic.
> 
