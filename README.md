RongCloud Server API(ES6版)
===========================
融云服务器端API。


## 功能列表
- 用户服务
- 群组服务
- 敏感词服务
- 聊天室服务
- 历史消息服务
- 发送消息（文本、图片、语音、视频、音乐、图文）

## 更新历史
- 1.0.0 第一版发布。   

详细参见[API文档](http://www.rongcloud.cn/docs/server.html)

## Installation

```sh
$ npm install sb-co-rongcloud-api
```

## Usage

```js
var RongAPI = require('sb-co-rongcloud-api');

var api = new RongAPI(appid, appsecret);
var token = yield* api.getToken('shanbang');
```

## Make Document

```sh
npm install doxmate -g
make dox
```

文档在 ./doc/index.html 处。

## License
The MIT license.
