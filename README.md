# Wonsz. the Game by Nicol Nguyen & Daria Łysenko

## Funkcje i tutorial

Uruchomienie:
Nasza gra została napisana w języku C++ i używa podstawowych plików nagłówkowych i ma miejsce w 100% w terminalu Windows, w związku z tym nie wymaga instalacji dodatkowych bibliotek. Grę można uruchomić normalnie z jednego pliku “main.cpp”. Zaczyna się prostym ekranem głównym.

### Menu

![image](https://github.com/datonenikki/wonsz/assets/83341484/41896fd3-cbea-4fd0-83e8-87d845a89e65)

Po uruchomieniu gry można wejść do ekranu personalizacji wciskając jakikolwiek klawisz oprócz klawisza H. W ekranie personalizacji personalizujemy swoją rozgrywkę “Wonsz. the Game”. Można wybrać poziom trudności dzięki zmianie szybkości poruszania się węża, w skali 1-10. Klawisze, którymi gracz będzie sterował węża też można w tym ekranie spersonalizować. 

![image](https://github.com/datonenikki/wonsz/assets/83341484/8c77232f-fd83-4294-926a-410ecbf9fa39)

### Rozgrywka

Gracz steruje wężem, jego jedynym celem jest zdobywanie punktów za pomocą stykania się główki węża z kwadracikiem odpowiadającym jedzeniu. Gracz może swobodnie przechodzić przez ściany, np. jeśli głową przejdzie przez lewą ścianę, głowa zostanie przeniesiona do prawej strony, a ciało będzie za nią podążać. Jeśli graczowi uda się zdobyć 200 punktów, po czym umrze - pojawia się specjalna wiadomość. Gra kończy się w przypadku, gdy głowa węża zetknie się z jego ciałem.

![image](https://github.com/datonenikki/wonsz/assets/83341484/22e45636-4308-4fd0-b413-098bd9b83198)

![image](https://github.com/datonenikki/wonsz/assets/83341484/f844f453-12c3-4008-9a83-9a41b832a6ef)


### Sterowanie

Gracz sam wybiera klawisze, jakimi będzie sterował wężem, ale w ekranie startowym można użyć H, aby uruchomić ekran historii rozgrywki i W, aby wrócić do ekranu głównego.

#### Historia rozgrywki

![image](https://github.com/datonenikki/wonsz/assets/83341484/d262e1c5-29a7-43c4-9081-2f34dcfdff66)

W przypadku wciśnięcia klawisza H, gracz jest przenoszony do ekranu z historią rozgrywki. Tam gracz może sprawdzić historię swoich podejść, gdzie rezultaty są wyświetlane w kolejności od najnowszego do najstarszego. Wyniki są zapisywane w pliku o nazwie “plik.txt”. Klawiszem W wracamy do ekranu startowego.

#### Aby “Wonsz. the Game” poprawnie działał, potrzebne są w sumie 3 pliki, z czego plik “main.cpp” jest potrzebny do kompilacji i uruchomienia gry w terminalu, a plik “temp.txt” tworzy się tylko w czasie rozgrywki i służy do odnoszenia się do pliku “plik.txt” w celu odczytywania historii wyników w poprawnej kolejności (najnowszy-najstarszy).





