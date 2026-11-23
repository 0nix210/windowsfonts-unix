1. download https://github.com/0nix210/windowsfonts-unix/releases/download/windows-fonts/windows-fonts-20261123.zip
2. extract
3. copy windows-fonts folder to:

mac: ~/Library/Fonts/ (local user) /Library/Fonts/ (system wide)
linux/bsd: ~/.local/share/fonts/ (local user) /usr/local/share/fonts/

linux quick:

curl -L https://github.com/0nix210/windowsfonts-unix/releases/download/windows-fonts/windows-fonts-20261123.zip --output /tmp
mkdir ~/.local/share/fonts/
chmod 755 ~/.local/share/fonts/
unzip /tmp/windows-fonts-20261123.zip ~/.local/share/fonts/
chmod -R 644 ~/.local/share/fonts/windows-fonts
fc-cache -frv
