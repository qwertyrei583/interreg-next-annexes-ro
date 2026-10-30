# Interreg NEXT — Română

Abilitate (skill) pentru Codex care pregătește anexele de control **4.1, 4.2 și 4.3** pentru proiectele **Interreg NEXT România – Republica Moldova**.

Comunicarea, clarificările și sintezele sunt în română. Anexele se completează implicit în engleză, păstrând denumirile oficiale și datele documentelor în limba originală. Limba poate fi schimbată la cerere.

## Conținut

- `SKILL.md` — instrucțiunile agentului în română.
- `agents/openai.yaml` — numele, descrierea și promptul de pornire.
- `references/` — regulile privind probele, întrebările și aplicabilitatea surselor.
- `assets/` — cele trei șabloane DOCX de control.

## Instalare în Codex

Clonează acest depozit în directorul de abilități Codex. Dacă folosești o locație personalizată prin `CODEX_HOME`, utilizează directorul `skills` din acea locație.

Windows PowerShell, pentru locația implicită:

```powershell
git clone https://github.com/qwertyrei583/interreg-next-annexes-ro.git "$HOME\.codex\skills\interreg-next-annexes-ro"
```

macOS / Linux, pentru locația implicită:

```bash
git clone https://github.com/qwertyrei583/interreg-next-annexes-ro.git ~/.codex/skills/interreg-next-annexes-ro
```

Dacă abilitatea este deja instalată, păstrează o copie a modificărilor locale înainte de a o înlocui sau actualiza.

## Ghid pentru utilizator

Citiți [ghidul de utilizare](references/user-guide.md): mesajul de bun venit, cum transmiteți documentele, ce informații indicați la început, documentele utile și un exemplu de prim mesaj.

Puteți încărca documentele direct în chat, trimite un link către un dosar accesibil printr-o aplicație conectată sau indica o cale locală într-un mediu cu acces la fișiere. Linkul singur nu acordă acces; dosarul nu trebuie făcut public. Puteți începe cu documentele disponibile, fără un set complet.

## Utilizare

Invocă abilitatea și indică dosarul documentelor, proiectul, partenerul și perioada de raportare, în măsura în care aceste informații sunt disponibile:

```text
Folosește $interreg-next-annexes-ro pentru a pregăti anexele de control
pentru proiectul [ID], partenerul [nume], perioada [perioadă].
Documentele se află în [cale]. Comunică în română.
```

Agentul examinează întâi documentele disponibile și solicită informațiile lipsă. Rezultatul include anexele DOCX aplicabile, sinteza întrebărilor deschise și registrul probelor și al bazei juridice.

## Reguli esențiale

- Annex 4.1 se completează întotdeauna.
- Conform instrucțiunilor acestei abilități, valoarea estimată fără TVA de peste 20 000 EUR conduce la Annex 4.2; intervalul 2 500–20 000 EUR inclusiv conduce la Annex 4.3. Aplicabilitatea regimului de achiziții și cazul exact de 2 500 EUR trebuie verificate potrivit instrucțiunilor detaliate.
- Datele precompletate din șabloane sunt exemple, nu probe pentru un proiect nou.
- Normele și versiunile aplicabile se verifică pentru fiecare proiect și procedură.
- Documentele pregătite necesită verificarea controlorului. Agentul nu semnează și nu încarcă rezultatele în Jems fără o însărcinare separată.

Acest depozit conține abilitatea și șabloanele sale, fără dosare de proiect, documente justificative sau rezultate ale verificărilor.
