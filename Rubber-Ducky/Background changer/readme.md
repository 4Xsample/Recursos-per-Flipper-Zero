
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample)
 | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |


# Cambiar fons d'escriptori windows

Aquest és un script escrit en llenguatge de Rubber Ducky per a ser utilitzat amb un dispositiu Rubber Ducky. El Rubber Ducky és un dispositiu que es presenta com una unitat flash normal, però quan es connecta a un ordinador pot executar comandes com si es digitessin des del teclat.

## Funcionament

Quan es connecta el Rubber Ducky al ordinador, es comença a executar el script. Aquest script es divideix en línies d'ordres, cada una de les quals es descriu a continuació:

1. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
2. `GUI r` - Pressiona la tecla de GUI (Windows) i la tecla "r". Això obre el diàleg "Executar".
3. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
4. `STRING cmd` - Escriu la paraula "cmd" com si fos digitada des del teclat.
5. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
6. `ENTER` - Pressiona la tecla d'intro (Enter).
7. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
8. `STRING powershell -Command "Invoke-WebRequest -Uri 'https://images.pexels.com/photos/1933239/pexels-photo-1933239.jpeg' -OutFile 'C:\image.jpg'"` - Escriu la comanda "powershell -Command "Invoke-WebRequest -Uri 'https://images.pexels.com/photos/1933239/pexels-photo-1933239.jpeg' -OutFile 'C:\image.jpg'"" com si fos digitada des del teclat. Aquesta comanda descarrega una imatge d'Internet i la desa a l'ordinador amb el nom "image.jpg" a la carpeta arrel del disc C.
9. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
10. `ENTER` - Pressiona la tecla d'intro (Enter).
11. `STRING reg add "HKEY_CURRENT_USER\Control Panel\Desktop" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f` - Escriu la comanda "reg add "HKEY_CURRENT_USER\Control Panel\Desktop" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f" com si fos digitada des del teclat. Aquesta comanda modifica la clau de registre de Windows per a establir la imatge descarregada com a fons d'escriptori per a l'usuari actual.
12. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
13. `ENTER` - Pressiona la tecla d'intro (Enter).
14. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
15. `STRING reg add "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f` - Escriu la comanda "reg add "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows\CurrentVersion\Policies\System" /v Wallpaper /t REG_SZ /d "C:\image.jpg" /f" com si fos digitada des del teclat. Aquesta comanda modifica la clau de registre de Windows per a establir la imatge descarregada com a fons d'escriptori per a tots els usuaris de l'ordinador.
16. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
17. `ENTER` - Pressiona la tecla d'intro (Enter).
18. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
19. `STRING rundll32.exe user32.dll,UpdatePerUserSystemParameters` - Escriu la comanda "rundll32.exe user32.dll,UpdatePerUserSystemParameters" com si fos digitada des del teclat. Aquesta comanda actualitza els paràmetres del sistema per a que es reflecteixi el nou fons d'escriptori.
20. `DELAY 500 - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
21. `ENTER` - Pressiona la tecla d'intro (Enter).

Aquest script obre el diàleg "Executar", escriu la paraula "cmd" i pressiona intro per obrir una finestra del símbol del sistema, després descarrega una imatge d'Internet i la desa a l'ordinador amb el nom "image.jpg" a la carpeta arrel del disc C. A més a més, modifica la clau de registre de Windows per a establir la imatge descarregada com a fons d'escriptori per a tots els usuaris de l'ordinador i finalment actualitza els paràmetres del sistema per a que es reflecteixi el nou fons d'escriptori.