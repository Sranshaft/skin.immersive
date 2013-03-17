XBMC Immersive

XBMC Immersive combines the elegant simplicity of Microsoft's Metro UI with the media richness of XBMC to create an extremely user-friendly and inviting skin.

What addons are needed?

Skin Widgets: http://mirrors.xbmc.org/addons/frodo/service.skin.widgets/
RandomandLastItem: http://mirrors.xbmc.org/addons/frodo/script.randomandlastitems/
PlayAlbum: http://mirrors.xbmc.org/addons/frodo/script.playalbum/
Favourites: http://mirrors.xbmc.org/addons/frodo/script.favourites/

These should be downloaded automatically upon installation of the skin but I've linked them just in case they don't. 

What addons are supported?

The Big Pictures: http://forum.xbmc.org/showthread.php?tid=97605
PseudoTV: http://forum.xbmc.org/showthread.php?tid=90738
TV Show Next Aired: http://forum.xbmc.org/showthread.php?tid=79493
Global Search: http://forum.xbmc.org/showthread.php?tid=109301
MetaData Actors: http://forum.xbmc.org/showthread.php?tid=123578
ForumBrowser: http://forum.xbmc.org/showthread.php?tid=85018
Library Editor: http://forum.xbmc.org/showthread.php?tid=158775

What should I do if I find a bug?

Please report the issue to the GIT page at https://github.com/Sranshaft/skin.immersive/issues. Note: you will need a GIT account to do this. 

Please do not report the issue to the forum. While I try my hardest to read each post, chances are it'll get overlooked / forgotten. It's much easier keep track of these issues when they are all in one place.

Extras

Charms bar: If you add the following code to your keymap.xml file (%appdata%\XBMC\Userdata\keymaps\keymap.xml) you will have access to a Charms bar-esque quick nav window that will allow you to quickly jump to different sections of the skin.

<keymap>
    <global>
        <keyboard>
			<a>XBMC.ActivateWindow(55)</a>
        </keyboard>
    </global>
</keymap>