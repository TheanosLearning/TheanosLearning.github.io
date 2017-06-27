## Hey guys! I'm TensorFlow,

I enjoy playing Gears of War 4 Horde and developing hobby projects to enhance player experience. Most of my projects are in Javascript, which I learned by taking the _30 day Javascript challenge_.

[![Javascript30](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/Js30Challenge.png)](https://javascript30.com)

### Extensions

Several projects are actually Chrome extensions. These can easily be installed from the Chrome Web Store.

[![Chrome Extensions](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/ChromeExtensions.png)](https://chrome.google.com/webstore/search/gears%20of%20war%204?utm_source=chrome-ntp-icon&_feature=free&_category=ext/14-fun)

### Works in Progress

**1. Gears Quest**

Project development will continue after [season 2](https://gearsofwar.com/en-us/community/news/announcing-gears-pro-circuit-season-2) launch (fall 2017) of the Gears Pro Circuit.

```javascript
var sidebar = document.getElementById('sidebar');
var quest = sidebar.querySelectorAll('[data-quest-id]')[0];
var rewardBtn = quest.querySelector('.reward .button');
// claim your quest reward!
rewardBtn.click();
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

**3. ReUp 10+ XP**

With ReUps 11-15 recently added, there is a continual effort to keep XP tables updated. Visit the [forums](https://gearsofwar.com/en-us/forums/e9b54fc61eb74ad783d533ca502b0132/threads/re-up-10-i-need-your-help/7dbfff35-ba75-451a-802b-ef1f540018e3/posts) if you would like to help with this effort.

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

### Contact

[![Twitter](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/TwitterIcon.png)](https://twitter.com/_TensorFlow)
[![DiscordApp](https://github.com/TheanosLearning/TheanosLearning.github.io/raw/master/images/Discord App Logo.png)](https://discord.gg/NvjBC7E)
