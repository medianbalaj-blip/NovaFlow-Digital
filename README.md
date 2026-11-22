# NOVAFLOW DIGITAL — Website

Faqe statike (një skedar `index.html`, pa varësi dhe pa build).

## Publikimi në GitHub + Vercel
1. Krijo një repository të ri në GitHub (p.sh. `novaflow-website`).
2. Ngarko të gjithë përmbajtjen e këtij folderi (`index.html`, `vercel.json`, `README.md`).
3. Në vercel.com → Add New → Project → zgjidh repository-n → Deploy.
   (Framework Preset: Other. Build Command dhe Output Directory lëri bosh.)

## Ndryshime të shpejta
Në fund të `index.html`, te blloku `CONFIG`:
- `galaxyUrl`, `redrollUrl` — linqet e projekteve
- `email`, `instagram`, `whatsapp`, `facebook` — kontaktet
- `formEndpoint` — vendos një endpoint (p.sh. Formspree) që formulari të dërgojë direkt;
  nëse është bosh, formulari hap aplikacionin e email-it.
