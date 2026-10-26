# RikyLab

La pagina di **rikylab.it** e **www.rikylab.it**: chi siamo («laboratorio di
idee»), le idee - FamilyDashboard, la casa su uno schermo, e BuildingDashboard,
il condominio in tasca (dal 26 ottobre 2026) - e il contatto info@rikylab.it.

Un file solo, `index.html`, statico: niente build, niente JavaScript. Stile
delle app di famiglia (scuro, Roboto Condensed da Google Fonts, i quattro
colori della famiglia come luci di fondo).

È una pagina pubblica: niente nomi, niente numeri, niente fotografie della
dashboard vera. Il disegno dello schermo è fatto in CSS.

## Dove sta

- **GitHub Pages**, da questo repository, ramo `main`, cartella `/`: un push
  ripubblica da solo. Il file `CNAME` dice il dominio (`rikylab.it`); `www` ci
  arriva con un redirect di GitHub. HTTPS con «Enforce HTTPS».
  Non Render: il piano del workspace ha due domini personalizzati in tutto, e
  li usano gia' familydashboard e familydash-mng (11 ottobre 2026).
- **Cloudflare** (dal 15 ottobre 2026; prima Register.it), zona DNS di
  `rikylab.it`: quattro record A del dominio nudo verso GitHub
  (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153) e
  `www` in CNAME verso `rikyvr81.github.io`. La posta di info@rikylab.it
  passa da Email Routing di Cloudflare. Gli altri sottodomini sono delle app,
  e non riguardano questa pagina.
- Il repository e' pubblico, perche' Pages gratuito lo vuole: i commit usano
  l'indirizzo anonimo di GitHub, non la mail personale.
