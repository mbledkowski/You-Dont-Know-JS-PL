# Nie Znasz Jeszcze JS-a
# Wstęp

Witaj w drugiej części, szeroko uznanej serii książek You Don't
Know JS (YDKJS): You Don't Know JS Yet (YDKJSY).

Jeśli przeczytałeś jakąkolwiek książkę z pierwszej edycji, spodziewaj się
odświeżonego podejścia w nowych książkach, z dużą ilością zaktualizowanego
pokrycia, tego co się zmieniło w JS-ie w czasie ostatnich pięciu lat.
To w co wierzę i mam nadzieję, to to, że wciąż dostaniesz z niej
to samo poświęcenie do respektowania JS-a i wchodzenia w szczegóły,
które powodują, że wszystko klika.

Jeśli to twój pierwszy raz, z tymi książkami, to cieszę się, że tu jesteś.
Przygotuj się na głęboką i obszerną podróż po wszystkich zakątkach JavaScript'u.

Jeśli jesteś nowy w programowaniu lub JS-ie, miej na uwadze to, że te książki nie
są stworzone jako delikatny "wstęp do JavaScript'u". Materiały te, momentami
skomplikowane i wyzywające, idą znacznie głębiej, niż jest to typowe dla
początkujących uczniów. Jesteś tu mile widziany niezależnie od twojej wiedzy,
jednak książki te zostały napisane wychodząc z założenia, że czujesz się komfortowo
z JS-em i masz conajmniej 6-9 miesięcy doświadczenia w nim.

## Elementy

Te książki mają zupełnie przeciwne podejście do JavaScript'u, niż *The Good Parts
(Dobre Elementy)*. Nie, to nie znaczy, że będziemy patrzeć na *złe elementy*, ale
raczej, że będziemy eksplorować **wszystkie elementy**.

Możliwe, że ktoś ci powiedział lub sam czułeś, że JavaScript jest 
niekonsekwentnie zaprojektowanym, w głębi wadliwym językiem. Wiele osób twierdziło,
że jest to najgorszy, spośród najpopularniejszych języków; nikt nie pisze JavaScript'u
ponieważ tego chce, tylko dlatego, że musi biorąc pod uwagę jego położenie w centrum
internetu. Jest to absurdalne, niezdrowe i całkowicie protekcjonalne podejście.

Miliony developerów piszą JavaScript każdego dnia, wiele z nich respektuje i docenia
ten język.

Jak każdy wielki język, ma on swoje świetne strony, jak i blizny. Nawet sam twórca
JS-a, Brendan Eich, lamentuje na temat niektórych z tych elementów języka,
uznając je za błędy. Aczkolwiek on nie ma racji: to wcale nie są błędy. JS jest
tym czym jest dzisiaj - najbardziej wszechobecnym i najbardziej wpływowym językiem
programowania. Dokładnie z powodu *wszystkich tych elementów*.

Nie kupuj kłamstwa, że powinnxś nauczyć się i używać tylko części
*dobrych elementów* i jednocześnie unikać złych. Nie kupuj panaceum o nazwie
"X jest nowym Y", że nowa funkcja języka natychmiast zdegraduje wszelkie użycie
starej funkcji do rangi przestarzałego. Nie słuchaj, gdy ktoś mówi, że twój kod
nie jest "nowoczesny", ponieważ nie używa stage-0 funkcji, która została
zaproponowana kilka tygodni temu!

Każdy element JS-a jest przydatny. Niektóre są przydatniejsze od innych. Niektóre
elementy wymagają, że będziesz ostrożniejszx i bardziej umyślnx.

Moim zdaniem jest to absurdalne, próbować być w pełni efektywnym developerem JS-a,
używając jednocześnie małego wycinka tego, co język ma do zaoferowania. Czy
możesz wyobrazić sobie pracownika budowlanego, który z całego zestawu narzędzi,
używa jedynie młotka i szydzi z śróbokręta i taśmy mierniczej, nazywając je gorszymi?
To jest po prostu głupie.

Moim bezwarunkowym twierdzeniem jest to, że powinnxś pójść drogą uczenia się wszystkich
elementów JavaScript'u i tam gdzie to odpowiednie, używać ich! I jeśli mogę być
na tyle bezczelnym, żeby Ci to zasugerować; to najwyższa pora wyrzucić wszelkie
książki, które mówią ci inaczej.

## Tytuł?

O co chodzi z tym tytułem?

Nie chcę cię urazić moim krytycyzmem, na temat braku twojej aktualniej wiedzy na
temat JS-a. Nie sugeruję, że nie jesteś, bądź nie będziesz w stanie nauczyć się
JS-a. Nie przechwalam się sekretną, insiderską wiedzą, którą tylko ja i kilku
wybranych posiada.

Poważnie, te wszystkie żywe reakcje na temat oryginalnego tytułu pochodzą od ludzi,
którzy nawet tych książek nie przeczytali i są bezpodstawne.

Główny powód dla tytułu You Don't Know JS Yet (Nie Znasz Jeszcze JS-a) jest taki,
że większość osób piszących kod, nie poświęca czasu, by zrozumieć jak na prawdę
on działa. Wiedzą, *że* działa - produkuje output, którego oczekują. Ale nie wiedzą
*jak* działa lub co gorsza, mają niedokładny obraz mentalny tego *jak*, który
mięknie przy bliższej obserwacji.

Prezentuję delikatne, ale poważne wyzwanie, dla ciebie, czytelnika. Odłóż na bok
założenia jakie masz odnośnie JS-a i podejdź do niego z świeżym okiem, oraz
pełną wigoru ciekawością, która prowadzi ciebie do pytania *dlaczego* dla każdej
linii kodu którą piszesz. Dlaczego to robi, to co robi? Dlaczego jedna metoda
jest lepsza lub właściwsza od połowy tuzinu innych sposobów, którymi mogłx byś
to osiągnąć. Dlaczego wszystkie "popularne dzieciaki" mówią, żeby robić X ze
swoim kodem, a tak na prawdę Y może okazać się lepszym wyborem.

Dodałem "Yet" ("Jeszcze") do tytułu, nie tylko dlatego, że jest to druga edycja
lecz ponieważ, chcę aby te książki Ciebie wyzwywały w optymistyczny, aniżeli
odstraszający sposób.

Lecz pozwól mi postawić sprawę jasno: Nie sądzę aby pełne poznanie JS-a było
możliwe. Nie jest to osiągnięcie do zdobycia, tylko raczej cel, do którego 
należy dążyć. Nie kończysz wiedząc wszystko o JavaScript'cie, tylko uczysz się
więcej i więcej, im więcej czasu spędzasz z językiem. Im głębiej pójdziesz, tym
więcej razy spotkasz to co już wiedziałeś i nauczysz się ponownie z bardziej
doświadczonej perspektywy.

Zachęcam ciebie, aby wyrobić sobie mindset wokół JavaScript'u i w zasadzie,
wokół software developementu jako całości, że nigdy nie nauczysz się tego w pełni,
ale że możesz i powinieneś starać się by być bliżej końca tej podróży, która
będzie się ciągnęła przez całą twoją karierę developera i dalej.

Zawsze możesz znać JS-a lepiej, niż znasz go obecnie. To jest to, co mam nadzeję,
reprezentują książki YDKJSY.

## Misja

Naprawdę nie trzeba wyjaśniać, dlaczego developerzy powinni poważnie traktować
JS-a - Myślę, że jest bardziej niż udowodniono, że jest on wartym statusu języka
pierwszej klasy, wewnątrz świata języków programowania.

Ale inna, ważniejsza rzecz wymaga wyjaśnienia i te książki starają się podjąć to
wyzwanie.

Uczyłem ponad 5 tysięcy developerów z zespołów i firm na całym świecie w ponad 25
krajach, na sześciu kontynentach. To co zobaczyłem, to to, że zbyt często to co
ma znaczenie, to rezultat programu, nie to jak program jest napisany i jak/dlaczego
działa.

Moje doświadczenie, nie tylko jako developer, ale również jako osoba która uczyła
wielu innych developerów mówi mi: zawsze będziesz bardziej efektywny w swojej pracy
jako developer, jeśli całkowicie zrozumiesz jak kod działa, niż gdy po prostu
spowodujesz, że będzie produkować pożądany wynik.

W innych słowach, *wystarczająco dobre, żeby działać*, nie jest i nie
powinno być *wystarczająco dobre*.

Wszyscy developerzy regularnie borykają się z problemem, że niektóre fragmenty
kodu nie chcą działać i nie mogą zrozumieć dlaczego. Jednak zbyt często
developerzy JavaScript'u zrzucą to na język, zamiast samemu się przyznać,
że ich zrozumienie języka podupada. Te książki służą zarówno jako pytanie i
odpowiedź: dlaczego to robi *tak*, i tutaj jest jak spowodować, że to zrobi *to*
wzamian.

Moją misją z YDKJSY jest to, aby wzmocnić każdego developera JavaScript, by w pełni
posiadał kod który pisze, by zrozumiał go i pisał intencjonalnie i z zrozumieniem.

## Ścieżka

// TO BE CONTINUED