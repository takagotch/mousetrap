### mausetrap
---
https://github.com/ccampbell/mousetrap

```
npm test
cd /path/to/repo
npm install
npm install -g grunt-cli
```

```js
<script src="/path/to/mousetrap.min.js"></script>

<script>
  Mousetrap.bind('4', function(){ console.log('4'); });
  Mousetrap.bind("?", function(){ console.log('show shortcuts!')});
  Mousetrap.bind('esc', function(){ console.log('escape'); }, 'keyup');
  Mousetrap.bind('command+shift_k', function() { console.log('command shift k'); });
  Mousetrap.bind(['command+k', 'ctrl+k'], function(){
    console.log('command k or control k');
    return false;
  });
  Mousetrap.bind('g i', function(){ conslole.log('go to inbox'); });
  Mousetrap.bind('* a', function(){ console.log('select all'); });
  Mousetrap.bind('up up down down left right left right b a enter', function(){
    console.log('konami code');
  });
</script>
```

```js
var Mousetrap = require('mousetrap');
```

