NOM : EL KARROUMI
Pr�nom : Cherazade
LIFAMI - Mini-projet
Article I. Objectif de l'application et comment l'utiliser (touches, but de l'app, ect.)
Section 1.01 : But de l'app
L'application est un mini jeu vid�o de type " Space Shooter " Avec ajout de particularit�s physiques (loi de la gravitation universelle dans sa version classique, m�canique classique).
Section 1.02 : Touches
(a) Touches du menu
Lorsque vous d�marrez l'application, vous vous trouvez dans le menu 'Pause'. Vous trouvez le menu en bas � gauche de l'�cran. Le menu poss�de deux choix, 'Pause' et 'Resume'. Ce menu reste affich� tant que l'application est ouverte. Le bouton 'Pause' vous permet de revenir � la page sur laquelle vous vous trouvez lorsque vous avez lanc� l'application. 'Resume' vous permet de revenir au jeu. Vous trouverez �galement sur la page du menu 'Pause' les r�gles �crites en anglais ainsi que l'histoire du jeu. Si vous souhaitez quitter l'application, appuyez sur la touche 'espace'. Pour r�initialiser une partie, appuyez sur la touche 'k' lorsque vous avez perdu, gagn� ou bien lorsque vous �tes dans le menu 'Pause'.  IMPORTANT : Si vous �tes coinc� � un moment ou � un autre sur l'application, vous pouvez toujours vous rendre dans le menu 'PAUSE' et appuyer sur la touche 'k' pour r�initialiser votre partie.
(b) Touches du jeu
Pour d�placer votre soucoupe vous devez orienter votre souris � l'endroit o� vous voulez aller et faire un clic gauche � cet endroit-l�. Cependant, gardez en t�te que les r�acteurs de votre soucoupe fonctionnent avec des forces. Une force appliqu�e dans une direction devra �tre compens�e par une autre force dans la direction oppos�e pour rester immobile dans le r�f�rentiel de l'�cran. Vous pouvez �galement vous d�fendre en lan�ant un laser avec la touche 'z'. Vous ne pouvez pas lancer un laser lorsqu'il y en a d�j� un existant sur l'�cran.
Section 1.03 : Fonctionnement du jeu
Vous perdez la partie si vous vous �crasez sur un ast�ro�de. Gardez en m�moire que votre soucoupe ne peut pas sortir de l'�cran. Vous gagnez la partie lorsque vous atteignez la derni�re plan�te. Il y a trois stages diff�rents et donc trois plan�tes diff�rentes � atteindre. Vous pouvez cependant recommencer chaque niveau � l'infini apr�s avoir fini le jeu sans perdre votre score. Votre score d�pend de deux param�tres : les plan�tes sur lesquelles vous avez d�j� atterri et le nombre d'ast�ro�des d�truits. Le score li� � l'ast�ro�de d�pend de sa taille. Plus l'ast�ro�de est grand, plus sa force gravitationnelle est grande, ce qui entraine un risque plus �lev�. La r�compense est proportionnelle au risque. Le score li� aux plan�tes est fixe. La derni�re plan�te n'ajoute pas de score. (Cf. Article V)
Article II. Des explications en fran�ais/anglais (et non en code) de comment votre code fait les choses (TRES IMPORTANT)
Mon code se structure en dix points majeurs class�s dans l'ordre ou vous les trouverez dans le .cpp ci-joint : 
1. Les librairies
2. Les constantes
3. Les structures 'Particule', 'Ast�ro�d' et 'World' qui permettent d'afficher tous les objets du jeu (plan�tes, soucoupe, ast�ro�des, lasers, images...) et la structure 'Vecteur' qui est un outil qui va permettre de coder les fonctions de mise en mouvement des objets.
4. La surcharge des op�rateurs pour les vecteurs et les fonctions de base d'utilisation des vecteurs : distance, normalisation d'un vecteur et rotation. Ce sont des outils qui vont permettre de coder la physique du jeu et la mise en mouvement des objets.
5. L'initialisation du score, du laser et du monde ainsi que les fonctions qui initialisent la position al�atoire des ast�ro�des.
6. Les fonctions qui servent � calculer les forces en pr�sences sur la soucoupe ainsi que la proc�dure associ�e qui met � jour la position de la soucoupe. Elles d�finissent les lois physiques du jeu et le mouvement de la soucoupe.
7. Les proc�dures du fonctionnement du laser, des parties gagn�es ou perdues.
8. La proc�dure qui affiche le jeu et la proc�dure 'update' qui appelle toutes les proc�dures et fonctions du jeu.
9. Le menu
10. La fonction 'main()' qui permet le lancement du jeu.
Vous trouverez �galement des commentaires dans le code qui vont permettront de comprendre l'utilit� de chaque fonction/proc�dure.
Article III. Des r�f�rences vers des documents qui vous ont servis (Wikipedia, ect.) (IMPORTANT)
Section 3.01 : R�f�rences vers des documents scientifiques
(a) Informations sur les corps c�lestes :
- https://fr.wikipedia.org/wiki/Syst%C3%A8me_solaire
- https://fr.wikipedia.org/wiki/Ast%C3%A9ro%C3%AFde
(b) Informations sur la gravitation et mouvement des corps c�lestes :
- https://fr.wikipedia.org/wiki/Loi_universelle_de_la_gravitation
- https://fr.wikipedia.org/wiki/Lois_de_Kepler
- https://fr.wikipedia.org/wiki/Champ_gravitationnel
- https://fr.wikipedia.org/wiki/M%C3%A9canique_quantique
(c) Informations sur les collisions :
- https://fr.wikipedia.org/wiki/Choc_%C3%A9lastique
- https://fr.wikipedia.org/wiki/Lois_de_Snell-Descartes
(d) Informations sur la propulsion spatiale :
- https://fr.wikipedia.org/wiki/Propulsion_spatiale
Section 3.02 : R�f�rences vers les sources des images et des musiques
(a) Images
- Dossier 'Background': https://opengameart.org/users/rawdanitsu
- Dossier 'Planet' : https://opengameart.org/users/screaming-brain-studios
- 'cursor_hand.png' et 'glassPanel.png': https://opengameart.org/users/kenney
- 'laserRed.png', 'laserOrange.png' et 'laserYellow.png': https://opengameart.org/users/bonsaiheldin
- 'spaceCat.png' : https://opengameart.org/content/pixel-cat-and-courgette
- 'YouLose.png', 'YouWin.png', 'Reacteur.png', 'Soucoupe.png', 'Asteroide.png', 'Explosion.png', 'Debris.png' ont �t� trouv�es sur un site qui a pour but de partager des images non prot�g�es : https://www.pngmart.com/fr/copyright-policy 
(b) Musiques
- ObservingTheStar.wav: https://opengameart.org/users/yd
Article IV. L'historique des �volution des trois derni�res semaines (texte que vous avez d�j� largement commenc�)
Section 4.01 : DEBUT DU TRAVAIL SUR LE CODE : Structures, Surcharges d'operateurs pour les vecteurs, fonctions de base d'utilisation des vecteurs, proc�dure d'initialisation, proc�dure d'affichage. 
(a) Explications
Dans les premiers jours du travail sur ce code, j'ai ajout� les librairies et les constantes. J'ai �galement �cris les structures de base, les surcharges d'op�rateurs pour les vecteurs et les fonctions de base d'utilisation des vecteurs. Je me suis concentr�e sur la fa�on de proc�der pour faire apparaitre al�atoirement des ast�ro�des sur l'�cran. J'ai cr�� une proc�dure basique d'affichage afin de v�rifier mon code. Elle affichait la Lune et la soucoupe de fa�on immobile. Apr�s avoir fini le TP " SystemeMasseRessort " J'ai pu rajouter les fonctions de normalisation d'un vecteur et de calcul de la distance. Pour finir j'ai �cris la proc�dure d'initialisation.
(b) Qu'est ce que le code affiche ?
Un cercle plein en haut � gauche de l'�cran qui repr�sente la Lune. Un cercle plein en bas au milieu de l'�cran qui repr�sente la soucoupe. Des cercles pleins de taille comprise entre 0 et 30 qui apparaissent al�atoirement sur l'�cran � chaque lancement de l'application (Cf. Article V : Taille des ast�ro�des modifi�s).
Section 4.02 : STADE INTERMEDIAIRE DU TRAVAIL SUR LE CODE : Modification des structures, de la proc�dure d'initialisation et de la proc�dure d'affichage. Fonctions/proc�dures : M�canique classique, lois de la gravitation universelles classique, proc�dure laser.
(a) Explications
La partie suivante concerne principalement le code des lois m�caniques et le fonctionnement du laser. J'ai commenc� par ajouter une force d'attraction � chaque ast�ro�de. Ensuite, j'ai ajout� une vitesse pour la soucoupe. J'ai remarqu� que la soucoupe pouvait �chapper � n'importe quelle force d'attraction. J'ai corrig� le probl�me en modifiant cette fonction en la rempla�ant par une force. Les lois physiques du jeu fonctionnent. J'ai ensuite travaill� sur le fonctionnement du laser. Dans ses d�buts, le laser pouvait �tre lanc� sans " cooldown ". C'est un probl�me r�current dans les jeux que l'on retrouve notamment dans les " platformer " ou le nombre de saut doit �tre limit�. J'ai modifi� cette proc�dure afin que le laser fonctionne correctement puis j'ai modifi� la proc�dure d'initialisation et d'affichage afin d'y incorporer ces modifications. Entre temps j'ai �galement ajout� une image � chaque objet (Cf. dossier 'Images').
(b) Qu'est ce que le code affiche ?
Des ast�ro�des avec une position initiale al�atoire, en mouvement, exer�ant une force d'attraction sur la soucoupe. Une soucoupe qui peut se mouvoir et lancer des lasers. Un fond d'�cran et une image pour chaque objet.
Section 4.03 : FIN DU TRAVAIL SUR LE PROJET : Modification des structures, de la proc�dure d'initialisation, de la proc�dure d'affichage. Proc�dure partie gagn� ou partie perdu, proc�dure 'update' et ajout du menu.
Mon projet s'est termin� par l'�criture de la proc�dure partie gagn�e et partie perdue, 'update' et l'ajout d'un menu. Le jeu contenait initialement dix niveaux, son nombre a �t� diminu�. J'ai d� faire un compromis en r�duisant le nombre de niveau. Chaque niveau a � pr�sent une particularit� et une mini histoire. La proc�dure update est principalement une proc�dure qui fait le lien entre les diff�rentes fonctions et proc�dures du code tout en ajoutant les limites du monde (Cf. Article V).
Article V. Informations suppl�mentaires
(a) Informations
Le programme peut �tre lent selon la qualit� de votre ordinateur.
Copyright : La provenance de certaines images ne sont pas pr�cis�es (voir Article III). Aucunes images utilis�es dans ce programme ne m'appartiennent.
(b) Phases de 'test'
La phase de 'test' a permis de prendre connaissance des probl�mes du jeu et de les corriger au mieux.
(1) Probl�mes r�solus
(i) Am�lioration de la jouabilit�
- Sortie de l'�cran : dans les pr�c�dentes versions du jeu la sortie de l'�cran �quivalait � une partie perdue. Etant donn� que les forces en pr�sences sur la soucoupe sont massives, cette difficult� suppl�mentaire a �t� retir�e.
- Collision avec les limites de l'�cran : les collisions ont �t� modifi�es afin d'emp�cher la soucoupe de rebondir. Cela a permis d'am�liorer la maniabilit�.
- Tailles des ast�ro�des : les ast�ro�des pouvaient initialement prendre une taille entre 0 et 30. Ainsi, certains ast�ro�des n'�taient pas visibles aux yeux du joueurs. Cette valeur se situe � pr�sent entre 15 et 30.
(ii) Ajustement de la difficult�
- Forces gravitationnelles trop faible. La masse des ast�ro�des a �t� augment�e.
(iii) Fonctionnement du jeu
- Probl�mes de comptabilisation du score.
- Partie perdue : Lorsque la partie �tait perdue, le joueur ne pouvait plus bouger la soucoupe. Les forces d'attraction qui s'exer�aient sur elles continuaient � agir sur son mouvement et la soucoupe pouvait s'�chapper, le jeu reprenait. A pr�sent, lorsque la partie est perdu, tous les �l�ments du jeu se figent.
- (Probl�me r�solu le 09/04/2023) Score de la derni�re plan�te : Augmentation du score � l'infini � cause d'une boucle 'if'. Ajout d'une nouvelle boucle 'if' avec le compteur 'w.win' � l'interieur de celle-ci afin de pallier au probl�me. 
(iv) Affichage
- Probl�me d'affichage des images.
(2) Probl�mes non r�solus
- Partie perdue : Dans certaines situations o� la soucoupe s'�crase sur un ast�ro�de au m�me moment ou le laser d�truit ce m�me ast�ro�de, les �l�ments du jeu restent fig�s. La partie est perdu bien que les messages d'informations ne s'affichent pas. La r�initialisation d'une partie ne marche pas dans le jeu. Il faut retourner dans le menu 'Pause' et recommencer une partie. (Modification du 09/04/2023 : ce bug est moins pr�sent car le laser se fige lorsque la partie est perdue)
(c) Am�liorations r�centes
(i) Modifications du 09/04/2023
- Modification de la structure 'Asteroid' : les images des ast�ro�des ont �t� d�plac�es dans la structure 'World' pour qu'elles ne soient charg�es qu'une seule fois.
- Ajout d'une plan�te et un fond d'�cran (Background) diff�rent pour chaque stage. 
- Ajout de trois lasers de couleur diff�rentes, lanc�s al�atoirement.
- Ajout d'une UI (User Interface) suppl�mentaire : mini-histoire pour chaque stage.
- Modification de l'Easter Egg pour probl�mes de copyright.
- Modification du mouvement du laser lors d'une partie perdue.
- Resolution du bug de score de la derni�re planete.
(d) Licence
- CC-BY-NC (attribution, pas d'utilisation commerciale)
(e) Remerciements
- Layachi MOUSSI (Testeur)



