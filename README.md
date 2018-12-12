# 雷公天气
一款天气应用微信小程序
<p align='center'>
    <img src='https://github.com/huangchaosysu/quietweather/blob/master/img/weather.jpg'>
</p>

## 截图
<div >
    <img src='https://raw.githubusercontent.com/myvin/miniprogram/master/quietweather/images/screenshot_1.png' style='width:300px;'>
    <img src='https://raw.githubusercontent.com/myvin/miniprogram/master/quietweather/images/screenshot_2.png' style='width:300px;'>
    <img src='https://raw.githubusercontent.com/myvin/miniprogram/master/quietweather/images/screenshot_3.png' style='width:300px;'>
    <img src='https://raw.githubusercontent.com/myvin/miniprogram/master/quietweather/images/screenshot_4.png' style='width:300px;'>
</div>

## 数据来源
地理编码、天气数据均来自[百度地图开放平台](https://lbsyun.baidu.com/)。个人开发完全免费，有对应的小程序 `sdk`，加入即可，但是返回的天气数据较少。

## 运行前准备
> * [注册微信小程序](https://mp.weixin.qq.com/wxopen/waregister?action=step1)，获取 `appid`，配置域名白名单(在小程序后台将使用到的 `API` 添加到域名白名单)；
> * 注册[百度地图开放平台](https://lbsyun.baidu.com/)开发者，创建应用 **（注意：应用类型选择微信小程序时，请填写真实的小程序 appid）** ，获取 `ak`（其他配置可自行查看）；
> * 在 `app.js` 中替换 `globalData` 中的 `ak` 为自己的 `ak`；
> * Run and Enjoy!

## 请喝咖啡

如果你觉得这个项目对你有用不妨帮我转发个朋友圈宣传一下.
