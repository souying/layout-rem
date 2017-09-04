# rem.js
移动端页面满屏自适应方案（采用rem作为单位，设计稿为750 * 1334 或者设计稿为640 * 1334）
> [博客地址](http://www.jiaoyiba.cc)

[![NPM](https://nodei.co/npm/layout-rem.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/layout-rem/)
* 此方案删除了dpr，保留rem
* 满屏自适应，要求设计稿为750 * 1334
* 单位换算为1rem = 100px

## 使用方法
### 第一种：
    <head>
        <script src="rem.min.js"></script>
        <script>
            new Rem({
                desinWidth:750, //750这个值，根据设计师的psd宽度来修改，是多少就写多少，插件默认750 
                num:100         //100这个值，是1rem = 100px的比例 默认100比1的 可修改自己的比例 计算
            })
        </script>
    </head>
### 第二种npm下载：
    $ npm install --save layout-rem
### 使用1
    import rem from 'layout-rem';
    new Rem({
        desinWidth:750, //750这个值，根据设计师的psd宽度来修改，是多少就写多少，插件默认750 
        num:100         //100这个值，是1rem = 100px的比例 默认100比1的 可修改自己的比例 计算
    })
    使用2
    var rem = require('layout-rem')
    var rem = {
        desinWidth:750, //750这个值，根据设计师的psd宽度来修改，是多少就写多少，插件默认750 
        num:100         //100这个值，是1rem = 100px的比例 默认100比1的 可修改自己的比例 计算
    }
    
### 推荐使用第一种方法

> [github地址：](https://github.com/souying/layout-remc)