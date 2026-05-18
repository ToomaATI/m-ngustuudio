# Mängustuudio projekt

## Operatsioonsüsteem - Debian 13
Debian on staabiilne operatsioonsüsteem ja kiirem kui tavaline Windows server. Debian on ka tasuta ja ei pea maksma licence fee et kasutada

## Töötaja
Töötajatel on VPN ja virtual disk'i et saada faili serverisse sisse. Töötajad saavad sisse Windows kui ka Linux arvutidega mis on ühendatud VPN´iga.

## Staatiline IP
Valisime staatilise IP, et töötajad saaksid faili servelile ligi ilma et peaks otsima uue ip iga kord kui server restardib

## Back up
Tegime backup'i, et kindlustada meie andmete olemasolu isegi kui mingi probleem juhtub serveris. Backup'i jaoks kasutame rsync kuna see on open source ja tasuta teenus

## Fail jagamine
Faili jagamine on tähtis mängu stuudiole, et failidele liigisaada ja muuta aktiivselt. Failidele saab ligi kasutades cron, valisime cron kuna see on tasuta teenus ja laia tugega

## VPN
Kasutame OpenVPN et töötajad saaksid failidele ligi läbi oma Windwos'i ja Linux aruvtite. Samuti OpenVPN pakkub tasuta teenust kui ise hostid mis on ekstra boonus

