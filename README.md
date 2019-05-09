# README.md

### Purpose
* to acquire data from remote location (e.g. GSM/Nb-IOT)
* provide high density IO collection

### HLD
* master slave structure
* slave (STM32) provide high density of io collection
* master provide high(mid?) level of customization (user logic)
* master communicate to server:
    * wifi ? (esp8266)
    * GSM ? (A8)
    * Nb-IOT ?
