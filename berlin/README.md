# Berlin: Verfahrenshinweise zum Aufenthalt in Berlin (VAB), source PDFs

Every version we could find of the *Verfahrenshinweise zum Aufenthalt in Berlin* (VAB), the Berlin immigration office's internal guidance on residence, asylum and naturalisation law.

The office (Landesamt für Einwanderung, formerly the Ausländerbehörde Berlin) publishes the VAB as a single PDF of up to 1,000 pages. It replaces the file several times a year, keeps no old versions online and publishes no change log. This folder keeps the old versions. It was moved here on 15 November 2026 from the separate `vabpdfs` repository.

## The files

Each file is named `YYYY-MM-DD-vab-berlin.pdf` after the day the PDF was generated, which is printed on its first page. The files are unmodified.

The text of these PDFs is also kept as a git history, one commit per version, so that the changes between versions can be read as diffs. That history is in the separate repository [immigration-guidelines/berlin_vab](https://github.com/immigration-guidelines/berlin_vab) and is generated from the PDFs in this folder.

## Adding a version

If you have a version that is not listed below, open a pull request against [immigration-guidelines/de](https://github.com/immigration-guidelines/de) that adds the PDF to this `berlin/` folder.

- Add the PDF unmodified, as it was published.
- Name it `YYYY-MM-DD-vab-berlin.pdf`, using the date printed on its first page ("Dieses PDF wurde erstellt am", or "Erstellt am" in versions before 2011).
- Say in the pull request where the file came from.

After the pull request is merged, the text history is regenerated from the full set of PDFs.

## Versions

79 versions, from 14.09.2007 to 31.08.2026.

| Year | Versions | Dates |
|---|---|---|
| 2007 | 2 | 14.09. 05.12. |
| 2008 | 1 | 27.10. |
| 2009 | 1 | 30.09. |
| 2010 | 3 | 02.02. 22.04. 16.06. |
| 2011 | 4 | 11.01. 15.04. 20.10. 08.12. |
| 2012 | 3 | 09.03. 02.08. 21.11. |
| 2013 | 5 | 18.02. 02.05. 11.07. 11.09. 04.12. |
| 2014 | 4 | 05.03. 22.05. 29.08. 08.10. |
| 2015 | 6 | 03.03. 29.05. 24.08. 15.10. 03.11. 03.12. |
| 2016 | 8 | 05.01. 22.02. 17.03. 05.08. 12.09. 07.11. 05.12. 28.12. |
| 2017 | 6 | 20.03. 01.06. 01.08. 08.08. 23.10. 11.12. |
| 2018 | 5 | 19.03. 30.04. 01.08. 22.10. 27.11. |
| 2019 | 5 | 11.03. 08.07. 16.08. 23.08. 29.11. |
| 2020 | 7 | 06.01. 04.03. 17.06. 26.06. 07.09. 18.11. 18.12. |
| 2021 | 4 | 21.04. 21.05. 14.06. 27.09. |
| 2022 | 3 | 08.02. 05.05. 01.06. |
| 2023 | 2 | 28.02. 29.12. |
| 2024 | 4 | 19.03. 26.03. 13.06. 16.07. |
| 2025 | 4 | 18.02. 18.06. 30.09. 23.12. |
| 2026 | 2 | 25.02. 31.08. |

## Known missing versions

The office's download page shows the date of the version that is live. Archived copies of that page prove that these versions were published, but no copy of the PDF has been found:

| Version | Download page archived on |
|---|---|
| 25.02.2022 | 03.03.2022 |
| 18.03.2022 | 20.03.2022 |
| 22.03.2022 | 23.04.2022 |
| 08.09.2022 | 04.10.2022 |
| 21.11.2023 | 29.11.2023 |
| 31.10.2024 | 24.11.2024 |
| 30.12.2024 | 23.01.2025 |
| 12.06.2026 | 18.06.2026 |

A version from around January 2023 (846 pages) is also missing; it is known only from an excerpt published by the Flüchtlingsrat NRW.

The list is not complete: it only covers 2020 onwards, and about a third of the archived pages could not be read. Nothing earlier than September 2007 has been found either, although the oldest copies carry amendment notes going back to 2005.

If you have one of these, see "Adding a version".

## Where the files came from

- **Landesamt für Einwanderung:** the current version, from its [VAB page](https://www.berlin.de/einwanderung/service/downloads/artikel.875097.php).
- **Wayback Machine:** archived copies of the office's download links from 2008 onwards.
- **FragDenStaat:** two freedom-of-information requests that released versions from March 2015 to September 2021 ([first](https://fragdenstaat.de/anfrage/altere-versionen-der-verfahrenshinweise-der-auslanderbehorde-berlin-2/), [second](https://fragdenstaat.de/anfrage/interne-weisungen-erfassung-und-auswertung-geleisteter-arbeit-dienstaufsichtsbeschwerden-47/)).
- **Other copies:** Flüchtlingsrat Niedersachsen and einwanderer.net (2007), Flüchtlingsrat Berlin (2013), Studierendenwerk Berlin (2023).

`index.tsv` in this folder lists each file with its version date and page count.
