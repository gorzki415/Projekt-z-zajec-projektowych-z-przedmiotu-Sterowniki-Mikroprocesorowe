# Projekt-z-zajec-projektowych-z-przedmiotu-Sterowniki-Mikroprocesorowe  
English below.  
  
Jest to projekt płytki PCB wykonany na potrzeby zajęć projektowych z przedmiotu "Sterowniki Mikroprocesorowe"  
  
Tematem zajęć było zaprojektowanie płytki PCB wykorzystującej mikrokontroler do sterowania elementem wyjściowym. Projekt był projektem grupowym, w grupie pracą podzieliliśmy się tak, że ja projektowałem PCB, inna osoba lutowała cały układ i pisała dokumentacje, a trzecia osoba pisała kod.  
  
Jednym z założeń projektu było wykonanie fizycznej płytki a nie tylko schematów.  
  
Zgodnie z założeniami zaprezentowanymi przez prowadzącego trzeba było wykorzystać dowolny mikrokontroler, przynajmniej dwa urządzenia wyjściowe oraz urządzenia wejściowe.  
  
Zaprojektowany układ steruje zaworem, poprzez mikrokontroler w postaci Atmegi 328p oraz układu przekaźnika. Układ wyposażony jest również w zegar RTC oraz czujnik wilgotności gleby, tak aby na podstawie danych z tych czujników można było sterować pracą zaworu. Układ posiada również wyświetlacz, na którym można wyświetlić dowolne parametry, na przykład ile czasu upłynęło od ostatniej aktywacji zaworu czy poziom wilgotności gleby. Dodatkowo układ posiada przyciski pozwalające na kontrolowanie pracy układu.

English:  

This project was created as part of a design course focused on microprocessor-based control systems.  

The assignment required designing a PCB that uses a microcontroller to control an output element. It was a group project, where responsibilities were divided as follows: I was responsible for the PCB design, another team member handled soldering and documentation, and a third person developed the software.  
  
One of the key requirements was to produce a physical PCB, not just schematic designs.  

According to the project guidelines, it was necessary to use any microcontroller, at least two output devices, and input devices.  

The designed system controls a valve using an Atmega328P microcontroller and a relay module. The system is also equipped with an RTC (real-time clock) and a soil moisture sensor, allowing the valve operation to be controlled based on sensor data.  

Additionally, the system includes a display that can show various parameters, such as the time elapsed since the last valve activation or the current soil moisture level. The system also features buttons that allow the user to control its operation.  
  
![](sch.png)
  
![](Atmega.png)
  
![](Czujniki.png)
  
![](Przyciski.png)
  
![](Układ%20Przekaźnika.png)
  
![](Wyświetlacz.png)
  
![](układ%20zasilania.png)
  
![](brd.png)
