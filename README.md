![Jekyll site CI](https://github.com/beschlagnahmt-org/website/workflows/Jekyll%20site%20CI/badge.svg)


![Check markdown links](https://github.com/beschlagnahmt-org/beschlagnahmt/workflows/Check%20markdown%20links/badge.svg)

Die Webseite wird mittels [Jekyll](https://jekyllrb.com/) generiert. 

Die einzelnen Themen findet ihr im Verzeichnis '_posts', die anderen Seiten unter '_pages'.

Das PDF kann mit dem Befehl
`pandoc -s -f markdown _pages/about.md _posts/* -o acab.pdf --resource-path=.:./assets/ --pdf-engine=xelatex --template=template.latex`
generiert werden.
