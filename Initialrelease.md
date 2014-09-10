InitialRelease
=============
Today I am proud to announce a new update mechanism for Spigot, which will see us through the future, at least in the short term until more permanent mechanisms are put into place and other things are sorted out. As of today, all Spigot updates will come in the form of binary patches based on the last public build, #1649. These patches will be issued nightly, based on the day’s current date, and will contain a summary of all changes issued since build #1649.

Binary patches are a safe method of distributing and applying updates as they do not contain any copyrighted code, and are something which have been pioneered within the ROMhacking / homebrew community for over twenty years. In order to apply these patches you will need the special Spigot specific tool named “SpigotPatcher”, which you may download from the links below. The patching format is currently based on the beat or BPS-1 specification, however this is subject to change, and as such you should always use the official tool we have provided.

Updating your Spigot jar is now a slightly different and marginally more complex process, however it should still be relatively painless, especially for those who have run modded servers before. The steps are as follows:

    Obtain a copy of Spigot build #1649. Unfortunately we cannot help you with obtaining such a build, but please remember to obtain all such copies legally.
    Ensure that the build which you have obtained matches the md5 checksum: f2edc09c45b1f80237602dc0d1b05969
    Download a copy of the patch for the update which you wish to apply and the latest version of SpigotPatcher.
    Run the following command: java -jar SpigotPatcher.jar /path/to/spigot-1649.jar /path/to/patch.bps /path/to/output.jar
    The tool will run and create a new Spigot jar, as well as print out a variety of information. You should check that the printed md5 matches the one which is listed on the update post, and then proceed to run your newly updated Spigot.
    Ensure you keep a copy of Spigot #1649 as you will require it next time you update.

Here is the changelog and download to the first update of Spigot, Spigot-20140909a:
Download:
SpigotPatcher 1.0: http://www.spigotmc.org/spigot-updates/SpigotPatcher-1.0.jar (33a73112e1fa90706b96cd02c87b447a)
Spigot-20140909a.bps: http://www.spigotmc.org/spigot-updates/spigot-20140909a.bps
(98bc6f3b4a5927a026739cfe8747f998)
Final Checksum: a08aaa6d7f13b648ddf40801a3343ac8

Changelog:

    Remove startup delay which warns users of outdated builds.
    Add a mechanism to use the BungeeCord chat API. This allows you to use sendMessage with the new chat features presented in the following wiki article:http://www.spigotmc.org/wiki/the-chat-component-api/. Special thanks to @letomcat who originally worked on this (however we lost his work in the takedown and did have to rewrite it from scratch)

Source:
At this time we cannot legally distribute the source code, due to a DMCA notice affecting our GitHub repository. However, we aim to rectify this situation as soon as possible and will keep you updated.

Long live Spigot!
~ Spigot Team