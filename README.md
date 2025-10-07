Inhoud van beoordeling
Wat dien je in?


Een zip-bestand met:
Enkel de Eindopdracht van MQTT (deel 2).
De volledige broncode van je toepassing.
Eventueel een video


Verwachte werking


Je toepassing ontvangt locaties via MQTT op het topic PXLcommunicationRX.
Je toepassing haalt de actuele weersgegevens van deze locaties op via de OpenWeather API (met je eigen API key).
Er geldt een timeout van 2 seconden: als er binnen 2 seconden geen nieuwe locatiegegevens binnenkomen, ga je over tot verwerking.
Het resultaat wordt verzonden via MQTT naar het topic PXLcommunicationTX, in exact het voorgeschreven JSON-formaat.


Beoordeling


Je wordt beoordeeld op:

Correct gebruik van MQTT (RX/TX)
Correcte verwerking en structuur van JSON-data
Correct gebruik van de OpenWeather API
Het naleven van de timeout-vereiste
Netheid en volledigheid van je code en README
Volledig begrip van de code (aanpassingen ten allen tijde)
Zie rubriek in Blackboard
