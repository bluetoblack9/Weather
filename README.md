# Weather
Kotlin练习项目，查看天气
# 主要功能
1. 搜索全球大多数国家的各个城市数据
3. 查看全球绝大多数城市的天气信息
4. 自由地切换城市，查看其它城市天气
5. 手动刷新实时的天气

# 前期准备工作
1. 使用彩云天气的API实现信息的获取
2. 相关功能的接口  
（1）获取全球绝大数城市的数据，接口过期，使用文件读取方式，调用第三方的接口   
（2）根据经纬度获取天气 https://api.caiyunapp.com/v2.5/TAkhjf8d1nlSlspN/121.6544,25.1552/weather.json   
（3）获取该地方未来几天的天气 https://api.caiyunapp.com/v2.5/TAkhjf8d1nlSlspN/121.6544,25.1552/daily.json
