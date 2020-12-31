### Example in support of a webpack question on Stack Overflow:

https://stackoverflow.com/questions/65525095/webpack-output-change-v4-to-v5/

On migrating the basic sample from the [v4 webpack getting started guide](https://v4.webpack.js.org/guides/getting-started/#basic-setup) (as an example, this occurred on a real project), I run into this issue:

The [output of v5](https://github.com/tlmii/webpack-v4-to-v5-example/blob/main/v5/dist/main.js) seems to be immediately/self -executing:

```javascript
(function() {
...
})();
```

whereas the [output of v4](https://github.com/tlmii/webpack-v4-to-v5-example/blob/main/v4/dist/main.js) was not:

```javascript
(function(modules) {
...
});
```
