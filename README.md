# Dyspraktik.cz

Jednoduchý statický český rozcestník o vývojové poruše koordinace (DCD).

## Nasazení na GitHub Pages

1. Nahrajte všechny soubory z archivu do **kořene** repozitáře.
2. V **Settings → Pages** vyberte **Deploy from a branch**, větev `main`, složku `/ (root)`.
3. Při použití vlastní domény nastavte DNS podle dokumentace GitHub Pages a doménu zadejte v **Settings → Pages → Custom domain**.
4. **Pozor:** `sitemap.xml`, `robots.txt` a kanonické URL v HTML jsou nastavené na `https://dyspraktik.cz/`. Pokud se doména liší, nahraďte ji všude skutečnou doménou.
5. Až bude vlastní doména potvrzená a fungovat přes HTTPS, lze přidat soubor `CNAME` obsahující samotnou doménu. Není zde přiložen, aby omylem nepřesměroval existující web.

## Soubory

- `index.html`: O dyspraxii
- `napsali.html`: Média, odborné články a knihy
- `organizace.html`: Organizace a odborníci
- `o-projektu.html`: O projektu
- `style.css`: sdílený vzhled
- `favicon.svg`: ikona webu
- `sitemap.xml`, `robots.txt`: podklady pro vyhledávače
- `404.html`: chybová stránka

Web nepoužívá JavaScript, externí fonty ani analytické cookies. Odkazy a bibliografická metadata vyžadují průběžnou redakční kontrolu.
