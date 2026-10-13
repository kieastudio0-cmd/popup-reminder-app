# Pop-up — Neo-Tactile Reminder App 🪔

> **"Small reminders. A happier home."**  
> A mobile-first, high-fidelity reminder web application designed with a sleek **Neo-Tactile (Dark Glassmorphic & 3D Extruded)** aesthetic.

Built with **Next.js 16 (App Router)**, **TypeScript**, **Tailwind CSS**, and **Lucide Icons**.

---

## 📱 Features

- **Neo-Tactile Visual Design**: Deep obsidian canvas (`#0b0f19`), neon cyan edge glow (`#00f0ff`), and tactile 3D interactive controls.
- **Mobile-First Experience**: Built for mobile viewports, plus an interactive desktop shell with a toggle for **Mobile Mockup** vs **Full View**.
- **Login Screen**: Welcome greeting (*"Namaste! Chhote reminders, badi khushi 🪔"*), mobile/email login, and a 1-click **"Explore Demo Mode"** button.
- **Home Dashboard**:
  - Total monthly due amount badge (e.g., ₹18,450) & festive Diya badge.
  - **Tabs**: `Today` (with overdue alerts), `Upcoming`, and `Done`.
  - **Task Cards**: Category badges, amounts, due dates, tap-to-edit, and tactile checkboxes.
  - **Floating Action Button (FAB)**: Floating mic pill with glowing concentric neon cyan ring `[🎙️ Add task]`.
- **Add Task Modal**:
  - Interactive voice mic button with animated pulse soundwaves (*“bijli ka bill 15 tarikh ko remind karo”*).
  - Category suggestion chips (Electricity, EMI, Rent, School, LIC, Recharge).
  - Date & Time selectors.
  - Optional amount (₹).
  - 3D tactile switch: *"Remind 3 days, 1 day & on day"*.
  - Recurrence selector (Once, Monthly, Yearly).
- **Edit Task Modal**: Update task title, category, date, time, amount, mark as completed, or delete.
- **Settings Screen**:
  - Profile card (Priya Sharma).
  - Free usage meters with neon slider tracks (Tasks 17/20, Voice 4/5).
  - **Go Premium Card**: ₹49 / month offer with Razorpay upgrade button.
  - Push notifications and sound & vibration toggles.
  - Multi-language switcher (Hinglish, Hindi, English).

---

## 🚀 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed (version 18 or newer).

### Installation & Run

1. Clone or download this repository.
2. Open your terminal in the project folder and install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 16](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **Icons**: [Lucide React](https://lucide.dev/)

---

## 📂 Project Structure

```text
popup/
├── src/
│   ├── app/
│   │   ├── globals.css         # Tailwind & global styling
│   │   ├── layout.tsx          # Root layout & metadata
│   │   └── page.tsx            # App container & screen switcher
│   ├── components/
│   │   ├── AddTaskModal.tsx    # Add reminder bottom sheet & voice mic
│   │   ├── BottomNavBar.tsx    # Tactile bottom navigation bar
│   │   ├── EditTaskModal.tsx   # Edit/delete reminder modal
│   │   ├── HomeScreen.tsx      # Today / Upcoming / Done dashboard
│   │   ├── LoginScreen.tsx     # Welcome & authentication screen
│   │   ├── SettingsScreen.tsx  # Usage, premium plan & settings
│   │   └── TaskCard.tsx        # Neo-Tactile task card component
│   ├── constants/
│   │   └── dummyData.ts        # Mock tasks, category chips & options
│   └── types/
│       └── task.ts             # TypeScript definitions
├── package.json
├── tsconfig.json
└── README.md
```

---

## 📄 License

MIT License — Feel free to use and customize for your own projects!
