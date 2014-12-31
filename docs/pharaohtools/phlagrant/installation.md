Requirements:
------------

If you wish to use the Phlagrant, ensure whether the Virual box is installed in your machine, along with the Virtual box guest additions functionality

Code for installing virtual box:
-------------------------------

	sudo cleopatra virtualbox install --yes --guess --with-guest-additions

Installation:
-------------

There is two possible ways to install the Phlagrant tool to your machine:

1)Installation via Cleopatra
2)Installing Phlagrant alone

Installation via Cleopatra:
---------------------------

if you have Cleopatra tool in your machine, then it's simple to install the phlagrant by using the code as given below

	sudo cleopatra phlagrant install --yes --guess

here the word guess can be ignored while selecting your own directory during installation.

Installing Phlagrant alone:
---------------------------

If you want to install the phlagrant tool to your machine without depending on the Cleopatra tool, it is easier by using the command,

        sudo apt-get install php5 git
        
this command will install php5 and git on your machine. After that use the following command,

        git clone http://github.com/PharaohTools/phlagrant && sudo php phlagrant/install-silent

the command on the above mentioned can be used if you don't want to select the location during the installation. If you wish to do so, use the following command:

	git clone http://github.com/PharaohTools/phlagrant && sudo php phlagrant/install

