# mm-vue-tab

> 简易的移动端多栏tab

## Demo

仓库：https://github.com/er567/mm-vue-tab

## Installation

#### npm  
```bash
npm install mm-vue-tab 
```

## Usage 

import first

```javascript
import Vue from 'vue'
import Tab from 'mm-vue-tab'
Vue.use(Tab); 
```

use components

```html
<mm-vue-tab :options="option">
    <div slot="bd-1">...</div>
    <div slot="bd-2">...</div>
</mm-vue-tab>
```

## Constructor Options

```javascript
option:{
    name: ['导航一','导航二'],   //导航名称
    lineColor: '',              //默认 #f95d5b
    slotName: ['bd-0','bd-1'],  //插槽名称
    tabClick:function(){        //触发导航
        console.log('click tab')
    }
} 
```