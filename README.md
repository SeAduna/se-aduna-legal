# Pagini pregătite pentru publicare — Politica de confidențialitate & Termeni (Se Adună)

Acest folder conține versiuni HTML statice, autonome (fără JavaScript, fără CSS extern, fără font-uri externe, fără orice fel de script de analytics/tracking), generate din documentele Markdown din `legal/`:

- `privacy-policy.html` ← din `legal/POLITICA_DE_CONFIDENTIALITATE.md`
- `terms.html` ← din `legal/TERMENI_SI_CONDITII.md`
- `financial-disclaimer.html` ← din `legal/DECLARATIE_EXONERARE_FINANCIARA.md`
- `index.html` — pagină simplă cu linkuri către cele trei de mai sus

## Ce NU s-a făcut

- **Publicate (Etapa 4)** la https://seaduna.github.io/se-aduna-legal/ — repository GitHub `SeAduna/se-aduna-legal`.
- **Nu a fost cumpărat niciun domeniu.**
- **Nu a fost creat niciun cont extern** (GitHub, Cloudflare, Netlify, Google, etc.).
- **Nu a fost inventată nicio informație.** Numele operatorului (Alexandru Dan) și e-mailul de contact (contimac2024@gmail.com) au fost furnizate de utilizator (Etapa 5) și introduse. Adresa poștală rămâne intenționat nepublicată (minimizare a datelor). Data publicării rămâne `USER INPUT REQUIRED`.
- **Nu au fost eliminate marcajele `REQUIRES LEGAL REVIEW`** — apar vizibil, într-un chenar albastru, exact ca în documentele Markdown sursă.

## Sursa de adevăr rămâne Markdown-ul

Aceste pagini HTML sunt o **conversie fidelă**, pregătită pentru cazul în care alegi să publici documentele static. Dacă modifici conținutul juridic, modifică întâi fișierul `.md` corespunzător din `legal/`, apoi regenerează (sau cere-mi să regenerez) pagina HTML — nu edita doar HTML-ul, ca să nu diverjeze cele două versiuni.

## Înainte de publicare reală

1. Completează, în cele trei fișiere HTML, toate câmpurile marcate `USER INPUT REQUIRED` (nume operator, adresă, e-mail, dată).
2. Decide dacă vrei confirmare juridică pentru punctele marcate `REQUIRES LEGAL REVIEW` înainte sau după publicarea inițială (poți publica și cu ele vizibile ca note, dar ideal sunt rezolvate înainte).
3. Alege o metodă de hosting (vezi opțiunile propuse separat, în raportul de etapă) — nu a fost aleasă niciuna automat.
4. Abia după ce URL-urile sunt live, le poți folosi în App Store Connect / Google Play Console.

## Ce NU e acest folder

Nu este un site „webapp" al aplicației și nu are nicio legătură cu `webapp/`, care rămâne FROZEN și neatins. Acesta e strict un set de pagini statice pentru documentele juridice, independent de restul proiectului.
