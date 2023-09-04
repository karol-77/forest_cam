# WildCamX
![image](https://github.com/karol-77/WildCamX/assets/73350901/10eed231-5f6d-4524-bbc3-6bd7c4f90a14)


Kamera służąca do wykrywania zwierząt w lesie poprzez czujnik ruchu.


## Elementy systemu 
1. Procesor kontrojący elementy - głowny element kontrolujący inne elementy, oraz przechwytujący obraz z kamery
2. Akumulator - żródło zasilania
3. Panele słoneczne - system ładowania baterii
4. System wykrywający ruch
5. Oświetlenie IR - potrzebny aby kamera mogła nagrywać w nocy
6. Przetwornik obrazu (czujnik optyczny, kamera)  
7. Modem LTE - do przesyłania filmów na inne urządzenia
8. Mikrokontroler wybudzający procesor w razie wykrycia ruchu 

## Opis działania
System ma się wybudzać w razie wykrycia ruchu w celu zwiększenia żywotności baterii. Kamera będzie włączać nagrywanie na 1 minutę a następnie ponownie przechodzić w stan uśpienia.
