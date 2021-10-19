# M226B - Objektorientiert (mit Vererbung) implementieren
## Community Guidelines
Please read the community guide lines [on this page](https://github.com/INFAxb/example-repository) first!

## Lernziele
- [ ] Ein objektorientiertes Design nachvollziehen und durch Einsatz der Vererbung erweitern.	
 	- **Handlungsnotwendige Kenntnisse:**
    1. Kennt den objektorientierten Ansatz mit Klassen und Vererbung.
    2. Kann durch die Anwendung von Vererbung Redundanzen im Klassendesign eliminieren.
    3. Kann durch den Einsatz von Delegation und Vererbung switchartige Strukturen vermeiden und dadurch die Erweiterbarkeit der Anwendung sicherstellen.
    4. Versteht das Prinzip der dynamischen Bindung.
    5. Berücksichtigt beim Erstellen von Vererbungshierarchien das Prinzip von Spezialisierung/Generalisierung inklusive abstrakter Klassen.

- [ ]	Die Notation dynamischer und statischer Strukturen einer Anwendung mittels Unified Modeling Language (UML) nachvollziehen.	
 	- **Handlungsnotwendige Kenntnisse:**
    1.	Kennt Diagrammnotationen zur Darstellung von Vererbung.
    2.	Kennt Diagrammnotationen zur Darstellung von Schnittstellen.

- [ ]	Objektorientiertes Design implementieren.	
 	- **Handlungsnotwendige Kenntnisse:**
    1.	Kennt Elemente einer objektorientierten Sprache für die Umsetzung der Vererbung im objektorientierten Design.
    2.	Kennt Elemente einer objektorientierten Sprache für das Überschreiben von Methoden im objektorientierten Design.
    3.	Kennt Elemente einer objektorientierten Sprache für die Realisierung von Schnittstellen und abstrakten Klassen.

- [ ]	Fortgeschrittene Testfälle für funktionale Einheiten implementieren, welche durch geeignete Techniken von anderen Systemteilen unabhängig sind.	
 	- **Handlungsnotwendige Kenntnisse:**
    1.	Kennt das Hilfsmittel des Mockings um Abhängigkeiten aus den Testfällen zu eliminieren.
    2.	Kennt Mittel zur Isolierung der Testdaten und Testfälle, um die gegenseitige Unabhängigkeit der Testfälle zu garantieren.
    3.	Kennt Werkzeuge zur Implementation von isolierten Testfällen.

## Termine
*Kompetenzen werden selbstständig abgegeben*



## FAQ



### <span id="whyNotPushMainDirectly">Wieso darf ich nicht direkt in main pushen?</span>

Sehr gute Frage!

Die `main` branch hat eine wichtige Bedeutung. Sie ist das Endprodukt. Das Finalem. Das wo nur die <i>Crème de la Crème</i> der Codebase stehen sollte. Wenn nun jeder einfach so ohne Kontrolle seinen Code dort reinpusht, dann ist dem nicht mehr so. Ausserdem wird die `main` branch im Arbeitsumfeld für Releases genutzt, weshalb fast immer mit pull requests gearbeitet wird (pull requests sind in GitHub dass, was merge requests in GitLab sind). Dies stellt sicher das mindestens eine andere Person, als diejenige wo den Code geschrieben hat, sich den Code ansieht.



### <span id="howToContribute">Wie kann ich mitarbeiten?</span>

+ Falls du Fehler finden solltest, hilft es <strong><a href="#whatIsAnIssue">ein Issue zu erstellen</a></strong>.
+ Wenn du Code beitragen willst, dann musst du:
  + Die repository mit `git clone https://github.com/INFA2b/226b.git` klonen.
  + Eine neue branch mit `git checkout -b <branchName>` erstellen.
    + Deine branch name sollte so aussehen: `<username>-<feature/patch/bugfix>-<digit>-<branchPurpose>`
    + Beispiel: `git checkout -b thebadev-hotfix-42-fixCSRFVulnerabilitiesInForms`
  + Deine branch kannst du mit `git push origin <branchName>` auf die remote Repository hochladen.
  + Eine neue <strong><a href="#howTocreatePullRequest">pull request erstellen</a></strong>.



### <span id="whatIsAnIssue">Was ist ein <i>Issue</i>?</span>

Kurzgesagt: Ein Issue kann eine Frage, ein Vorschlag oder das aufmerksam machen auf ein Problem im Code sein.

<strong><a href="https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues" target="_blank">What is a issue?</a></strong>

<strong>Im Moment existiert noch keine Übersetzung ins Deutsche für diesen Artikel.</strong>



### <span id="howToCreateAnIssue">Wie erstelle ich ein <i>Issue</i>?</span>

<strong><a href="https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue" target="_blank">How do i create an issue?</a></strong>

<strong>Im Moment existiert noch keine Übersetzung ins Deutsche für diesen Artikel.</strong>



### <span id="whatIsAnPullRequest">Was ist eine <i>pull request</i>?</span>

+ <strong><a href="https://docs.github.com/de/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests" target="_blank">Was ist eine Pull request?</a></strong>

+ <strong><a href="https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests" target="_blank">What is a pull request?</a></strong>



### <span id="howTocreatePullRequest">Wie erstelle ich eine <i>pull request</i>?</span>

+ <strong><a href="https://docs.github.com/de/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request" target="_blank">Wie erstelle ich eine pull request?</a></strong>

+ <strong><a href="https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request" target="_blank">How to create a pull request.</a></strong>

