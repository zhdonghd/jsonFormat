# jsonFormat

HTML display thestring in json format!

Input String：'{"name":"中国","province":[{"name":"黑龙江","cities":{"city":["哈尔滨","大庆"]}},{"name":"广东","cities":{"city":["广州","深圳","珠海"]}}]}'

output：

``` 
{
    name: "中国",
    province: [
    {
        name: "黑龙江",
        cities: {
            city: [
                "哈尔滨",
                "大庆"
            ]
        }
    },
    {
        name: "广东",
        cities: {
            city: [
                "广州",
                "深圳",
                "珠海"
            ]
        }
    }
    ]
}
```

