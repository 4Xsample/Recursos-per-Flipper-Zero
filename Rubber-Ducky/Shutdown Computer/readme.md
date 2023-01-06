
|               |               |               |               |               |               |
|:-------------:|:-------------:|:-------------:|-------------:|-------------:|-------------:|
| ![Hack the planet](https://img.shields.io/badge/Hack-The%20Planet-orange) | [![Discord](https://img.shields.io/discord/667340023829626920?logo=discord)](https://discord.gg/ahVq54p) | [![Twitter](https://img.shields.io/twitter/follow/4xsample?style=social&logo=twitter)](https://twitter.com/4xsample/follow?screen_name=shields_io) | [![4Xsample@mastodon.social](https://img.shields.io/badge/Mastodon-@4Xsample-blueviolet?style=for-the-badge&logo=mastodon)](https://mastodon.social/@4Xsample) | [![4Xsample](https://img.shields.io/badge/Twitch-4Xsample-6441A4?style=for-the-badge&logo=twitch)](https://twitch.tv/4Xsample)
 | [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=EFVMSRHVBNJP4) |



# Apagar l'ordinador amb un Rubber Ducky

Aquest script utilitza el llenguatge DuckyScript per apagar l'ordinador amb un Rubber Ducky.

## Passos del script

1. Esperar 1 segon (`DELAY 1000`)
2. Pressionar la tecla Windows + R (`GUI r`)
3. Esperar mig segon (`DELAY 500`)
4. Escriure "cmd" i pressionar Enter (`STRING cmd` i `ENTER`)
5. Esperar mig segon (`DELAY 500`)
6. Escriure "shutdown /s /t 0" i pressionar Enter (`STRING shutdown /s /t 0` i `ENTER`)
7. Esperar mig segon (`DELAY 500`)

Això farà que l'ordinador es tanqui immediatament.
