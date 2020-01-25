# 中国新型冠状病毒肺炎疫情地级市图

## 使用说明

```bash
python3 generate_data.py # 这一步会从丁香园疫情网页上获得地级市的疫情确认数，之后写入到 dxy_confirmed_data.js
open map.html # 使用高德地图 API 画图，使用了上一步中的获得的数据
```

## 注意事项
* 目前没有处理疑似病例
* 不包括港澳台。直辖市不细分区县。
* 丁香园的数据（地级市名字）比较脏，代码中我自己洗了数据。大家有更好的办法欢迎告诉我
* 高德地图 JS API 需要使用开发者 Key，现在我为了方便大家，直接放入了我个人的 Key，请大家友善对待～

