# Consulta si eres beneficiado del Aporte Familiar Permanente (Bono Marzo) vía WhatsApp

in developing...

## Instalación

```bash
$ git clone https://github.com/jlobos27/bono-marzo-whatsapp.git
$ cd bono-marzo-whatsapp
$ virtualenv -p /usr/bin/python2.7 ./python_modules && source python_modules/bin/activate && pip install -r requirements.txt && deactivate
$ npm i
```

## Registrar número de WhatsApp

[Mobile country code](https://en.wikipedia.org/wiki/Mobile_country_code)

```bash
$ ./python_modules/bin/yowsup-cli registration --requestcode sms --phone 569xxxxxxxx --cc 56 --mcc 730 --mnc 03
$ ./python_modules/bin/yowsup-cli registration --register 450-703 --phone 569xxxxxxxx --cc 56
```