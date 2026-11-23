# Klimagrößen

Saisonale Angaben beziehen sich auf das meteorologische Jahr, d.h. Angaben für den Frühling basieren auf allen Tagen in März, April und Mai. Der Sommer setzt sich aus allen Tagen der Monate Juni, Juni und August zusammen, der Herbst aus allen Tagen in September, Oktober und November. Angaben für den Winter basieren auf allen Tagen der Monate Januar und Februar sowie des Dezembers des Vorjahres. 

Alle Klimagrößen  wurden auf monatlicher, saisonaler und jährlicher Basis bereitgestellt. Bei Zählindizes (z. B. SU30, FD, RR1 oder R20mm) entspricht der Wert der Anzahl der Ereignisse innerhalb des jeweiligen Zeitraums. Bei Mittelwertindizes (z. B. TG und RRm) entspricht der Wert dem Mittelwert über den jeweiligen Zeitraum. Die Berechnung der Mehrzahl der Kilimagrößen basiert  auf den Definitionen der xclim python [Bibliothek für Klimaservices](https://github.com/Ouranosinc/xclim)*.
<br>
* Bourgault, P., et al. (2023). xclim: xarray-based climate data analytics. Journal of Open Source Software, 8(85), 5415.
https://doi.org/10.21105/joss.05415.
</small>

| Name der Klimagröße | Definition | Index Name |
|---------------------|------------|------------|
|Dauerregen | Anzahl der Ereignisse mit ≥ 60 mm Niederschlag innerhalb von drei aufeinanderfolgenden Tagen | N6 |
|Eistage | Anzahl der Tage mit Tagesmaximumtemperatur < 0 °C | T3 |
|Frosttage | Anzahl der Tage mit Tagesminimumtemperatur < 0 °C | T2 |
|Hagel | Häufigkeit von Hagelereignissen pro Jahr | H1 |
|Heiße Tage | Anzahl der Tage mit Tagesmaximumtemperatur > 30 °C | T2 |
|Heiße Trockentage | Anzahl der Tage mit Tagesmaximumtemperatur > 30 °C und Niederschlag unter dem definierten Perzentil | TN1 |
|Nasse Tage | Anzahl der Tage mit Niederschlag > 1 mm | N2 |
|Saisonale Temperatur | Bodennahe Lufttemperatur in °C | T1 |
|Saisonaler Niederschlag | Mittlere saisonale Tagessumme des Niederschlags (flüssig und fest) | N1 |
|Sonnenscheindauer | Saisonale Sonnenscheindauer pro Tag | E1 |
|Spätfrost im April, Mai und Juni | Anzahl der Tage von April bis Juni mit Tagesminimumtemperatur < 0 °C | T3 |
|Spätfrost im März | Anzahl der Tage im März mit Tagesminimumtemperatur < 0 °C | T4 |
|Starkregen | Anzahl der Tage mit Niederschlag ≥ 20 mm | N5 | 
|Sehr heiße Tage | Anzahl der Tage mit Tagesmaximumtemperatur > 35 °C | T4 |
|Tropische Nächte | Anzahl der Tage mit Tagesminimumtemperatur > 20 °C | T5 | 
|Trockentage | Anzahl der Tage mit Niederschlag < 1 mm | N3 | 
|Trockenperioden | Anzahl von Trockenperioden mit mindestens fünf aufeinanderfolgenden Tagen und Niederschlag < 1 mm | N4 |
