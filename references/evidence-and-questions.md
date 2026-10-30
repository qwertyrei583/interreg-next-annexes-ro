# Probe și întrebări

Păstrează în dosarul rezultatelor un registru (CSV UTF-8 sau Markdown), pentru a continua după răspunsul utilizatorului fără pierderea contextului.

Pentru fiecare probă: ID E-001; cale; denumire; număr; dată; sumă/monedă/TVA; proiect/partener/perioadă; procedură/contract/cheltuială; pagină sau tabel; semnătură/aprobare; puncte asociate; ce anume este confirmat. Distinge originalul, copia, scanarea, exportul și mesajul utilizatorului. Verifică pe imagine elementele importante extrase prin OCR; nu ghici textul ilizibil.

Pentru fiecare întrebare: ID Q-001; anexă/punct; achiziție/cheltuială; document/fapt lipsă; întrebare; motivul solicitării; data solicitării; răspuns; statut (`awaiting-user`, `unavailable`, `answered-needs-check`, `resolved`); impact asupra concluziei; E-ID asociate. Dacă privește mai multe câmpuri, enumeră-le pe toate.

| Situație | Acțiune |
|---|---|
| Cerință confirmată prin probe | Yes/No potrivit sensului întrebării, probe în Comments |
| Nerespectare confirmată | Răspuns potrivit sensului întrebării, abaterea și norma |
| Neaplicabilitate stabilită | N.A. cu motiv și temei |
| Date încă lipsă | Întrebare către utilizator, amânarea concluziei dependente |
| Utilizatorul confirmă imposibilitatea furnizării | Indicator OPEN Q-ID în câmp și Comments, includere în sinteză |

Exemplu Comments (date fictive, nu le prelua în proiect):

`Available documents: (1) Service contract No. 17 dated 12.03.2025 — MDL 180,000.00, excluding VAT; (2) Acceptance certificate No. 8 dated 30.04.2025 — MDL 180,000.00, excluding VAT; (3) Payment order No. 245 dated 06.05.2025 — MDL 180,000.00. Procurement PR-003. [E-014–E-016].`

Sumele contractului, actului de recepție și plății pot diferi: verifică recepțiile parțiale, avansurile, TVA și plățile multiple; nu le egaliza artificial. Pentru ordin: `Appointment order No. … dated …; Amount: not applicable.` Pentru un document într-adevăr nenumerotat: `unnumbered`; pentru un număr care nu poate fi văzut: `number not established` și o întrebare dacă este esențial.

## Solicitări în funcție de necesitate

Verifică întâi dosarul, apoi solicită doar documentele relevante:

- Contractul de grant/modificări/anexe, cererea de finanțare și bugetul, acordul de parteneriat; statutul partenerului și regimul achizițiilor.
- Raportul partenerului și lista cheltuielilor, exporturile Jems, rapoarte/liste de verificare ale controalelor anterioare, metodologia de eșantionare.
- Contracte, facturi, acte de recepție/documente de livrare, plăți/extrase, registre contabile, informații despre TVA/cofinanțare.
- Salarii: documente de muncă/numiri, calcule, state/fluturași de salariu, ore/fișe de pontaj, impozite/plăți în funcție de metoda de calcul al costurilor.
- Deplasări: ordin, legătura cu proiectul, invitație/program/participare, transport/cazare, diurnă, raport/rambursare conform regulilor aplicabile.
- Achiziții: valoarea estimată, documentele procedurii, publicări/invitații/termene, oferte/clarificări, comisie/declarații, evaluare/decizie/notificări, contract/modificări, recepție/plăți. Nu solicita fără justificare documente neobligatorii pentru procedura stabilită.
- Echipamente/lucrări: inventariere, livrare/punere în funcțiune, autorizații/documentație tehnică, recepție și probe de vizibilitate, după caz.

Nu înlocui tacit documentul cu un mesaj: distinge `document verified` de `reported by the user; supporting evidence not provided`.
