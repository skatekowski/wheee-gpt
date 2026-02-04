# wheee-gpt

**Ein ChatGPT-Assistent für Produktdesign und UI-Design** – für Projekte, die mit dem WHEEE-Protokoll arbeiten. Du richtest ihn einmal ein und nutzt ihn danach nur über den Chat: Nachrichten schreiben, Dateien hochladen, Prototypen oder Dokumente anfordern. **Kein Programmieren, keine technischen Tools.**

**Repo:** [github.com/skatekowski/wheee-gpt](https://github.com/skatekowski/wheee-gpt)

---

## Für Designer:innen – in Kürze

- **Was ist das?** Anleitung, um in ChatGPT einen **eigenen Assistenten** („Produktdesign-Begleiter“) anzulegen. Der Assistent spricht deine Sprache (UX/UI-Fachbegriffe), begleitet dich bei Discovery, Design-System, Prototyping und Handoff.
- **Was brauchst du?** Einen ChatGPT-Account (z. B. Plus), um einen „Custom GPT“ zu erstellen. Zugang zu deinen Projektdateien oder zu kurzen Text-Ausgaben aus dem Projekt (z. B. Projektstand, Plan) – je nachdem, was dein Team nutzt.
- **Was brauchst du nicht?** Keine Programmierung, keine API, keine Entwicklungsumgebung. Alles läuft über den Chat.

---

## So richtest du den Begleiter ein (Schritt für Schritt)

1. **ChatGPT öffnen** und oben auf **Explore** gehen, dann **Create a GPT** wählen.  
   *(Das ist die Funktion, mit der man einen eigenen Assistenten mit festen Regeln und Stil anlegt.)*

2. **Name eingeben:** z. B. **WHEEE Produktdesign-Begleiter**.  
   Die genaue Bezeichnung und eine Kurzbeschreibung stehen in der Datei [Protokoll-GPT-UX-UI.md](Protokoll-GPT-UX-UI.md) unter „1. Name & Kurzbeschreibung“ – diese kannst du kopieren.

3. **Instructions einfügen:** In derselben Datei [Protokoll-GPT-UX-UI.md](Protokoll-GPT-UX-UI.md) den **gesamten Abschnitt „2. Instructions“** markieren und kopieren (inkl. der Zeilen zwischen den \`\`\`). Diesen Text in das Feld **Instructions** beim Create-a-GPT-Dialog einfügen.  
   *(Instructions = die Regeln und die „Rolle“, die dein Assistent im Chat einnimmt.)*

4. **Conversation Starters (optional):** In Abschnitt „3. Conversation Starters“ der gleichen Datei findest du Vorschläge für Startfragen. Du kannst einige davon in ChatGPT unter „Conversation starters“ eintragen – dann hat der Assistent von Anfang an passende Einstiege.

5. **Fertig.** Keine „Actions“, keine API, kein Code. Der Assistent arbeitet nur über den Chat.

---

## So nutzt du den Begleiter

- **Im Chat schreiben:** Du beschreibst, was du brauchst (z. B. „Erstelle einen Prototyp für die Startseite“ oder „Fasse die Design-Entscheidungen aus dem Journal zusammen“).
- **Dateien hochladen:** Du kannst Projektdateien (z. B. Process Journal, Projektstand) in den Chat hochladen – der Begleiter wertet sie aus und antwortet darauf.
- **Text einfügen:** Wenn jemand in deinem Team dir eine Text-Ausgabe aus dem Projekt gibt (z. B. „Projektstand“ oder „Abhängigkeiten für Komponente X“), kannst du sie in den Chat einfügen und den Begleiter bitten, sie zu erklären oder nächste Schritte vorzuschlagen.
- **Dateien anfordern:** Du kannst den Begleiter bitten, dir etwas **zum Download** oder zum **Copy-Paste** zu liefern: z. B. einen klickbaren Prototyp (HTML), eine Design-Spec, einen Style Guide, eine Kontext-Datei für einen neuen Chat. Er erklärt dir, wie du die Datei speicherst oder einfügst.

**Du lädst keine Apps, du programmierst nichts** – alles über Nachrichten, Upload und Download/Copy-Paste.

---

## Was du in diesem Repo findest

| Datei | Wofür? |
|-------|--------|
| [Protokoll-GPT-UX-UI.md](Protokoll-GPT-UX-UI.md) | **Anleitung für den Produktdesign-Begleiter.** Enthält Name, Kurzbeschreibung, die kompletten Instructions zum Kopieren und Vorschläge für Startfragen. Alles, was du brauchst, um den Assistenten in ChatGPT anzulegen. |
| [chat-kontext-vorlage.md](chat-kontext-vorlage.md) | **Vorlage für einen neuen Chat.** Wenn du einen neuen Chat startest, kannst du diese Vorlage ausfüllen (oder vom Begleiter ausfüllen lassen) und den Inhalt im neuen Chat hochladen oder einfügen – dann hat der Assistent sofort den richtigen Kontext (Projekt, Phase, letzte Entscheidungen, offene Punkte). |

---

## Was der Begleiter kann (ohne Technik-Kenntnisse)

- **Prototyp:** Auf Wunsch eine **Datei zum Download** (eine klickbare Webseiten-Vorschau) oder Text zum Copy-Paste. Geeignet für einzelne Screens, Navigation, Layout, Typo und Farben. Export für **Figma** (kein Pencil).
- **Dokumentation & Planung:** Auf Wunsch **Dateien zum Download** oder Text zum Copy-Paste: z. B. Eintrag fürs Process Journal, Projektstand, Plan-Skizze, **Style Guide**, **UI-Spec** (Farbsystem, Typo, Abstände), Komponenten-Dokumentation, Barrierefreiheits-Checkliste. Der Begleiter nennt dir immer den vorgeschlagenen Dateinamen und Ordner (z. B. `architecture/`, `docs/`).
- **Kontext für den nächsten Chat:** Eine **kurze Kontext-Datei** (Download oder Copy-Paste) mit Projektname, Phase, letzten Entscheidungen und offenen Punkten. Beim Start eines neuen Chats lädst du die Datei hoch oder fügst den Text ein – der neue Chat hat sofort den richtigen Kontext.

---

## Was ist WHEEE? (Hintergrund)

**WHEEE** ist ein **Arbeits- und Planungsprotokoll** für Software-Projekte. Es legt fest, wie geplant, designt und umgesetzt wird – mit klaren Phasen, Ordnern und Abläufen. **Mode D (Design)** ist der Modus für Produktdesign und UI-Design: Discovery, Prototyping, Design-System, Validierung und Übergabe (Handoff) an die Umsetzung.

Wenn dein Projekt mit WHEEE arbeitet, gibt es z. B. Planungsordner (`.planning/`, `project/`, `architecture/`) und einheitliche Abläufe. Der **Produktdesign-Begleiter** kennt diese Struktur und spricht die gleiche Sprache (User Flows, Design Tokens, Style Guide, Usability-Validierung, Handoff).  
Technische Details: [WHEEE Protocol](https://github.com/wheee-protocol).

---

## Credits

- **[Get Shit Done (GSD)](https://github.com/glittercowboy/get-shit-done)** – Light-weight meta-prompting, context engineering und spec-driven development (Claude Code, OpenCode, Gemini CLI). WHEEE baut auf GSD-Methodik auf.
- **[Boris Cherny – How I use Claude Code](https://threadreaderapp.com/thread/2007179832300581177.html)** – Thread mit Setup und Tipps vom Creator von Claude Code (Plan mode, Slash Commands, Verification).
- **[Boris Cherny auf X](https://x.com/bcherny/status/2017742741636321619)** – Weitere Tipps vom Claude-Code-Team (Parallel Sessions, Plan-first, Verification).

---

## Lizenz

**MIT-Lizenz** – dieses Repo ist Open Source. Siehe [LICENSE](LICENSE).
