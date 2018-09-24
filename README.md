
# Table of Contents

1.  [Aktiver Tiefpassfilter im Rahmen des Schaltungstechnik Praktikums](#org2ca6da9)
    1.  [Realisierung eines 1kHz Tiefpassfilter mit veränderlicher Verstärkung](#orgb551641)
    2.  [Bill of Materials](#orga90318e)


<a id="org2ca6da9"></a>

# Aktiver Tiefpassfilter im Rahmen des Schaltungstechnik Praktikums


<a id="orgb551641"></a>

## Realisierung eines 1kHz Tiefpassfilter mit veränderlicher Verstärkung

Der Filter nutzt eine Sallen-Key Topologie und kann mit verschiedenen Spannungsquellen betrieben werden.
Desweiteren lässt sich die Verstärkung über ein Potentiometer verstellen.

Der Jumper ist entsprechend der Spannungsversorgung zu setzen. Auf der Stellung **GND** wird das GND potential
zur Referenzspannung für den Verstärker, somit sollte eine symmetrische Spannungsversorgung genutzt werden.
Auf der Stellung **REF** wird eine interne Referenzspannung genutzt, es ist empfohlen das Spannungsquelle und
Signal in diesem Fall voneinander galvanisch getrennt sind.


<a id="orga90318e"></a>

## Bill of Materials

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-right" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">Pos</th>
<th scope="col" class="org-left">Item</th>
<th scope="col" class="org-left">Value</th>
<th scope="col" class="org-left">Package</th>
<th scope="col" class="org-right">Qty</th>
<th scope="col" class="org-left">Cost</th>
<th scope="col" class="org-left">Link</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-right">1</td>
<td class="org-left">Op-Amp</td>
<td class="org-left">ADA4610-2</td>
<td class="org-left">SOIC-8</td>
<td class="org-right">1</td>
<td class="org-left">2.04 €</td>
<td class="org-left">[@digikey](https://www.digikey.de/product-detail/de/analog-devices-inc/ADA4062-2ARZ/ADA4062-2ARZ-ND/1979393)</td>
</tr>


<tr>
<td class="org-right">2</td>
<td class="org-left">Capacitor</td>
<td class="org-left">10uF</td>
<td class="org-left">SMT 5x5.4</td>
<td class="org-right">1</td>
<td class="org-left">0.30 €</td>
<td class="org-left">[@digikey](https://www.digikey.de/product-detail/de/panasonic-electronic-components/EEE-1VA100WR/PCE3948CT-ND/766324)</td>
</tr>


<tr>
<td class="org-right">5</td>
<td class="org-left">Potentiometer</td>
<td class="org-left">100kΩ</td>
<td class="org-left">SMT</td>
<td class="org-right">1</td>
<td class="org-left">0.71 €</td>
<td class="org-left">[@digikey](https://www.digikey.de/product-detail/de/vishay-sfernice/TS53YL104MR10/TS53YL-100KCT-ND/1587994)</td>
</tr>


<tr>
<td class="org-right">3</td>
<td class="org-left">Pin Header</td>
<td class="org-left">Male</td>
<td class="org-left">THT 1x3</td>
<td class="org-right">3</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-right">6</td>
<td class="org-left">Resistor</td>
<td class="org-left">47kΩ</td>
<td class="org-left">SMT 0603</td>
<td class="org-right">3</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-right">7</td>
<td class="org-left">Resistor</td>
<td class="org-left">820kΩ</td>
<td class="org-left">SMT 0603</td>
<td class="org-right">1</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-right">8</td>
<td class="org-left">Resistor</td>
<td class="org-left">3.3kΩ</td>
<td class="org-left">SMT 0603</td>
<td class="org-right">1</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-right">9</td>
<td class="org-left">Capacitor</td>
<td class="org-left">100nF</td>
<td class="org-left">SMT 0603</td>
<td class="org-right">4</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-right">10</td>
<td class="org-left">Capacitor</td>
<td class="org-left">1.2nF</td>
<td class="org-left">SMT 0603</td>
<td class="org-right">2</td>
<td class="org-left">&#xa0;</td>
<td class="org-left">&#xa0;</td>
</tr>
</tbody>
</table>

