# Hey guys, I'm TensorFlow!

### I enjoy playing Gears of War 4 Horde and developing hobby projects to enhance player experience.

&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
![Born to Kryll](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/born_to_kryll.jpg)

I also like nerding out on in-game numbers, creating spreadsheets, and chatting with fellow Gears players & friends on the **Gears of War Project Development** channel on [Discord](https://discordapp.com/). Take a look at what I've been up to lately:

## Extensions

Several projects are actually Chrome extensions which can be installed from the Chrome Web Store.

[![Chrome Extensions](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/ChromeExtensions.png)](https://chrome.google.com/webstore/search/gears%20of%20war%204?utm_source=chrome-ntp-icon&_feature=free&_category=ext/14-fun)

## Tac-Com

Other projects are hosted by [Tac-Com](http://gowtaccom.weebly.com/) on their tools page.

[![Helpful Tools](http://gowtaccom.weebly.com/uploads/5/4/7/8/54784787/lp-headers-tools_3_orig.jpg)](http://gowtaccom.weebly.com/tools.html)

## Works in Progress

**1. Gears Quest**

Project development will continue after [season 2](https://gearsofwar.com/en-us/community/news/announcing-gears-pro-circuit-season-2) launch (fall 2017) of the Gears Pro Circuit.

```javascript
var sidebar = document.getElementById('sidebar');
var claimableQuests = sidebar.querySelectorAll('[data-quest_id].completed');
var rewardBtns = Array.from(claimableQuests).map(quest => quest.querySelector('.reward > .button'));
// claim all completed rewards!
rewardBtns.map(btn => btn.click());
```
  
**2. Color Blast Packs**

Setting the glow animation on open instead of on hover. Just look at those beautiful floating particles of rarity!

![gif demo](https://media.giphy.com/media/QLen4sArKARjO/giphy.gif)

```css
#pack-view .revealPack .card-list-item .hoverParticles div {
  -webkit-animation-iteration-count: infinite;
  animation-iteration-count: infinite;
}
```

**3. Wings**

With ReUps 11-15 recently added, there is a continual effort to keep XP tables updated. Visit the [forums](https://gearsofwar.com/en-us/forums/e9b54fc61eb74ad783d533ca502b0132/threads/re-up-10-i-need-your-help/7dbfff35-ba75-451a-802b-ef1f540018e3/posts) if you would like to contribute.

```javascript
var xp = JSON.parse(document.getElementById('initialState').textContent).versus.ExperienceStats.Stats[0];
/*{
  Level: 100,
  ReUp: 10,
  EXP: 10899900,
  EXPToCurrent: 0,
  EXPToNext: 0
}*/
console.log(xp);
```

## Contact me on Twitter or Discord

[![Twitter](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/twitter-red_125x125.png)](https://twitter.com/_TensorFlow)
&emsp;&emsp;
[![DiscordApp](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/gpd_125x125.png)](https://discord.gg/NvjBC7E)
