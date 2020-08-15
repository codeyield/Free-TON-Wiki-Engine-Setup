## Free TON Wiki Engine Setup ##

![Free TON Wiki Logo](https://i.ibb.co/bRSkwp2/Free-TON-Wiki-Logo-Blue-200x155.png)

This describes the technical configuration and setup of the [Free TON Wiki](https://freeton.wiki) website so that the **Free TON** community can contribute to the technical support of this encyclopedia.

**Free TON Wiki** uses the [Dokuwiki](https://www.dokuwiki.org) engine and some plugins:

* Dokuwiki Release rc-2020-06-09 "Hogfather" RC3
* [Bootstrap3 Template](https://www.dokuwiki.org/template:bootstrap3)
* [Translation Plugin](https://www.dokuwiki.org/plugin:translation)
* [SMTP Plugin](https://www.dokuwiki.org/plugin:smtp)
* [Wrap Plugin](https://www.dokuwiki.org/plugin:wrap)
* [Video Share Plugin](https://www.dokuwiki.org/plugin:vshare)
* [OrphansWanted Plugin](https://www.dokuwiki.org/plugin:orphanswanted)

The main settings are located in the file `/conf/local.php`. Some parameter values have been hidden for security reasons.

### Free TON Wiki Sandbox

To enable members of the Free TON community to learn, test, and improve the Wiki, we have deployed the [Free TON Wiki Sandbox](https://sandbox.freeton.wiki) to a subdomain of the main site. The sandbox site strives to faithfully replicate all settings and technical settings of the original [Free TON Wiki](https://freeton.wiki) with the following exceptions:

* Content corresponds to the Dokuwiki installation out of the box
* SMTP Plugin and mail settings are missing
* User registration is disabled and emails are not delivered
* Minor design changes to avoid confusion with the main site

To enter the sandbox site, you can use the following data:

**As admin:**  
Login: admin  
Pass: admin0214987653214  

**As user:**  
Login: user  
Pass: user35872014785139  

**ATTENTION! The sandbox site is automatically rolled back to its original state every day at 03:00 UTC. Save your changes and/or configuration file to avoid data loss!**

Members of the Free TON community can also obtain FTP credentials to access the sandbox site. Contact the Free TON Wiki chat administrators (see below).

### Credits

* [Free TON Community](https://freeton.org/)
* [Free TON Wiki Section on the Free TON Forum](https://forum.freeton.org/c/free-ton-wiki/33)
* [Free TON Wiki Team](https://freeton.wiki/en:about:team)
* [Free TON Wiki Chat EN](https://t.me/freeton_wiki)
* [Free TON Wiki Chat RU](https://t.me/freetonwiki_chat)

We also thank the [Move TON](https://github.com/move-ton) and **Ivan Kotelnikov** for the idea of creating this repository and the first donate in the history of the Free TON Wiki.

### Support us

The Free TON Wiki is community-driven. We will be grateful for any support. All funds will be used to reward the authors of the Wiki and those who help develop the project.

**Official Free TON Wiki address:**  
0:25291140411cd18a6a87908ff6b51cd86a6945cbf747afd784dadcd0aa3937a1
