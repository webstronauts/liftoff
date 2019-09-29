# liftoff 🚀

> Liftoff is a script to set up a macOS laptop for development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

## Install

Download the script:

```sh
git clone git@github.com/webstronauts/liftoff.git && cd liftoff
```

Review the script (please don't run scripts you don't understand):

```sh
less liftoff
```

Liftoff:

```sh
cd liftoff
./liftoff 2>&1 | tee ~/liftoff.log
```
Just follow the prompts and you’ll be fine. 👌

:warning: Warning: I advise against running [this script](liftoff) unless you understand what it’s doing to your computer.

We created this based on our own preferences; your mileage may vary.

Once the script is done, quit and relaunch Terminal.

It is highly recommended to run the script regularly to keep your computer up to date.

Your last Liftoff run will be saved to `~/liftoff.log`. To review it, run `less ~/liftoff.log`.

That's it! :sparkles:

## What it sets up

The setup process will install:

<details>
<summary>Basic tools:</summary>

* [XCode Command Line Tools](https://developer.apple.com/xcode/downloads/) for developer essentials.
* [Oh My Zsh](https://ohmyz.sh/) for managing zsh configuration.
* [Git](https://git-scm.com/) for version control.
* [Homebrew](http://brew.sh/) for managing operating system libraries.
</details>

<details>
<summary>CLI Tools & Utilities:</summary>

* [ASDF](https://asdf-vm.com/) for managing programming language versions.
* [Overmind](https://github.com/DarthSim/overmind)  Process manager for Procfile-based applications.
* [mas](https://github.com/mas-cli/mas) Mac App Store command line interface.
</details>

### Apps

<details>
<summary>Browsers</summary>

* [Firefox](https://www.mozilla.org/en-US/firefox/new/) for web browsing and testing.
</details>

<details>
<summary>Productivity</summary>

* [Alfred](https://www.alfredapp.com/) for increased productivity and efficiency with macOS.
</details>

<details>
<summary>Development</summary>

* [Dash](https://kapeli.com/dash) offline access to API documentation sets.
* [Docker](https://www.docker.com/) to containerize applications.
* [iTerm](https://www.iterm2.com/) for a better terminal.
* [Tower](https://www.git-tower.com/) for managing git repositories.
* [Vagrant](https://www.vagrantup.com/) for development environments.
* [Virtual Box](https://www.virtualbox.org/) powerful virtualization tool.
</details>

<details>
<summary>Communication</summary>

* [Slack](https://slack.com/) where work happens.
* [WhatsApp](https://www.whatsapp.com/) to communicate with friends and family.
</details>

<details>
<summary>Utilities</summary>

* [1Password](https://1password.com/) for password management.
* [Bartender](https://www.macbartender.com/) to organize the menu bar.
* [Viscosity](https://www.sparklabs.com/viscosity/) to connect with private VPN networks.
</details>

<details>
<summary>Miscellaneous</summary>

* [Spotify](https://www.spotify.com/) for music.
* [VLC](http://www.videolan.org/) for a better media player.
</details>

<sub>See [`stages`](stages) for the full list of apps that will be installed. Adjust it to your personal taste.</sub>

It should take less than 20 minutes to install (depends on your machine).

## Acknowledgements

As it's just a modification of [Formation](https://github.com/minamarkham/formation), all credits should go to [Mina Markham](https://github.com/minamarkham) for doing all the hard work on the scripts. We just prefered a space theme over Beyonce and tweaked it according to our own needs (Zsh over Bash for example).

## 📜 License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
