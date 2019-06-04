# 百度移动统计Cordova插件

[![Greenkeeper badge](https://badges.greenkeeper.io/1ziton/cordova-plugin-baidutji.svg)](https://greenkeeper.io/)

## How to debug:
1. clone this project
2. remove the old plugin from the project
  ```
  cordova plugin remove cordova-plugin-baidu-mob-stat
  ```

3. add the plugin  

	iOS:  
  	```
  	cordova plugin add cordova-plugin-baidutji --variable APP_KEY=59db3b4b1e
  	```
  	
  	Android:  
  	```
  	cordova plugin add cordova-plugin-baidutji --variable APP_KEY="9c86821e1b"
  	```
  	
4. build and debug
