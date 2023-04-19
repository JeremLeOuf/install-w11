# Installer une copie neuve de Windows 11 en formattant tout ses disques /!\ 
Tuto pour FRIP pour installer W11

__Matériel nécessaire:__

- Un ordinateur avec une connexion Internet
- Une clé USB d'au moins 8 Go
- (Un fichier d'installation de Windows 11 au format ISO)

~~-Étape 1: Téléchargement du fichier ISO de Windows 11</h3>
Téléchargez le fichier ISO de Windows 11 à partir d'un site de téléchargement fiable, tel que le site officiel de Microsoft.~~<br>
<a href="https://1drv.ms/u/s!AnaHt2PTkorMhtcQnew9KNACDV01og?e=0kMtCK">Windows 11 Pro 22H2 x64.iso</a><br>

<h3>- Étape 2: Téléchargement de Rufus</h3>
Téléchargez Rufus à partir du site officiel de Rufus. Rufus est un logiciel qui vous permettra de créer une clé USB bootable à partir de votre fichier ISO.<br>
<a href="https://github.com/pbatard/rufus/releases/download/v3.22/rufus-3.22.exe">Rufus 3.22<a><br>

<h3>- Étape 3: Création de la clé USB bootable avec Rufus</h3>
  <ul>
    <li>Insérez votre clé USB dans un port USB de votre ordinateur. 
    <li>Ouvrez Rufus et sélectionnez votre clé USB dans le menu déroulant « Périphérique ». 
    <li>Assurez-vous que le système de fichiers est « **FAT32** ». 
    <li>Sélectionnez votre fichier ISO de Windows 11 en cliquant sur « Sélectionner ». 
    <li>Cliquez sur le bouton « Démarrer » pour lancer le processus de création de la clé USB bootable.
  </ul>
    
<h3>- Étape 4: Redémarrage de l'ordinateur</h3>
Redémarrez votre ordinateur et accédez au BIOS en appuyant sur la touche spécifiée lors du démarrage (généralement la touche <b>Suppr, F2 ou F12</b>).
  <br>
  > <b>Vérifie ce que c'est pour ta carte mère, ça peut varier !!</b>
  <br>

<h3>- Étape 5: Configuration du BIOS</h3>
Dans le BIOS, <b>modifiez l'ordre de démarrage pour que l'ordinateur démarre à partir de la clé USB. 
  Enregistrez les modifications et quittez le BIOS.</b>
  <br>
  > <b>Y'a des tutos pour ça en fonction de ta carte mère si besoin</b>
  <br>

<h3>- Étape 6: Installation de Windows 11</h3>
- L'installation de Windows 11 devrait démarrer automatiquement. 
- Suivez les instructions à l'écran pour installer Windows 11. 
- <b>Lorsque vous arrivez à l'étape de partitionnement du disque dur, sélectionnez l'option pour supprimer toutes les partitions existantes et créer une nouvelle partition pour l'installation de Windows 11.</b>
  > <b><i>!!! TRÈS IMPORTANT !!!</b></i>

<h3>- Étape 7: Installation des pilotes et des logiciels</h3>
Une fois que Windows 11 est installé, vous devrez installer les pilotes de périphériques pour votre ordinateur, ainsi que tout logiciel que vous souhaitez utiliser.<br>
  > <b>Jte conseille <a href="https://www.iobit.com/en/driver-booster.php#">Driver Booster</a> pour ça, c'est carré</b>
