# MPD Server configuration
---


- [Utworzenie katalogów](#utworzenie-katalogow)
- [Instalacja serwera](#instalacja)
- [Instalacja dodatków](#instalacja-dodatkow)
- [Konfiguracja serwera](#konfiguracja-serwera)
- [Aplikacje do obsługi](#aplikacje-do-obsługi)

### utworzenie katalogów
    z playlistą i plikami
- uprawnienia 7777

### instalacja 
(Ubuntu server)

sudo apt update
sudo apt install mpd

### instalacja dodatków 
- lame

sudo apt update
sudo apt install lame

### konfiguracja serwera


sudo nano /etc/mpd.conf

wybranie drugiej karty muzycznej

``` bash
aplay -l
```
w konfiguracji

"hw: 0:0" pierwsza wartość to hardware, druga karta, trzecia urządzenie na karcie



### aplikacje do obsługi