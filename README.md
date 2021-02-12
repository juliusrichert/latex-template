# Template für `scrartcl`
Seitenränder
- oben,unten,links,rechts: 2,5cm

Schriftarten (XeTeX)
- Main/Serif: Minion Pro
- Sans: Myriad Pro
- Mono: Fira Mono

Pakete
- Mathe: `amsmath,amssymb,mathtools,`
- Chemie: `chemmacros,chemformula,siunitx`
- Informatik: `listings`
- Typographie und Layout: `geometry,microtype,enumitem`
- Bilder: `graphicx,subcaption,tikz`
- Tabellen: `array,makecell,multirow,booktabs`
- Links: `xurl,hyperref`
- Utility: `todonotes,blindtext,`

Makros
- `\hl[color]{hervorgehobener Text}`
- `\Xbb` für X = {N,Z,Q,R,C,P} erzeugt Blackboard-Bold
- `\Xc` für X = {A bis Z} erzeugt `\mathcal{X}`

Umgebungen für Definitionen und Beispiele
```latex
\begin{beispiel}[optionaler Titel]
  Beispieltext
\end{beispiel}

\begin{definition}[optionaler Titel]
  Definitionstext
\end{definition}
```
- auch unnummeriert
- Definitionen eingerahmt in `BrickRed`, 2pt, runde Ecken
- Beispiele in `YellowGreen`
