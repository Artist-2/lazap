<p align="center">
<a href="#" target="_blank"><img src="https://media.discordapp.net/attachments/910422768045133869/914878042508251156/icon.png" width="200px" height="auto"/></a>
</p>

<h1 align="center">
  Lazap Launcher
</h1>

<p align="center">
  Lazap, a cross-platform Games Client/Launcher <br>
  All your games at one library with a modernish look and experience.
</p>

<p align="center">
  <a href="https://github.com/Lazap-Development/lazap/releases">
     <img src="https://img.shields.io/github/downloads/Lazap-Development/lazap/total.svg?style=for-the-badge&color=ffffff&logo=windows" />
  </a>⠀
  <a href="https://dashcruft.com/discord">
      <img src="https://img.shields.io/discord/836790685784211486?logo=discord&label=Discord&style=for-the-badge&color=228B22">
  </a>
 </p>

<br>

**The new face of Open Source Game Launchers**, Lazap unites all your games together in one place! Whether it be Linux, Windows or MacOS, we got you covered. Lazap can connect with other proprietary game launchers such as Riot Games, Epic Games Launcher and Steam. Our team of Developers make sure that Lazap is customizable, Meet up the user's need and have a glancing & modernish look - meaning, custom JavaScript & CSS scripts, games outside the launchers we support and much more!

## How do I start using Lazap?
`1` - Head over to the [releases](https://github.com/Lazap-Development/lazap/releases) page in lazap's github and download the latest zip file.<br>
`2` - Once downloaded, unzip the downloaded file and extract it.<br>
`3` - Once extracted, inside of the extracted content you should see a file named `Lazap Setup.exe`<br>
`4` - Go on and double click the file. Follow the setup and Lazap should be installed for you! <br>

Interestingly we have developed a system to handle automatic updates for Lazap once a new version releases.<br>
Furthermore, don't hesitate to disable this `auto update` feature inside of the settings in lazap.

## Building Lazap (Developers & Contributers)
Building Lazap is very simple. Simply run these commands in order and you should be good to go:<br>
__NOTE:__ Make sure you have [Node.js](https://nodejs.org/en/download/) and [git](https://git-scm.com/) installed
```
git clone https://github.com/Lazap-Development/lazap.git
cd lazap
git switch nightly
npm i
npm start
```
And if you did everything right, Lazap should start right up!

After doing those, if you would like to have the `exe` file (and the installable), rather then running a cmd each time, simply run the following:
```
npm run build
```
Then you should see a new directory named `dist`. Open it up and you can easily figure everything out yourself.

## Help & Support
We are here to help you if you get any problems when building Lazap, just join our [Discord](https://discord.gg/DashCruft)!<br><br>
**Want to help out insted of getting help?** We love Pull Requests and Issue hunters! Open up a PR and fix some gears, we would love the community's help to improve lazap and make it more user friendly! 😀

## License
Lazap is licensed under the terms of [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://github.com/Lazap-Development/lazap/blob/main/LICENSE.md) ("CC-BY-NC-SA-4.0"). Commercial use is not allowed under this license. This includes any kind of revenue made with or based upon the software, even donations.

The CC-BY-NC-SA-4.0 allows you to:
- [x] **Share** -- copy and redistribute the material in any medium or format
- [x] **Adapt** -- remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
- **NonCommercial** — You may not use the material for commercial purposes. 
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

More information can be found [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).
