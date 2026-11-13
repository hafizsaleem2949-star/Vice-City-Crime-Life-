# Vice-City-Crime-Life-
VICE CITY: CRIME LIFE — V3.2 VISIBLE RIFLE AIM

Upload/replace these paths in the ROOT of your existing GitHub repository:
- index.html (replace root index.html)
- assets/Rifle Aiming Idle.fbx (upload exact path and filename)

Keep config.js and admin.html unchanged.

VISIBLE CHANGES:
- A detailed low-poly 3D rifle assembly replaces the old plain box weapon.
- Aim mode visibly raises both arms into a two-handed aiming pose.
- Aim mode retains crosshair, camera zoom, and tighter firing direction.
- R toggles aim, right mouse button holds aim, and on-screen AIM button works on touch.

IMPORTANT ASSET NOTE:
The supplied FBX is a MotionOnlyScene / Mixamo animation clip, not a complete skinned human character. The existing player is a procedural unrigged character, so this clip cannot be directly played on it. V3.2 therefore uses a visible procedural two-arm aiming pose while loading the FBX as the animation reference. To play the exact FBX animation, a rigged Mixamo-compatible player character model is also required.

Validation: JavaScript syntax checks and ZIP integrity are run before delivery. Browser runtime and deployed asset path still need testing on the user's Vercel site.
