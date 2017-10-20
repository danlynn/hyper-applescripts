## hyper-applescripts

These are a set of useful AppleScript apps that can be used to interact with the [Hyper](https://hyper.is) terminal app on MacOS.  Simply clone this repo and start using.

![screenshot](https://raw.githubusercontent.com/danlynn/hyper-applescripts/master/assets/Screenshot.png)

### Scripts:

<table>
  <tr>
    <td nowrap style="font-size: 1.5em">hyper-new-window<br/><img src="https://raw.githubusercontent.com/danlynn/hyper-applescripts/master/assets/hyper-new-window-icon.png" width="100"></td>
    <td>
Opens a new Hyper terminal window.  The default directory will be dictated by whatever defaults or hyper plugins that you have installed.  This is useful for invoking via a Spotlight search, as a dock icon, or (my fave) as the target of a global hotkey using [Alfred](https://www.alfredapp.com).  Whenever I hit `cmd-opt-t`, a new hyper window pops open.  Note that since this script uses System Events, you will be prompted by a dialog the first time you run it to grant it access to control your computer via the Accessibility settings in the Security & Privacy system preference pane.
    </td>
  </tr>
  <tr>
    <td nowrap style="font-size: 1.5em">hyper-open-dir-finder<br/><img src="https://raw.githubusercontent.com/danlynn/hyper-applescripts/master/assets/hyper-open-dir-icon.png" width="100"></td>
    <td>
Opens a new Hyper terminal window/tab cd'd to the same directory as the currently front-most Finder window.  It is super useful to place this script app in the toolbar of your Finder windows.  To to this, open a Finder window then right-click on the window's toolbar and select 'Customize Toolbar...'.  You can then drag the hyper-open-dir-finder script to the toolbar.  Now, whenever you want to open a Hyper window/tab for the current folder, you can just click that icon.

<img src="https://raw.githubusercontent.com/danlynn/hyper-applescripts/master/assets/CustomizeFinderWindow.png">

    </td>
  </tr>
  <tr>
    <td nowrap style="font-size: 1.5em">hyper-open-dir-pathfinder<br/><img src="https://raw.githubusercontent.com/danlynn/hyper-applescripts/master/assets/hyper-open-dir-icon.png" width="100"></td>
    <td>
Opens a new Hyper terminal window/tab cd'd to the same directory as the currently front-most <a href="https://cocoatech.com/#/">PathFinder</a> window.  It is super useful to place this script app in the toolbar of your Finder windows.  This can be accomplished in the same manner as with the hyper-open-dir-finder script above.
    </td>
  </tr>
</table>
