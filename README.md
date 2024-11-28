# Miniatura-NCN

**************************** English description ****************************

The data and results stored in this repository were obtained within the framework of the research activity MINIATURE 7 (No. 2023/07/X/NZ9/00300) “Frost resistance in freshwater mussels - influence of individual condition and habitat parameters”, funded by the National Science Center.

Description of the files provided and their contents:

Mussels.csv - Table showing descriptive statistics of age (Age) and shell length (Length [mm]) of collected individuals of Anodonta anatina. Variable - variable under study, Region - categorical variable describing the region from which specimens were sampled (Scandinavia/Poland/Portugal), Habitat - categorical variable describing the form of the terrain (Highland/Lowland), Locality - (categorical variable) code of the site from which specimens of A. anatina, Valid N - the number of collected and measured individuals at a given locality, Mean - the mean value of the studied parameter, Median - the median of the studied parameter, Minimum - the lowest value of the studied parameter at a given locality, Maximum - the highest value of the studied parameter at a given locality, LQ - the donly quartile (25%) of the studied parameter at a given locality, UQ - the upper quartile (75%) of the studied parameter at a given locality, SD - the standard deviation of the mean of the studied parameter at a given locality,

Localities.csv - List of sampled sites. Site - name of the site, Code - code of the site, Country - name of the country in which the site is located.

Shape.csv - Table showing the effective Principal Components describing the shape of the shells of collected individuals of A. anatina obtained using the EFD (Elliptical Fourier Descriptors) method. Mussel_ID - unambiguous identifier of the analyzed individual, consisting of the locality code and the number of the individual, PC1 - First Principal Component, PC2 - Second Principal Component, PC3 - Third Principal Component, PC4 - Fourth Principal Component, PC5 - Fifth Principal Component.

INFO.txt - File containing description of data collection, protocol and methodology of laboratory work.

t_water_Flake.txt - output file with modelled mean monthly and mean weekly water temperatures in each lake using FLake. 

glycogen.xlsx - Table showing the glycogen concentration in analysed mussels. ID - unambiguous identifier of the analyzed individual, consisting of the locality code and the number of the individual, Region - categorical variable describing the region from which specimens were sampled (Scandinavia/Poland/Portugal), Habitat - categorical variable describing the form of the terrain (Highland/Lowland), glycogen - glycogen concentration [ug/ml]

length.xlsx - Table showing the shell length and age of collected mussels. ID - unambiguous identifier of the analyzed individual, consisting of the locality code and the number of the individual, Region - categorical variable describing the region from which specimens were sampled (Scandinavia/Poland/Portugal), Habitat - categorical variable describing the form of the terrain (Highland/Lowland), length - shell length of each individual [mm], age - age [years] of each individual.

regressions.xlsx - Table showing row data used in Regression analysis. glycogen - glycogen concentration in mussel tissues [ug/ml], SCP - measured supercooling point [deg C], t_water - measured water temperature [deg C]


**************************** Opis w języku polskim: ****************************

Umieszczone w tym repozytowium dane oraz wyniki zostały pozyskane w ramach działania badawczego MINIATURA 7 (nr 2023/07/X/NZ9/00300) "Odporność na zamarzanie u małży słodkowodnych - wpływ kondycji osobnika i parametrów siedliska", finansowanego przez Narodowe Centrum Nauki.

Opis udostępnionych plików i ich zawartości:

Mussels.csv - Tabela przedstawiająca statystyki opisowe wieku (age) oraz długości muszli (Length [mm]) zebranych osobników Anodonta anatina.
    Variable - badana zmienna,
    Region - zmienna kategoryczna opisująca region z którego pobierano próby (Skandynawia/Polska/Portugalia),
    Habitat - zmienna kategoryczna opisująca forme terenu (wyżyna - Highland/ nizina - Lowland),
    Locality - (zmienna kategoryczna) kod stanowiska z którego pobierano osobniki A. anatina,
    Valid N - liczba pobranych i zmierzonych osobników na danym stanowisku,
    Mean - wartość średnia badanego parametru,
    Median - mediana badanego parametru,
    Minimum - najniższa wartość badanego parametru na danym stanowisku,
    Maximum - najwyższa wartość badanego parametru na danym stanowisku,
    LQ - donly kwartyl (25%) badanego parametru na danym stanowisku,
    UQ - górny kwartyl (75%) badanego parametru na danym stanowisku,
    SD - odchylenie standardowe średniej badanego parametru na danym stanowisku,

Localities.csv - Lista stanowisk z których pobierano próby.
    Stanowisko - nazwa stanowiska,
    Kod - kod stanowiska,
    Kraj - nazwa kraju na terenie którego położone jest stanowisko

Shape.csv - Tabela przedstawiająca efektywne Główne Składowe (Principal Components) opisujące kształt muszli zebranych osobników A. anatina uzyskane za pomocą metody EFD (Elliptical Fourier Descriptors).
    Mussel_ID - jednoznaczny identyfikator analizowanego osobnika, składający się z kodu stanowiska oraz numeru osobnika,
    PC1 - Pierwsza Główna Składowa,
    PC2 - Druga Główna Składowa,
    PC3 - Trzecia główna składowa,
    PC4 - Czwarta Główna Składowa,
    PC5 - Piąta Główna składowa

INFO.txt - Plik zawierający opis zbierania danych, protokół oraz metodykę prac laboratoryjnych.

t_water_Flake.txt - plik wyjściowy z wynikami modelowania średniej miesięcznej i średniej tygodniowej temperatury wody w jeziorach za pomocą modelu FLake. 

glycogen.xlsx - Tabela przedstawiająca stężenie glikogenu w tkankach analizowanych małży. ID - jednoznaczny identyfikator analizowanego osobnika, składający się z kodu stanowiska i numeru osobnika, Region - zmienna kategoryczna opisująca region, z którego pobrano próbki (Skandynawia/Polska/Portugalia), Habitat - zmienna kategoryczna opisująca formę terenu (Wyżyna/Nizina), glikogen - stężenie glikogenu [ug/ml].

length.xlsx - Tabela przedstawiająca długość muszli i wiek zebranych osobników. ID - jednoznaczny identyfikator analizowanego osobnika, składający się z kodu miejscowości i numeru osobnika, Region - zmienna kategoryczna opisująca region, z którego pobrano osobnika (Skandynawia/Polska/Portugalia), Habitat - zmienna kategoryczna opisująca formę terenu (Wyżyny/Niziny), Długość - długość muszli każdego osobnika [mm], Wiek - wiek [lata] każdego osobnika.

regressions.xlsx - surowe dane użyte w analizie regresji glycogen -stężenie glikogenu w tkankach małża [ug/ml], SCP - zmierzony punkt przechłodzenia [stopnie C], t_water - zmierzona temperatura wody [stopnie C]
