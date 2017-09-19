# cordova-plugin-amap
高德地图Amap的Cordova插件

### 安装
`cordova plugin add https://github.com/eyre/cordova-plugin-amap.git --variable API_KEY=your_api_key`
### 插件调用
```
...
declare var AmapPlugin: any;
...
...
    AmapPlugin.getLocation('xxx',
    succ=>{
    	alert(succ);
    },
    err=>{
    	alert(err);
    });
  ...

```