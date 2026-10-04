# Sanjeevani HIMS

A modern, responsive Hospital Information Management System MVP for hospital client demonstrations.

## Live demo

https://sanjeevani-careflow-hims.yogita-06.chatgpt.site

Demo credentials:

- Email: `admin@hospital.com`
- Password: `admin123`

The role selector can be used to preview Admin, Receptionist, Doctor, Lab Technician, Radiologist, Pharmacist, Cashier and Store Manager access.

## Included modules

- Patient registration and patient records
- Laboratory orders and result entry
- Radiology orders and reporting
- Pharmacy inventory
- OPD and IPD pharmacy workflows
- Department indent management
- Fixed Asset Register
- Cash billing and collections
- Operational reports and audit history
- User, doctor and department administration

The seeded Raj Patel journey demonstrates a connected workflow from registration through CBC, chest X-ray, medicine issue and a combined ₹1,320 bill.

## Run locally

Requirements: Node.js 22.13 or newer.

```powershell
corepack enable
pnpm install
pnpm run dev
```

Open the local URL printed by the development server, normally `http://localhost:5173`.

Create a production build with:

```powershell
pnpm run build
```

## Technology

Next.js, React, TypeScript, Tailwind CSS, shadcn/ui, Lucide Icons and Vinext/Cloudflare Workers.

## Demo notice

This repository is an MVP demonstration, not production-ready healthcare software. All patient and clinical information is fictional. It must not be used for medical diagnosis, treatment decisions or real patient records.
