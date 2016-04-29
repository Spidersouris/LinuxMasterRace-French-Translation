# [/r/LinuxMasterRace](https://www.reddit.com/r/LinuxMasterRace) Wiki

Bienvenue sur notre wiki ! Nous ne disposons pas de beaucoup de contenu pour l'instant, mais nous avons ces pages pour votre plaisir de lecture:

[Pourquoi GNU/Linux?](why_linux.md)

[Configuration de votre propre Cloud (en)](https://www.reddit.com/r/linuxmasterrace/wiki/cloud)

[Qu'est-ce que l'Open Source Software et pourquoi devrais-je m'en soucier ? (en)](https://www.reddit.com/r/linuxmasterrace/wiki/what_is_open_source)

[Conseils (en)](https://www.reddit.com/r/linuxmasterrace/wiki/tips)

Nous avons aussi un petit sommaire de ressources externes.

## Wikis externes et documentation

- [Arch Wiki](https://wiki.archlinux.fr), légendaire pour sa vaste bibliothèque de connaissances liées à de nombreux composants de bureaux GNU/Linux populaires (la version française n'est parfois pas aussi complète).
- [Gentoo Wiki (en)](https://wiki.gentoo.org), couvre de nombreux composants de bas niveau.
- [Documentation Officielle Ubuntu (en)](https://help.ubuntu.com/) et [le Wiki communautaire (en)](https://help.ubuntu.com/community), spécifiques à Ubuntu et est également proposé avec un guide soigné pour les réfugiés de Windows/OS X.
- [Red Hat Product Documentation (en)](https://access.redhat.com/documentation/en-US/), un guide d'administration système professionnellement écrit. Applicable pour RHEL, Fedora et CentOS et partiellement pour d'autres distros utilisant leurs composants. Vaut la lecture. Ainsi que les [Documentations Fedora (quelques pages sont en français...)](https://docs.fedoraproject.org/fr-FR/index.html) !
- [Die.net (en)](https://www.die.net/) contient des tonnes de documentation GNU/Linux et des pages de manuel, bien formaté et facilement consultable.
- Votre système contient généralement des pages de manuel pour chaque programme installé! Tapez `man ls` dans votre terminal pour afficher la documentation sur ls, ou tout autre programme que vous voulez. [Voici un petit guide.(en) ](http://www.linuxcommand.org/reading_man_pages.php).
- En fait, [LinuxCommand.org (en)](http://www.linuxcommand.org/index.php) est sympa et vous devriez y jeter un coup d'oeil aussi.

## Trouver des alternatives pour des logiciel propriétaire/Windows/OS X

Vous êtes à la recherche pour de pages comme [AlternativeTo (en)](http://alternativeto.net/), [osalt.com (en)](http://www.osalt.com/) ou [cette liste sur Wikipedia](https://fr.wikipedia.org/wiki/Liste_de_logiciels_libres). Recherchez "<Votre application> alternative Linux" ou "<Votre application> open source libre". Essayez d'entrer quelques mots-clés dans une base de données des paquets de votre distro, toujours rien ? Demandez à ces subreddit (tous anglais) : [/r/linux4noobs](http://reddit.com/r/linux4noobs), [/r/linuxquestions](http://reddit.com/r/linuxquestions) ou [/r/linux](http://reddit.com/r/linux) :)

## Distros populaires

- [Arch Linux](https://archlinux.org) est une distro "faite-le-vous-même", se fait adorer en raison du wiki et Arch User Repository et il est recommandé d'avoir une certaine connaissance de GNU/Linux avant de l'essayer, bien que certains soutiennent qu'un "novice déterminée" peut le configurer correctement durant leur premier essai. Livré avec presque rien de plus que les bases par défaut, vous devez installer presque tous les autres composants de votre système. Cela prend beaucoup de temps, mais c'est gratifiant. Arch est un très bon distro pour expérimenter et d'essayer de nouvelles configurations, car il ne cherche jamais à cacher des processus de bas niveau ou de configurer quoi que ce soit pour vous (sauf les choses les plus basiques comme les pilotes etc). vous devez installer et configurer le système de base manuellement, mais utiliser Antergos vous donne essentiellement le même résultat avec moins de travail (mais aussi moins d'expérience de votre côté - il est recommandé de l'installer manuellement au moins une fois). Recommandé pour les utilisateurs avancés / intermédiaires.
- [Debian GNU/Linux](https://debian.org) est une distro universelle qui va très bien depuis plus de 20 ans et est la distro la plus forkée. Légere,  elle vous oblige à choisir vos propres composants (mais les configure automatiquement la plupart du temps, à un certain degré). Elle suit strictement les principes du logiciel libre (mais inclut des logiciels non-libres sur les dépôts non-libres) et dispose de 3 branches : stable, instable et test. Il est également intéressant de mentionner qu'elle fonctionne sur un grand nombre d'architectures et peut fonctionner avec les noyaux GNU Hurd et kFreeBSD. Recommandé pour les utilisateurs un peu plus expérimentés qui savent déjà ce qu'ils veulent.
- [CentOS](https://www.centos.org/) est une distro destinée pour les serveurs, ce qui signifie que chaque version est prise en charge pour une longue période de temps et que les paquets ont tendance à être plus âgés. Recompilé directement à partir de RHEL (qui est un distro financée, car elle reçoit le soutien de Red Hat), CentOS de l'autre côté est maintenue par la communauté.
- [Fedora](https://getfedora.org) est une communauté encore maintenue collégialement soutenu par le distro Red Hat, où toutes les nouvelles fonctionnalités viennent en premier, sont testés et sont finalement adoptés par d'autres distros. Ces nouveautés habituellement ne causent pas trop de problèmes, beaucoup de développeurs Linux (y compris Linus lui-même) utilisent Fedora. Livré avec le bureau Gnome 3 mais offre également des "spins" avec différents DEs. Les repos par défaut ne comprennent que des logiciels libres, mais vous pouvez activer les repos de RPMFusion qui contiennent les logiciels non-libre si vous le souhaitez. Recommandé pour les utilisateurs et les développeurs expérimentés. Il est également intéressant de mentionner que Red Hat et les développeurs de Fedora par extension contribuent au plus haut pourcentage de code du noyau Linux que tout autre projet.
- [Gentoo Linux](https://www.gentoo.org/) est une distribution basée sur la source, ce qui signifie que vous devez télécharger le code source du logiciel et le compiler avant de l'utiliser. Grâce à cette approche, elle est très personnalisable avec comme désavantage d'être très coûteuse en temps, car de gros paquets tels que LibreOffice ou Firefox prennent des heures à compiler. L'installation est très manuelle et vous devez configurer à peu près tout vers le noyau lui-même (bien que vous puissiez tricher avec `genkernel` pour faire un noyau générique qui fonctionnera dans la plupart des systèmes). Portage (le gestionnaire de paquets de gentoo) a beaucoup de fonctionnalités puissantes telles que les options USE pour adapter les paquets à vos besoins, CFLAGS pour contrôler l'optimisation de la compilation et beaucoup d'autres options avancées. Il est également intéressant de mentionner que Gentoo supporte un grand nombre d'architectures et a développé son propre système d'initialisation appelé [OpenRC](https://wiki.gentoo.org/wiki/Project:OpenRC), mais vous pouvez également utiliser systemd si vous le désirez. Recommandé pour les utilisateurs avancés.
- [Linux Mint](http://www.linuxmint.com/), une distribution basée sur Ubuntu. Cible les débutants. Livrée avec un bureau Cinnamon modifié, c'est un bureau extrêmement personnalisable et extensible. Pas le plus léger, mais il fonctionne bien sur la plupart des PC modernes (pensez 2007+). Recommandé pour les nouveaux arrivants.
- [OpenSUSE](https://www.opensuse.org), une distro unique qui cible les utilisateurs à la fois expérimentés et nouveaux, est considéré comme la meilleir expérience KDE. YaST est un outil graphique pour configurer tout ce que le DEs pourrait ne pas faire. Peut être fait rouler avec Tumbleweed.
- [Slackware](http://www.slackware.com/) est la plus ancienne distro linux encore en développement, suit la philosophie UNIX, pas systemd, centrée sur l'utilisateur, au point que par défaut, elle ne propose pas un gestionnaire de paquets avec la résolution automatique de dépendance, ce qui n'est pas considéré comme un défault par la communauté. À également Slackbuilds qui est comme l'AUR de Arch.
- [Ubuntu](http://ubuntu.com), distro populaire, visant les débutants. Nécessite presque aucune configuration, prend surtout soin de lui-même. Livré avec le bureau Unity controversée, que les utilisateurs OS X peuvent trouver familier. Il y a aussi des versions d'Ubuntu officielles en utilisant divers autres bureau, comme Kubuntu avec KDE, Xubuntu avec Xfce, Ubuntu MATE avec classic MATE Desktop et Lubuntu avec LXDE qui est extrêmement léger (pour les ordinateurs plus âgés / moins puissants). ** Soyez averti que beaucoup ont des préoccupations avec sa position controversée sur les idéaux de logiciels open source, le reste de la communauté FOSS et des pratiques de confidentialité ombragées des développeurs. ** Recommandé pour les nouveaux arrivants.

## Amis, cinglés et distros non-bureau
- [Alpine Linux](http://www.alpinelinux.org/) est un distro sans paquets GNU, utilise MUSL et busybox qui sont plus légers que glibc et coreutils GNU
- [Android](https://android.com/) est basé sur Linux, mais pas GNU, car les applications habituellement ne lui parlent pas directement; Android tente de cacher tous les processus de bas niveau derrière des cadres "simples". S'il n'était pas basé sur Linux, vous ne le remarqueriez probablement pas. (Et il y a des ports du Runtime d'Android non basés sur Linux)
- Les BSDs! Ils ne sont pas GNU / Linux, mais sont issus du [Berkeley Software Distribution](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution). Les deux sont de type Unix, donc les "règles" du noyau gouvernant les deux mondes sont similaires. Le support matériel n'est pas aussi bon, mais les BSDs offrent généralement des performances supérieures aux distributions GNU/Linux et sont souvent utilisés dans les serveurs. Les distributions les plus populaires sont: [PC-BSD](http://www.pcbsd.org/) (ciblant principalement les utilisateurs de bureau). [FreeBSD](https://www.freebsd.org/) (en général, vous obtenez ce que vous installez), [OpenBSD](http://www.openbsd.org/) (concentre ses efforts sur la prestation d'un système stable et sûr - couramment utilisé sur les serveurs), [NetBSD](https://www.netbsd.org/) (met l'accent sur la portabilité) et [ghostbsd](http://www.ghostbsd.org/) (autre distro bureau).
- [Nixos](https://nixos.org/) est un système avec une solution d'emballage unique - au lieu de garder une trace de quels fichiers appartiennent à quel paquet, Nixos conserve chaque paquet séparé du système de base, cela permet des restaurations faciles et mises à niveau atomique [Lisez la documentation si vous voulez en savoir plus sur ce système unique.](https://nixos.org/nix/manual/)
- [OpenELEC](http://openelec.tv/), une distro unique qui offre un environnement parfaitement réglé pour le cinéma maison PC. Livré avec Kodi, qui gère à peu près la plupart des besoins multimédia. Bien conçu.
- [QubesOS](https://www.qubes-os.org/) est un système basé sur Fedora qui vise à fournir une parfaite sécurité en isolant les applications. Quoi qu'il arrive dans un conteneur donné affecte uniquement ce conteneur, les applications fonctionnent dedans et les ressources qui lui sont fournis - rien ne s'échappe des conteneurs sans votre permission explicite. Il offre également l'interopérabilité avec les instances de Windows virtualisés.
- [Raspbian](http://www.raspbian.org/), Debian modifié pour la Raspberry Pi!
- [ReactOS](https://www.reactos.org/) est un système qui vise à devenir une alternative libre Windows. exécute les logiciels fait pour Windows, écrit à partir de zéro, ne reposent pas GNU / Linux ou BSD.
- [Sailfish OS](https://sailfishos.org/), de l'autre côté, est le système d'exploitation exécuté sur les appareils [Jolla](https://jolla.com/). Il est plus proche de Linux "de base" et expose ce fait à des applications et des utilisateurs, tout en offrant une interface utilisateur sur mobile. Il offre également l'interopérabilité avec les applications Android. Sa communauté vient la plupart du temps de [The United Maemo/MeeGo Kingdom](http://maemo.org/).
- [Steamos](http://store.steampowered.com/steamos/) est la tentative de Valve pour créer un simple distro avec l'expérience d'une console pour tout le monde. Contrôlable avec un gamepad, mais pas aussi universel que d'autres distros. Basé sur Debian.
- [Tails](https://tails.boum.org/) est un *système direct*, développé par le [Project Tor](https://www.torproject.org/) qui tente de protéger votre vie privée. **S'il vous plaît lire la documentation avant de l'utiliser.** Merci.

## Serveurs officiels RMT
Comme beaucoup d'entre nous sont des joueurs, plusieurs membres de la communauté accueillent également les serveurs de jeu. [S'il vous plaît jeter un oeil ici](https://www.reddit.com/r/linuxmasterrace/wiki/servers).
