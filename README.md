# postcss-pxtopx
px to rem AND rem to px AND px to rpx AND rpx to px

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
