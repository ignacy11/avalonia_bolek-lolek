# Lista zadań Bolka i Lolka

Uczeń wpisuje zadanie (np. „pójść na ryby”, „zbudować latawiec”).
Wybiera, kto ma je zrobić – Bolek czy Lolek (ComboBox + obrazek bohatera).
Zaznacza, czy zadanie jest pilne (CheckBox).
Priorytet: łatwe / średnie / trudne (RadioButton).
Wszystkie zadania pojawiają się na liście (ListBox).
Drugie okno – kalendarz przygód: lista zadań przypisana do wybranego dnia.

## Funkcjonalności

1. **Dodawanie zadania**
   ○ Użytkownik wpisuje nazwę zadania w polu **TextBox** (np. _„zbudować domek na drzewie”_ ).
   ○ Kliknięcie przycisku **„Dodaj”** dodaje zadanie do listy.
2. **Przypisanie bohatera**
   ○ Z listy rozwijanej ( **ComboBox** ) użytkownik wybiera, kto ma wykonać zadanie: **Bolek** czy **Lolek**.
   ○ Obok wyświetla się obrazek wybranego bohatera ( **Image** w **Border** ).
3. **Priorytet zadania**
   ○ Za pomocą **RadioButton** można określić priorytet:
   ■ niski ( _łatwe_ ),
   ■ normalny ( _zwykłe_ ),
   ■ wysoki ( _trudne_ ).
4. **Opcje dodatkowe**
   ○ Użytkownik może zaznaczyć pola ( **CheckBox** ), które opisują zadanie, np.:
   ■ „Na dworze”
   ■ „Potrzebny sprzęt”
   ■ „Z udziałem innych kolegów”
5. **Lista zadań**
   ○ Wszystkie dodane zadania wyświetlają się w **ListBoxie** w postaci krótkiego opisu (np. _„Bolek –_
   _zbudować domek na drzewie [trudne]_ 🌳 _”_ ).
   ○ Kliknięcie na element listy zaznacza go, aby można było go później usunąć.


6. **Usuwanie zadań**
   ○ Użytkownik wybiera zadanie z listy i naciska przycisk **„Usuń”** , aby je skasować.
7. **Kalendarz przygód**
   ○ Użytkownik wybiera datę w **Calendar** , do której przypisuje zadanie (np. _„sobota”_ ).
   ○ Drugie okno aplikacji ( **SummaryWindow** ) pokazuje **listę zadań Bolka i Lolka tylko dla**
   **wybranego dnia**.

## Ćwiczone kontrolki i elementy Avalonia

```
● TextBox – wpisywanie treści zadania.
● TextBlock – etykiety i podsumowania.
● ComboBox – wybór bohatera (Bolek/Lolek).
● Image + Border – wyświetlanie avatara bohatera.
● CheckBox – dodatkowe opcje dla zadania.
● RadioButton – priorytet zadania.
● Button – dodawanie/usuwanie zadań, otwieranie drugiego okn.
● ListBox – lista wszystkich zadań.
● Calendar – wybór dnia przygody.
● Drugie okno – podsumowanie zadań dla konkretnej daty.
● Layouty – Grid (układ główny), StackPanel (formularz), WrapPanel (opcje CheckBox).
```
## Przykładowy scenariusz użycia

1. Uczeń wybiera Lolka lub Bolka
2. Uczeń wpisuje w pole _„Nazwa zadania”_ tekst: „pójść na ryby”.
3. Z ComboBoxa wybiera: **Lolek**.
4. Ustawia priorytet: **normalny**.
5. Zaznacza CheckBox: _Na dworze_.
6. W kalendarzu wybiera datę: _15.09._.
7. Kliknięcie przycisku **„Dodaj”** powoduje, że na liście pojawia się wpis:
   _„Lolek – pójść na ryby [normalne]”_.
8. Po naciśnięciu **„Podsumowanie dnia”** otwiera się drugie okno z listą wszystkich zadań przypisanych
   na 15.09.2025.


