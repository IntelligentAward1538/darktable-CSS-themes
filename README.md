# 'Dark Metal' CSS theme for [darktable](https://www.darktable.org/) 5.6+<br>

### Design with a dark, polished metallic finish, clearly defined areas and featuring contrasting <sup>(1)</sup><br>
'Oasis' evolves and becomes 'Dark Metal'.<br>
Visually, the flat style is abandoned in favor of a more elaborate look. Inspired by the look of an AV receiver.<br>
Special attention has been paid to the interactions with collections and the visual consistency across different views.<br>
The scope of personalization has also been expanded.<br>

## <b>Screenshots:</b> 

<p align="center"><img width="2560" height="1440" alt="Captura_3" src="https://github.com/user-attachments/assets/cb7abca1-68e0-4659-a350-aab81741e684" /></p>
<p align="center"><img width="2560" height="1440" alt="Captura de pantalla 2026-10-21 182247" src="https://github.com/user-attachments/assets/5d379e11-36d9-4f9d-b27a-03aba00b8755" /></p>
<p align="center"><img width="287" height="600" alt="Captura_4" src="https://github.com/user-attachments/assets/e75663ea-ca2c-4ca2-a8ab-01e351123cf3" /></p>

## <b>Requirements:</b>

- Minimum version: darktable 5.6.0
- Recommended version: dakrtable 5.6.2 / 5.7.0
- Install all files in the correct directories

## <b>Installation:</b>

1. Place the CSS file in the darktable themes directory:<br>
   ```[installation directory]\share\darktable\themes\```<br>
  
2.  This theme uses its own images which must be placed in:<br>
   	```[installation directory]\share\darktable\pixmaps\thematic_images\```<br>
	<b>This directory does not exist. You need to create it and place the images for the theme there.</b>
		  
3. Open the application and select the new theme. You can choose another theme from your catalog at any time.
4. Restart darktable after selecting the new theme.

## <b>Compatibility:</b>

Tested on Windows 10 with darktable 5.7.0+1175 and a QHD screen.<br>
For proper display do not activate the theme modifiers included from version 5.6.1 onwards.<br>
If the font is not what you expect, check the font names in the font-family lines.<br>

## <b>Further information and practical tips:</b>

To make the most of this feature, it is important to be familiar with some of darktable’s default keyboard shortcuts:<br>
```Click``` activates the image and selects it<br>
```Ctrl+Click``` Selects/Deselects<br>
```Ctrl+A``` Selects all<br>
```Ctrl+Shift+A``` Deselects all<br>
```w``` Zooms in whilst the key is held down<br>
```f``` Persistent zoom view<br>
```r``` Rejects/cancels the rejection<br>
```Ctrl+f``` shows/hides the film strip<br>
```b``` shows/hides the panel folds<br>
```tab``` hides/shows all panels<br>
```F11``` full/normal window<br>

A different appearance has been intentionally defined depending on the states of the elements:<br>
- Photo selected/not selected<br>
- Photo rejected/not rejected.<br>
- Show some type of overlay / no overlay.<br>
- A "refused" stamp can be superimposed on rejected photos.<br>

It probably took you a while to get used to darktable. Take some time to familiarize yourself with how this theme works.<br>

Different backgrounds and borders have also been chosen depending on the full view being used.<br>
1. In the darkroom:<br>
  - the main background and second view are 50% grey <br>
  - Pressing ```w``` switches to a white background.<br>
  - The top-left thumbnail has an almost black background.<br>
2. In lighttable mode:<br>
  - using the ```w``` or ```f``` keys:<br>
		- 50% grey background if the image is not selected<br>
		- Grey gradient if the image is selected.<br>
		- Red border if the image is rejected<br>
  - With ```s```:<br>
		- Black background<br>

The screenshots included here are intended to show what all the panels look like<sup>(2)</sup>, but if you need a development environment that is as neutral as possible, you can use the keyboard shortcuts mentioned above to maximise the development area and leave only the development modules panel visible.

<p align="center"><img width="2560" height="1440" alt="Captura_5" src="https://github.com/user-attachments/assets/1d67e610-cd1c-4ac2-822f-472a7aada6b8" /></p>


## <b>Release List:</b>

[Here](https://github.com/IntelligentAward1538/darktable-CSS-themes/releases) are all the versions available so far.<br>

---
<b>Notes</b>:<br>
(1)  High-contrast themes can highlight visual flaws in the programme, which largely go unnoticed with plain, neutral themes.<br>
(2)  The screenshots may not include all the latest modifications.<br>
