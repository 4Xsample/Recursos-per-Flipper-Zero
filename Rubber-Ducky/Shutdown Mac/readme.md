
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |



# Apagar Mac

Aquest és un script escrit en llenguatge de Rubber Ducky per a ser utilitzat amb un dispositiu Rubber Ducky. El Rubber Ducky és un dispositiu que es presenta com una unitat flash normal, però quan es connecta a un ordinador pot executar comandes com si es digitessin des de el teclat.

## Funcionament

Quan es connecta el Rubber Ducky al ordinador, es comença a executar el script. Aquest script es divideix en línies d'ordres, cada una de les quals es descriu a continuació:

1. `DELAY 1000` - Fa una pausa de 1000 mil·lisegons (1 segon) abans de continuar amb la següent línia.
2. `COMMAND SPACE` - Pressiona la tecla de comandes (Command) i la tecla d'espai (Space). Això obre el Finder.
3. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
4. `STRING terminal` - Escriu la paraula "terminal" com si fos digitada des del teclat.
5. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
6. `ENTER` - Pressiona la tecla d'intro (Enter).
7. `DELAY 500` - Fa una pausa de 500 mil·lisegons (0,5 segons) abans de continuar amb la següent línia.
8. `STRING shutdown -h now` - Escriu la comanda "shutdown -h now" com si fos digitada des del teclat.
9. `ENTER` - Pressiona la tecla d'intro (Enter).

Aquest script obre una finestra de terminal i després introdueix una comanda per a apagar l'ordinador.

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*