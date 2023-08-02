### Dlaczego?
Podstawowy system broni pozostawia wiele do życzenia. Brakuje tam jakiejkolwiek różnorodności. Dlatego, celem poprawienia zarówno jakości, jak i satysfakcji z gry, proponuję to oto rozszerzenie
### Jak?
Całość będzie rozwijać podstawowy system broni poprzez dodanie do bazy różnego rodzaju bonusów, dzięki czemu będzie można stworzyć wiele ciekawych kombinacji, i w miarę możliwości, odwzorować większość historycznej broni.

### Podstawy
Przypomnijmy sobie raz jeszcze podstawę broni:

|Nazwa|Obrażenia|Cena|
|---|---|---|
|**Bez Broni**|1|Darmowy|
|**Podstawowa**|k6|128|
|**Dobra**|k8|256|
|**Potężna**|k10|512|

Aby stworzyć coś ciekawego na daną bazę należy *nałożyć* cechy, zmieniając przy okazji cenę broni za każdy. Niektóre cechy uniemożliwiają dodanie jakiejś innej cechy. Opisane jest to w kolumnie _**Wykluczone**_

|Nazwa|Cena|Opis|Wyklucza|
|---|---|---|---|
|Dwuręczna|1|Z broni można korzystać jedynie za pomocą dwóch rąk. +2 do puli ataku, +1 do obrażeń|Półtoraręczna|
|Parująca|0.5|+1 do puli w obronie||
|Obronna|-0.5|Zwiększ pancerz podczas obrony o połowę obrażeń broni. Nie można wykorzystać w ataku. -2 do obrażeń||
|Kłująca|0.5|+1 do puli ataku. +1 do obrażeń przy nieparzystej liczbie sukcesów, -1 w innym wypadku||
|Ciężka|0.5|Zwiększ obrażenia broni podczas szarży o pół kości obrażeń broni(k6 dostaje k3, k8 ma k4 etc). -1 do puli ataku poza szarżą||
|Druzgocząca|1.5|Do obrażeń broni dodaj różnicę sukcesów między obrońcą a atakującym||
|Ogłuszająca|0.5|+1 do puli ataku, -1 do obrażeń. Zamiast zadawać obrażenia możesz ogłuszyć wroga. By się przed tym obronić, obrońca musi zdać test **Odporności** o puli pomniejszonej o twoje obrażenia|
|Miażdżąca|0.5|Przy ataku obniż pancerz wroga o 1. Pancerz nie może być niższy od 0. Można wykupić wielokrotnie|
|Drzewcowa|0|+1 do puli obrony, -1 do puli ataku|
|Półtoraręczna|0.5|+1 do puli ataku i +1 do obrażeń, gdy broń trzymana jest oburącz|Półtoraręczna|
|Bezużyteczna|Specjalne|Ta broń nie nadaje się do walki. By określić jej wartość, rzuć 10k10|Wszystko|

By obliczyć cenę końcową broni należy do ceny bazowej dodać zsumowaną cenę wszystkich modyfikatorów pomnożoną przez cenę bazową broni.

#### Przykład
*Cena bazowa broni k6 to $\it 128$ złota. Po nałożeniu cech __Dwuręczna__ i __Parująca__ ostateczną cenę broni opisuje równanie $\it{128 + 128 *(1 + 0.5) = 128 + 192 = 320}$  *

Kilka przykładowych broni i ich ceny

|Nazwa|Cena|Bonus Puli|Obrażenia|Cechy|
|---|---|---|---|---|
|Miecz jednoręczny|128|-|k6|-|
|Mała Tarcza|128|+1|k3 - 1|Parująca, Obronna|
|Włócznia|320|+2 Atak / +1 Obrona|k6+1|Drzewcowa, Dwuręczna, Kłująca|
|Topór|192|-1 Atak|k6|Ciężka|
|Wielka Halabarda Zniszczenia|2304|+2/+2|k10+1, -3 AP|Drzewcowa, Dwuręczna, Kłująca, Parująca, Miażdżąca(3)|
|Orczy Tasak|384|-1 Atak|k6|Druzgocząca, Ciężka|

