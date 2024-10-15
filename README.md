# MohistRLcraft-bugfixes
Bug fixes for the RLcraft modpack running on Mohist server software

This repository will probably be updated regularly as I am running a mohist server with RLcraft on it. 

For the first fix that's very annoying, it's the keepInventory fix. For some people, this glitch may be a blessing, but to me it was a nightmare. I went through every config trying to find what mod's configs I could tweak to stop it, but it never worked... This glitch really removed the challenge from rlcraft, as well as taking away from the experience.

Fortunately, using skript I have made a script similar to plugins like the graves mod. The only difference being is this actually works as a solution by logging all the items in your inventory and then putting them in a chest when you respawn. All you have to do is just go back to where you died and there will be a double chest laying there for you! This also clears your inventory so you don't duplicate items upon death. Now, for the installation: just download this repository's zip, download Skript plugin on your server if you haven't already, and upload the .sk file from the repository zip file into your skript/scripts directory. It's as easy as that, all you have to do is /skript reload scripts and you'll now lose items on death and be able to get them back!

I haven't come up with a fix for the missing hurt sounds, but that's honestly the less worse glitch in this equation.
