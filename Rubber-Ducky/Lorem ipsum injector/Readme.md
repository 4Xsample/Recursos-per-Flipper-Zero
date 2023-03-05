|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |

# Script d'injectar text Lorem Ipsum per a Flipper Zero

Aquest script serveix per a injectar text Lorem Ipsum en un dispositiu a través de la funció BadUSB o BadKB de Flipper Zero. 
Jo personalment faig servir aquest script per fer proves en xats on necessito tenir una injecció constant de linies per comprovar com reaccionen automatismes, etc.

## Requisits

Per a utilitzar aquest script, es necessita un dispositiu amb connexió USB o Bluetooth, i Flipper Zero amb la app BadUSB o BadKB.

## Com utilitzar l'script en un Rubber ducky

Per utilitzar aquest script, només has de seguir aquests passos senzills:

1. Personalitza l'script segons les teves necessitats (Nomes les necessitats contemplades a l'apartat de personalització, sobre les teves altres necessitats ja t'espavilaras)
2. Converteix el contingut del fitxer `lorem_ipsum_10_lines.txt` amb la aplicació `ducktools.py` per generar l'arxiu `inject.bin`.
3. Copia l'arxiu `inject.bin` a una tarjeta sd i posar-la al Rubber Ducky.
4. Connecta el teu dispositiu Rubber Ducky al teu servidor i deixa que s'executi l'script.
5. Deixa que l'script vagi escrivint el lorem ipsum linia rere linia sense haver de moure un dit (Crec que fins hi tot tu sabras fer-ho això d'esperar i no fotre l'ou)

## Com utilitzar l'script en un Flipper Zero

1. Personalitza l'script segons les teves necessitats (Nomes les necessitats contemplades a l'apartat de personalització, sobre les teves altres necessitats ja t'espavilaras)
2. Copia l'arxiu `lorem_ipsum_10_lines.txt` a la carpeta `BadUSB` o `BadKB` del flipper zero
3. Obre la app `BadUsb` o `BadKb` del Flipper Zero i selecciona el payload.
4. Conecta via usb o bluetooth el flipper zero al ordinador objectiu.
5. Executa el payload.
6. Deixa que l'script vagi escrivint el lorem ipsum linia rere linia sense haver de moure un dit (Crec que fins hi tot tu sabras fer-ho això d'esperar i no fotre l'ou)

I això és tot! Ja no has de preocupar-te per escriure aquest text tant valuos a ma, be a cop de tecla vull dir.

El text que s'injecta és el Lorem Ipsum, un text de farciment utilitzat com a exemple en la indústria de la tipografia i la impressió. Si vols injectar més o menys text, pots triar entre dos payloads diferents: un amb 10 línies i un amb 229 línies. 

## Lorem Ipsum

El Lorem Ipsum és un text estàndard de farciment que es fa servir en disseny gràfic i editorial. Es tracta d'un text sense sentit, format per paraules en llatí que simula un text real, però no té cap significat ni coherència.

La seva utilitat rau en el fet que, quan es dissenya una pàgina o un document, és necessari posar text per ocupar l'espai i visualitzar com quedaria el disseny amb contingut real. En aquests casos, el Lorem Ipsum és un text estàndard que es fa servir per fer de farciment.

La seva origen es remunta a l'any 45 aC, quan el filòsof Ciceró va escriure un text que es va fer famós per la seva estructura i ritme. A partir d'aquí, el text va ser adaptat i modificat fins a convertir-se en el que avui coneixem com a Lorem Ipsum.

## Contribucions

Si tens qualsevol idea per a millorar aquest script, si us plau, no dubtis en enviar una sol·licitud de pull. Estaré encantat de col·laborar amb tu per fer-lo millor.

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*