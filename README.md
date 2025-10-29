# [Nautilus](https://gitlab.gnome.org/GNOME/nautilus) - Video convertion

A suite of scripts to convert videos to other format or compress them - requires `ffmpeg`.
Right on a video or a list of videos, go to "Scripts" and select the convertion.

# Installation
1. Git clone _(recommended)_ or download
2. Symlink _(recommended)_ or extract to `~/.local/share/nautilus/scripts`

>[!WARNING]
> Use hard symlink as nautilus doesn't seem to work with symbolic link

```
cd nautilus-desktop-file
ln Convert\ to\ Theora ~/.local/share/nautilus/scripts/Convert\ to\ Theora
```

# Updating
If you used Git clone and symlinked the script; all you have to do is run `git pull` in the Git cloned directory to update the files.\
Otherwise, you'll have to re-download all the files and extract them to your nautilus scripts folder on each update.
