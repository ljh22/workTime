# workTime

## 拉取优化后记得提交哈！！！！！

#### 介绍
计算工时

#### 使用说明

 **1.  打开个人考勤，点击查看打卡数据，随后打开控制台（快捷键F12）点到 network 选项卡，清空请求数据** 
|![输入图片说明](https://foruda.gitee.com/images/1711614780301895326/9c11fc4b_10888693.png "屏幕截图")|
|--|
|![输入图片说明](https://foruda.gitee.com/images/1711614915826357888/3812038f_10888693.png "屏幕截图")|

 **2.清空数据后，选择50条数据，点击 getLocSetDataByPage 请求，切换到 response** 
|![输入图片说明](https://foruda.gitee.com/images/1711614969130527928/dc35a170_10888693.png "屏幕截图")|
|--|
|![输入图片说明](https://foruda.gitee.com/images/1711615026549164653/9f871844_10888693.png "屏幕截图")|

 **3.找到 items，点击左侧收起的小图标，之后复制这个数组带不带后面的逗号均可以** 
|![输入图片说明](https://foruda.gitee.com/images/1711615092070250659/a95d1b2c_10888693.png "屏幕截图")|
|--|
|![输入图片说明](https://foruda.gitee.com/images/1711615148303292328/279ba83a_10888693.png "屏幕截图")|

#### JSON数据模版

```json
[
                    {
                        "dt": "2024-05-06",
                        "checktime": "2024-05-06 08:39:52",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-06",
                        "checktime": "2024-05-06 17:40:28",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-07",
                        "checktime": "2024-05-07 08:37:59",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-07",
                        "checktime": "2024-05-07 19:38:11",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-08",
                        "checktime": "2024-05-08 08:37:07",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-08",
                        "checktime": "2024-05-08 19:53:59",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-09",
                        "checktime": "2024-05-09 08:39:34",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-09",
                        "checktime": "2024-05-09 19:34:17",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-10",
                        "checktime": "2024-05-10 08:38:17",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-10",
                        "checktime": "2024-05-10 17:45:36",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-11",
                        "checktime": "2024-05-11 08:37:25",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-11",
                        "checktime": "2024-05-11 17:43:55",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-13",
                        "checktime": "2024-05-13 08:37:33",
                        "type": "1"
                    },
                    {
                        "dt": "2024-05-13",
                        "checktime": "2024-05-13 17:39:01",
                        "type": "2"
                    },
                    {
                        "dt": "2024-05-14",
                        "checktime": "2024-05-14 08:37:43",
                        "type": "1"
                    }
                ],
```


