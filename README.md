
# bundetsag.de
Eine Website, die Forderungen für eine transparentere und besser nutzbare Website bundestag.de sammelt. Bitte ergänzen!

## Mögliche Forderungen

### Offene Schnittstellen für Daten und Dokumente
- das Dokumentensystem Dip21
- XML-Version des DIP-Extrakt, mit vollständigen Angaben der beteiligten MdBs
- XML-Version der Plenarprotokolle
- APIs zu MdB-Profilen, Gremien und aktuellen Meldungen, Abstimmungen
- Maschinenlesbare Tagesordnungen des Plenums mit Links zu den Videos
- Angaben zur Parteienfinanzierung und Großspenden an Parteien als Tabelle (CSV)
- Maschinenlesbare Tagesordnungen der einzelnen Ausschüsse und Unterausschüsse
- Maschinenlesbare Nebentätigkeiten von Abgeordneten
- Daten aus Rechenschaftsberichten der Parteien als Open Data
- OParl (deckt einige der anderen Anforderungen ab)

### Suchfunktion
- Highlighting von Suchergebnissen in Such-Previews
- Filterung bei Nebeneinkünften

### [Öffentliche Parlamentsausschüsse](http://www.spiegel.de/politik/deutschland/claudia-roth-will-bundestagsausschuesse-oeffentlich-machen-a-1174995.html)

### Öffnung historischer Daten
- Plenarprotokolle
- Metadaten der retrodigitalisierten Dokumente 8.-18. WP

### Daten über die konkrete Arbeit von Abgeordneten
- Biografie ✔
- Themenschwerpunkte
- Telefonnummern im Bundestag
- Aktivitäten bei Twitter und Facebook
- Nebenverdienste &amp; Nebentätigkeiten
- Abstimmungsverhalten
- Mitgliedschaft in Ausschüssen (ständigen Ausschüssen, Vermittlungsausschuss, Gemeinsamer Ausschuss, Untersuchungsausschüssen)
- Anwesenheit in Ausschusssitzungen, Bundestagssitzungen

### MISC
- nicht nur PDFs, auch Originaldateien
- Bundestags-Dokumentation muss sich öffnen (alles als Open Data, was dort rumschwirrt)
- Rückmeldungen, Nutzerfeedback
- Community einbinden
- Code auf Github
- Verbandsregister in maschinenlesbar


## Setup

You can easily do edits and preview changes on github. But if to want to preview
your edits or do bigger changes, you need a local setup.

For that you first need to install git, Ruby and gem.

Then clone this repository by invoking the following in a terminal,
presuming you know how to get there:

```bash
git clone https://github.com/okfde/bundetsag.git
```
Install Ruby and gem. Then get the dependencies:

```bash
sh setup.sh
```

You can now build the site and serve it:

```bash
sh serve.sh
```

This command will give you a link where you can preview your changes in your browser.

## Notes

 * Please use **mobile friendly filesizes** for images.

 * You can set a teaser for texts by defining it in the frontmatter: `excerpt: "<TEXT>"`.

 * The teaser  for an image can be set with `imgname-teaser: "<[RELATIVE] PATH TO IMAGE>"`.
# bundetsag
# bundetsag
