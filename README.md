# DMI Admitere 2026 — GitHub Pages

## Publicare

1. Creează pe contul personal un repository public, de exemplu `dmi-admitere-2026`.
2. Încarcă în rădăcina repository-ului toate fișierele din acest pachet.
3. Deschide `Settings → Pages` și alege `GitHub Actions` la `Source`.
4. Deschide fila `Actions` și urmărește rularea `Deploy GitHub Pages`.
5. După finalizare, adresa va fi `https://NUME-CONT.github.io/dmi-admitere-2026/`.

## Încărcare din terminal

```bash
git init
git add .
git commit -m "Publicare dashboard admitere"
git branch -M main
git remote add origin https://github.com/NUME-CONT/dmi-admitere-2026.git
git push -u origin main
```

Progresul checklisturilor și valorile editate sunt păstrate în `localStorage`, separat pentru fiecare browser și dispozitiv.
