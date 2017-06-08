# Glomex Player API

This is a non offical Player API, until Glomex release a own player api. 

### Demo
[Link](https://lukas-vollmer.github.io/glomex-player-api/index.html)

### Configuration


```js
$('.glomexPlayer').glomexPlayer({
    videoId: 'v-b6tzpugd4ogh', //videoId
    duration: 35640, //Video duration in ms
    load: function () {
        console.log('VIDEO LOADED');
    },
    start: function () {
        console.log('VIDEO START');
    },
    break: function(){
        console.log('VIDEO BREAK');
    },
    complete: function () {
        console.log('VIDEO COMPLETE');
    }
});
```
**Please note that the player only works with domains, that are registered at glomex!**

License
----

MIT


**Free Software, Hell Yeah!**
