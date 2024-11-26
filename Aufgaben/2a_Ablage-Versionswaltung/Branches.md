# Branches

![Branches][branches]

## Was sind Branches?
Dem Entwickler wird es ermöglicht unabhängig vom main Branch oder anderen Branches, Änderungen am Projekt vorzunehmen. Sobald man fertig ist, kann man diese Änderungen wieder in das main Branch einschliessen.
Vorteile:
* Parallele Entwicklung:
    * Teams können gleichzeitig an verschiedenen Features oder Bugs des Projektes arbeiten.
* Versionskontrolle:
    * Es ist einfach, zu einem stabilen Zustand des Projektes zurückzukehren.
* Isolierung:
    * Änderungen in einem Branch sind unabhängig von anderen Branches und können somit keinen Schaden verurusachen.

## Wie man mit Branches umgeht?
* Zum erstellen eines neuen Branches:

```git branch <branch-name>```

* Um zu einem Branch zu wechseln:

```git switch <branch-name>```

* Einen Branch erstellen und direkt zu diesem wechseln:

```git switch -c <branch-name>```

* Einen abgeschlossenen Branch mit der main zusammenfügen:

```git checkout main```

```git merge <branch-name>```

* Einen Branch löschen:

```git branch -d <branch-name>```


[branches]: /Aufgaben/2a_Ablage-Versionswaltung/Branches.jpg
