# Nougat for KMod FWA

Due to the constant insistence of the people to adapt KMod FWA to Nougat and higher, I have decided to write this article.

The reason this module doesn't work, is because Nougat has changed the permissions to use MODE_WORLD_READABLE, which is used to read the preferences from Xposed, and now can't be used. Therefore, I have to use MODE_PRIVATE, which doesn't work with Xposed. 
So, since I have to change the way Xposed reads all the values of the assigned variables in KMod FWA, I have to create the code for it and adapt it, which is a lot of work.

Further, currently Xposed for Nougat isn't a final version of robo89 and has quite a few bugs. I will not create the code for something I have already tested and doesn't work with resources. 
So until robo89 doesn't post Xposed to Nougat in a stable way, I will not start working on support for Nougat. Above all, I'm working on another project that possibly replaces KMod FWA and will be prepared to work on Nougat.

So please, be patient. If you all insist on the same thing, you only get that I don't want to work on it any more.

Regards, and thanks to all who support my work.

Krowne.
