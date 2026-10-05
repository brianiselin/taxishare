OUR CAB — HOSTINGER PROTOTYPE

This is the quick prototype version for the four-person team to test.

HOSTINGER INSTALL
1. Create the subdomain: taxishare.brianiselin.com
2. Set its document root to a new folder.
3. Upload ALL contents of this package into that folder.
4. Make sure SSL/HTTPS is enabled.
5. Open https://taxishare.brianiselin.com/

IMPORTANT FILE-FORMAT SAFEGUARD
The entry point is INDEX.HTML — not INDEX.HTM.
Do not rename it. The package contains no .htm entry point.
All paths are relative, so it is safe to deploy at a subdomain.

WHAT THIS PROTOTYPE TESTS
- Home/dashboard concept
- Book the car
- Booking conflict / override interaction
- Upcoming bookings
- Car location
- Team messages
- Mobile-first layout
- PWA manifest and service worker

IMPORTANT LIMITATION
This is a prototype, not yet a live shared database application. The demo data and changes are held in the browser/front-end, so changes made on one phone are not automatically shared with the other phones.

That is deliberate: this version is for the team to test the workflow and interface quickly. Once everyone agrees the concept works, the next build can add shared login, live bookings, recurring schedules, real-time notifications and a shared database.
