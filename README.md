# Theme Collection for darktable 5.6+

## <b>Requirements:</b>

- Minimum version: darktable 5.6.0
- Recommended version: darktable 5.6.2 / 5.7.0
- Install all files in the correct directories

## <b>Installation:</b>
To enjoy the latest version, download the files from the main branch.<br>
1. Place the CSS files in the darktable themes directory:<br>
   ```[installation directory]\share\darktable\themes\```<br>
2.  This themes uses its own images which must be placed in:<br>
   	```[installation directory]\share\darktable\pixmaps\thematic_images\```<br>
	<b>This directory does not exist. You need to create it and place the images for the themes there.</b>	  
3. Open the application and select the new theme. You can choose another theme from your catalog at any time.<br>
4. Restart darktable after selecting the new theme.<br>

## <b>Compatibility:</b>

Tested on Windows 10 with darktable 5.7.0+1175<sup>(2)</sup> and a QHD screen.<br>
For proper display do not activate the theme modifiers included from version 5.6.2 onwards.<br>
If the font is not what you expect, check the font names in the font-family lines.<br>
If the interface appears distorted compared to the screenshots, check the following sections in the program's main settings:<br>
- font size in points<br>
- GUI controls and text DPI<br>
The latter depends on your resolution and the size of your monitor in inches. <br>
<img width="663" height="386" alt="Captura6" src="https://github.com/user-attachments/assets/4b9bf793-f1c3-4ef3-83db-a0652f7f0239" />

A different appearance has been intentionally defined depending on the states of the elements:<br>
- Photo selected/not selected.<br>
- Photo rejected/not rejected.<br>
- Show some type of overlay / no overlay.<br>
- A "refused" stamp can be superimposed on rejected photos.<br>

It probably took you a while to get used to darktable. Take some time to familiarize yourself with how this themes works.<br>


## <b>Further information and practical tips:</b>

To make the most of this feature, it is important to be familiar with some of darktable’s default keyboard shortcuts:<br>
-	```Click``` activates the image and selects it<br>
-	```Ctrl+Click``` Selects/Deselects<br>
-	```Ctrl+A``` Selects all<br>
-	```Ctrl+Shift+A``` Deselects all<br>
-	```w``` Zooms in whilst the key is held down<br>
-	```f``` Persistent zoom view<br>
-	```r``` Rejects/cancels the rejection<br>
-	```Ctrl+f``` shows/hides the film strip<br>
-	```b``` shows/hides the panel folds<br>
-	```tab``` hides/shows all panels<br>
-	```F11``` full/normal window<br>

# 1) ___Dark Metal___<br>
### Design with a dark, polished metallic finish, clearly defined areas and featuring contrasting <sup>(1)</sup>
Inspired by the look of an AV receiver.<br>
'Dark Metal' is ideal for a novice user who needs to clearly distinguish and locate all interface elements.<br>
Special attention has been paid to the interactions with collections and the visual consistency across different views.<br>

Different backgrounds and borders have also been chosen depending on the full view being used:<br>
1. In the darkroom:<br>
	- the main background and second view are 50% grey.<br>
	- Pressing ```w``` switches to a white background.<br>
	- The top-left thumbnail has an almost black background.<br>
2. In lighttable mode:<br>
	- using the ```w``` or ```f``` keys:<br>
		- 50% grey background if the image is selected.<br>
		- Grey gradient if the image is not selected.<br>
		- Red border if the image is rejected & selected.<br>
	- With ```s```:<br>
		- Black background.<br>

## <b>DM Screenshots:</b> 
<p align="center"><img width="2560" height="1440" alt="Captura_01" src="https://github.com/user-attachments/assets/96a3d0a0-ecf3-46fb-b7d3-1a91e1795997" /></p>
<p align="center"><img width="2560" height="1440" alt="Captura_02" src="https://github.com/user-attachments/assets/46f91b95-a38e-49f9-91c7-f5476248c698" /></p>
<p align="center"><img width="287" height="600" alt="Captura_4" src="https://github.com/user-attachments/assets/e75663ea-ca2c-4ca2-a8ab-01e351123cf3" /></p>
		
The screenshots included here are intended to show what all the panels look like<sup>(3)</sup>, but if you need a development environment that is as neutral as possible, you can use the keyboard shortcuts mentioned above to maximise the development area and leave only the development modules panel visible.

<p align="center"><img width="2560" height="1440" alt="Captura_04" src="https://github.com/user-attachments/assets/525c24a9-21cd-44a9-bb55-10fbc0b74c65" /></p>

# 2) ___Light Metal___<br>

'Light Metal' is a medium-gray theme that serves as an alternative to “darktable-icons-grey”, striking a balance between neutrality and visual comfort.<br>
A neutral gray theme prevents the colors and brightness of the interface from distorting visual perception when editing a photograph.<br>
The delineation of elements, simulated relief, and metallic reflections create a sense of depth, as well as a dynamic response—sometimes accentuated—that makes it easier to locate elements and reduces eye strain.<br>
While 'Dark Metal' is ideal for a novice user, “Light Metal” is geared toward a more advanced user seeking a balance between visual comfort and neutrality.<br>
'Light Metal.css', like “darktable-icons-grey.css,” modifies the base theme “darktable.css” to create the new look. This reduces maintenance, although it requires more precise declarations.<br>
## <b>LM Screenshots:</b> 


<p align="center"><img width="2560" height="1440" alt="Captura 2026-11-15_2" src="https://github.com/user-attachments/assets/2d2fb980-442e-4fe4-aafb-3de80edaae0a" /></p>

<p align="center"><img width="2560" height="1440" alt="Captura 2026-11-15_1 " src="https://github.com/user-attachments/assets/ada76749-dad6-4984-b7ed-43521433343b" /></p>

---

## <b>Release List:</b>
The 'releases' are snapshots of a specific moment in the project. These can be useful if you want to revert to a previous version.<br>
[Here](https://github.com/IntelligentAward1538/darktable-CSS-themes/releases) are all the versions available so far.<br>

---
>[!NOTE]<br>
> 1) High-contrast themes can highlight visual flaws in the programme, which largely go unnoticed with plain, neutral themes<br>
> 2) Some definitions are not yet in effect in version 5.6.2 because it does not yet include those classes. They only take effect in later nightly builds<br>
> 3) The screenshots may not include all the latest modifications<br>


