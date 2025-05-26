# Model systemu: Pralka automatyczna (AADL)
Real-time Systems course

## Moje dane:

**Imię i nazwisko:** Konrad Tendaj  
**E-mail:** kon.tendaj@gmail.com


## Opis modelowanego systemu

### Ogólny opis
Model przedstawia system sterowania pralką automatyczną, zaprojektowany przy użyciu języka AADL w środowisku OSATE. Pralka jako system wbudowany składa się z wielu komponentów realizujących funkcje takie jak: napełnianie wodą, podgrzewanie, wirowanie, odpompowywanie wody, obsługa panelu użytkownika oraz komunikacja między komponentami.

### Opis dla użytkownika
System odwzorowuje podstawowe cykle prania i obsługiwany jest przez użytkownika za pomocą prostego interfejsu, który pozwala na wybór trybu pracy. Model umożliwia analizę działania oraz wykrywanie potencjalnych błędów projektowych we wczesnej fazie tworzenia systemu.


## Spis komponentów AADL z komentarzem 

| Typ komponentu | Nazwa komponentu | Opis |
| -------------- | ---------------- | ---- |
| device | WasherMotor | silnik do obracania bębna |
| device | WaterValve | zawór elektroniczny do wody |
| device | WaterLevelSensor | czujnik kontrolujący poziom wody w bębnie |
| device | WaterPump | pompa wyciągająca wodę z bębna |
| device | WaterHeater | grzejnik do wody |
| device | TemperatureSensor | czujnik temperatury wody w zbiorniku |
| device | DoorClosedSensor | czujnik zakmnięcia drzwiczek |
| device | DoorLock | zamek do blokowania drzwi |
| device | UserScreen | ekran sterowania pralką |
| device | ModeChangeKnob | pokrętło do zmiany trybu pralki |
| processor | Microcontroller | procesor do sterowania pracą pralki |
| memory | MainMemory | pamięć do przechowywania ostatnich ustawień programu użytkownika |
| bus | SystemBus | magistrala systemowa do przesyłania danych i sygnałów |


## Model - rysunek

...


## Proponowane metody analizy modelu. Wyniki przeprowadzonych analiz. 

...
