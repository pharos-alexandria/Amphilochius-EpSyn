# Eine kritische (Neu-)Edition der »Epistula synodalis« des Amphilochius von Ikonium

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3727094.svg)](https://doi.org/10.5281/zenodo.3727094)

Die sog. »Epistula synodalis« des Amphilochius von Ikonium (CPG 3243; CPG 8596) lag bisher nur in dem vorkritischen Druck von J.B. Cotelier, Ecclesiae Graecae Monumenta II, Paris 1681, 99–104, und dessen Nachdrucken sowie bei C. Datema, Amphilochii Iconiensis Opera, Turnhout 1978 (Corpus Christianorum. Series Graeca 3), 219–221, vor.

Wie schon B. Gain, Note sur l'Epistula Synodalis (CPG, t. II, no. 3243) d'Amphiloque d'Iconium, Sacris Erudiri 27, 1984, 19–25 festgestellt hat, verwendet Datema nicht alle bekannten Handschriften, die diesen Text überliefern, und gibt vor allem den Überlieferungsbefund (bzgl. der Edition Coteliers und der Handschrift Pg) falsch wieder.
Eine Neuedition war daher dringend geboten.

## Daten

Die Neuedition ist nach dem TEI-Standard ([Schema des Patristic Text Archive](https://github.com/PatristicTextArchive/Schema) in Version 1.3) erstellt, folgt den [Capitains-Guidelines](http://capitains.org/) (in Version 2.0) und umfaßt in der digitalen Version (im Ordner [data](data)) neben der kritischen Edition auch die Transkriptionen der vier Handschriften sowie eine deutsche Übersetzung:

- Kritische Edition [pta0013.pta003.pta-grc1.xml](data/pta0013/pta003/pta0013.pta003.pta-grc1.xml)
- Deutsche Übersetzung [pta0013.pta003.pta-deu1.xml](data/pta0013/pta003/pta0013.pta003.pta-deu1.xml)
- Transkription der Handschrift Ps [pta0013.pta003.pta-msPs.xml](data/pta0013/pta003/pta0013.pta003.pta-msPs.xml)
- Transkription der Handschrift La [pta0013.pta003.pta-msLa.xml](data/pta0013/pta003/pta0013.pta003.pta-msLa.xml)
- Transkription der Handschrift Vi [pta0013.pta003.pta-msVi.xml](data/pta0013/pta003/pta0013.pta003.pta-msVi.xml)
- Transkription der Handschrift Pg [pta0013.pta003.pta-msPg.xml](data/pta0013/pta003/pta0013.pta003.pta-msPg.xml)


## Kollationen

Auf Grundlage der Transkriptionsdateien wurde mit Hilfe von [CollateX](https://collatex.net/) (und einem [Python-Script](https://github.com/PatristicTextArchive/collator)) eine Kollationstabelle erstellt. Diese liegt im Ordner [collation](collation) in zwei Fassungen vor, die im Browser betrachtet werden können:

- [Kollation auf Basis des Buchstabenbestandes (normalisiert](collation/collation-without-diacritis.html)
- [Kollation auf Basis des Textes mit Diakritika](collation/collation.html)

(Die Interpunktion ist in beiden Fällen vorher entfernt worden.)

Die (vom Python-Script erstellten) JSON-Inputdateien für CollateX liegen ebenfalls im Ordner [collation](collation).

## Einfache Readerumgebung

Die Editionsdatei wurde mit Hilfe des Scripts [xml2edition-md.xsl](https://github.com/PatristicTextArchive/Stylesheets/blob/master/xml2edition-md.xsl) in eine Markdown-Datei transferiert, die dann mit Hilfe von [Pandoc](https://pandoc.org) in eine html-Datei konvertiert wurde.

Diese Datei kann unter <https://pharos-alexandria.github.io/Amphilochius-EpSyn> betrachtet werden.
