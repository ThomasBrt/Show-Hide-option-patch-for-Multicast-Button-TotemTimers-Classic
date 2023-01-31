<h1 style="color:blue">Multicast Button Show/Hide toggle option</h1>
<h3>Patch for TotemTimers WotLK classic addon v3.1.15</h3>

---

<h2 style="color:blue">Why this patch ?</h2>

Like many other shamans on Azeroth, I much prefer TotemTimers to the default totem bar. But if you also think that the Multicast Button is often not needed, thanks to the addon... you may want to disable it in the TotemTimers options ! However, this option causes <b>a switch to the default totem bar (as written on their CurseForge page), so you're not able to pre-select totems individually anymore.</b> This patch is a try to do it right, <b>giving you finally a way to show/hide this button while retaining all the good features of TotemTimers</b>.

---

<h2 style="color:blue">Features</h2>

* <b>An additional option to show/hide your Multicast Button from TotemTimers, without switching to the default totem bar</b> (go in TotemTimers options panel > Timers tab).
* Two commands to switch the display mode more quickly : <b>"/tt mc on" and "/tt mc off"</b>, when needed between fights.
* No UI reload required 

---

<h2 style="color:blue">How to install</h2>

To install the patch, all you need is to replace 5 files in your TotemTimers addon folder (or their content with any text editor) by the following ones. 

 <h3 style="color:cyan">Files link here : https://jumpshare.com/b/wSlVKGLuAT3aS0sCM4mp</h3>

<b>It contains 5 updated lua files :  MultiSpell.lua, Timers.lua, Settings.lua, DefaultSettings.lua and TotemTimers.lua</b>

In case of improper manipulation, don't forget you can always redownload the addon from Curseforge (I will try to upload future versions of the patch if needed).

---