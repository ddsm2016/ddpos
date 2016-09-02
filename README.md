# 东大购物中心POS机镜像文件

镜像位置：百度云@东大公司 -> 收银机镜像 文件夹内。

镜像命名：`类型_子公司编号_主机型号_终端号`，终端号`000`表示未初始化。

例：*pos_xzbh_hk380_000.json*
```json
{
	"id": "ID，一般为文件名称",
    "name": "名称",
	"desc": "描述",
    "file": "文件下载地址",
	"key": "下载文件时的验证码,需要先解密",
    "application": [  
		"应用软件列表",
        "c_winxp",
        "ehd_pos_v9",
        "oracle_8.1.7",
        "pcaw_10.5",
    ],
    "environment": [
		"系统环境列表",
        "j2re-1_4_2_01",
        ".net_4.0"
    ]
}
```

[解密地址](http://tool.chinaz.com/tools/textencrypt.aspx)

**类型分类**

1. pos : 收银机

**子公司编号**

1. xzbh : 忻州百货
2. ypbh : 原平百货

