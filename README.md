# Mybb-Bump-Thread-plugin

Podbij temat / Bump Thread Addon for MyBB

 Autor: -n3veR (ja)
 Modyfikacje: Dedito
 
 Plugin umożliwia użytkownikom podbicie własnych tematów bez pisania postów. Plugin bazuje na starej wersji pluginu 'Bump Thread' od ZiNgA BuRgA (wielkie podziękowania).

Dodatkiem można zarządzać przez ACP: Konfiguracja -> Ustawienia -> Podbij Temat - Opcje.

Zmienna wyświetlająca przycisk, to: {$bumpthread} - i po zainstalowaniu znajduje się ona w szablonie showthread.

Wygląd można modyfikować poprzez odwołanie się do klas: button, button-bump w CSSie.

Uwaga!
Wtyczka wymaga PHP w wersji co najmniej 5.6

Poprawiono:

    Możliwość podbijania nie swoich wątków przez adminów i modów,
    Ukrywanie buttona przed nieuprawnionymi,
    Błąd przy aktywacji wtyczki związany z brakiem pola description.

