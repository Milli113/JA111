# JA111 – Budakeszi, József Attila utca 111.

Statikus weboldal (HTML + képek + videó), build lépés nélkül.

## Feltöltés GitHub Pagesre
1. Hozz létre egy új repót a GitHubon (pl. `ja111-web`).
2. Töltsd fel a mappa teljes tartalmát a repó gyökerébe (`index.html`, `img/`, `video/`, `.nojekyll`).
3. Settings → Pages → Source: *Deploy from a branch*, Branch: `main`, mappa: `/ (root)` → Save.
4. Pár perc múlva elérhető: `https://<felhasználónév>.github.io/ja111-web/`

## Saját domain (ja111.hu)
Settings → Pages → Custom domain: `ja111.hu`, majd a domain DNS-ében:
- `A` rekordok: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- vagy `www` → `CNAME` → `<felhasználónév>.github.io`

## Szerkezet
- `index.html` – az egész oldal (stílus és script is benne)
- `img/` – látványtervek, helyszínrajz, kivilágítási rétegek, alaprajzok (`img/plans/`)
- `video/` – nyitófilm (1080p asztalra, 720p mobilra)

Az oldalon található alaprajzok, látványtervek és adatok tájékoztató jellegűek.
