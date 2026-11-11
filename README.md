# Snake II

Klasična zmija u stilu starog mobitela. Radi u pregledniku, a može se instalirati na mobitel kao aplikacija (PWA) i igrati bez interneta.

## Objava na GitHub Pages (GitHub Desktop)

1. **File → Add local repository…** → odaberi ovu mapu. Kad javi da to nije repozitorij, klikni **create a repository** → **Create repository**.
2. **Publish repository**. Makni kvačicu *Keep this code private* (Pages je besplatan samo za javne repozitorije).
3. Na github.com otvori repozitorij → **Settings → Pages** → *Source: Deploy from a branch* → *Branch: `main`*, mapa `/ (root)` → **Save**.
4. Nakon 1–2 minute igra je na `https://<korisnicko-ime>.github.io/<ime-repozitorija>/`.

## Instalacija na mobitel

- **Android (Chrome):** otvori adresu → izbornik ⋮ → **Instaliraj aplikaciju** / **Dodaj na početni zaslon**.
- **iPhone (Safari):** otvori adresu → gumb Dijeli → **Dodaj na početni zaslon**.

## Ažuriranje

Nakon izmjene datoteka povećaj `VERSION` u `sw.js` (npr. `snake-v2`), zatim u GitHub Desktopu **Commit** → **Push origin**. Instalirana aplikacija preuzme novu verziju pri sljedećem pokretanju (ponekad tek pri drugom).
