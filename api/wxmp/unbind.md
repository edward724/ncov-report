**简要描述：**

- 用户解除绑定

> ** 此接口需要传递 token 信息**

**请求URL：**
- ` ~/index/login/unbind `

**请求方式：**
- POST

**参数：**

| 参数名 | 必选 | 类型 | 说明 |
| :---- | :--- | :----- | :--- |
| uid | 是 | int | 用户在微信小程序信息库中的编码id|
| token | 是 | string | token|

**返回示例**

```
{
	"errcode ": 0,
	"is_registered ": 0,
}
```



**备注**

- 更多返回代码请看全局返回参数说明