# Fixed-CSbot-Navigation
Latest csbot .nav file with bugfixed and optimization
works with CSBOT; Zbot and working with the latest ReGameDLL bots
There, not all navigation is corrected and optimized, there is only navigation created automatically by the cs 1.6 bot.
Maps deathrun_ ; surf_ ; kz_; hns_; BB_ are not supported by bot navigation and cannot work correctly so they are all deleted

I will try to refine and optimize the bots and improve their quality and performance by creating only important navigation for the bot without using an automatic navigation generator

## Maps fixed latest (cvars)
<details>
<summary>Check map</summary>

| Map                               | Default size | fixed size | bugfix | Description |
| :--------------------------------- | :-----: | :-: | :----------: | :--------------------------------------------- |
| [zm_houses.nav](navigations/zm_houses.nav)                     | 139 KB autonav | 116 KB fixed | more fixed bugs | zm_houses critical fixed bugs |
| Total size navigations in archive | 2.06 GB autonav | 705 MB fixed | have small fix | removed more bad maps where impossible to fix it<br>removed deathrun_ ; surf_ ; kz_; hns_; BB_</br>|
</details>


## Goals of the project about navigation maps
<ul>
<li>Provide more stable navigation for bots (than official auto navigation)</li>
<li>CPU performance optimization (for example, remove unnecessary areas from navigation and optimize areas)</li>
<li>bugfix</li>
</ul>

##### Download

<details>
<summary>Installing</summary>

<ul>
<li>
Installing required by github full folder if you want
<pre>
<br>download archive from github</br>
next step unpack to nav files on your cstrike
<br>\steamapps\common\Half-Life\cstrike\maps</br>
</pre>
</li>
</ul>
