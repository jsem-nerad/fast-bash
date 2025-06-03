# Fast Bash
No need to write long commands, just run a fast bash command

## You can find it on [bash.vojtikdortik.eu](https://bash.vojtikdortik.eu/)

Just so you know, this is in early development phase, so there is not much things here, the website looks terrible and some of the scripts may not work on some platforms, but I am planing to change this

# Basic usage

The base command always looks like this:

```bash
curl -sSL script.vojtikdortik.eu/[script name] | bash
```

If you want to save time, you can visit [bash.vojtikdortik.eu](https://bash.vojtikdortik.eu/), where you can just quickly copy the command and paste it into your terminal.

## Available Scripts

Here is a list of all available scripts at this point of early testing:

| Script Name | Description |
| --- | --- |
| install-docker | Detects the Linux distribution and installs Docker accordingly |
| install-geckodriver | Installs the latest geckodriver based on the system architecture |
| install-git / configure-git | Installs and configures git for you |
| install-raspi-fm | Installs Raspi-FM using its install script |
| install-tmux | Installs tmux using apt - not universal yet |
| start-wifi-ap | Starts a WiFi access point based on your input |
| stop-wifi-ap | Stops WiFi access point made with hostapd |


# Contributing

All contributions to this project are welcome. 
If you find a bug, want a new feature of have any script to share, feel free to create an issue or a pull request.


