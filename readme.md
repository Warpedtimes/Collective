<h2>Collective</h2>
<p><a href="https://github.com/Serilum/Collective"><img src="https://serilum.com/assets/data/logo/collective.png"></a></p><h2>Download</h2>
<p>You can download Collective on CurseForge and Modrinth:</p><p>&nbsp;&nbsp;CurseForge: &nbsp;&nbsp;<a href="https://curseforge.com/minecraft/mc-mods/collective">https://curseforge.com/minecraft/mc-mods/collective</a><br>&nbsp;&nbsp;Modrinth: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://modrinth.com/mod/collective">https://modrinth.com/mod/collective</a></p>
<h2>Issue Tracker</h2>
<p>To keep a better overview of all mods, the issue tracker is located in a separate repository.<br>&nbsp;&nbsp;For issues, ideas, suggestions or anything else, please follow this link:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/issue-tracker">Issue Tracker</a></p>
<h2>Pull Requests</h2>
<p>Because of the way mod loader files are bundled into one jar, some extra information is needed to do a PR.<br>&nbsp;&nbsp;A wiki page entry about it is available here:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/pull-requests">Pull Request Information</a></p>
<h2>Mod Description</h2>
<p><a href="https://serilum.com/" rel="nofollow"><img src="https://github.com/Serilum/.cdn/blob/main/description/header/header.png" alt="" width="838" height="400"></a></p>
<p><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/header.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:75125" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_20.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:73407" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_19.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:73250" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_18.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:73242" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_17.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:70886" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_16.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:68722" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_15.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:64806" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_14.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/collective/files/all?filter-status=1&filter-game-version=1738749986:628" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_12.png"><span style="font-size:12px"><br><br></span></a><span style="font-size:24px">Collective is a shared library mod with common code for all of Serilum's mods.</span><span style="font-size:16px"><br><span style="font-size:16px;color:#000">It contains data and functions centralized in one place. Collective helps a great deal in maintainting both the Forge and Fabric versions.<br><br></span></span><span style="font-size:16px"><span style="font-size:16px;color:#000">Having access to the library's code environment, creates possibilities for current and future project features. The updating process is also made easier when there's an improvement for a function that is relevant to many others. For example this means having to update one project, instead of six. This saves time and makes me a little happier.</span><span style="font-size:16px;color:#000"><br></span></span><span style="font-size:24px"><span style="font-size:20px;font-weight:bolder;color:#000"><br>Features:</span></span></p>
<ul>
<li><span style="font-size:18px;color:#000">Manages all config files of dependent mods.<br></span></li>
<li><span style="font-size:18px;color:#000">Variables for increased compatibility with other projects.</span></li>
<li><span style="font-size:18px;color:#000">Functions that convert data for mods.</span></li>
<li><span style="font-size:18px;color:#000">An event to replace and resupply entities.</span></li>
<li><span style="font-size:18px;color:#000">Centralized backwards compatibility for major version changes.</span></li>
</ul>
<p><br><br><strong><span style="font-size:20px">Configurable:</span> <span style="color:#008000;font-size:14px"><a style="color:#008000" href="https://serilum.com/url/issue-trackerwiki/how-to-configure-mods" rel="nofollow">(&nbsp;how do I configure?&nbsp;)</a></span></strong><strong><br>transferItemsBetweenReplacedEntities</strong>&nbsp;(default = true): When enabled, transfer the held items and armour from replaced entities by any of the Entity Spawn mods which depend on Collective.<br><strong>loopsAmountUsedToGetAllEntityDrops</strong>&nbsp;(default = 100, min 1, max 200): The amount of times Collective loops through possible mob drops to get them all procedurally. Drops are only generated when a dependent mod uses them. Lowering this can increase world load time but decrease accuracy.<br><strong>findABlockcheckAroundEntitiesDelayMs</strong>&nbsp;(default = 30000, min 0, max 3600000): The delay of the is-there-a-block-around-check around entities in ms. Used in mods which depends on a specific blockstate in the world. Increasing this number can increase TPS if needed.<br><br><strong>enableAntiRepostingCheck</strong>&nbsp;(default = true): Please check out <a href="https://stopmodreposts.org/" rel="nofollow">https://stopmodreposts.org/</a> for more information on why this feature exists.</p>
<p><br>------------------<br><br><span style="font-size:24px"><strong>You may freely use this mod in any modpack, as long as the download remains hosted within the CurseForge or Modrinth ecosystem.</strong></span><br><br><span style="font-size:18px"><a style="font-size:18px;color:#008000" href="https://serilum.com/" rel="nofollow">Serilum.com</a> contains an overview and more information on all mods available.</span><br><br><span style="font-size:14px">Comments are disabled as I'm unable to keep track of all the separate pages on each mod.</span><span style="font-size:14px"><br>For issues, ideas, suggestions or anything else there is the&nbsp;<a style="font-size:14px;color:#008000" href="https://serilum.com/url/issue-tracker" rel="nofollow">Github repo</a>. Thanks!</span><span style="font-size:6px"><br><br></span><a href="https://ricksouth.com/donate" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/shields/donation_rounded.svg" alt="" width="306" height="50"></a></p>