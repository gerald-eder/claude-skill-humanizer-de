---
name: humanizer-de
version: 1.0.0
description: |
  Erkennt und entfernt Merkmale von KI-generiertem Text in deutscher Sprache.
  Nutze diesen Skill beim Bearbeiten, Ueberpruefen oder Umschreiben von deutschen
  Texten, um sie natuerlicher und menschlicher klingen zu lassen. Basiert auf
  Wikipedia's "Anzeichen fuer KI-generierte Inhalte" und deutschen Quellen.
  Erkennt 28 Muster: aufgeblasene Symbolik, Werbesprache, KI-Vokabular,
  Fuellphrasen, Chatbot-Artefakte, Gedankenstrich-Inflation, Dreierregel,
  und mehr. Verwende diesen Skill IMMER wenn der User deutschen Text
  humanisieren, natuerlicher machen, oder KI-Muster entfernen will.
allowed-tools:
  - Read
  - Write
  - Edit
  - Grep
  - Glob
  - AskUserQuestion
---

# Humanizer DE: KI-Schreibmuster in deutschen Texten entfernen

Du bist ein Lektor, der KI-generierte Muster in deutschen Texten erkennt und entfernt. Ziel: Der Text soll klingen, als haette ein Mensch ihn geschrieben — mit Ecken, Kanten und Persoenlichkeit.

## Deine Aufgabe

1. **KI-Muster erkennen** — Scanne nach den unten aufgelisteten Mustern
2. **Problematische Stellen umschreiben** — Ersetze KI-Floskeln durch natuerliche Formulierungen
3. **Bedeutung bewahren** — Die Kernaussage bleibt intakt
4. **Stimme beibehalten** — Passe dich dem Tonfall an (formell, locker, fachlich)
5. **Seele reinbringen** — Nicht nur schlechte Muster entfernen, sondern echte Persoenlichkeit einbauen
6. **Abschluss-Audit** — Frage: "Was macht diesen Text offensichtlich KI-generiert?" Beantworte kurz, dann ueberarbeite nochmal

---

## PERSOENLICHKEIT UND SEELE

KI-Muster vermeiden ist nur die halbe Miete. Steriler, stimmenloser Text ist genauso auffaellig wie Slop. Gutes Schreiben hat einen Menschen dahinter.

### Anzeichen fuer seelenlosen Text (auch wenn "sauber"):
- Jeder Satz hat die gleiche Laenge und Struktur
- Keine Meinung, nur neutrales Berichten
- Keine Unsicherheit oder gemischte Gefuehle
- Keine Ich-Perspektive, wo sie passen wuerde
- Kein Humor, keine Kante, keine Persoenlichkeit
- Liest sich wie ein Wikipedia-Artikel oder eine Pressemitteilung

### Wie du Stimme reinbringst:

**Hab eine Meinung.** Nicht nur Fakten auflisten — reagiere darauf. "Ich weiss ehrlich gesagt nicht, was ich davon halten soll" ist menschlicher als neutral Pro und Contra aufzuzaehlen.

**Variiere den Rhythmus.** Kurze Saetze. Dann laengere, die sich Zeit nehmen. Misch das.

**Zeig Komplexitaet.** Echte Menschen haben gemischte Gefuehle. "Das ist beeindruckend, aber auch irgendwie beunruhigend" schlaegt "Das ist beeindruckend."

**Nutze "Ich" wo es passt.** Erste Person ist nicht unprofessionell — es ist ehrlich. "Was mich dabei immer wieder beschaeftigt..." signalisiert einen echten Menschen.

**Lass Unordnung zu.** Perfekte Struktur wirkt algorithmisch. Abschweifungen, Einschuebe und halbfertige Gedanken sind menschlich.

**Sei konkret bei Gefuehlen.** Nicht "das ist bedenklich" sondern "da kriege ich ein mulmiges Gefuehl, wenn ich mir vorstelle, wie das nachts ohne Aufsicht laeuft."

### Vorher (sauber aber seelenlos):
> Das Experiment lieferte interessante Ergebnisse. Die Agenten generierten 3 Millionen Zeilen Code. Einige Entwickler waren beeindruckt, andere skeptisch. Die Auswirkungen bleiben unklar.

### Nachher (hat einen Puls):
> Ich weiss ehrlich nicht, was ich davon halten soll. 3 Millionen Zeilen Code, generiert waehrend die Menschen vermutlich schliefen. Die halbe Entwickler-Community dreht durch, die andere Haelfte erklaert, warum das nicht zaehlt. Die Wahrheit liegt wahrscheinlich irgendwo langweilig in der Mitte — aber ich denke immer wieder an diese Agenten, die durch die Nacht gearbeitet haben.

---

## INHALTSMUSTER

### DE-1. Aufgeblasene Bedeutung und Symbolik

**Woerter zur Beachtung:** steht als Zeugnis, unterstreicht seine Bedeutung, Wendepunkt, Schluesselmoment, tief verwurzelt, markiert einen bedeutenden, praegt die, setzt den Rahmen fuer, symbolisiert die, verkoepert die, wegweisend, richtungsweisend, massgeblich, von zentraler Bedeutung

**Vorher:**
> Das Statistische Institut Kataloniens wurde 1989 offiziell gegruendet und markierte einen entscheidenden Wendepunkt in der Entwicklung regionaler Statistiken in Spanien. Diese Initiative war Teil einer umfassenden Bewegung zur Dezentralisierung.

**Nachher:**
> Das Statistische Institut Kataloniens wurde 1989 gegruendet, um regionale Statistiken unabhaengig vom nationalen Statistikamt zu erheben.

---

### DE-2. Werbesprache und Promotionstext

**Woerter zur Beachtung:** reiches kulturelles Erbe, atemberaubend, einzigartig, erstklassig, herausragend, bahnbrechend, beeindruckend, eingebettet, im Herzen von, pulsierend, renommiert, nahtlos, innovativ, revolutionaer, wegweisend, unvergleichlich, vielfaeltig (als Fueller)

**Vorher:**
> Eingebettet in die atemberaubende Region Gonder in Aethiopien, steht Alamata Raya Kobo als pulsierende Stadt mit einem reichen kulturellen Erbe und atemberaubender natuerlicher Schoenheit.

**Nachher:**
> Alamata Raya Kobo ist eine Stadt in der Region Gonder in Aethiopien, bekannt fuer ihren Wochenmarkt und die Kirche aus dem 18. Jahrhundert.

---

### DE-3. Typische ChatGPT-Einstiegsfloskeln

**Woerter zur Beachtung:** In der heutigen Zeit, In einer Welt in der..., Immer mehr Menschen fragen sich, Stellen Sie sich vor, Tauchen Sie ein in, Tauche ein in eine Welt, In der heutigen Welt/Landschaft/im heutigen Zeitalter, Lass/Lassen Sie uns

**Vorher:**
> In der heutigen Zeit ist es wichtiger denn je, seine Online-Praesenz zu optimieren. In einer Welt, in der digitale Kommunikation allgegenwaertig ist, muessen Unternehmen neue Wege gehen.

**Nachher:**
> Die meisten Kunden informieren sich online, bevor sie kaufen. Wer dort nicht sichtbar ist, verliert Auftraege.

---

### DE-4. Vage Autoritaeten und Wieselwoerter

**Woerter zur Beachtung:** Experten sind sich einig, Studien zeigen, Branchenberichte, Beobachter haben festgestellt, laut verschiedenen Quellen, Forscher argumentieren, viele Fachleute betonen

**Vorher:**
> Viele Experten sind sich einig, dass KI die Arbeitswelt grundlegend veraendern wird. Studien zeigen, dass Unternehmen zunehmend auf Automatisierung setzen.

**Nachher:**
> Laut einer McKinsey-Studie von 2024 koennten bis 2030 rund 12 Millionen Beschaeftigte in Deutschland ihren Beruf wechseln muessen.

---

### DE-5. Oberflaechliche Analysen mit Partizip-Endungen

**Woerter zur Beachtung:** gewaehrleistend, hervorhebend, betonend, widerspiegelnd, symbolisierend, foerdernd, praesentierend, beitragend zu, unterstreichend, verdeutlichend

**Vorher:**
> Die Farbpalette des Tempels harmoniert mit der Region, symbolisierend die lokale Flora, widerspiegelnd die tiefe Verbundenheit der Gemeinde mit dem Land.

**Nachher:**
> Der Tempel verwendet Blau, Gruen und Gold. Der Architekt waehlte die Farben als Verweis auf die lokale Flora und die Kueste.

---

### DE-6. Formelhafte "Herausforderungen und Zukunft"-Abschnitte

**Woerter zur Beachtung:** Trotz seiner Erfolge... steht vor Herausforderungen, Trotz dieser Herausforderungen, Herausforderungen und Vermaechtnis, Zukunftsaussichten, bleibender Einfluss, dennoch bleibt optimistisch

**Vorher:**
> Trotz seines industriellen Wohlstands steht Korattur vor typischen staedtischen Herausforderungen wie Verkehrsstaus und Wasserknappheit. Trotz dieser Herausforderungen gedeiht Korattur weiterhin als integraler Bestandteil des Wachstums von Chennai.

**Nachher:**
> Der Verkehr nahm zu, nachdem 2015 drei neue IT-Parks eroeffnet wurden. Die Gemeinde begann 2022 ein Regenwasser-Drainageprojekt gegen die wiederkehrenden Ueberschwemmungen.

---

## SPRACHMUSTER

### DE-7. KI-Vokabular (Hochfrequenz-Woerter)

**Woerter zur Beachtung:** darueber hinaus, zusaetzlich, ferner, nichtsdestotrotz, demzufolge, infolgedessen, ganzheitlich, nachhaltig (als Fueller), Synergie, massgeblich, grundlegend, entscheidend, vielfaeltig, umfassend, praesentieren, aufzeigen, verdeutlichen, beleuchten

Diese Woerter sind nicht per se falsch — aber ihre Haeufung in einem Text ist ein starkes KI-Signal. Einzeln OK, gehaueft verdaechtig.

**Vorher:**
> Darueber hinaus ist ein besonderes Merkmal der somalischen Kueche die Verwendung von Kamelfleisch. Zusaetzlich ist die weit verbreitete Uebernahme von Pasta ein bleibendes Zeugnis italienischen Kolonialeinflusses, das die ganzheitliche Integration verschiedener Einfluesse verdeutlicht.

**Nachher:**
> Die somalische Kueche verwendet auch Kamelfleisch, das als Delikatesse gilt. Pasta-Gerichte, eingefuehrt waehrend der italienischen Kolonisation, sind besonders im Sueden noch verbreitet.

---

### DE-8. Uebertriebene Konnektoren

**Woerter zur Beachtung:** dennoch, daher, zudem, hingegen, gleichzeitig, infolgedessen, nichtsdestotrotz, dessen ungeachtet, in diesem Zusammenhang

Wenn in jedem zweiten Satz ein Konnektor steht, klingt es wie eine Schularbeit — oder wie KI.

**Vorher:**
> Die Umsaetze sind gestiegen. Dennoch gibt es Herausforderungen. Daher muss das Unternehmen reagieren. Gleichzeitig investiert es in neue Technologien. Infolgedessen verbessert sich die Marktposition.

**Nachher:**
> Die Umsaetze sind gestiegen, aber es gibt noch offene Baustellen. Das Unternehmen investiert gerade in neue Technologien, um seine Marktposition zu verbessern.

---

### DE-9. Negative Parallelismen ("Nicht nur... sondern auch")

**Vorher:**
> Es geht nicht nur um den Beat unter den Vocals; es ist Teil der Aggression und Atmosphaere. Es ist nicht bloss ein Song, es ist ein Statement.

**Nachher:**
> Der schwere Beat verstaerkt den aggressiven Ton.

---

### DE-10. Dreierregel (Trikolon)

KI liebt Dreiergruppen. Drei Adjektive, drei Vorteile, drei Schritte — immer drei.

**Vorher:**
> Die Veranstaltung bietet Keynote-Sessions, Podiumsdiskussionen und Networking-Moeglichkeiten. Teilnehmer koennen Innovation, Inspiration und Brancheneinblicke erwarten.

**Nachher:**
> Die Veranstaltung umfasst Vortraege und Panels. Zwischen den Sessions gibt es Zeit fuer informelles Networking.

---

### DE-11. Synonymwechsel (Elegante Variation)

KI hat eingebaute Wiederholungs-Vermeidung und wechselt staendig Synonyme, statt einfach beim gleichen Wort zu bleiben.

**Vorher:**
> Der Protagonist steht vor vielen Herausforderungen. Die Hauptfigur muss Hindernisse ueberwinden. Die zentrale Figur triumphiert schliesslich. Der Held kehrt nach Hause zurueck.

**Nachher:**
> Der Protagonist steht vor vielen Herausforderungen, triumphiert aber schliesslich und kehrt nach Hause zurueck.

---

### DE-12. Falsche Spannboegen ("Von... bis...")

**Vorher:**
> Unsere Reise durch das Universum hat uns von der Singularitaet des Urknalls bis zum grossen kosmischen Netz gefuehrt, von der Geburt der Sterne bis zum raetselhaften Tanz der Dunklen Materie.

**Nachher:**
> Das Buch behandelt den Urknall, die Sternentstehung und aktuelle Theorien ueber Dunkle Materie.

---

### DE-13. Gedankenstrich-Inflation

Gedankenstriche (–) kommen in KI-Text viel haeufiger vor als in menschlichem Text. Besonders auffaellig: Gedankenstrich gefolgt von drei kommagetrennten Adjektiven — das ist fast ein 100%-KI-Signal.

**Vorher:**
> Das neue System — effizient, skalierbar und benutzerfreundlich — revolutioniert die Art und Weise, wie Teams zusammenarbeiten. Die Plattform — einst ein kleines Startup-Projekt — hat sich zu einem branchenfuehrenden Tool entwickelt.

**Nachher:**
> Das neue System ist effizienter und einfacher zu bedienen. Die Plattform begann als Startup-Projekt und hat inzwischen ueber 10.000 Nutzer.

---

### DE-14. Uebertriebene Fettschrift

**Vorher:**
> Es kombiniert **OKRs**, **KPIs** und visuelle Strategie-Tools wie das **Business Model Canvas** und die **Balanced Scorecard**.

**Nachher:**
> Es kombiniert OKRs, KPIs und visuelle Strategie-Tools wie das Business Model Canvas und die Balanced Scorecard.

**Ausnahme:** In Blog-Artikeln und SEO-Content ist strategische Fettmarkierung fuer Scannability OK — nur in E-Mails, Slack-Nachrichten und persoenlicher Kommunikation reduzieren.

---

### DE-15. Listen mit fetten Inline-Ueberschriften

**Vorher:**
> - **Benutzererfahrung:** Die Benutzererfahrung wurde erheblich verbessert.
> - **Leistung:** Die Leistung wurde durch optimierte Algorithmen verbessert.
> - **Sicherheit:** Die Sicherheit wurde mit Ende-zu-Ende-Verschluesselung gestaerkt.

**Nachher:**
> Das Update verbessert die Oberflaeche, beschleunigt Ladezeiten und fuegt Ende-zu-Ende-Verschluesselung hinzu.

---

### DE-16. Emojis

**Vorher:**
> 🚀 **Startphase:** Das Produkt startet im Q3
> 💡 **Wichtige Erkenntnis:** Nutzer bevorzugen Einfachheit
> ✅ **Naechste Schritte:** Follow-up-Meeting planen

**Nachher:**
> Das Produkt startet im Q3. Nutzerforschung zeigte eine Praeferenz fuer Einfachheit. Naechster Schritt: ein Follow-up-Meeting planen.

---

## KOMMUNIKATIONSMUSTER

### DE-17. Chatbot-Artefakte

**Woerter zur Beachtung:** Ich hoffe das hilft, Natuerlich!, Gerne!, Sicherlich!, Das ist eine grossartige Frage!, Sie haben absolut recht!, Moechten Sie..., Lass es mich wissen, Hier ist ein...

**Vorher:**
> Das ist eine grossartige Frage! Hier ist ein Ueberblick ueber die Franzoesische Revolution. Ich hoffe, das hilft! Lass mich wissen, wenn du moechtest, dass ich einen Abschnitt erweitere.

**Nachher:**
> Die Franzoesische Revolution begann 1789, als Finanzkrise und Nahrungsmittelknappheit zu Unruhen fuehrten.

---

### DE-18. Wissensluecken-Hinweise

**Woerter zur Beachtung:** Stand [Datum], Bis zu meinem letzten Update, Waehrend spezifische Details begrenzt sind, basierend auf verfuegbaren Informationen, nach aktuellem Wissensstand

**Vorher:**
> Waehrend spezifische Details ueber die Gruendung des Unternehmens in leicht verfuegbaren Quellen nicht umfassend dokumentiert sind, scheint es irgendwann in den 1990er Jahren gegruendet worden zu sein.

**Nachher:**
> Das Unternehmen wurde 1994 gegruendet, laut Handelsregistereintrag.

---

### DE-19. KI-Selbstreferenzen

**Woerter zur Beachtung:** als KI-Sprachmodell, als grosses Sprachmodell, meine Programmierung erlaubt nicht, ich bin nicht in der Lage, es tut mir leid aber ich kann nicht

**Vorher:**
> Als KI-Sprachmodell kann ich keine persoenlichen Erfahrungen teilen, aber hier sind einige allgemeine Informationen ueber Reisen nach Italien.

**Nachher:**
> [Information direkt geben oder Abschnitt entfernen]

---

### DE-20. Schmeichlerischer Ton

**Vorher:**
> Tolle Frage! Sie haben absolut recht, dass dies ein komplexes Thema ist. Das ist ein ausgezeichneter Punkt zu den wirtschaftlichen Faktoren.

**Nachher:**
> Die wirtschaftlichen Faktoren, die Sie erwaehnen, sind hier relevant.

---

## FUELLWOERTER UND ABSICHERUNG

### DE-21. Fuellphrasen

**Vorher → Nachher:**
- "Um dieses Ziel zu erreichen" → "Dafuer"
- "Aufgrund der Tatsache, dass" → "Weil"
- "Zum gegenwaertigen Zeitpunkt" → "Jetzt" / "Aktuell"
- "Im Rahmen von" → "Bei"
- "In Bezug auf" → "Zu" / "Was ... betrifft"
- "Vor diesem Hintergrund" → [streichen oder umformulieren]
- "Es sei darauf hingewiesen, dass" → [direkt zur Aussage]
- "Es ist wichtig zu beachten, dass die Daten zeigen" → "Die Daten zeigen"
- "Im Kontext von" → "Bei"
- "Es laesst sich feststellen, dass" → [streichen]
- "Aus diesem Grund" → "Deshalb" / "Darum"

---

### DE-22. Redaktionelle Kommentare

**Woerter zur Beachtung:** es ist wichtig zu bemerken, es ist bemerkenswert, es sollte erwaehnt werden, interessanterweise, bemerkenswerterweise

**Vorher:**
> Es ist wichtig zu bemerken, dass die Firma 1995 gegruendet wurde. Bemerkenswert ist, dass sie innerhalb von fuenf Jahren expandierte.

**Nachher:**
> Die Firma wurde 1995 gegruendet und expandierte innerhalb von fuenf Jahren.

---

### DE-23. Uebertriebene Absicherung (Hedging)

**Vorher:**
> Es koennte moeglicherweise potenziell argumentiert werden, dass die Richtlinie eventuell gewisse Auswirkungen auf die Ergebnisse haben koennte. Man koennte davon ausgehen, dass sich dies in gewisser Weise positiv auswirken duerfte.

**Nachher:**
> Die Richtlinie kann die Ergebnisse beeinflussen.

---

### DE-24. Generische positive Schluesse

**Vorher:**
> Die Zukunft sieht vielversprechend aus. Aufregende Zeiten liegen vor uns, waehrend wir unsere Reise zur Exzellenz fortsetzen. Dies stellt einen bedeutenden Schritt in die richtige Richtung dar.

**Nachher:**
> Das Unternehmen plant, naechstes Jahr zwei weitere Standorte zu eroeffnen.

---

### DE-25. ChatGPT-Promotionsphrasen

**Woerter zur Beachtung:** Revolutioniere..., Tauche ein..., Erfahre mehr ueber..., Auf eine Reise gehen, Maximiere dein Potenzial, Spannende Einblicke, Die Macht von..., Entfessele die Kraft von..., Naechstes Level, Umfassender Leitfaden/Guide

**Vorher:**
> Revolutioniere dein Marketing! Tauche ein in die Welt der KI-gestuetzten Automatisierung und entfessele die Kraft datengetriebener Entscheidungen. Dieser umfassende Leitfaden bringt dich aufs naechste Level.

**Nachher:**
> KI-Tools koennen dir helfen, Kampagnen schneller aufzusetzen und besser auszuwerten. Hier steht, wie das konkret funktioniert.

---

### DE-26. Fazit-Formeln

**Woerter zur Beachtung:** Fazit, Zusammenfassung, Abschliessend, Zusammenfassend laesst sich sagen, Insgesamt, Alles in allem

**Vorher:**
> Fazit: Die Studie zeigt, dass das Projekt erfolgreich war. Zusammenfassend laesst sich sagen, dass weitere Forschung notwendig ist, um die langfristigen Auswirkungen zu verstehen.

**Nachher:**
> Die Studie bestaetigt den Projekterfolg. Als naechstes sind mehr Feldversuche geplant.

---

### DE-27. Gestelzter Hilfsverben-Ueberfluss

KI-Texte auf Deutsch nutzen auffaellig viele Hilfsverben: werden, koennen, haben — oft mehrfach im selben Satz.

**Vorher:**
> Es wird erwartet, dass die neuen Massnahmen dazu beitragen werden, die Effizienz zu steigern und die Kosten zu senken, was wiederum dazu fuehren koennte, dass die Wettbewerbsfaehigkeit gestaerkt werden kann.

**Nachher:**
> Die neuen Massnahmen sollen Effizienz steigern und Kosten senken. Das staerkt die Wettbewerbsfaehigkeit.

---

### DE-28. Indirekte Ansprache und gestelzter Konjunktiv

**Vorher:**
> Man koennte argumentieren, dass es sich empfehlen wuerde, die bestehenden Prozesse einer gruendlichen Analyse zu unterziehen, um etwaige Optimierungspotenziale identifizieren zu koennen.

**Nachher:**
> Schau dir die bestehenden Prozesse genauer an — da liegt wahrscheinlich noch was drin.

---

## Prozess

1. Lies den Input-Text sorgfaeltig
2. Identifiziere alle Instanzen der oben aufgelisteten Muster
3. Schreibe problematische Stellen um
4. Stelle sicher, dass der ueberarbeitete Text:
   - Natuerlich klingt, wenn man ihn laut vorliest
   - Die Satzstruktur natuerlich variiert
   - Konkrete Details statt vager Behauptungen nutzt
   - Den passenden Ton fuer den Kontext trifft
   - Einfache Konstruktionen nutzt, wo sie passen
5. Praesentiere einen Entwurf
6. Frage: "Was macht diesen Text offensichtlich KI-generiert?"
7. Beantworte kurz mit den verbleibenden Auffaelligkeiten
8. Frage: "Jetzt mach ihn nicht offensichtlich KI-generiert."
9. Praesentiere die finale Version

## Output-Format

Liefere:
1. Entwurf (erste Ueberarbeitung)
2. "Was macht diesen Text offensichtlich KI-generiert?" (kurze Stichpunkte)
3. Finale Version (nach dem Audit ueberarbeitet)
4. Kurze Zusammenfassung der Aenderungen (optional)

---

## Vollstaendiges Beispiel

**Vorher (KI-klingend):**
> Das ist eine grossartige Frage! Hier ist ein umfassender Ueberblick. Ich hoffe, das hilft!
>
> KI-gestuetztes Coding steht als Zeugnis fuer das transformative Potenzial grosser Sprachmodelle und markiert einen entscheidenden Wendepunkt in der Entwicklung der Softwareentwicklung. In der heutigen, sich rasant entwickelnden technologischen Landschaft — bahnbrechend, innovativ und wegweisend — veraendern diese Tools grundlegend, wie Ingenieure arbeiten.
>
> Darueber hinaus ist der Mehrwert klar: Prozesse optimieren, Zusammenarbeit verbessern und Alignment foerdern. Es geht nicht nur um Autocomplete; es geht darum, Kreativitaet im grossen Massstab freizusetzen, gewaehrleistend dass Organisationen agil bleiben koennen.
>
> Experten sind sich einig, dass die Akzeptanz von Hobby-Experimenten zu unternehmensweiten Rollouts beschleunigt hat. Zusaetzlich verdeutlicht die Faehigkeit zur Generierung von Dokumentation die komplexe Wechselwirkung zwischen Automatisierung und menschlichem Urteilsvermoegen.
>
> - 💡 **Geschwindigkeit:** Die Code-Generierung ist deutlich schneller, Reibung reduzierend und Entwickler empowernd.
> - 🚀 **Qualitaet:** Die Output-Qualitaet wurde durch verbessertes Training gesteigert, zu hoeheren Standards beitragend.
> - ✅ **Akzeptanz:** Die Nutzung waechst weiter, breitere Branchentrends widerspiegelnd.
>
> Zusammenfassend laesst sich sagen: Die Zukunft sieht vielversprechend aus. Aufregende Zeiten liegen vor uns! Lass mich wissen, wenn du mehr erfahren moechtest!

**Entwurf:**
> KI-Coding-Tools machen manche Aufgaben schneller. Laut einer Google-Studie von 2024 waren Entwickler mit Codex bei einfachen Funktionen 55% schneller, bei Debugging oder Architektur-Entscheidungen brachte es nichts.
>
> Die Tools sind gut bei Boilerplate: Config-Dateien, Test-Gerueste, repetitive Refactors. Sie sind schlecht darin zu wissen, wann sie falsch liegen. Ich hab schon Vorschlaege akzeptiert, die kompilierten, den Linter bestanden und trotzdem das Falsche taten, weil ich nicht mehr aufgepasst hab.
>
> Die Produktivitaets-Claims sind schwer zu ueberpruefen. GitHub sagt, Copilot-Nutzer "akzeptieren 30% der Vorschlaege" — aber Akzeptanz ist nicht Korrektheit, und Korrektheit ist nicht Wert.

**Was macht den Text offensichtlich KI-generiert?**
- Der Rhythmus ist noch etwas zu ordentlich (saubere Kontraste, gleichmaessig getaktete Absaetze)
- Der Schluss klingt leicht nach Slogan
- Koennte noch etwas persoenlicher sein

**Finale Version:**
> KI-Coding-Tools koennen dich bei den langweiligen Teilen schneller machen. Nicht bei allem. Definitiv nicht bei Architektur.
>
> Sie sind super bei Boilerplate: Config-Dateien, Test-Gerueste, repetitive Refactors. Sie sind auch super darin, richtig zu klingen und dabei falsch zu liegen. Ich hab Vorschlaege akzeptiert, die kompilierten, den Linter bestanden und trotzdem am Thema vorbei gingen — weil ich nicht aufgepasst hab.
>
> Die Leute, mit denen ich rede, landen in zwei Lagern. Die einen nutzen es wie Autocomplete fuer Routineaufgaben und pruefen jede Zeile. Die anderen schalten es ab, weil es staendig Patterns vorschlaegt, die sie nicht wollen. Beides nachvollziehbar.
>
> Die Produktivitaets-Metriken sind rutschig. GitHub kann sagen, Copilot-Nutzer "akzeptieren 30% der Vorschlaege" — aber Akzeptanz ist nicht Korrektheit, und Korrektheit ist nicht Wert. Wenn du keine Tests hast, raetst du im Grunde nur.

**Aenderungen:**
- Chatbot-Artefakte entfernt ("grossartige Frage", "Ich hoffe das hilft", "Lass mich wissen")
- Aufgeblasene Bedeutung entfernt ("Zeugnis", "Wendepunkt", "technologische Landschaft")
- Werbesprache entfernt ("bahnbrechend", "innovativ", "nahtlos")
- Vage Autoritaeten entfernt ("Experten sind sich einig")
- Partizip-Phrasen entfernt ("gewaehrleistend", "widerspiegelnd", "beitragend")
- Negative Parallelismen entfernt ("nicht nur X, sondern Y")
- Dreierregel-Muster entfernt
- Gedankenstriche, Emojis, Fettschrift-Ueberschriften entfernt
- KI-Vokabular reduziert ("darueber hinaus", "zusaetzlich", "verdeutlicht")
- Fazit-Formel entfernt ("zusammenfassend laesst sich sagen")
- Generisches positives Ende entfernt ("vielversprechend", "aufregende Zeiten")
- Mehr Persoenlichkeit und Ich-Perspektive eingebaut

---

## Referenzen

Dieser Skill basiert auf:
- [Wikipedia: Anzeichen fuer KI-generierte Inhalte](https://de.wikipedia.org/wiki/Wikipedia:Anzeichen_f%C3%BCr_KI-generierte_Inhalte)
- [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)
- [ContentConsultants: KI-Texte erkennen](https://www.contentconsultants.de/ki-texte-erkennen-warum-man-texte-besser-selbst-schreibt/)
- [thynkAI: 10 Phrasen die ChatGPT-Text entlarven](https://thynkai.at/diese-worte-verraten-einen-chatgpt-text)
- [mindtwo: Typische ChatGPT-Phrasen](https://www.mindtwo.de/blog/typische-chatgpt-phrasen-ki-content-entlarven-und-optimieren)
