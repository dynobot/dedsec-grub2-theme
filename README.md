
### ✔️ Installation

```shell
git clone --depth 1 https://github.com/VandalByte/dedsec-grub2-theme.git && cd dedsec-grub2-theme
sudo python3 dedsec-theme.py --install
```

### ✔️ Manual Installation
*Click to view...*
<details>
 <summary><b>Debian 💀 Ubuntu 💀 Arch</b></summary>
 
  #### 1️⃣ Download your favourite version of the theme from [**Pling**](https://www.pling.com/p/1569525/).

  Now extract your downloaded .zip file.

  Either manually extract it or use the command below. ( *Here I'm using 'brainwash' version of my theme as an example* )
  ```shell
  unzip dedsec-brainwash.zip
  ```
  *The rest of the commands are the same for all the theme styles.*

  #### 2️⃣ Copy the theme directory.
  ```shell
  sudo cp -r dedsec /boot/grub/themes/
  ```
  #### 3️⃣ Make changes to the GRUB config file.

  ```shell
  sudo nano /etc/default/grub
  ```
  Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub/themes/dedsec/theme.txt"`

  Then save the file.

  #### 4️⃣ Finally, update the grub.
  ```shell
  sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  Now the theme should be installed successfully, enjoy !!
</details>

<details>
 <summary><b>Fedora 💀 Redhat</b></summary>
 
  #### 1️⃣ Download your favourite version of the theme from [**Pling**](https://www.pling.com/p/1569525).

  Now extract your downloaded .zip file.

  Either manually extract it or use the command below. ( *Here I'm using 'brainwash' version of my theme as an example* )
  ```shell
  unzip dedsec-brainwash.zip
  ```
  *The rest of the commands are the same for all the theme styles.*

  #### 2️⃣ Copy the theme directory.
  ```shell
  sudo cp -r dedsec /boot/grub2/themes/
  ```
  #### 3️⃣ Make changes to the GRUB config file.

  ```shell
  sudo nano /etc/default/grub
  ```
  Find the line `GRUB_THEME=` then change it to `GRUB_THEME="/boot/grub2/themes/dedsec/theme.txt"`
 
  Change the line `GRUB_TERMINAL_OUTPUT=console` to this *(comment it out)* `#GRUB_TERMINAL_OUTPUT=console`

  Then save the file.

  #### 4️⃣ Finally, update the grub.
  ```shell
  sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  ```
  Now restart your computer the grub theme should be installed successfully, enjoy !!
</details>

### ❌ Uninstallation
```shell
sudo python3 dedsec-theme.py --uninstall
```
**With a little effort the theme's text colours, progress bar colours, progress bar text, and so on can all be customised in `theme.txt` to your liking 💕**
<p align="center">
  <b>Please consider 🤗 giving this project a star ⭐ if you liked it</b>
</p>

<p align="center">
  <b>Follow me on 💬 <a href="https://github.com/VandalByte">Github</a> or 💬 <a href="https://twitter.com/VandalByte">Twitter</a>  to stay up to date on all future updates ...</b>
</p>

## 📸 Preview

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-compact.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-hackerden.png" />
  <br>
  <b>💀 Compactㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 HackerDen</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-unite.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-wrench.png" />
  <br>
  <b>💀 Uniteㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ 💀 Wrench</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-sitedown.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-comments.png" />
  <br>
  <b>💀 SiteDownㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Comments</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-trolls.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-mashup.png" />
  <br>
  <b>💀 Trollsㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Mashup</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-fuckery.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-tremor.png" />
  <br>
  <b>💀 Fuckeryㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Tremor</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-reaper.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-stalker.png" />
  <br>
  <b>💀 Reaperㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Stalker</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-brainwash.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-lovetrap.png" />
  <br>
  <b>💀 Brainwashㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 LoveTrap</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-spyware.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-spam.png" />
  <br>
  <b>💀 Spywareㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Spam</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-redskull.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-strike.png" />
  <br>
  <b>💀 RedSkullㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 Strike</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-firewall.png" />
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-wannacry.png" />
  <br>
  <b>💀 Firewallㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤㅤ💀 WannaCry</b>
</p>

<p align="center">
  <img width="48%" src="https://raw.githubusercontent.com/VandalByte/dedsec-grub2-theme/main/media/previews/preview-legion.png" />
  <br>
  <b>💀 Legion</b>
</p>
