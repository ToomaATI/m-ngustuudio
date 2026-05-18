# Mängustuudio projekt

## Operatsioonsüsteem - Debian 13
Debian on staabiilne operatsioonsüsteem ja kiirem kui tavaline Windows server

## Töötaja
Töötajatel on VPN ja virtual disk'i et saada faili serverisse sisse

## Staatiline IP
Valisime staatilise IP, et me saaksime serverile ligi ilma probleemita 

## Back up
Tegime backup'i, et kindlustada meie andmete olemasolu isegi kui mingi probleem juhtub serveris. Backup'i jaoks kasutame rsync ja cron service et ligisaada failile

## Fail jagamine
Faili jagamine on tähtis mängu stuudiole, et failidele liigisaada ja muuta aktiivselt. 

## VPN
Kasutame OpenVPN et töötajad saaksid failidele ligi läbi oma Windwos'i ja Linux aruvtite. Samuti OpenVPN pakkub tasuta teenust kui ise hostid mis on ekstra boonus

