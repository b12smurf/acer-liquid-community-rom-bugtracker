#LCR 1.3 addons

# There was a bug with addon pack v1 (network access) and v2 (when no apps were installed from market before applying pack). If you have installed v1 or v2, simply install addon pack v3 to fix #

<table>
<tr>
<td>

Always launch a nandroid backup before applying any update.<br>
<br>
<h1>LCR 1.3 addons</h1>

This package can be applied on top of the LCR 1.3 rom.<br>
It does not work on LCR 1.4<br>
<br>
<h1>Contents</h1>

<ul><li>fixsu (fix root access issues (see below)<br>
</li><li>clock / wether widget<br>
</li><li>animated wallpaper (Earth / HTC)<br>
</li><li>Online wallpaper app<br>
</li><li>Original launcher with app/photo launcher (use adb shell launcher stock/helixir to change)<br>
</li><li>NemoPlayer<br>
</li><li>Dimmer (auto brightness ajust)</li></ul>

<h1>Fix root access issues</h1>

In case you have issues with root access, run this command<br>
<br>
<pre><code>adb shell fixsu<br>
</code></pre>


<h1>Animated wallpapers</h1>

If you encouter problems with Earth wallpaper, configure it to work in foreground<br>
<br>
<h1>Change default launcher</h1>

The rom will let you choose you launcher until you have checked the "use by default"<br>
<br>
If you want to change the default launcher used by the rom.<br>
<br>
Use default stock laucher with <b>mutlimedia widget and favorites by acer</b>

<pre><code>adb shell launcher stock <br>
</code></pre>

Use helix as default launcher<br>
<pre><code>adb shell launcher helixir <br>
</code></pre>

</td>
<td>
<img src='http://acer-liquid-community-rom-bugtracker.googlecode.com/files/LCR_1.3_addons.jpg' />
</td>
</tr>
</table>