# postcss-px2px
A plugin for PostCSS that convert px to rem AND rem to px AND px to rpx AND rpx to px

### Refer to
[pxtorem](https://github.com/cuth/postcss-pxtorem) AND [pxtorpx-pro](https://github.com/Genuifx/postcss-pxtorpx-pro) AND 

### Input/Output
With the default settings, only font related properties are targeted.

```scss
// input
h1 {
    margin: 0 0 20px;
    font-size: 32px;
    line-height: 1.2;
    letter-spacing: 1px;
}

// output
h1 { 
  margin: 0 0 40rpx; 
  font-size: 64rpx; 
  line-height: 1.2; 
  letter-spacing: 2rpx; 
}
```
