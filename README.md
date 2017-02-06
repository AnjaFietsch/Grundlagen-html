# Welcome to GitHub Pages

<h2> 
Eine Erkärung für html und deren Grundfunktionen.
</h2>

<h3>
<a id="Inh">Inhaltsverzeichins</a></h3>

<ul>
<li><a href="#Übe">1. Überschriften</a></li>
<li><a href="#Abs">2. Absätze</a></li>
<li><a href="#Fet">3. Textformatierung</a></li>
<li><a href="#Inn">4. innere Links</a></li>
<li><a href="#Äuß">5. äußere Links</a></li>
<li><a href="#Bil">6. Bilder</a></li>
<li><a href="#Tab">7. Tabellen</a></li>
<li><a href="#Que">8. Quellen</a></li>
</ul>

<h3>
<a id="Übe">1. Überschriften</a>
</h3>

<h1>
Überschrift
</h1>


<h2>
Überschrift
</h2>


<h3>
Überschrift
</h3>


<h4>
Überschrift
</h4>


<h5>
Überschrift
</h5>


<h6>
Überschrift
</h6>

<h3>
<a id="Abs">2. Absätze</a>
</h3>

<p>Um einen Absatz zu erstellen muss ein Befehl verwendet werden.</p>

<p>Ohne den Befehl ensteht ein langer Textblock</p>

<p>Egal wie lang ein Textblock ist, am Anfang und am Ende muss ein Befehl gesetzt werden.
Einfach in die nächste Zeile schreiben erstellt
keinen
Zeilenumbruch</p>

<p>Wenn ein Zelienumbruch erzwungen werden soll wird der Befehl "br" verwendet,<br>
durch diesen findet ein einfacher<br>
Zeilenumbruch statt</p>

<ul>
<li>Es können auch Listen erstellt werden, in denen ein automatischer Zeilenumbruch stattfindet</li>
<li>Thema 1</li>
<li>Thema 2</li>
<li>Thema 3</li>
</ul>

<h3>
<a id="Fet">3. Textformatierung</a>
</h3>

<p>Um <b>fett</b> zu schreiben wird der Befehl "b" verwendet. <b>Auch längere Texte können bearbeitet werden.</b></p>

<p>Um <i>kursiv</i> zu schreiben wird der Befehl "i" verwendet. <i>Auch hier gilt wieder die Regel für längere Texte.</i></p>

<p>Text kann auch <mark>markiert</mark> werden.</p>

<p>Oft ist es praktisch auch <sub>tiefgestellt</sub> oder <sup>hochgestellt</sup> schreiben zu können. Dies bezieht sich immer auf das vorherige Wort und wird diesem angeschlossen.</p>

<p style="color:blue;">Auch die Schriftfarbe kann verändert werden.</p>

<p style="color:orange;">Fast alle Farben sind möglich, in den Quellen ist eine Liste angegeben.</p>

<p>Es gibt noch weitere Befehle, die verwendet werden können, um Text zu formatieren. Diese können <a href="http://www.w3schools.com/html/html_formatting.asp">"hier"</a> nachgelesen werden.</p>

<h3>
<a id="Inn">4. innere Links</a>
</h3>

<p>Für innere Verlinkungen im Dokument, also zum Beispiel für ein Inhaltsverzeichnis, werden mehrere Befehle benötigt.</p>

<p><a href="#Inh">Inhaltsverzeichnis</a></p>

<p>Es wird also die Zeile als normaler Paragraph markiert, und mit dem Befehl "href=#(id Bookmark) und "a" die Verlinkung generiert.
Zusätzlich muss an die Stelle, zu die der Link führen soll, markiert werden.<br>
Dies geschieht durch eine id, die zugewiesen wird. Auch hier darf der Befehl "a" nicht ausgelassen werden.</p>

<p>Jedes Bookmark, dass durch eine id markiert ist kann von jeder beliebigen Stelle aus aufgerufen werden und verlinkt werden und auch mehrfach verwendet werden.</p>

<h3>
<a id="Äuß">5. äußere Links</a>
</h3>

<p>Äußere Links, also Links, die zu anderen Websites führen, verhalten sich ähnlich wie die inneren Links.<br>
Um einen äußeren Link zu erstellen wird dieselbe Form verwendet, die auch ein innerer Link verwendet, mit dem Unterschied, dass keine id notwendig ist. Stattdessen wird der Link zum Ziel eingefügt.</p>

<p><a href="http://stormarnschule.de/">Stormarnschule</a></p>

<p>Solange der Link erreichbar ist findet eine automatische Weiterleitung statt und die Ziel-Website öffnet sich. Wie der Link, den man auf der Website sieht, heißt, spielt keine Rolle.</p>

<h3>
<a id="Bil">6. Bilder</a>
</h3>

<p>Bilder besitzen einen eigenen Befehl, auch die Größe der Bilder kann variiert werden um beispielsweise zwei Bilder nebeneinander zu stellen.</p>

<p><img src="images/Bild1.jpg" alt="Bild1" style="width:420px;height:420px;border:0;"></p>

<p>Die Bilder sollten in einem Ordner im repository abgelegt sein, damit diese problemlos geladen werden können.</p>

<h3>
<a id="Tab">7. Tabellen</a>
</h3>

<p>Es gibt einfache Tabellen, die ohne großen Aufwand erstellt werden können. Diesen können durch zusätzliche Befehle aber weitere Funktionen und individualisierungen zugewiesen werden.<br>
Hier zeige ich eine einfache Tabelle, für weitere Informationen kann <a href="http://www.w3schools.com/html/html_tables.asp">hier</a> gesucht werden.</p>

<table>
<thead>
<tr>
<th>Spalte 1</th>
<th align="center">Spalte 2</th>
<th align="center">Spalte 3</th>
</tr>
</thead>
<tbody>
<tr>
<td>Spalte 1.1</td>
<td align="center">Spalte 2.1</td>
<td align="center">Spalte 3.1</td>
</tr>
<tr>
<td>Spalte 1.2</td>
<td align="center">Spalte 2.2</td>
<td align="center">Spalte 2.3</td>
</tr>
<tr>
<td>Spalte 1.3</td>
<td align="center">Spalte 2.3</td>
<td align="center">Spalte 3.3</td>
</tr>
<tr>
<td>Spalte 1.4</td>
<td align="center">Spalte 2.4</td>
<td align="center">Spalte 3.4</td>
</tr>
</tbody>
</table>

<p>Dieses Muster kann unendlich weitergeführt werden, wobei "tr" eine neue Zeile darstellt und "td" eine neue Spalte erstellt.</p>

<h3>
<a id="Que">8. Quellen</a>
</h3>

<p><a href="https://wiki.selfhtml.org/wiki/Startseite">selfhtml Wiki</a><br>
<a Href="http://www.w3schools.com/">w3schools</a><br>
<a Href="http://www.w3schools.com/colors/colors_names.asp">html Color names</a>
