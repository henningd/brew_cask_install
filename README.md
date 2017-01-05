# Programme automatsich installieren

Eine Sammlung von nützlichen Programmen, die über brew cask installiert werden

## Tip ##

Nach einer Neuinstallation von OS X die [dotfiles](https://github.com/mathiasbynens/dotfiles) von Mathias Bynens installieren.

    git clone https://github.com/mathiasbynens/dotfiles.git && cd dotfiles && source bootstrap.sh

Zum Updaten `cd` in das lokale `dotfiles` Repository (bei mir `cd ~/Projects/dotfiles`) und dann:

```bash
source bootstrap.sh
```

## Voraussetzungen ##

Xcode sollte installiert sein, und den Lizenzinfos sollte man zugestimmt haben.
[Link](https://www.google.de/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjo1LifpavRAhVLMlAKHZZgCDMQFggjMAA&url=https%3A%2F%2Fitunes.apple.com%2Fde%2Fapp%2Fxcode%2Fid497799835%3Fmt%3D12&usg=AFQjCNFEI0ltCIASrXkyMlPX9l7pVN4wkQ)

Homebrew muss installiert sein.
[Link](http://brew.sh/index_de.html)


## Installation ##

Verzeichnis anlegen, in das das Repository geklont werden soll.

    Beispiel: ~/Projekte/Installation


In Terminal in das Verzeichnis wechseln

    Beispiel: cd ~/Projekte/Installation


Repository klonen

    git clone https://github.com/henningd/brew_cask_install.git


In Terminal in das Verzeichnis wechseln

    Beispiel: cd ~/Projekte/Installation/brew_cask_install


In Terminal die Datei install.sh ausführen

    install.sh ausführen    


Es werden nun nacheinander alle Programme installiert.
