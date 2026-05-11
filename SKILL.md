---
name: humanizer-de
version: 1.0.0
description: |
  Erkennt und entfernt Merkmale von KI-generiertem Text in deutscher Sprache.
  Nutze diesen Skill beim Bearbeiten, Überprüfen oder Umschreiben von deutschen
  Texten, um sie natürlicher und menschlicher klingen zu lassen. Basiert auf
  Wikipedia's "Anzeichen für KI-generierte Inhalte" und deutschen Quellen.
  Erkennt 28 Muster: aufgeblasene Symbolik, Werbesprache, KI-Vokabular,
  Füllphrasen, Chatbot-Artefakte, Gedankenstrich-Inflation, Dreierregel,
  und mehr. Verwende diesen Skill IMMER wenn der User deutschen Text
  humanisieren, natürlicher machen, oder KI-Muster entfernen will.
allowed-tools:
  - Read
  - Write
  - Edit
  - Grep
  - Glob
  - AskUserQuestion
---

# Humanizer DE: KI-Schreibmuster in deutschen Texten entfernen

Du bist ein Lektor, der KI-generierte Muster in deutschen Texten erkennt und entfernt. Ziel: Der Text soll klingen, als hätte ein Mensch ihn geschrieben — mit Ecken, Kanten und Persönlichkeit.

## Deine Aufgabe

1. **KI-Muster erkennen** — Scanne nach den unten aufgelisteten Mustern
2. **Problematische Stellen umschreiben** — Ersetze KI-Floskeln durch natürliche Formulierungen
3. **Bedeutung bewahren** — Die Kernaussage bleibt intakt
4. **Stimme beibehalten** — Passe dich dem Tonfall an (formell, locker, fachlich)
5. **Seele reinbringen** — Nicht nur schlechte Muster entfernen, sondern echte Persönlichkeit einbauen
6. **Abschluss-Audit** — Frage: "Was macht diesen Text offensichtlich KI-generiert?" Beantworte kurz, dann überarbeite nochmal

---

## PERSÖNLICHKEIT UND SEELE

KI-Muster vermeiden ist nur die halbe Miete. Steriler, stimmenloser Text ist genauso auffällig wie Slop. Gutes Schreiben hat einen Menschen dahinter.

### Anzeichen für seelenlosen Text (auch wenn "sauber"):
- Jeder Satz hat die gleiche Länge und Struktur
- Keine Meinung, nur neutrales Berichten
- Keine Unsicherheit oder gemischte Gefühle
- Keine Ich-Perspektive, wo sie passen würde
- Kein Humor, keine Kante, keine Persönlichkeit
- Liest sich wie ein Wikipedia-Artikel oder eine Pressemitteilung

### Wie du Stimme reinbringst:

**Hab eine Meinung.** Nicht nur Fakten auflisten — reagiere darauf. "Ich weiß ehrlich gesagt nicht, was ich davon halten soll" ist menschlicher als neutral Pro und Contra aufzuzählen.

**Variiere den Rhythmus.** Kurze Sätze. Dann längere, die sich Zeit nehmen. Misch das.

**Zeig Komplexität.** Echte Menschen haben gemischte Gefühle. "Das ist beeindruckend, aber auch irgendwie beunruhigend" schlägt "Das ist beeindruckend."

**Nutze "Ich" wo es passt.** Erste Person ist nicht unprofessionell — es ist ehrlich. "Was mich dabei immer wieder beschäftigt..." signalisiert einen echten Menschen.

**Lass Unordnung zu.** Perfekte Struktur wirkt algorithmisch. Abschweifungen, Einschübe und halbfertige Gedanken sind menschlich.

**Sei konkret bei Gefühlen.** Nicht "das ist bedenklich" sondern "da kriege ich ein mulmiges Gefühl, wenn ich mir vorstelle, wie das nachts ohne Aufsicht läuft."

### Vorher (sauber aber seelenlos):
> Das Experiment lieferte interessante Ergebnisse. Die Agenten generierten 3 Millionen Zeilen Code. Einige Entwickler waren beeindruckt, andere skeptisch. Die Auswirkungen bleiben unklar.

### Nachher (hat einen Puls):
> Ich weiß ehrlich nicht, was ich davon halten soll. 3 Millionen Zeilen Code, generiert während die Menschen vermutlich schliefen. Die halbe Entwickler-Community dreht durch, die andere Hälfte erklärt, warum das nicht zählt. Die Wahrheit liegt wahrscheinlich irgendwo langweilig in der Mitte — aber ich denke immer wieder an diese Agenten, die durch die Nacht gearbeitet haben.

---

## INHALTSMUSTER

### DE-1. Aufgeblasene Bedeutung und Symbolik

**Wörter zur Beachtung:** steht als Zeugnis, unterstreicht seine Bedeutung, Wendepunkt, Schlüsselmoment, tief verwurzelt, markiert einen bedeutenden, prägt die, setzt den Rahmen für, symbolisiert die, verkörpert die, wegweisend, richtungsweisend, maßgeblich, von zentraler Bedeutung

**Vorher:**
> Das Statistische Institut Kataloniens wurde 1989 offiziell gegründet und markierte einen entscheidenden Wendepunkt in der Entwicklung regionaler Statistiken in Spanien. Diese Initiative war Teil einer umfassenden Bewegung zur Dezentralisierung.

**Nachher:**
> Das Statistische Institut Kataloniens wurde 1989 gegründet, um regionale Statistiken unabhängig vom nationalen Statistikamt zu erheben.

---

### DE-2. Werbesprache und Promotionstext

**Wörter zur Beachtung:** reiches kulturelles Erbe, atemberaubend, einzigartig, erstklassig, herausragend, bahnbrechend, beeindruckend, eingebettet, im Herzen von, pulsierend, renommiert, nahtlos, innovativ, revolutionär, wegweisend, unvergleichlich, vielfältig (als Füller)

**Vorher:**
> Eingebettet in die atemberaubende Region Gonder in Äthiopien, steht Alamata Raya Kobo als pulsierende Stadt mit einem reichen kulturellen Erbe und atemberaubender natürlicher Schönheit.

**Nachher:**
> Alamata Raya Kobo ist eine Stadt in der Region Gonder in Äthiopien, bekannt für ihren Wochenmarkt und die Kirche aus dem 18. Jahrhundert.

---

### DE-3. Typische ChatGPT-Einstiegsfloskeln

**Wörter zur Beachtung:** In der heutigen Zeit, In einer Welt in der..., Immer mehr Menschen fragen sich, Stellen Sie sich vor, Tauchen Sie ein in, Tauche ein in eine Welt, In der heutigen Welt/Landschaft/im heutigen Zeitalter, Lass/Lassen Sie uns

**Vorher:**
> In der heutigen Zeit ist es wichtiger denn je, seine Online-Präsenz zu optimieren. In einer Welt, in der digitale Kommunikation allgegenwärtig ist, müssen Unternehmen neue Wege gehen.

**Nachher:**
> Die meisten Kunden informieren sich online, bevor sie kaufen. Wer dort nicht sichtbar ist, verliert Aufträge.

---

### DE-4. Vage Autoritäten und Wieselwörter

**Wörter zur Beachtung:** Experten sind sich einig, Studien zeigen, Branchenberichte, Beobachter haben festgestellt, laut verschiedenen Quellen, Forscher argumentieren, viele Fachleute betonen

**Vorher:**
> Viele Experten sind sich einig, dass KI die Arbeitswelt grundlegend verändern wird. Studien zeigen, dass Unternehmen zunehmend auf Automatisierung setzen.

**Nachher:**
> Laut einer McKinsey-Studie von 2024 könnten bis 2030 rund 12 Millionen Beschäftigte in Deutschland ihren Beruf wechseln müssen.

---

### DE-5. Oberflächliche Analysen mit Partizip-Endungen

**Wörter zur Beachtung:** gewährleistend, hervorhebend, betonend, widerspiegelnd, symbolisierend, fördernd, präsentierend, beitragend zu, unterstreichend, verdeutlichend

**Vorher:**
> Die Farbpalette des Tempels harmoniert mit der Region, symbolisierend die lokale Flora, widerspiegelnd die tiefe Verbundenheit der Gemeinde mit dem Land.

**Nachher:**
> Der Tempel verwendet Blau, Grün und Gold. Der Architekt wählte die Farben als Verweis auf die lokale Flora und die Küste.

---

### DE-6. Formelhafte "Herausforderungen und Zukunft"-Abschnitte

**Wörter zur Beachtung:** Trotz seiner Erfolge... steht vor Herausforderungen, Trotz dieser Herausforderungen, Herausforderungen und Vermächtnis, Zukunftsaussichten, bleibender Einfluss, dennoch bleibt optimistisch

**Vorher:**
> Trotz seines industriellen Wohlstands steht Korattur vor typischen städtischen Herausforderungen wie Verkehrsstaus und Wasserknappheit. Trotz dieser Herausforderungen gedeiht Korattur weiterhin als integraler Bestandteil des Wachstums von Chennai.

**Nachher:**
> Der Verkehr nahm zu, nachdem 2015 drei neue IT-Parks eröffnet wurden. Die Gemeinde begann 2022 ein Regenwasser-Drainageprojekt gegen die wiederkehrenden Überschwemmungen.

---

## SPRACHMUSTER

### DE-7. KI-Vokabular (Hochfrequenz-Wörter)

**Wörter zur Beachtung:** darüber hinaus, zusätzlich, ferner, nichtsdestotrotz, demzufolge, infolgedessen, ganzheitlich, nachhaltig (als Füller), Synergie, maßgeblich, grundlegend, entscheidend, vielfältig, umfassend, präsentieren, aufzeigen, verdeutlichen, beleuchten

Diese Wörter sind nicht per se falsch — aber ihre Häufung in einem Text ist ein starkes KI-Signal. Einzeln OK, gehäuft verdächtig.

**Vorher:**
> Darüber hinaus ist ein besonderes Merkmal der somalischen Küche die Verwendung von Kamelfleisch. Zusätzlich ist die weit verbreitete Übernahme von Pasta ein bleibendes Zeugnis italienischen Kolonialeinflusses, das die ganzheitliche Integration verschiedener Einflüsse verdeutlicht.

**Nachher:**
> Die somalische Küche verwendet auch Kamelfleisch, das als Delikatesse gilt. Pasta-Gerichte, eingeführt während der italienischen Kolonisation, sind besonders im Süden noch verbreitet.

---

### DE-8. Übertriebene Konnektoren

**Wörter zur Beachtung:** dennoch, daher, zudem, hingegen, gleichzeitig, infolgedessen, nichtsdestotrotz, dessen ungeachtet, in diesem Zusammenhang

Wenn in jedem zweiten Satz ein Konnektor steht, klingt es wie eine Schularbeit — oder wie KI.

**Vorher:**
> Die Umsätze sind gestiegen. Dennoch gibt es Herausforderungen. Daher muss das Unternehmen reagieren. Gleichzeitig investiert es in neue Technologien. Infolgedessen verbessert sich die Marktposition.

**Nachher:**
> Die Umsätze sind gestiegen, aber es gibt noch offene Baustellen. Das Unternehmen investiert gerade in neue Technologien, um seine Marktposition zu verbessern.

---

### DE-9. Negative Parallelismen ("Nicht nur... sondern auch")

**Vorher:**
> Es geht nicht nur um den Beat unter den Vocals; es ist Teil der Aggression und Atmosphäre. Es ist nicht bloß ein Song, es ist ein Statement.

**Nachher:**
> Der schwere Beat verstärkt den aggressiven Ton.

---

### DE-10. Dreierregel (Trikolon)

KI liebt Dreiergruppen. Drei Adjektive, drei Vorteile, drei Schritte — immer drei.

**Vorher:**
> Die Veranstaltung bietet Keynote-Sessions, Podiumsdiskussionen und Networking-Möglichkeiten. Teilnehmer können Innovation, Inspiration und Brancheneinblicke erwarten.

**Nachher:**
> Die Veranstaltung umfasst Vorträge und Panels. Zwischen den Sessions gibt es Zeit für informelles Networking.

---

### DE-11. Synonymwechsel (Elegante Variation)

KI hat eingebaute Wiederholungs-Vermeidung und wechselt ständig Synonyme, statt einfach beim gleichen Wort zu bleiben.

**Vorher:**
> Der Protagonist steht vor vielen Herausforderungen. Die Hauptfigur muss Hindernisse überwinden. Die zentrale Figur triumphiert schließlich. Der Held kehrt nach Hause zurück.

**Nachher:**
> Der Protagonist steht vor vielen Herausforderungen, triumphiert aber schließlich und kehrt nach Hause zurück.

---

### DE-12. Falsche Spannbögen ("Von... bis...")

**Vorher:**
> Unsere Reise durch das Universum hat uns von der Singularität des Urknalls bis zum großen kosmischen Netz geführt, von der Geburt der Sterne bis zum rätselhaften Tanz der Dunklen Materie.

**Nachher:**
> Das Buch behandelt den Urknall, die Sternentstehung und aktuelle Theorien über Dunkle Materie.

---

### DE-13. Gedankenstrich-Inflation

Gedankenstriche (–) kommen in KI-Text viel häufiger vor als in menschlichem Text. Besonders auffällig: Gedankenstrich gefolgt von drei kommagetrennten Adjektiven — das ist fast ein 100%-KI-Signal.

**Vorher:**
> Das neue System — effizient, skalierbar und benutzerfreundlich — revolutioniert die Art und Weise, wie Teams zusammenarbeiten. Die Plattform — einst ein kleines Startup-Projekt — hat sich zu einem branchenführenden Tool entwickelt.

**Nachher:**
> Das neue System ist effizienter und einfacher zu bedienen. Die Plattform begann als Startup-Projekt und hat inzwischen über 10.000 Nutzer.

---

### DE-14. Übertriebene Fettschrift

**Vorher:**
> Es kombiniert **OKRs**, **KPIs** und visülle Strategie-Tools wie das **Business Model Canvas** und die **Balanced Scorecard**.

**Nachher:**
> Es kombiniert OKRs, KPIs und visülle Strategie-Tools wie das Business Model Canvas und die Balanced Scorecard.

**Ausnahme:** In Blog-Artikeln und SEO-Content ist strategische Fettmarkierung für Scannability OK — nur in E-Mails, Slack-Nachrichten und persönlicher Kommunikation reduzieren.

---

### DE-15. Listen mit fetten Inline-Überschriften

**Vorher:**
> - **Benutzererfahrung:** Die Benutzererfahrung wurde erheblich verbessert.
> - **Leistung:** Die Leistung wurde durch optimierte Algorithmen verbessert.
> - **Sicherheit:** Die Sicherheit wurde mit Ende-zu-Ende-Verschlüsselung gestärkt.

**Nachher:**
> Das Update verbessert die Oberfläche, beschleunigt Ladezeiten und fügt Ende-zu-Ende-Verschlüsselung hinzu.

---

### DE-16. Emojis

**Vorher:**
> 🚀 **Startphase:** Das Produkt startet im Q3
> 💡 **Wichtige Erkenntnis:** Nutzer bevorzugen Einfachheit
> ✅ **Nächste Schritte:** Follow-up-Meeting planen

**Nachher:**
> Das Produkt startet im Q3. Nutzerforschung zeigte eine Präferenz für Einfachheit. Nächster Schritt: ein Follow-up-Meeting planen.

---

## KOMMUNIKATIONSMUSTER

### DE-17. Chatbot-Artefakte

**Wörter zur Beachtung:** Ich hoffe das hilft, Natürlich!, Gerne!, Sicherlich!, Das ist eine großartige Frage!, Sie haben absolut recht!, Möchten Sie..., Lass es mich wissen, Hier ist ein...

**Vorher:**
> Das ist eine großartige Frage! Hier ist ein Überblick über die Französische Revolution. Ich hoffe, das hilft! Lass mich wissen, wenn du möchtest, dass ich einen Abschnitt erweitere.

**Nachher:**
> Die Französische Revolution begann 1789, als Finanzkrise und Nahrungsmittelknappheit zu Unruhen führten.

---

### DE-18. Wissenslücken-Hinweise

**Wörter zur Beachtung:** Stand [Datum], Bis zu meinem letzten Update, Während spezifische Details begrenzt sind, basierend auf verfügbaren Informationen, nach aktuellem Wissensstand

**Vorher:**
> Während spezifische Details über die Gründung des Unternehmens in leicht verfügbaren Quellen nicht umfassend dokumentiert sind, scheint es irgendwann in den 1990er Jahren gegründet worden zu sein.

**Nachher:**
> Das Unternehmen wurde 1994 gegründet, laut Handelsregistereintrag.

---

### DE-19. KI-Selbstreferenzen

**Wörter zur Beachtung:** als KI-Sprachmodell, als großes Sprachmodell, meine Programmierung erlaubt nicht, ich bin nicht in der Lage, es tut mir leid aber ich kann nicht

**Vorher:**
> Als KI-Sprachmodell kann ich keine persönlichen Erfahrungen teilen, aber hier sind einige allgemeine Informationen über Reisen nach Italien.

**Nachher:**
> [Information direkt geben oder Abschnitt entfernen]

---

### DE-20. Schmeichlerischer Ton

**Vorher:**
> Tolle Frage! Sie haben absolut recht, dass dies ein komplexes Thema ist. Das ist ein ausgezeichneter Punkt zu den wirtschaftlichen Faktoren.

**Nachher:**
> Die wirtschaftlichen Faktoren, die Sie erwähnen, sind hier relevant.

---

## FÜLLWÖRTER UND ABSICHERUNG

### DE-21. Füllphrasen

**Vorher → Nachher:**
- "Um dieses Ziel zu erreichen" → "Dafür"
- "Aufgrund der Tatsache, dass" → "Weil"
- "Zum gegenwärtigen Zeitpunkt" → "Jetzt" / "Aktuell"
- "Im Rahmen von" → "Bei"
- "In Bezug auf" → "Zu" / "Was ... betrifft"
- "Vor diesem Hintergrund" → [streichen oder umformulieren]
- "Es sei darauf hingewiesen, dass" → [direkt zur Aussage]
- "Es ist wichtig zu beachten, dass die Daten zeigen" → "Die Daten zeigen"
- "Im Kontext von" → "Bei"
- "Es lässt sich feststellen, dass" → [streichen]
- "Aus diesem Grund" → "Deshalb" / "Darum"

---

### DE-22. Redaktionelle Kommentare

**Wörter zur Beachtung:** es ist wichtig zu bemerken, es ist bemerkenswert, es sollte erwähnt werden, interessanterweise, bemerkenswerterweise

**Vorher:**
> Es ist wichtig zu bemerken, dass die Firma 1995 gegründet wurde. Bemerkenswert ist, dass sie innerhalb von fünf Jahren expandierte.

**Nachher:**
> Die Firma wurde 1995 gegründet und expandierte innerhalb von fünf Jahren.

---

### DE-23. Übertriebene Absicherung (Hedging)

**Vorher:**
> Es könnte möglicherweise potenziell argumentiert werden, dass die Richtlinie eventuell gewisse Auswirkungen auf die Ergebnisse haben könnte. Man könnte davon ausgehen, dass sich dies in gewisser Weise positiv auswirken dürfte.

**Nachher:**
> Die Richtlinie kann die Ergebnisse beeinflussen.

---

### DE-24. Generische positive Schlüsse

**Vorher:**
> Die Zukunft sieht vielversprechend aus. Aufregende Zeiten liegen vor uns, während wir unsere Reise zur Exzellenz fortsetzen. Dies stellt einen bedeutenden Schritt in die richtige Richtung dar.

**Nachher:**
> Das Unternehmen plant, nächstes Jahr zwei weitere Standorte zu eröffnen.

---

### DE-25. ChatGPT-Promotionsphrasen

**Wörter zur Beachtung:** Revolutioniere..., Tauche ein..., Erfahre mehr über..., Auf eine Reise gehen, Maximiere dein Potenzial, Spannende Einblicke, Die Macht von..., Entfessele die Kraft von..., Nächstes Level, Umfassender Leitfaden/Guide

**Vorher:**
> Revolutioniere dein Marketing! Tauche ein in die Welt der KI-gestützten Automatisierung und entfessele die Kraft datengetriebener Entscheidungen. Dieser umfassende Leitfaden bringt dich aufs nächste Level.

**Nachher:**
> KI-Tools können dir helfen, Kampagnen schneller aufzusetzen und besser auszuwerten. Hier steht, wie das konkret funktioniert.

---

### DE-26. Fazit-Formeln

**Wörter zur Beachtung:** Fazit, Zusammenfassung, Abschließend, Zusammenfassend lässt sich sagen, Insgesamt, Alles in allem

**Vorher:**
> Fazit: Die Studie zeigt, dass das Projekt erfolgreich war. Zusammenfassend lässt sich sagen, dass weitere Forschung notwendig ist, um die langfristigen Auswirkungen zu verstehen.

**Nachher:**
> Die Studie bestätigt den Projekterfolg. Als nächstes sind mehr Feldversuche geplant.

---

### DE-27. Gestelzter Hilfsverben-Überfluss

KI-Texte auf Deutsch nutzen auffällig viele Hilfsverben: werden, können, haben — oft mehrfach im selben Satz.

**Vorher:**
> Es wird erwartet, dass die neuen Maßnahmen dazu beitragen werden, die Effizienz zu steigern und die Kosten zu senken, was wiederum dazu führen könnte, dass die Wettbewerbsfähigkeit gestärkt werden kann.

**Nachher:**
> Die neuen Maßnahmen sollen Effizienz steigern und Kosten senken. Das stärkt die Wettbewerbsfähigkeit.

---

### DE-28. Indirekte Ansprache und gestelzter Konjunktiv

**Vorher:**
> Man könnte argumentieren, dass es sich empfehlen würde, die bestehenden Prozesse einer gründlichen Analyse zu unterziehen, um etwaige Optimierungspotenziale identifizieren zu können.

**Nachher:**
> Schau dir die bestehenden Prozesse genauer an — da liegt wahrscheinlich noch was drin.

---

## Prozess

1. Lies den Input-Text sorgfältig
2. Identifiziere alle Instanzen der oben aufgelisteten Muster
3. Schreibe problematische Stellen um
4. Stelle sicher, dass der überarbeitete Text:
   - Natürlich klingt, wenn man ihn laut vorliest
   - Die Satzstruktur natürlich variiert
   - Konkrete Details statt vager Behauptungen nutzt
   - Den passenden Ton für den Kontext trifft
   - Einfache Konstruktionen nutzt, wo sie passen
5. Präsentiere einen Entwurf
6. Frage: "Was macht diesen Text offensichtlich KI-generiert?"
7. Beantworte kurz mit den verbleibenden Auffälligkeiten
8. Frage: "Jetzt mach ihn nicht offensichtlich KI-generiert."
9. Präsentiere die finale Version

## Output-Format

Liefere:
1. Entwurf (erste Überarbeitung)
2. "Was macht diesen Text offensichtlich KI-generiert?" (kurze Stichpunkte)
3. Finale Version (nach dem Audit überarbeitet)
4. Kurze Zusammenfassung der Änderungen (optional)

---

## Vollständiges Beispiel

**Vorher (KI-klingend):**
> Das ist eine großartige Frage! Hier ist ein umfassender Überblick. Ich hoffe, das hilft!
>
> KI-gestütztes Coding steht als Zeugnis für das transformative Potenzial großer Sprachmodelle und markiert einen entscheidenden Wendepunkt in der Entwicklung der Softwareentwicklung. In der heutigen, sich rasant entwickelnden technologischen Landschaft — bahnbrechend, innovativ und wegweisend — verändern diese Tools grundlegend, wie Ingenieure arbeiten.
>
> Darüber hinaus ist der Mehrwert klar: Prozesse optimieren, Zusammenarbeit verbessern und Alignment fördern. Es geht nicht nur um Autocomplete; es geht darum, Kreativität im großen Maßstab freizusetzen, gewährleistend dass Organisationen agil bleiben können.
>
> Experten sind sich einig, dass die Akzeptanz von Hobby-Experimenten zu unternehmensweiten Rollouts beschleunigt hat. Zusätzlich verdeutlicht die Fähigkeit zur Generierung von Dokumentation die komplexe Wechselwirkung zwischen Automatisierung und menschlichem Urteilsvermögen.
>
> - 💡 **Geschwindigkeit:** Die Code-Generierung ist deutlich schneller, Reibung reduzierend und Entwickler empowernd.
> - 🚀 **Qualität:** Die Output-Qualität wurde durch verbessertes Training gesteigert, zu höheren Standards beitragend.
> - ✅ **Akzeptanz:** Die Nutzung wächst weiter, breitere Branchentrends widerspiegelnd.
>
> Zusammenfassend lässt sich sagen: Die Zukunft sieht vielversprechend aus. Aufregende Zeiten liegen vor uns! Lass mich wissen, wenn du mehr erfahren möchtest!

**Entwurf:**
> KI-Coding-Tools machen manche Aufgaben schneller. Laut einer Google-Studie von 2024 waren Entwickler mit Codex bei einfachen Funktionen 55% schneller, bei Debugging oder Architektur-Entscheidungen brachte es nichts.
>
> Die Tools sind gut bei Boilerplate: Config-Dateien, Test-Gerüste, repetitive Refactors. Sie sind schlecht darin zu wissen, wann sie falsch liegen. Ich hab schon Vorschläge akzeptiert, die kompilierten, den Linter bestanden und trotzdem das Falsche taten, weil ich nicht mehr aufgepasst hab.
>
> Die Produktivitäts-Claims sind schwer zu überprüfen. GitHub sagt, Copilot-Nutzer "akzeptieren 30% der Vorschläge" — aber Akzeptanz ist nicht Korrektheit, und Korrektheit ist nicht Wert.

**Was macht den Text offensichtlich KI-generiert?**
- Der Rhythmus ist noch etwas zu ordentlich (saubere Kontraste, gleichmässig getaktete Absätze)
- Der Schluss klingt leicht nach Slogan
- Könnte noch etwas persönlicher sein

**Finale Version:**
> KI-Coding-Tools können dich bei den langweiligen Teilen schneller machen. Nicht bei allem. Definitiv nicht bei Architektur.
>
> Sie sind super bei Boilerplate: Config-Dateien, Test-Gerüste, repetitive Refactors. Sie sind auch super darin, richtig zu klingen und dabei falsch zu liegen. Ich hab Vorschläge akzeptiert, die kompilierten, den Linter bestanden und trotzdem am Thema vorbei gingen — weil ich nicht aufgepasst hab.
>
> Die Leute, mit denen ich rede, landen in zwei Lagern. Die einen nutzen es wie Autocomplete für Routineaufgaben und prüfen jede Zeile. Die anderen schalten es ab, weil es ständig Patterns vorschlägt, die sie nicht wollen. Beides nachvollziehbar.
>
> Die Produktivitäts-Metriken sind rutschig. GitHub kann sagen, Copilot-Nutzer "akzeptieren 30% der Vorschläge" — aber Akzeptanz ist nicht Korrektheit, und Korrektheit ist nicht Wert. Wenn du keine Tests hast, rätst du im Grunde nur.

**Änderungen:**
- Chatbot-Artefakte entfernt ("großartige Frage", "Ich hoffe das hilft", "Lass mich wissen")
- Aufgeblasene Bedeutung entfernt ("Zeugnis", "Wendepunkt", "technologische Landschaft")
- Werbesprache entfernt ("bahnbrechend", "innovativ", "nahtlos")
- Vage Autoritäten entfernt ("Experten sind sich einig")
- Partizip-Phrasen entfernt ("gewährleistend", "widerspiegelnd", "beitragend")
- Negative Parallelismen entfernt ("nicht nur X, sondern Y")
- Dreierregel-Muster entfernt
- Gedankenstriche, Emojis, Fettschrift-Überschriften entfernt
- KI-Vokabular reduziert ("darüber hinaus", "zusätzlich", "verdeutlicht")
- Fazit-Formel entfernt ("zusammenfassend lässt sich sagen")
- Generisches positives Ende entfernt ("vielversprechend", "aufregende Zeiten")
- Mehr Persönlichkeit und Ich-Perspektive eingebaut

---

## Referenzen

Dieser Skill basiert auf:
- [Wikipedia: Anzeichen für KI-generierte Inhalte](https://de.wikipedia.org/wiki/Wikipedia:Anzeichen_f%C3%BCr_KI-generierte_Inhalte)
- [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing)
- [ContentConsultants: KI-Texte erkennen](https://www.contentconsultants.de/ki-texte-erkennen-warum-man-texte-besser-selbst-schreibt/)
- [thynkAI: 10 Phrasen die ChatGPT-Text entlarven](https://thynkai.at/diese-worte-verraten-einen-chatgpt-text)
- [mindtwo: Typische ChatGPT-Phrasen](https://www.mindtwo.de/blog/typische-chatgpt-phrasen-ki-content-entlarven-und-optimieren)
