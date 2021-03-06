Configuració de la xarxa a les màquines virtuals - Exercicis pràctics
======================================================

> Aquestes primeres pràctiques es corregiran a classe. Cada pràctica l'explicarà un/a alumne/a escollit aleatòriament.


1. Quina és el tipus de targeta de xarxa virtual que s'ha configurat a la màquina virtual Windows?

2. Quina és el tipus de targeta de xarxa virtual que s'ha configurat a la màquina virtual Ubuntu?

3. Quina és l'adreça de xarxa IP de la màquina real?

   > Per conèixer la IP d'una màquina amb linux, cal obrir el *Terminal* i utilitzar la comanda
   ```console
   ip a
   ```
   > Les IPs estan darrera la paraula `inet`, i son del tipus `192.168.X.X`, `172.X.X.X`, etc... Ignorar la IP de loopback (`127.X.X.X`).

4. Prova la connexió a Internet.

   > Per fer una prova senzilla, pots fer un *test* de connexió a un servidor d'Internet amb la següent comanda:
   ```console
   ping 8.8.8.8
   ```

4. Apunta el mode en el que està configurada la xarxa de la màquina virtual Ubuntu. Canvia el mode per *No connectat*. Després, mostra quina és la seva IP. Finalment, prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

5. Canvia el mode de xarxa de la màquina virtual Ubuntu a *NAT*. Quina és la seva IP? Prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

5. Canvia el mode de xarxa de la màquina virtual Ubuntu a *Xarxa NAT*. Quina és la seva IP? Prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

5. Canvia el mode de xarxa de la màquina virtual Ubuntu a *Adaptador pont*. Quina és la seva IP? Prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

5. Canvia el mode de xarxa de la màquina virtual Ubuntu a *Xarxa interna*. Quina és la seva IP? Prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

5. Canvia el mode de xarxa de la màquina virtual Ubuntu a *Adaptador de només amfitrió*. Quina és la seva IP? Prova la connexió a Internet. Explica perquè has obtingut aquests resultats.

* Torna a deixar el mode de xarxa com estava abans de fer els canvis.

Grimpades
----------
>Les següents pràctiques son especialment difícils. La correcció a classe serà voluntària, però seran avaluades quan es lliurin al moodle.

1. Verifica si dues màquines virtuals configurades amb *NAT* tenen visibilitat de xarxa entre elles.

1. Verifica si dues màquines virtuals configurades amb *Xarxa NAT* tenen visibilitat de xarxa entre elles.

1. Verifica si dues màquines virtuals, que s'estiguin executant en dos ordinadors diferents, configurades amb *Xarxa NAT* tenen visibilitat de xarxa entre elles.

1. Verifica si dues màquines virtuals, que s'estiguin executant en dos ordinadors diferents, configurades amb *Adaptador pont* tenen visibilitat de xarxa entre elles.
