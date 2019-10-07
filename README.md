![Logo1](/_inc/images/logo.png)

<h1>Architect Emulationstation Theme for Retroflag GPI </h1>

Variation of the TFT theme by [anthony](https://github.com/anthonycaccese/es-theme-tft). 

Controller artwork originally from Carbon theme

OpenSans Font from Google Fonts

Works for Basic & Detail View

<h3>Screenshots</h3>

<h4>Main Screen</h4>

![Screenshot1](/screenshots/architect-main.png)

| Detailed View | Basic View | Detailed w/o Box Art
| --- | --- | ---
| ![Screenshot2](/screenshots/architect-detail-list.png) | ![Screenshot3](/screenshots/architect-basic-list.png) | ![Screenshot4](/screenshots/background-grid.png)

<h3>Supported Retropie Features</h3>

* RetroPie Menu 
* Favorites
* Recent
* All Games
* Collections

<h3>Supported Systems:</h3>

| Atari | Nintendo | Sega | Other 
| :---: | :---: | :---: | :---:
| Atari 2600 |  Nintendo 64 | Sega GameGear | Arcade 
| Atari 5200 |  Nintendo Entertainment System | Sega Genesis / Sega Megadrive | Colecovision 
| Atari 7800 | Nintendo GameBoy | Sega Master System | Mame
| Atari Lynx | Nintendo GameBoy Advance | Sega32x | NeoGeo Pocket Color
|  | Nintendo GameBoy Color | SegaCD |  Odyssey 2 / Videopac
|  |  Nintendo VirtualBoy |  | PC Engine SuperGrafx
|  |  |  | PC Engine TurboGrafx 16
|  |  |  | Sony Playstation
|  |  |  | Ports 

<h2>Instructions</h2>

<h2>Warning : Do not do any of this as root! </h2>

<h3>To add theme: </h3>

* `cd /home/pi/.emulationstation/themes`
* `sudo git clone https://github.com/kaleben0/es-architect`
* The theme will now show as an option in Emulationstation


<h3>To add launching images</h3>

<h2>Warning : Backup up your /opt/retropie/configs dir before doing this!</h2>

* Open RetroPie Setup
* Go to RetroPie Settings > Runcommand Configuration
* Set Launch Menu Art (Option 2) to Enabled
* Exit RetroPie setup
* Copy each of the "launching.png" files from /home/pi/.emulationstation/themes/es-architect/_inc/media/launchscreens/(system) to the matching folder in /opt/retropie/configs/(system) 
