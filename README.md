# Projekt aplikacji do monitorowania czasu pracy pracowników

## Widoki

### Widok rejestracji
#### Funkcjonalności:
>  Rejestrowanie głównego konta firmowego (Admin główny)
>  Wymaganie podania następujących danych:
>  * Nazwa firmy
>  * Imię i nazwisko 
>  * Adres e-mail
>  * Hasło i powtórzenie hasła

### Widok logowania
#### Funkcjonalności:
> Możliwość logowania użytkowników
> Do systemu będą mieli dostęp wszyscy użytkownicy dodani przez administratora
> Możliwość zresetowania hasła
> Wymaganie podania następujących danych:
> * Login(e-mail)
> * Hasło

### Strona główna
#### Funkcjonalności:
> Przycisk wylogowania
> Przycisk zmiany motywu jasny / ciemny
> Widok zależny od roli użytkownika w systemie
> Pracownik będzie miał możliwość:
> * Rozpoczęcia pracy
> * Zakończenia pracy ( możliwość dodania opisu wykonanych czynności)
> * Możliwość wznowienia pracy przy przypadkowym zakończeniu(dostępny tylko w określonym czasie)
> * Rozpoczęcia przerwy
> * Zakończenia przerwy
>  * Wyświetlenia informacji dot. jego pracy:
>> * Dotychczasowy czas pracy
>> * Aktualny status pracy.
>   
> Administrator / Administrator główny:
> Wyświetlenia informacji dot. pracowników:
>> * Lista ze statusami pracowników na aktualnej zmianie z możliwością zmiany statusu
>> * Zgłoszenie pracowników o nieobecności lub spóźnienia z możliwością akceptacji / nieakceptacji.
>> * Liczba obecnych pracowników na zmianie / Liczba nieobecnych 
>> * Możliwość podglądu czasu pracy pracowników z wybranego okresu

### Zakładki
#### Funkcjonalności:
> Poszczególne zakładki dostępne są dla odpowiednich ról
> Konto:
>> * Dostępne dla pracownika i administratora
>> * Możliwość edycji danych swojego konta (Personalia i hasło)
>
> Pracownicy: 
>> * Dostępne tylko dla administratorów
>> * Lista wszystkich pracowników z informacją o pensji z ostatniego miesiąca.
>> * Możliwość dodania nowego / usunięcia istniejącego / edycja danych.
>> * Przypisanie stawki godzinowej / godzin pracy
>> * Możliwość wyświetlenia raportu dot. pracy wybranego pracownika z wybranego miesiąca
>> * Generowanie raportu do PDF
>
> Firma:
>> * Dostępne tylko dla administratorów
>> * Wyświetlenie informacji o firmie.
>> * Możliwość edycji danych firmy
>
> Raport pracy:
> * Dostępne tylko dla pracowników
> * Wyświetlenia informacji dot. jego pracy z wybranego miesiąca:
>> *  Czas pracy
>> * Wykres godzinowy przerw/czasu pracy
>> * Obliczenie wypłaty 
>> * Lista wykonanych czynności
>> * Generowanie do PDF
