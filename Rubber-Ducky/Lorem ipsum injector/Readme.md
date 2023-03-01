|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample) | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |

# Script d'injectar text Lorem Ipsum per a Flipper Zero

Aquest script serveix per a injectar text Lorem Ipsum en un dispositiu a través de la funció BadUSB o BadKB de Flipper Zero. 
Jo personalment faig servir aquest script per fer proves en xats on necessito tenir una injecció constant de linies per comprovar com reaccionen automatismes, etc.

## Requisits

Per a utilitzar aquest script, es necessita un dispositiu amb connexió USB o Bluetooth, i Flipper Zero amb la app BadUSB o BadKB.

## Instal·lació

1. Carrega el fitxer `lorem_ipsum_10_lines.txt` o `lorem_ipsum_229_lines.txt` a la carpeta `badusb` o `badkb`, depenent del firmware que estiguis utilitzant, a través de l'aplicació QFlipper en el teu PC o directament carregant l'arxiu a la targeta SD a la carpeta corresponent.

2. Accedeix a l'aplicació BadUSB o BadKB, depenent del firmware que estiguis utilitzant.

3. Connecta el Flipper Zero al dispositiu que vols escriure a través de la connexió USB o Bluetooth.

4. Si utilitzes l'aplicació BadUSB, selecciona directament el payload que vols desplegar. Si utilitzes l'aplicació BadKB, tria entre fer l'atac a través de la connexió USB o emular un dispositiu Bluetooth al qual, si qualsevol dispositiu es connecta, farà d'HID.

5. Si cal, accedeix al menú de configuració fent clic a la fletxa esquerra per assegurar-te que has seleccionat el layout de teclat adequat per al dispositiu al qual vols injectar els caràcters.

6. Executa el payload triat. El script injectarà el text Lorem Ipsum allà on tinguis seleccionat.

El text que s'injecta és el Lorem Ipsum, un text de farciment utilitzat com a exemple en la indústria de la tipografia i la impressió. Si vols injectar més o menys text, pots triar entre dos payloads diferents: un amb 10 línies i un amb 229 línies. 

## Lorem Ipsum

El Lorem Ipsum és un text estàndard de farciment que es fa servir en disseny gràfic i editorial. Es tracta d'un text sense sentit, format per paraules en llatí que simula un text real, però no té cap significat ni coherència.

La seva utilitat rau en el fet que, quan es dissenya una pàgina o un document, és necessari posar text per ocupar l'espai i visualitzar com quedaria el disseny amb contingut real. En aquests casos, el Lorem Ipsum és un text estàndard que es fa servir per fer de farciment.

La seva origen es remunta a l'any 45 aC, quan el filòsof Ciceró va escriure un text que es va fer famós per la seva estructura i ritme. A partir d'aquí, el text va ser adaptat i modificat fins a convertir-se en el que avui coneixem com a Lorem Ipsum.

## Contribucions

Si tens qualsevol idea per a millorar aquest script, si us plau, no dubtis en enviar una sol·licitud de pull. Estaré encantat de col·laborar amb tu per fer-lo millor.

## Disclaimer: 
*Aquest codi s'ofereix tal com és i no es garanteix que funcioni correctament en totes les condicions. No em faig responsable dels danys que puguin resultar de l'ús d'aquesta informació. Utilitzeu-lo sota la vostra pròpia responsabilitat. Si teniu dubtes pregunteu i respondré al que pugui. Si voleu obrir proposar cambis podeu obrir fork i i voleu seguir-me, al panel del principi d'aquest readme podeu trobar links a les meves xarxes socials, Twitch i PayPal per si també voleu donar suport al meu treball.*