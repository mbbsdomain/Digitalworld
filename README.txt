MBBS Engineering Tools — Version 1
====================================

Deployment to InfinityFree
1. Extract this ZIP on your computer.
2. Log in to your InfinityFree control panel.
3. Open the File Manager for the hosting account and open the public web directory (commonly htdocs).
4. Upload the CONTENTS of this folder into that directory. Do not upload the outer MBBS_Website_V1 folder itself.
5. Confirm index.html is directly inside the public web directory.
6. Confirm these folders are also directly inside it:
   css/
   js/
   assets/
   apps/proposal/
7. Open your domain in a browser and test:
   Home -> Applications -> EIL Proposal Management Tool

Important:
- The existing bbs15.html application is copied unchanged into apps/proposal/.
- The existing application's own login is client-side; it should not be treated as strong internet-facing security.
- The portal is designed so Python web applications can be added later through a separate hosted service/subdomain/link.
