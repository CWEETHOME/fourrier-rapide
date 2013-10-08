************************************************************************************************************
	** Projet Math�matiques **
		d�but : 27/09/2013 - fin : 15/10/2013

	Cahier des charges : Coder un programme calculant la transform� rapide de fourier de n'importe quel fonction
	Langage choisit : C avec biblioth�ques GTK+ (interface graphique)

	Equipe : 
		- CACHELOU Christopher <mail@gmail.com>
		- CAZEAU Isabelle <cazeau.isabelle@gmail.com>
		- CORBINEAU Nadia <nadia.corbineau@gmail.com>
		- BRUHIERE Thibaut <tbruhiere@gmail.com>

************************************************************************************************************

Information "compilation du code" :

Ce projet a �t� cod� en C incluant les biblioth�ques GTK+ pour g�n�rer une interface graphique.
Pour compiler le code, il est n�cessaire de t�l�charger les biblioth�ques GTK+ les plus r�centes (V. 2.24)
Pour se faire, il faut :
	- Sous LINUX :
	- Sous Windows :

Pour compiler le code sous LINUX, il faut ouvrir un terminale de commande, se mettre dans le r�pertoire du projet, puis r�aliser la commande :
"gcc main.c -o main `pkg-config --cflags --libs gtk+-2.0` -lm"


-------------------------------------------------------

Information "Code" : (Chaque fichier est comment�)

Le programme est compos� de @nombre fichier ".C", @nombre ".h" et le fichier ".log.txt"

	- main.c => Ce fichier contient la fonction principal du code, il rassemble les autres fonction des autres fichiers .c et les met en relation afin de
			d'assurer le fonctionnement du code tout en r�duisant au maximum le nombre de ligne, facilitant ainsi le d�bogage.

	- methodes_saisir.C => Fichier permettant � l'utilisateur de saisir les diff�rents param�tres n�cessaires au calcul

	- methodes_calcul.c => Fichier calculant la fonction

	- .log.txt => Contient en dur tous les saisis de l'utilisateur, permettant une sauvegarde de ces valeurs dans le cas d'un bug, mais �galement de pouvoir, � tout moment, r�cup�rer ces valeurs pour le calcul


-------------------------------------------------------
