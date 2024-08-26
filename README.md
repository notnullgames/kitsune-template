This is a template for creating [Kitsune Tails](https://kitsunegames.com/kitsunetails/) mods.

The basic idea is that it will setup all the dependencies for editing maps in [Tiled](https://www.mapeditor.org/).

To use it, click the Github "Use This Template" button, and follow the directions below in "Development", locally.

In this file, replace `MYORG` with your Github name, and `MYGAME` with your project-name.

### you can delete above this line


## Usage

First, locate your [Kitsune Tails](https://kitsunegames.com/kitsunetails/) `levels/` directory. On steam it might be one of these:


```
C:\AppData\Roaming\KitsuneTails\levels
$XDG_DATA_HOME/KitsuneTails/levels
~/Library/Application Support/KitsuneTails/levels
~/.local/share/KitsuneTails/levels
~/.var/app/com.valvesoftware.Steam/.local/share/Steam/steamapps/common/KitsuneTails/levels
```

Grab [the latest release](https://github.com/MYORG/MYGAME/releases) and extract to your `levels/` dir. Open Kitsune Tails, and "Mods", and you should see "MYGAME".


## Development

You must have node installed.

This assumes you have your levels-dir (see above) in `~/.local/share/KitsuneTails/levels`

```
git clone git@github.com:MYORG/MYGAME.git ~/.local/share/KitsuneTails/levels/MYGAME
cd  ~/.local/share/KitsuneTails/levels/MYGAME

npm it
```

Now, you can edit maps in [Tiled](https://www.mapeditor.org/), and open any built-in maps in `deps/Content/`.

Users who have installed flatpak version of Tiled & Steam will have issues, so it's recommended you install a non-flatpak version of 1 of those (I install non-flatpak Steam.)
