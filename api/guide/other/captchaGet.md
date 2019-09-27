# 获取验证码图片 API

获取验证码图片，使用`GET`发起请求，请求地址为`/api/v1/captcha/{name}`

```http
GET /api/v1/captcha/{name} HTTP/1.1
```

## 请求 URI

| 参数名 | 位置  | 类型   | 必填   | 说明                                          |
| ------ | ----- | ------ | ------ | --------------------------------------------- |
| name   | path  | 字符串 | **是** | 验证码名称                                    |
| apiKey | query | 字符串 | 否     | API 密钥，请参考[身份认证](authentication.md) |

## 返回

| 名称   | 类型 | 说明     |
| ------ | ---- | -------- |
| 200 OK | 图片 | 返回图片 |

## 示例

### 请求示例

```http
GET /api/v1/captcha/yzm HTTP/1.1
```

### 返回示例

![Image](/docs/api/assets/captcha/01.png)
