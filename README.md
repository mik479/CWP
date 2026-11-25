# CWP
System zarządzania magazynem części

Dla pracownika:
- dodawanie (in: [nazwa, ilość, gdzie] out: odnowiony magazyn)
- usuwanie (in: [nazwa, ilość, gdzie] out: odnowiony magazyn)
- wyszukiwanie (in: [nazwa] out: [ilość, gdzie])
- sortowanie (in: magazyn out: odnowiony magazyn)

Dla administratora:
- zliczanie artykułów (dostarczone, zakupione, obecny stan) (in: [nazwa, magazyn, lista dostaw, lista zakupów] out: ilość)
- pilnowanie ilości towarow w magazynie i informowanie o wyczerpaniu (in: [nazwa, lista minimalnych ilości, magazyn] out: lista dostaw)
- monitorowanie ilości pracownikow (in: [ilość pracowników, lista dostaw, lista zakupów, wydajność pracownika] out: instrukcja - dodać/usunąć pracownika)
