---
layout: docs
title: NetHydra Installation standard 
permalink: /doc/installation/installation-standard
comments: true
desc: Guide book standard installation for NetHydra
author: Joe
update: 2026-03-14 13:46:00 +0700
---


# NetHydra Installation - Book Guide.



## Single boot installations
> Before we start please make sure you have ready to backup your data, This process will <b>Wipe</b> your data on the <b>Disk</b>


### 1.1 Preparation

I'm sure you have already know how to Installing "OS" using calamares, but don't worries we will give you guide if you doesnt know.
make sure you have ISO image from [Official NetHydra site](/) (if you don't know how to download [clickme](/doc/introductions/downloading-image-from-hydra-site)).
second step you need burn ISO image to your Media such <b>FLASHDRIVE</b> or <b>CD</b> doesn't know how to burn? [clickme](/doc/installation/make-media-bootable-for-hydra).
<br>

### 1.2 Boot into NetHydra system using LIVE media.

next step you need to boot into NetHydra Live environment, but before thats you need to <b>disable secure boot</b> first.
second step after you <b>disable secure boot</b> time to boot Hydra environment! you need to plugin your Hydra media like flashdrive into your computer, then reboot your computer for entering boot chooser select <n>media/drive</n> you already burned.
GRUB will show up, just press enter ("Try/Install").

![boot into NetHydra](/assets/doc_assets/installation_graphics/calamares/boot-into-hydra.png)



### 1.3 NetHydra Environment

in some version release Hydra you may should login and you can enter user <b>nethydra</b> and password <b>nethydra</b>.
after you success login you will seen Desktop icon with label "Install NetHydra" just double click thats icon.

> In some case you need launch manually, just open terminal and type <b>"sudo debian-install"</b> may you need entering password <b>nethydrda</b>

Or not you can click applications launcher and type "Install NetHydra"

![boot into NetHydra](/assets/doc_assets/installation_graphics/calamares/whisker-menu.png)


### 2.1 NetHydra calamares - Welcome

In this step you must have Installation welcome screen may will like this.
> PS: Different Hydra Version Different UI.

![NetHydra calamares](/assets/doc_assets/installation_graphics/calamares/01-calamares.png)

> You can choise your language (default is American english).

you can click <n>next</n> if you sure what are you choise.


### 2.2 NetHydra calamares - Location and Date.

In this step you may will see like this.

> You can set your default <b>region</b> and <b>timezone</b>

![NetHydra calamares](/assets/doc_assets/installation_graphics/calamares/02-calamares.png)


### 2.3 NetHydra calamares - Keyboard.

In this step you may will see like this. just choose your keyboard setup configuration.

![NetHydra calamares](/assets/doc_assets/installation_graphics/calamares/03-calamares.png)

### 2.4 NetHydra calamares - Partitions.

> Pls read carefully this tutorial for <b>SINGLE BOOT</b> so all data on your computer will <b>Wipe/formated</b>.

![NetHydra calamares](/assets/doc_assets/installation_graphics/calamares/04-calamares.png)


### 2.5 NetHydra calamares - User setup.

in this setup you will seen <b>user setup</b> screen.

> eg:<b>
username: nethydra
login name: nethydra
yourcomputername: nethydracomputer
password: toor</b>

![nethydra calamares](/assets/doc_assets/installation_graphics/calamares/05_user_setup_bt.png)

### 2.6 NetHydra calamares - Confirmation.

This is the last step, you may will seen.

> <b>This is confirmation screen, after you click next all data in your computer will wiped, and you can comeback.</b>

after you sure what are you choise just click <b>install</b>.

![NetHydra calamares](/assets/doc_assets/installation_graphics/calamares/06-calamares.png)

### 2.7 NetHydra calamares - Installation proccess.

> Wait until installation done, after that you can click finish and your computer automatically reboot, when your computer reboot you can unplug installation media!.

![HydraPWK calamares](/assets/doc_assets/installation_graphics/calamares/07-calamares.png)
![HydraPWK calamares](/assets/doc_assets/installation_graphics/calamares/08-calamares.png)


### End

You can reboot and dont forgot to unplug your Bootable Media

![NetHydra Installation done](/assets/doc_assets/installation_graphics/calamares/grub-done.png)
