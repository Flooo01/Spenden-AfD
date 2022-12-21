CODEBUCH

Datenquelle: Rechenschaftsberichte des Deutschen Bundestages (https://www.bundestag.de/parlament/praesidium/parteienfinanzierung/rechenschaftsberichte/rechenschaftsberichte-202446)

Edgelist:

<table>
  <thead>
    <tr>
      <th>Attribut</th>
      <th>Kommentar</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>from</td>
      <td>definiert den Sender der Spende</td>
    </tr>
    <tr>
      <td>to</td>
      <td>definiert den Empfänger der Spende</td>
    </tr>
    <tr>
      <td>donation</td>
      <td>Höhe der Spende, gerundet und geteilt durch 10000</td>
    </tr>
    <tr>
      <td>weight</td>
      <td>Kleinspende=1, Großspende=2, Erbnachlass=3, Spendenjahr=4</td>
    </tr>
    <tr>
      <td>year</td>
      <td>Jahr der Spende</td>
    </tr>
  </tbody>
</table>

Nodelist:

<table>
  <thead>
    <tr>
      <th>Attribut</th>
      <th>Kommentar</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>id</td>
      <td>eindeutige Identifikation jedes einzelnen Knotens, der erfasst wird</td>
    </tr>
    <tr>
      <td>name</td>
      <td>Name oder Bezeichnung des Knotens</td>
    </tr>
    <tr>
      <td>state</td>
      <td>Bundesland des Spenders</td>
    </tr>
    <tr>
      <td>zip code</td>
      <td>Registrierte Postleitzahl des Spenders</td>
    </tr>
    <tr>
      <td>town</td>
      <td>Registrierter Wohnort des Spenders</td>
    </tr>
    <tr>
      <td>type</td>
      <td>Art des Spenders, also natürliche Person (n) oder juristische Person (j); ggf. Spendenjahr (y)</td>
    </tr>
    <tr>
      <td>member</td>
      <td>Mitglied der AfD zur Zeit der Spende: ja (j) oder nein (n)?</td>
    </tr>
    <tr>
      <td>mandate</td>
      <td>Mandatsträger der AfD zur Zeit der Spende: ja (j) oder nein (n)?</td>
    </tr>
    <tr>
      <td>gender</td>
      <td>Geschlecht des Spenders (male=m, female=f, divers=d)</td>
    </tr>
    <tr>
      <td>alter</td>
      <td>Alter des Spenders zum Zeitpunkt der Spende: 20-39 Jahre= y(oung), 40-59 Jahre=m(iddle), 60+=o(ld)*</td>
    </tr>
    <tr>
      <td>doctorade</td>
      <td>Promotion: ja (j) oder nein (n)?</td>
    </tr>
  </tbody>
</table>

	
<i>Info: Der Parameter k definiert fehlende Werte im Datensatz</i>
