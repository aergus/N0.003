# N0.003

Zusammenfassung unserer Vorbereitung auf SS 13 @ Uni Bonn.

## Kurzanleitung zur Formatierung der Beiträge:

Eure Beiträge benötigen **_keine Header_**, das wird mittels einer zentralen Datei gehandhabt.

Ebenfalls bitte **kein \begin{document} bzw. \end{document} verwenden**.

Bitte benennt eure Dateien entsprechend folgender Konvention: Haltet ihr den „ab“-ten Vortrag (Dezimaldarstellung), so sollte eure Datei anaab.tex , laab.tex bzw. almaab.tex halten. Ist a in Dezimaldarstellung 0, so schreibt es dennoch!

Jeder Beitrag sollte mit \subsection{Passender Titel} beginnen, hat der Beitrag weitere Unterteilungen, sollte \subsubsection{Passender Untertitel} verwendet werden.

### Eine Definition sieht so und nur so aus: 

```latex
\begin{definition}
Eine Definition ist eine \textbf{Definition}.
\end{definition}
```

.

### Ein Beispiel sieht so und nur so aus:

```latex
\begin{beispiel}
Dies ist ein Beispiel für ein Beispiel.
\end{beispiel}
```

.

### Ein Satz mit Beweis sieht so und nur so aus:

```latex
\begin{satz}
Dies ist ein Satz.
\end{satz}
\begin{proof}
Er ist korrekt.
\end{proof}
```

. 
Insbesondere werden von dem Format auch automatisch „end-of-proof“-Symbole eingefügt.

### Zu Abbildungen:

Es besteht die Möglichkeit, **Skizzen** (d.h. Bilder) einzufügen. Diese sind standardmäßig von width 8cm, in diesem Fall können sie mit

```latex
\Skizze{Bild10.png}
```

eingebunden werden. Das Bild muss dann natürlich auch hochgeladen werden.


