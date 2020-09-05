# CalcFetch
 A simple Linux fetch script using Nerdfonts

![Screenshot](https://cdn.discordapp.com/attachments/671117418189422594/751940350314283048/unknown.png)

Dependencies:

- [Any nerdfonts font](https://www.nerdfonts.com/font-downloads)
- Bash
- Pretty much any Linux distro

To install and run:

```sh
git clone https://github.com/ThatOneCalculator/CalcFetch.git
cd CalcFetch/
sudo cp calcfetch ~/.local/bin/
sudo chmod +x ~/.local/bin/calcfetch 
cd ~
calcfetch
```

Know issue(s):

- In Cool-Retro-Term, the coffee icon shows up as a Chinese character. To fix this, replace the current coffee icon with `nf-fa-coffee` from [Nerdfont's Cheat Sheet](https://www.nerdfonts.com/cheat-sheet)