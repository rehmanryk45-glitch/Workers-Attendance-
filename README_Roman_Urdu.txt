WORKERS ATTENDENCE — PWA INSTALLATION GUIDE (ROMAN URDU)

IMPORTANT: Purani Workers_Attendence.html file ko delete ya overwrite NA karein. Browser data clear na karein.

A. PURANI APP KA DATA SAFE KAREIN
1. Usi Windows PC aur usi Google Chrome mein purani Workers_Attendence.html open karein.
2. Admin login karein.
3. Backup / Restore tab kholein.
4. Download Full Backup par click karein.
5. Workers_Attendence_Backup.json ko Documents mein save karein aur ek extra copy USB/secure folder mein rakhein.
6. Agar backup button kaam na kare, purani app ko band/delete/reset na karein. Pehle madad lein.

B. PWA FILES HOST KAREIN (FREE GITHUB PAGES)
1. Is ZIP ko Windows par right-click > Extract All karein.
2. https://github.com par login/create account karein.
3. New repository banayein, naam: workers-attendence. Public repository mein app ka source code public ho sakta hai. Is package mein attendance data GitHub par upload nahi hota.
4. Repository ke root mein ye files upload karein: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
5. Repository > Settings > Pages kholein.
6. Build and deployment > Source: Deploy from a branch select karein.
7. Branch: main aur folder: /(root) select karke Save karein.
8. GitHub Pages ka HTTPS link banne par usay Chrome mein open karein.

C. INSTALLABLE APP BANAYEIN
Windows Chrome/Edge:
1. HTTPS website open karein.
2. Browser menu mein Install page as app / Install Workers Attendence select karein.
3. App Start Menu ya desktop se open ki ja sakti hai.

Android Chrome:
1. HTTPS link open karein.
2. Three dots > Install app ya Add to Home screen select karein.

D. PURANA DATA NAYI PWA MEIN IMPORT KAREIN
1. Nayi PWA open karein. Agar pehli dafa hai to temporary Admin account banayein aur login karein.
2. Backup / Restore tab kholein.
3. Restore Backup JSON select karein.
4. Purani app se banayi hui Workers_Attendence_Backup.json file select karein.
5. Confirmation accept karein. Restore current PWA data replace karega aur imported Admin/worker/attendance records load karega.
6. Dobara login ki zaroorat ho to backup mein maujood Admin username/password use karein.
7. Restore verify karne ke baad foran naya Download Full Backup banayein.

E. DATA AUR PRIVACY KI ZAROORI BAATEIN
- Data is PWA ke local browser storage mein save hota hai. App data automatically online database mein upload nahi hota.
- Data sirf isi browser profile aur isi website address/origin par hota hai. Doosre PC/mobile par automatically share nahi hota.
- Chrome ka site data clear karne, browser profile delete hone, ya device kharab hone par data lose ho sakta hai. Regular JSON backups zaroor banayein.
- Website ka source code public ho sakta hai. Is version ko high-security production system na samjhein; password browser storage mein rakha jata hai. Sensitive company data ke liye secure server/database wali app behtar hai.
- PWA ko install karne ke liye GitHub Pages jaisi HTTPS hosting chahiye. File ko double-click karke kholna installable PWA ka poora experience nahi deta.
