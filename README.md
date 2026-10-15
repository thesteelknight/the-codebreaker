# The Codebreaker v2.2 — Fair Combat & Health

- Guard damage only within **2.55 world units**, when guard faces Ronin **and Ronin is at least roughly facing the guard**, with no obstacle between them.
- SENTINEL-X damage only within **3.25 units**, with the same face-to-face and obstacle checks. No more damage from far away.
- Guard hits: **7 HP** before blocking. SENTINEL-X hits: **11 HP** before blocking.
- Blocking reduces damage to **25%**. Dodging retains invulnerability.
- After a hit, Ronin has **1.35 seconds** of protection to prevent simultaneous enemies draining all HP.
- Guard attack intervals 1.55–2.10 seconds; Sentinel intervals 1.75–2.30 seconds. Enemies can still chase aggressively but do not damage until combat conditions are met.
- All v2.1 features, soundtrack, 15 floors, multiplayer prototype, phone, models, and collisions remain.

Run `npm install` then `npm start`; visit http://localhost:3000.

Note: these are simplified proximity and facing checks, not animation-frame-perfect hitboxes. Multiplayer combat is still client-local. JavaScript syntax checked; visual/browser gameplay has not been tested.
