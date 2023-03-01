# Главная

Docsify топчик :heart:

```js
Array.prototype.likeFilter = function (f) {
  let re = [];
  this.forEach(e => {
    if (f(e)) {
      re.push(e);
    }
  });
  return re;
};

const arr = [1, 2, 3, 4, 5, 6];

arr.likeFilter(value => value % 2 == 0); // [2, 4, 6]
```
