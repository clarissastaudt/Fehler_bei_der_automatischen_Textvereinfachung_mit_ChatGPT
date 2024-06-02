# Fehler bei der automatischen Übersetzung mit ChatGPT in einfache Sprache 

## Hintergrund

Dieses Repository stellt zur Erhöhung der Transparenz und Nachvollziehbarkeit Daten sowie Skripte zur Verfügung, die sich auf eine Studie von Hohenwalde et al. beziehen. In dieser Untersuchung wurde in der die Fähigkeit von ChatGPT-4-Turbo analysiert, wissenschaftsjournalistische Texte in einfache Sprache zu übersetzen. Zudem bewerteten Codierer im Rahmen einer Inhaltsanalyse die Fehleranfälligkeit dieser Übersetzungen.

Zitationsvorschlag:  Hohenwalde, C. E., Wahl, M., & Lehmkuhl, M. (2024): Kann ChatGPT komplexe wissenschaftsjournalistische Texte verständlich machen? Fehler bei der automatischen Übersetzung mit ChatGPT in einfache Sprache. 

## Dateistruktur des Repositories
- [texte_uebersicht.csv](texte_uebersicht.csv): Enthält eine Übersicht aller in der Studie analysierten Texte. Insgesamt wurden 20 Artikel aus „Spektrum der Wissenschaft" ausgewählt, die zwischen 2019 und 2024 in der Kategorie „News" erschienen und online frei zugänglich sind.
- [data](data): Dieser Ordner enthält die Unterordner [data/originaltexte](data/originaltexte) und [data/vereinfachte_Texte](data/vereinfachte_Texte), die die Originaltexte sowie die automatisch von ChatGPT in einfache Sprache übersetzten Versionen beinhalten.
- [ChatGPT_Uebersetzung_in_einfache_Sprache.ipynb](ChatGPT_Uebersetzung_in_einfache_Sprache.ipynb): Dieses Jupyter Notebook enthält den notwendigen Pythoncode, um Texte mittels des vorgestellten Verfahrens automatisch mit ChatGPT in einfache Sprache übersetzen zu lassen. Zur Ausführung benötigt man einen OpenAI-Account bzw. einen kostenpflichtigen API-Schlüssel. 
- [codierung.csv](codierung.csv): Die Fehleranfälligkeit der automatischen Übersetzungen wurde von zwei Codern im Rahmen einer Inhaltsanalyse bewertet. Die Codierung sowie Kommentare zu den von ChatGPT gemachten Fehlern sind in dieser Datei hinterlegt.
