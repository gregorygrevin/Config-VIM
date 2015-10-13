Configuration personnalisée pour Vim
-------------------------------
##Récupération
<p>Clonez le dépôt dans le <code>$HOME</code> avec la commande :    <br/>

<code>git clone https://github.com/gregorygrevin/Config-VIM.git $HOME</code></p>
<p>Puis copiez les fichier <code>.vimrc</code>et<code>.viminfo</code>ainsi que le dossier<code>.vim</code>hors du répertoire Config-Vim:<br/>
<code>cd $HOME/Config-Vim</code><br/>
<code>cp -rf .vim* $HOME</code><br/></p>
----------------------------------------------
###ATTENTION! 
<p>Après avoir cloné ce dépôt dans le <code>$HOME</code> avec la commande :<br/>
<code>git clone https://github.com/gregorygrevin/Config-VIM.git $HOME</code></p>
<p>Il faut penser à cloner le dépôt de Vundle dans le dossier 
<code>~/.vim/bundle/vundle</code>à l'aide de la commande :
<code>git clone https://github.com/gmarik/Vundle.vim.git $HOME/.vim/bundle/Vundle</code><br/></p>
-----------------------------------------------

##Installation

<p>Lancez <code>vim</code> et exécutez la commande : 
<br/><code>:BundleInstwqall</code><br/>
Afin que tout les plugins puissent être installer à l'aide des dépôts déclarés dans le fichier<code>.vimrc</code>.</p>



<p>Inclus les plugins <b>NeoComplCache</b> et <b>NERDTree</b>, ainsi que les themes <i>Tomorrow-Night ( activé de base lors du clonage ) BusyBee Symfony Two2tango</i> ( à choisir dans le fichier<code>.vimrc</code>).</p>
