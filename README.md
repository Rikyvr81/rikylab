# RikyLab

La pagina di **rikylab.it** e **www.rikylab.it**: chi siamo («laboratorio di
idee»), FamilyDashboard come una delle idee, e il contatto info@rikylab.it.

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
- **Register.it**, zona DNS di `rikylab.it`: quattro record A del dominio nudo
  verso GitHub (185.199.108.153, 185.199.109.153, 185.199.110.153,
  185.199.111.153) e `www` in CNAME verso `rikyvr81.github.io`. I record MX
  della posta (info@rikylab.it, `mail.register.it`) restano come sono.
- Il repository e' pubblico, perche' Pages gratuito lo vuole: i commit usano
  l'indirizzo anonimo di GitHub, non la mail personale.
