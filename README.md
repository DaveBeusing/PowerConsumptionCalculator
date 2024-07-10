# Power Consumption Calculator
A very simple energy consumption calculator, written as part of my Summer of Code 2024 projects. 🌞


### 🔸 Screenshots
TBD


### Formula
Basic consumption formular based on BdE e.v. (https://www.energieverbraucher.de/)

<br>p = number of persons in the household
<br>wh = base 200 kWh if waterheating is electrically 550 kWh
<br>app = count of large appliances used
<br>s = living space in m²

Consumption = p * wh * app * 200 kWh + s * 9 kWh

In a four-person household of an average family, there are eight large electrical appliances such as televisions or tumble dryers on 120 square meters of living space. 
The calculation here is therefore: 4 * 200 + 8 * 200 + 120 * 9 = 3480. 
3455 kWh of electricity consumption could be expected per year for this household.

<br><b>Usual electricity consumption depending on the living situation (without electric water heating)</b>
Size of Household | Type of Household | low | medium | high
------------------|-------------------|-----|--------|------
1 Person | Apartment | < 1000 kWh | 1000 - 1700 kWh | > 1700 kWh
1 Person | House | < 1800 kWh | 1800 - 3400 kWh | > 3400 kWh
2 Persons | Apartment | < 1700 kWh | 1700 - 2500 kWh | > 2500 kWh
2 Persons | House | < 2500 kWh | 2500 - 3500 kWh | > 3500 kWh
3 Persons | Apartment | < 2100 kWh | 2100 - 3300 kWh | > 3300 kWh
3 Persons | House | < 3000 kWh | 3000 - 4400 kWh | > 4400 kWh
4 Persons | Apartment | < 2300 | 2300 - 3600 kWh | > 3600 kWh
4 Persons | House | < 3500 kWh | 3500 - 5000 kWh | > 5000 kWh


<br><b>Average electricity consumption in apartments with and without hot water preparation**</b>
Size of Household | w/o elec. Waterheating | with elec. Waterheating
------------------|------------------------|------------------------
1 Person  | 1400 kWh p. A. | 1700 kWh p. A.
2 Persons | 2000 kWh p. A. | 2800 kWh p. A.
3 Persons | 2600 kWh p. A. | 3600 kWh p. A.
4 Persons | 2900 kWh p. A. | 4200 kWh p. A.


<br><b>Average electricity consumption in the house without and with hot water preparation**</b>
Size of Household | w/o elec. Waterheating | with elec. Waterheating
------------------|------------------------|------------------------
1 Person  | 2400 kWh p. A. | 2700 kWh p. A.
2 Persons | 3000 kWh p. A. | 3500 kWh p. A.
3 Persons | 3600 kWh p. A. | 4500 kWh p. A.
4 Persons | 4000 kWh p. A. | 5100 kWh p. A.

**Source German "Stromspiegel 2022/23"


### 🔸License
Copyright ©️ 2024 Dave Beusing

MIT License - https://opensource.org/license/mit/

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished 
to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION 
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE 
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.