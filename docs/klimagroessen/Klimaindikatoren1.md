# Klimaindikatoren

<small><span style="color:blue;">Hinweise: </span>
Die Werte für Jahresmittel und Jahreszeiten werden aus Tagesmittelwerten, bzw. Tagesmaximalwerten oder Tagesminimalwerten berechnet. 

Alle Indizes werden auf **monatlicher, saisonaler und jährlicher Basis** bereitgestellt. Bei Zählindizes (z. B. SU30, FD, RR1 oder R20mm) entspricht der Wert der Anzahl der Ereignisse innerhalb des jeweiligen Zeitraums. Bei Mittelwertindizes (z. B. TG und RRm) entspricht der Wert dem Mittelwert über den jeweiligen Zeitraum.

Saisonale Angaben beziehen sich auf das meteorologische Jahr, d.h. Angaben für den Frühling basieren auf allen Tagen in März, April und Mai. Der Sommer setzt sich aus allen Tagen der Monate Juni, Juni und August zusammen, der Herbst aus allen Tagen in September, Oktober und November. Angaben für den Winter basieren auf allen Tagen der Monate Januar und Februar sowie des Dezembers des Vorjahres. 
<br><br>
Die Berechnung der Mehrzahl der Indizes basiert auf den Definitionen der xclim python [Bibliothek für Klimaservices](https://github.com/Ouranosinc/xclim)*.
<br>
* Bourgault, P., et al. (2023). xclim: xarray-based climate data analytics. Journal of Open Source Software, 8(85), 5415.
https://doi.org/10.21105/joss.05415.
</small>



| Index ID | Index Name | Definition |
|-----------|------------|------------|
| **TG (tas)** | Bodennahe Lufttemperatur (2 m über Grund) | Bodennahe Lufttemperatur (2 m über Grund). |
**SU30 (tasmax)** | Heiße Tage | Anzahl an Tagen pro Jahr bzw. pro Jahreszeit mit einer Tagesmaximumtemperatur von mehr als 30 °C. |
| **SU35 (tasmax)** | Sehr heiße Tage | Anzahl an Tagen pro Jahr bzw. pro Jahreszeit mit einer Tagesmaximumtemperatur von mehr als 35 °C. |
| **TR (tasmin)** | Tropische Nächte | Anzahl an Tagen pro Jahr mit einer Minimumtemperatur von mehr als 20 °C. |
| **FD (tasmin)** | Frosttage | Anzahl der Tage pro Jahr bzw. pro Jahreszeit mit einer Tagesmaximumtemperatur geringer als 0 °C. |
| **ID (tasmax)** | Eistage | Anzahl der Tage mit einer täglichen Höchsttemperatur (tasmax) unter 0 °C. |
| **RRm (pr)** | Niederschlag |  Die Niederschlagswerte werden als mittlere jährliche bzw. saisonale Tagessummen des Niederschlags angegeben. Sie beinhalten sowohl flüssigen als auch festen Niederschlag. |
| **RR1 (pr)** | Tage mit messbarem Niederschlag | Anzahl der Tage mit einer Niederschlagsmenge von mindestens 1 mm/Tag. |
| **DD (pr)** | Trockentage | Anzahl der Tage mit einer Niederschlagsmenge von weniger als 1 mm/Tag. |
| **DSf (pr)** | Trockenperioden | Anzahl zusammenhängender Trockenperioden mit weniger als 1 mm Niederschlag pro Tag. |
| **R20mm (pr)** | Starkniederschlagstage | Anzahl der Tage pro Jahr bzw. pro Jahreszeit, an denen die Niederschlagsmenge von 20 mm erreicht oder überschritten wird. |
| **CRE (pr)** | Andauerndes Niederschlagsereignis | Ereignis, bei dem die akkumulierte Niederschlagssumme innerhalb eines gleitenden Fensters von mindestens drei aufeinanderfolgenden Tagen 50 mm oder mehr erreicht. |

<span style="color:orange;"> Kombinierte Extremereignisse </span>

| Index ID | Index Name | Definition |
|-----------|------------|------------|
| **CHDD** | Kombinierte heiße und trockene Tage | Anzahl der Tage, an denen die Höchsttemperatur mindestens 30 °C erreicht und gleichzeitig der Tagesniederschlag unter dem 25. Perzentil der Referenzperiode 1971 bis 2000 liegt. |
