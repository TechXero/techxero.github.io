 
---
title: Calamares Config
---

{{< figure src="https://raw.githubusercontent.com/calamares/calamares/master/src/branding/default/squid.png#center" >}}

### About

This is where I will be posting my custom Calamares Config. This can be used with various distros that use that installer, but mainly it was built with ArcoLinux in mind, specifically ArcoLinux Plasma. I do not know if it works with other D.E's as I haven't tested as of yet. I will soon, if you want you can test it and report back.

{{< figure src="https://i.imgur.com/GZ5LGlo.png#center" height=340px >}}

### How-To

Ok, now for the "How-To Use" part of it all. Here I will show you how to use my own script, but if you are as much of tinkerer as I am I have more in-depth tutorial on how you can build your own custom config over at [ArcoLinux Forums](https://arcolinuxforum.com/viewtopic.php?f=46&t=2525).

Anyway, for now, here's how to use my own Calamares Config, the way I made it. First, boot into your ISO of choice, in this case ArcoLinux B Plasma, do NOT run installer yet, as we want it to use our config, since it doesn't have it yet, it will use default. Now head into /etc/ folder and open Terminal there. Since a *calamares* folder already exists there, we will first have to rename it to something else in order for us to replace it with our own. To do that run command below :

#### Command

```bash
sudo mv calamares calamares.old
```

Then, once that's done all we have to do is get my config in by cloning my git via command below :

#### Command

```bash
sudo git clone https://github.com/TechXero/calamares.git 
```

Now, you can finally run installer, once you do, you will see my config instead of the *ArcoLinux* one. 

### Final words

I hope this proves to be helpful to you. You are free to use my config as a baseline, or, if you are building a Distro of your own, no need to ask me for permission, just use it, as long as you credit me it's fine. THat's the best part of Linux, FREEDOM... :D