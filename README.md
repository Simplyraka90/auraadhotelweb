# AURELIA GRAND — Cinematic Emerald Edition

Premium responsive Next.js 15 / React 19 / TypeScript / Tailwind / React Three Fiber hotel demo.

## Run

```bash
npm install
npm run dev
```

Visit `http://localhost:3000` and `http://localhost:3000/admin`.

Demo admin login: `rachixxx` / `rachuuu`.

## Included

Public pages: Home, About, Rooms, Room Details, Booking, Contact, Gallery, Facilities, Dining, Offers, FAQ, Terms, Privacy.

Admin demo: overview, add/edit/delete rooms, toggle availability, booking and enquiry status changes. Forms use browser `localStorage` and the admin session uses `sessionStorage`. All demo data is stored only on the same device/browser; it is not shared with customers on other devices.

The architectural WebGL model is procedural Three.js geometry, not a photorealistic GLB walkthrough. Photography is loaded from Unsplash and needs internet access.

**Security:** Hard-coded demo credentials are visible to visitors in browser-delivered JavaScript. This is not secure authentication. Do not deploy as a real booking or customer-data management service. For production, add backend, protected authentication and database.

## Build

```bash
npm run build
npm start
```
