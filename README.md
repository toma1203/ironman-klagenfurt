# Road to Klagenfurt

Trening aplikacija za IRONMAN Kärnten-Klagenfurt, 13. lipnja 2027. Cilj: oko 12 sati.

- **Today:** današnji trening, provjera oporavka (puls u mirovanju, san, Body Battery) i usporedba jučerašnjeg treninga s planom.
- **Week:** treninzi po danima (odrađeno, djelomično, propušteno) i sati plivanja, bicikla i trčanja u odnosu na plan.
- **Plan:** svih 34 tjedna (Base, Build, Peak, Taper), od 19. 10. 2026.
- **Progress:** tjedni sati, disciplina laganog trčanja, najduži treninzi, puls u mirovanju i san.
- **Race & zones:** plan tempa za 12 sati, zone pulsa, FTP i CSS (unosiš ih nakon testova u 1. tjednu).

## Datoteke

| Datoteka | Sadržaj |
|---|---|
| `index.html` | Cijela aplikacija s planom treninga |
| `data.json` | Garmin aktivnosti i podaci o oporavku. Svako jutro u 7:50 ažurira ih zakazani zadatak u Claudeu. |

Dnevni check-in, FTP i rezultati testa plivanja spremaju se u preglednik na uređaju koji koristiš.

## Pokretanje

Aplikacija radi preko GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.
Lokalno: `python3 -m http.server` u ovoj mapi, pa otvori `http://localhost:8000`. Dvoklik na `index.html` ne radi, jer preglednik tada ne učita `data.json`.
