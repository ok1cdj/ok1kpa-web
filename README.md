# OK1KPA — Radioklub Pardubice

Landing page radioklubu OK1KPA. Statická stránka bez frameworku a bez buildu — jeden `index.html` + obrázky.

## Obsah

- `index.html` — celá stránka (CZ/EN přepínatelné vlaječkou)
- `images/` — fotky (tým, shack, antény, dron záběr táboru)
- víc fotek ze závodů na blogu [prdec.cz](https://prdec.cz)

## Nasazení (GitHub Pages)

1. V nastavení repa: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**
2. Stránka pak poběží na `https://ok1cdj.github.io/ok1kpa-web/`
3. Pro vlastní doménu (např. `ok1kpa.cz` nebo `spalava.ok1cdj.com`) přidej soubor `CNAME` s doménou a nastav DNS (CNAME záznam na `ok1cdj.github.io`).

## Editace

Vše je v jednom `index.html` — CSS v `<style>`, JS pro přepínání jazyka na konci souboru. Fotky do sekce galerie stačí přidat jako další `.photo-card` blok s `<img>`.

## Odkazy

- Vyhodnocení provozního aktivu VKV: https://vkvpa.hamradio.cz/
- Blog se staršími závody: https://prdec.cz
