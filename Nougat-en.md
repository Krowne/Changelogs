# Nougat for KMod FWA

Due to the constant insistence of the people to adapt KMod FWA to Nougat and higher, I have decided to write this article.

The reasons why the module doesn't work, is because Nougat has changed the permissions to use MODE_WORLD_READABLE, which is used to read the preferences from Xposed, and now it's not allowed to use, therefore, I have to use MODE_PRIVATE, which doesn't work with Xposed. So, since I have to change the way Xposed reads all the values of the assigned variables in KMod FWA, I have to create the code for it and adapt it, which is a lot of work.

Also currently Xposed for Nougat, it's not a final version of robo89 and has quite a few bugs, I will not create the code for something I have already tested and it doesn't work with resources. So until robo89 doesn't post Xposed to Nougat in a stable way, I will not start working on support for Nougat. Above all, because I'm working on another project that possibly replaces KMod FWA, which will be prepared to work on Nougat.

So please, be patient, because if you all insist on the same thing, the only thing that you are going to get, is that I don't want to work on it.

Regards, and thanks to all who support my work.

Krowne.
