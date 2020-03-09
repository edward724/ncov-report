
**简要描述：**
- 学生端，提交上报表单

**请求URL：**
- ` ~/index/report/save `

**请求方式：**
- POST

**参数：**

| 参数名 | 必选 | 类型 | 说明 |
| :---- | :---- | :---- | ---- |
| uid | 是 | int | 用户在微信小程序信息库中的编码id|
| token | 是 | string | token|
| template_code | 是 | string | 模板编码 |
| data | 是 | object | 表单数据（具体请参见表单模板文档） |

**表单模板列表**

| 表单说明 | 模板编码 | 文档链接 |
| ------------ | ------------ | ------------ |
| 默认模板 | default |  |



**参数实例**
```
{
	"uid": 3,
	"token": "",
	"template_code": "default",
	"data": {}
}
```

 **返回示例**

```
{
	"errcode": 0,
	"message": "数据提交成功"
}
```

 **备注**

- 更多返回代码请看全局返回参数说明