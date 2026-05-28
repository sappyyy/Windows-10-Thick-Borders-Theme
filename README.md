Windows 10 Thick Borders Theme

<img width="1579" height="1039" alt="w10-thick-borders-example" src="https://github.com/user-attachments/assets/67b890b8-45e3-4042-9797-448849653b31" />

Tested and created on Windows 10 22H2, but earlier builds (from 2020 onward) should be fine too

INSTALLATION - 
1) Install SecureUxTheme or UltraUXThemePatcher
2) Replace your original C:\Windows\Resources\Themes\aero\aero.msstyles with the one from archive
3) Set your accent color in Personalize\Colors (preferrably some dark color)
4) Update registry with accent.reg

This way you can have disconnected and independent window border-title color (like some light color - yellow, pink, etc) and accent color (prefferably some dark color). Accent color affect many other colors in many different places (and if set to yellow, for example, effect is no good).

But in order this to be accomplished border color had to be "hard-coded" into .msstyles. 

So if you want some different color than the default yellow, you should -
1) Edit "atlas-thick-borders.png" at 396,220px with Paint.NET and "hard-code" your wanted color
2) Replace it in .msstyles in Resource Hacker (resource - STREAM/1269)
3) Update accent.reg with your wanted color (you can get your color code from registry temporarily setting accent color in Personalize\Colors)
