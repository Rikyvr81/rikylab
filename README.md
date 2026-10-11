# RikyLab

La pagina di **rikylab.it** e **www.rikylab.it**: chi siamo («laboratorio di
idee»), FamilyDashboard come una delle idee, e il contatto info@rikylab.it.

Un file solo, `index.html`, statico: niente build, niente JavaScript. Stile
delle app di famiglia (scuro, Roboto Condensed da Google Fonts, i quattro
colori della famiglia come luci di fondo).

È una pagina pubblica: niente nomi, niente numeri, niente fotografie della
dashboard vera. Il disegno dello schermo è fatto in CSS.

## Dove sta

- **Render**, Static Site `rikylab-static-page`
  (https://rikylab-static-page.onrender.com), collegato a questo repository,
  ramo `main`, Publish Directory `./`, nessun comando di build: un push
  ripubblica da solo.
- **Register.it**, zona DNS di `rikylab.it`: un record A per il dominio nudo
  verso l'IP che Render indica in «Custom Domains», e `www` in CNAME verso
  `rikylab-static-page.onrender.com`. I record MX della posta (info@rikylab.it)
  restano quelli di Register.it. Il certificato HTTPS lo fa Render.
