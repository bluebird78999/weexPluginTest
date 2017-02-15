# 如何使用
```
weexpack plugin add weex-chart
```

# 代码示例
```html
<chart id="c1" width="750" height="400"></chart>
```
```
var G2=require('weex-chart')('g2');//使用g2这个chart 目前只支持g2
module.exports={
        ready:function(){
            var chart = new GM.Chart({
                    id: 'c1'
            });
            ...
            chart.render()
        }
}
```
关于g2的用法 请参见[g2-module](https://github.com/antvis/g2-mobile)