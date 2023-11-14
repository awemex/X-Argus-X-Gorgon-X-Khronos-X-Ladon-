## 抖音IOS X-Argus X-Gorgon X-Khronos X-Ladon

```text
抖音IOS X-Argus X-Gorgon X-Khronos X-Ladon 
[联系测试](https://psslk.org/kiins)
```

## /解密

```text
暂无描述
```

#### 接口状态

> 开发中

#### 接口URL

> http://xxxxxxx/api/ios/dy_argus_decode

#### 请求方式

> POST

#### Content-Type

> json

#### 请求Header参数

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| auth | 9959be5dd8490410f2bb41b2ba92ccec | Text | 是 | - |
| Content-Type | application/json | Text | 是 | - |

#### 请求Body参数

```javascript
//抓包得到
{
    
        "gorgon": "xx",
        "argus": "xxx",
        "ladon": "xxxx"
    }



```

#### 预执行脚本

```javascript
暂无预执行脚本
```

#### 后执行脚本

```javascript
暂无后执行脚本
```

## /加密

```text
暂无描述
```

#### 接口状态

> 开发中

#### 接口URL

> http://xxxxxxx/api/ios/dy_argus

#### 请求方式

> POST

#### Content-Type

> json

#### 请求Header参数

| 参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述 |
| --- | --- | ---- | ---- | ---- |
| auth | 9959be5dd8490410f2bb41b2ba92ccec | Text | 是 | - |
| Content-Type | application/json | Text | 是 | - |

#### 请求Body参数

```javascript
{
"url": "https://api26-normal-hl.amemv.com/aweme/v1/commit/item/digg/xxxxxxxxxxxxxxxxx", 
"method": "post", 
"body": "nearby_level=0&friend_recommend=0&type=1&aweme_id=xxxxxxx&channel_id=13&is_commerce=0", 

//解密得到
 "device_id": "xxxxx", 
        "gorgon_sdk_version_str": "xxx",
        "appid": "1128",
        "app_version": "24.8.0",
        "argus_sdk_version_str": "v04.04.01-ml-iOS",
        "argus_sdk_version": 134742530,
        "argus_devices_token": ""
        
}
```

