# Dental Clinic Scheduler

A web-based scheduling system designed for a dental clinic to assign staff (Dental Assistants and Front Desk) to shifts (Morning, Afternoon, Evening) on a calendar view. Built to simplify and visualize the clinic's daily workforce planning.

## Features

- Interactive monthly calendar (with printing support)
- Employee setup page for adding/removing staff
- Smart validation:
  - Warns if no dental assistants are scheduled
  - Enforces at least 2 assistants for surgery shifts
- Local storage persistence (no backend required)
- Built with React, Vite, MUI, dayjs, and `react-big-calendar`

## Technologies Used

- **React** – component-based UI
- **Vite** – fast build tool
- **MUI (Material UI)** – design system for modern UI
- **dayjs** – lightweight date library
- **react-big-calendar** – calendar component
- **uuid** – unique IDs for employees
- **localStorage** – persist schedule and employee data

## How to Run Locally

1. Clone the repo:

```bash
git clone https://github.com/YOUR_USERNAME/dental-clinic-scheduler.git
cd dental-clinic-scheduler
```
Then install dependencies:
```bash
npm install
```
Start the development server:
```bash
npm run dev
```
Visit http://localhost:5173

## Motivation
This scheduler was built to help manage staff assignments at my mom's dental clinic. It aims to reduce miscommunication, ensure surgery readiness, and provide a printable daily view of assignments.

## Future Improvements
1. Admin login
2. Backend database integration
3. Mobile-friendly responsive layout


