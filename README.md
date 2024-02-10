# my neofetch configurations

## <p align="center">![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/musicalskele/neofetch/total) [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)</p>
## <p align="center">description</p>

this repository contains my custom configuration for neofetch, a command-line utility to display system information. feel free to use and customize it according to your preferences. i only ask credit for the ascii art.

## <p align="center">screenshots </p>

![neofetch recording](/pretty-readme/recording_tk.gif)
<sub>recording of the configuration in `configs/trans_flag_config/nerdfonts/`, recorded on a rasberry pi 4 running raspberry pi os 64 bit using [asciinema](https://asciinema.org/) terminal. rendered on windows with `noto sans nerd font` and the following parameters `agg.exe --fps-cap 60 --font-size 24 --font-family "NotoMono NFM" `</sub>
## <p align="center">features </p>

- **custom ascii art**: a very cute pixel kitty :3
- **usage of nerd fonts:** you can choose between regular versions or get nerdfonts [here](https://www.nerdfonts.com/).
- **additional information**: added and modified information lines to display specific details i wanted, customize it as much as you like.

## <p align="center">installation </p>

1. clone this repository:

    ```bash
    git clone https://github.com/musicalskele/neofetch
    ```


2. optionally make a backup or rename the already present `config.conf` file:

	<sub>backup the file like this</sub>
	```bash
	cp ~/.config/neofetch/config.conf ~/.config/neofetch/config.conf.old
	```
	<sub>rename the file like this</sub>
	```bash
	mv ~/.config/neofetch/config.conf ~/.config/neofetch/config.conf.old
	```

3. copy the configuration file and ascii of your choice to the neofetch directory:
	
	<sub>we will be cloning nerdfonts version of the trans pride flag (`configs/trans_flag_config/nerdfonts/`)</sub>

    ```bash
    cp neofetch/configs/trans_flag_config/nerdfonts/config.conf  ~/.config/neofetch/config.conf; cp neofetch/configs/trans_flag_config/nerdfonts/asciilogo ~/.config/neofetch/asciilogo
    
    ```

4. run neofetch to confirm it's working:

    ```bash
    neofetch
    ```

	<sub>if you picked a nerdfont one and it doesn't show up with icons check you're using the correct terminal font</sub>
## <p align="center">customization </p>

feel free to modify the `config.conf` and `asciilogo` files to suit your preferences. 
refer to the neofetch documentation for more details on customization: 
[information customization](https://github.com/dylanaraps/neofetch/wiki/Customizing-Info)
[ascii file format](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format)
[default config file](https://github.com/dylanaraps/neofetch/wiki/Custom-Ascii-art-file-format)

## <p align="center">issues and pull requests </p>

if you encounter any issues or have suggestions for improvement, [please open an issue](https://github.com/musicalskele/neofetch/issues). 

if you have a suggestion for a different flag, you can either [open an issue](https://github.com/musicalskele/neofetch/issues) or [create a pull request](https://github.com/musicalskele/neofetch/pulls)

## <p align="center">credits and license </p>

- neofetch: source code available [here](https://github.com/dylanaraps/neofetch).
- ascii art by me, licensed under [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)