The 'Screenshots' folder contains images of all the various windows/dialogs used in XBMC and are labelled the same as their relevant XML.

To make use of the Debug Grid and Info add this to your Keymap.xml (or create a new one in the USERDATA/Keymaps folder)

<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<keymap>
	<global>
		<keyboard>
			<F5>XBMC.ReloadSkin()</F5>
			<F6>Skin.ToggleSetting(DebugGrid)</F6>
			<F7>Skin.ToggleSetting(HideDebugInfo)</F7>
			<F8>Notification(Testing 123,Hello world)</F8>
		</keyboard>
	</global>
</keymap>

F5 - Reload skin
F6 - Show/Hide the Debug Grid
F7 - Show/Hide the Debug Info
F8 - Activates the KaiDialogToast.xml


Further window info can be found in the WIKI (http://wiki.xbmc.org/index.php?title=List_of_Built_In_Controls).