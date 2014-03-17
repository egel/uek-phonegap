# UEK Phonegap
> Aplikacja tworzona na zajęcia z Zaawansowanych Aplikacji Internetowych w oparciu o technologię Phonegap oraz jQuery mobile

## Zadanie
Zbudowanie aplikacji w oparciu o HTML5 + CSS + JavaScript.

Wykońać do tego:

  - skórkę na postawie [http://themeroller.jquerymobile.com/](http://themeroller.jquerymobile.com/),
  - zbudować apikację na urządzenia mobilne dzięki usłudze [Phonegap Build](http://build.phonegap.com).

### Instalacja

 - Pobrać plik `.zip`
 - lub użyć git'a

```bash
cd /path/to/your/folder/
git clone git@github.com:egel/uek_stal_zai_zadanie_1.git
```

## Wytyczne

  1. Wykonaj aplikację ‘UEK’ zgodnie z podaną treścią zadania.
  2. Dodaj do menu aplikacji pozycję ‘Autor’.
  3. Dodaj do aplikacji ekran ‘Autor’, na którym wyświetl swoje dane personalne: imię i nazwisko, nr albumu, nr grupy dziekańskiej.
  4. Utwórz motyw dla aplikacji, w którym zdefiniuj kolory dla poszczególnych jej elementów (napisy, tła, nagłówki, stopki, elementy formularza, itd.)
  5. Utwórz plik konfiguracyjny aplikacji „config.xml”, w którym określ nazwę oraz nr wersji aplikacji, wprowadź jej krótki opis, oraz wprowadź dane personalne autora aplikacji (imię i nazwisko). Szczegóły znajdziesz pod adresem: [http://docs.build.phonegap.com/en_US/3.1.0/configuring_basics.md.html#The%20Basics](http://docs.build.phonegap.com/en_US/3.1.0/configuring_basics.md.html#The%20Basics)
  6. Zaprojektuj i dodaj do aplikacji ikonę. Przygotuj zestaw ikon w zależności od wielkości ekranu urządzenia mobilnego. Do utworzenia wielu ikon możesz wykorzystać poniższą usługę. Umieść ikony w odpowiednim folderze. Zmodyfikuj plik konfiguracyjny „config.xml”. [http://android-ui-utils.googlecode.com/hg/asset-studio/dist/index.html](http://android-ui-utils.googlecode.com/hg/asset-studio/dist/index.html)
  7. Zaprojektuj i dodaj do aplikacji „splash screen”. Przygotuj różne wersje ekranu startowego w zależności od wielkości ekranu urządzenia mobilnego. Do jego utworzenia możesz również wykorzystać powyższą usługę. Zmodyfikuj plik konfiguracyjny „config.xml”.
  8. Wprowadź zmiany w pliku konfiguracyjnym, aby w serwisie Phonegap Build tworzona była tylko wersja aplikacji dla systemu operacyjnego Android. Wprowadź zmiany w pliku konfiguracyjnym.
  9. Korzystając z usługi ‘Phonegap Build’, utwórz natywną wersję aplikacji dla systemu operacyjnego Android.
  10. Umieść wszystkie pliki wchodzące w skład aplikacji (apk, html, css, itd.) w archiwum ZIP o nazwie TwojeNazwiskoImie-UEK.zip a następnie prześlij plik ZIP na platformę Moodle do oceny.


### Wsparcie

  - [W3School](http://www.w3schools.com/jquerymobile/jquerymobile_examples.asp) jQuery Mobile examples
  - WAŻNE - Zanim projekt zostanie przekompilowany do aplikacji mobilnej, warto sprawdzić go odpowiednim [validatorem](http://validator.w3.org/#validate_by_input) udostępnionemu dzięki konsorcjum **W3C**, aby pozbyć się potencjalnych błędów w działaniu aplikacji.


### Phonegap Build

Dzięki usłudze [build.phonegap.com](http://build.phonegap.com) można w bardzo przyjemny sposób połaczyć niniejsze repozytorium z usługą.

Wystarczy:

  - Podać URL do repozytorium (usługa rozpoznaje tylko gałąć master) np.:`https://github.com/egel/uek_stal_zai_zadanie_1/`,
  - Skonfigurować aplikację dołączając:
    - tytuł,
    - opis,
    - wersję,
    - konfigurację (zalecana powyżej v3.0.0)
    - opis
  - A następnie zbudować aplikację

## License
Oprogramowanie na licencji [GNU AGPLv3](http://www.gnu.org/licenses/agpl-3.0.html)
