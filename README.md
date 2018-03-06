# gistediter
gistediter
```js
(function(root){

function entry(obj){
 let o={};
 
 o.nc =function(){console.log('nullcaller')} 
 o.save =o.nc;
 o.load =o.nc;
 o.draw =o.nc;

}
;
 root.modXX =entry;
})(this);

```
