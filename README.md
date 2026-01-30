# NoteHub (Next.js)

NoteHub is a simple note management application built with **Next.js (App Router)**.  
The app allows users to browse notes, search through them, view note details, and create new notes via a modal interface.

The project is an adaptation of a previous React application, refactored to use Next.js features such as server components, client components, dynamic routing, and layout-based architecture.

---

## 🚀 Features

- Notes list with pagination
- Search notes by keyword
- Note details page with dynamic routing
- Create a new note using a modal window
- Client-side data fetching with React Query
- Server-side prefetching and hydration
- Responsive layout with Header and Footer

---

## 🧱 Project Structure

- **app/**
  - `page.tsx` – Home page
  - `layout.tsx` – Root layout with Header, Footer, and providers
  - `loading.tsx` – Global loading state
  - `notes/`
    - `page.tsx` – Notes list page
    - `[id]/`
      - `page.tsx` – Note details page
      - `error.tsx` – Error boundary for note details
- **components/** – Reusable UI components
- **lib/** – API functions
- **types/** – TypeScript types
- **public/** – Static assets

---

## 🛠 Tech Stack

- **Next.js** (App Router)
- **TypeScript**
- **React**
- **TanStack Query (React Query)**
- **Axios**
- **CSS Modules**
- **Formik + Yup**

---

