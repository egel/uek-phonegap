# Zaawansowane Aplikacje Internetowe

## Zadanie 1
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
  4. Utwórz motyw dla aplikacji, w którym zdefiniuj kolory - [http://themeroller.jquerymobile.com/](http://themeroller.jquerymobile.com/) -  dla poszczególnych jej elementów (napisy, tła, nagłówki, stopki, elementy formularza, itd.)
  5. Korzystając z usługi ‘Phonegap Build’ - [build.phonegap.com](http://build.phonegap.com), utwórz natywną wersję aplikacji dla systemu operacyjnego Android.
  6. Umieść wszystkie pliki wchodzące w skład aplikacji (apk, html, css, itd.) w archiwum ZIP o nazwie `TwojeNazwiskoImie-UEK.zip`, a następnie prześlij plik ZIP na platformę Moodle do oceny.

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

### W3C Validator
Zanim projekt zostanie przekompilowany do aplikacji mobilnej, warto sprawdzić go odpowiednim [validatorem](http://validator.w3.org/#validate_by_input) udostępnionemu dzięki konsorcjum **W3C**, aby pozbyć się potencjalnych błędów w działaniu aplikacji.

## License
Oprogramowanie na licencji [GNU AGPLv3](http://www.gnu.org/licenses/agpl-3.0.html)
