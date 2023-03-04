|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |

# Rubber Ducky Script per actualitzar el repositori A_cagar_a_la_via

Així que te n'has adonat que actualitzar manualment els teus repositoris és una pèrdua de temps i has decidit crear un script que ho faci per tu? Bé, no busquis més! Aquest script de Rubber Ducky és tan simple que fins i tot el teu gat podria entendre'l.

## Personalització

Aquest script està dissenyat per actualitzar el repositori "A_cagar_a_la_via" de GitHub de la carpeta `/var/www/html/A_cagar_a_la_via`, però és fàcilment adaptable a altres repositoris. Només has de canviar la ubicació del repositori a la línia `STRING cd /var/www/html/A_cagar_a_la_via`. Fes-ho servir amb moderació, però, no vull que et converteixis en un màquina de clonar repositoris!

Ah i no oblidis afegir les linies per introduir la contrasenya de superusuari en cas de que el teu servidor sigui tan segur que fins i tot et demana codi per executar com a root. Espera, què? El teu servidor no et demana codi per executar com a superusuari? Ai, quina llàstima. Segur que és molt segur, no? Potser els administradors només van pensar "qui necessita seguretat quan pots viure perillosament?" o potser simplement van decidir llançar una moneda a l'aire i deixar que el destí decidís. En qualsevol cas, si ets d'aquells que prefereixen viure al límit i no tenir cap mena de seguretat en el teu servidor, no cal que afegiu les línies per introduir la contrasenya.
Tot i això si insisteixes en usar codi pel root del teu servidor es pot fer afegint el seguent text just despres de la linea `STRING sudo su`

```plaintext
ENTER
DELAY 1000
STRING 123456
```

Si estem parlant d'un servidor tan segur com per utilitzar codis per al root, segurament la contrasenya hauria de ser algo així com "123456". Però espera, que hi ha gent que utilitza contrasenyes més complexes? No siguis ridícul, ningú no necessita més seguretat que això! Així que si ets dels que prefereixen complicar-se la vida amb contrasenyes llargues i complicades, molt bé per a tu, però no et passis, eh?

## Com utilitzar l'script en un Rubber ducky

Per utilitzar aquest script, només has de seguir aquests passos senzills:

1. Personalitza l'script segons les teves necessitats (Nomes les necessitats contemplades a l'apartat de personalització, sobre les teves altres necessitats ja t'espavilaras)
2. Converteix el contingut del fitxer `rubber_ducky_script.txt` amb la aplicació `ducktools.py` per generar l'arxiu `inject.bin`.
3. Copia l'arxiu `inject.bin` a una tarjeta sd i posar-la al Rubber Ducky.
4. Connecta el teu dispositiu Rubber Ducky al teu servidor i deixa que s'executi l'script.
5. Espera uns segons mentre el script navega fins a la carpeta del clon del repositori. (Crec que fins hi tot tu sabras fer-ho això d'esperar i no fotre l'ou)
6. Observa com el script descarrega les últimes actualitzacions del repositori des de la branca "origin".
7. Contempla amb admiració com el script actualitza el clon local del repositori al darrer commit de la branca "main".

I això és tot! Ja no has de preocupar-te per actualitzar manualment els teus repositoris com un animal prehistòric. De res!

## Com utilitzar l'script en un Flipper Zero

1. Personalitza l'script segons les teves necessitats (Nomes les necessitats contemplades a l'apartat de personalització, sobre les teves altres necessitats ja t'espavilaras)
2. Copia l'arxiu ``Update A cagar.txt`` a la carpeta ``BadUSB`` o ``BadKB`` del flipper zero
3. Obre la app ``BadUsb`` o ``BadKb`` del Flipper Zero i selecciona el payload.
4. Conecta via usb o bluetooth el flipper zero al ordinador objectiu.
5. Executa el payload. (Els següents passos potser et sonen una mica, no t'espantis)
6. Espera uns segons mentre el script navega fins a la carpeta del clon del repositori. (Crec que fins hi tot tu sabras fer-ho això d'esperar i no fotre l'ou)
7. Observa com el script descarrega les últimes actualitzacions del repositori des de la branca "origin".
8. Contempla amb admiració com el script actualitza el clon local del repositori al darrer commit de la branca "main".


## Nota

Aquest script està dissenyat per a ús educatiu o d'investigació i no està destinat a ser utilitzat per a finalitats malintencionades (això és el que diuen tots els scripts Rubber Ducky, oi?). L'autor no es fa responsable de l'ús incorrecte d'aquest script (com si algú anés a culpar-me si algú l'utilitza de manera inadequada).

Per a més informació sobre Rubber Ducky i com utilitzar aquest script, consulteu la documentació oficial de Hak5: https://docs.hak5.org/hc/en-us/categories/360002167614-Rubber-Ducky (si no saps com utilitzar un Rubber Ducky, millor no intentis utilitzar aquest script).

Per a més informació sobre el repositori "A_cagar_a_la_via", consulteu https://github.com/4xsample/A_cagar_a_la_via.git (si realment necessites més informació sobre això, no estic segur que aquest script sigui per a tu).

Si us plau, no utilitzeu aquest script per a finalitats malintencionats o il·legals. Utilitzeu-lo només amb permís adequat i de manera ètica (com si això fos alguna cosa que hagi de ser dit).

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*