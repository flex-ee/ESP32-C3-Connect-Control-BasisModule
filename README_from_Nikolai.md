# notes from Nikolai



- Recherche BLE:    
    - Verschiedene Gerätetypen
    - Gateway, GATT, Router, Repeater,...




- Pairing
    - Wie physisch?: Knopf/Button ODER Schnelles Ein/Aussschalten
    - Implementierung SW



FIRST GOAL:
    - Staubsaugersteuerung: single Device To single device
    Stromsensor triggert ESP1 --> BLE --> ESP2 triggert Staubsauger
    STROMSENSOR: Analog output --> Analog Input ESP --> interner ADC --> // int value = analogRead(A4);
                                        value = 0 // kein Strom
                                        value = 1023 // maximaler Strom    



ADDITIONAL:
    
    - FOTA --> Firmware over the air
    - Gateway Thematik: Smartphone als Gateway
    - App Entwicklung
    -
