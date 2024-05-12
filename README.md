# Lama-sdrc-tr-vy

Projekt Měření Vzdálenosti a vlhkosti Trávy pomocí HC-SR04 a LM393 s ESP32

Úvod
Dokumentace popisuje projekt na bázi ESP32, který kombinuje schopnosti HC-SR04 a LM393 
a ukazuje jejich výsledek na webové stránce na mobiním telefonu či počítači.

Použité součástky a zapojení:
ESP32 	- Báze a mikrokontroler
LM393 	- Měřič vlhkosti

	VCC 		 - 3,3V
	GND 		 - GND pin
	Výstupní pin 	 - pin 14
	
HC-SR04 - Měřič vzdálenosti

	Trigger pin 	- pin 12
	Echo pin 	- pin 13
	VCC 		- 5V
	GND		- GND pin

![tinkr](https://github.com/Trpaslik18/Lama-sdrc-tr-vy/assets/167974133/75b09fe3-aa44-4fb0-aa46-0bbfb3815bec)

Návod na použití

	1) Zapojení viz. obrázek
	2) Nahrání dodaného kódu
	3) Zapnutí konzole
	4) Připojení k Wifi síťi
	5) Otevření webové stránky a kontrola výsledků

Funkce
	
	Měření vlhkosti trávy a posílání signálu do ESP32
	Měření vzdálenosti mezi senzorem a potencionální překážkou a posílání dat do ESP32
	Sběr poslaných dat a jejich zobrazení
	
Poznámka

	Pro vylepšení přesnosti je doporučeno použít více jak jednu dvojici měřičů.
	Tím je možno se vyvarovat nepřesnostem a možným vadám systému.
	
	
