# MyPi-GrowBox

## How
Based on sensors, the main program witten in python, will write/append in a file all sensors datas with date and time.
index.php will read the file and explodes the values to fill a table with dates and datas.

## Comment
En utilisant les données de différents capteurs, pour renseigner un fichier de données avec horodatage.
La partie PHP exploite ces données pour remplir un tablea de suivi.


## Why
Log all sensors datas of a GrowBox (growing plants indoor) and then having charts or tables to supervise the growth conditions.

## Pourquoi
Enregistrer les données des capteurs placés dans une GrowBox (espace de culture en intérieur) et en sortir des tableaux, des statistiques etc.

## What
- temperature and humidity from DHT11 sensor
- light sensor
- UV sensor
- hall effect sensor
- PHP server (i'm using a raspberry zero for MyPi-GrowBox)

## Python

## PHP
- Bootstrap 4
- Font Awesome
- mypigrowbox.css

# License
MyPi-GrowBox is published under the GNU Affero 3.0 because I believe in open development. It comes with both rights and obligations. Whether you use this GrowBox firmware as the driver for your open or closed-source product, you must keep it open, and you must provide your compatible source code to end users upon request. The most straightforward way to comply with the license is to make a fork of this project on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.

# Future
- camera for timelapse
- separate by months
- use of charts
- use of Bootstrap/Dashboard
- separate .php pages/codes

# favico
https://gauger.io/fonticon/ to create favicon.ico with FontAwesome
