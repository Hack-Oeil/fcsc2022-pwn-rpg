# FCSC 2022 RPG

Jean-Michel est un grand fan de jeu de rôle. Malheureusement, il n'a jamais eu l'occasion de rejouer avec ses amis depuis la crise du Covid-19.

Ils ont travaillé sur une application de chat qui permet aux joueurs de tirer toute sorte de dés, sur la base d'un CSPRNG.

Voici la première version de leur application. Trouvez une vulnérabilité pour lire le fichier ```flag.txt```.



Fichiers :
- [ld-2.33.so](ld-2.33.so)
- [libc-2.33.so](libc-2.33.so)
- [Makefile](Makefile)
- [rpg](rpg)
- [rpg.c](rpg.c)



Auteur : XeR

Origine : [RPG](https://hackropole.fr/fr/challenges/pwn/fcsc2022-pwn-rpg/)


-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc rpg.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-pwn-rpg.git

> cd fcsc2022-pwn-rpg


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2022-pwn-rpg/