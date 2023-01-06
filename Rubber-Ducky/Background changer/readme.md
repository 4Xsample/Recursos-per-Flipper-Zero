
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample)
 | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |


# Canviar el fons d'escriptori amb un Rubber Ducky

Aquest script utilitza el llenguatge DuckyScript per descarregar una imatge d'internet i establir-la com a fons d'escriptori per a l'usuari actual i per a tots els usuaris d'un ordinador.

## Passos del script

1. Esperar mig segon (`DELAY 500`)
2. Pressionar la tecla Windows + R (`GUI r`)
3. Esperar mig segon (`DELAY 500`)
4. Escriure "cmd" i pressionar Enter (`STRING cmd` i `ENTER`)
5. Esperar mig segon (`DELAY 500`)
6. Descargar una imatge d'internet amb una comanda PowerShell (`STRING powershell -Command "Invoke-WebRequest -Uri 'https://images.pexels.com/photos/1933239/pexels-photo-1933239.jpeg' -OutFile 'C:\image.jpg'"`)
7. Esperar mig segon (`DELAY 500`)
8. Canviar el fons d'escriptori per l'imatge descarregada amb una comanda del registre (`STRING reg add "HKEY_CURRENT_USER\Control Panel\Desktop" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f`)
9. Esperar mig segon (DELAY 500)
10. Canviar el fons d'escriptori per l'imatge descarregada en tots els usuaris amb una comanda del registre (STRING reg add "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f)
11. Esperar mig segon (DELAY 500)
12. Actualitzar els paràmetres de sistema per a tots els usuaris (STRING rundll32.exe user32.dll,UpdatePerUserSystemParameters)
13. Esperar mig segon (DELAY 500)

Això farà que l'ordinador descarregui una imatge d'internet, la estableixi com a fons d'escriptori per a l'usuari actual i per a tots els usuaris i actualitzi els paràmetres de sistema per a tots els usuaris per aplicar els canvis.
