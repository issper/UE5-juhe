# UE5-juhe
UE5数字孪生图标聚合

## 代码使用蓝图编写

## 使用方法
1. 将 **BP_juhe.uasset** 、**Struct_juhe.uasset** 导入到内容 **Content** 目录
2. 点击 **BP_juhe** 打开细节面板
3. 设置 **Juhe Min Value** : 聚合半径，屏幕像素小于该值会聚合
4. 设置 **Juhe Actor** : 为需要聚合的actor
5. 设置 **Tick Do** : 是否需要每帧聚合，否者需要主动调用 **BP_juhe** 里的 **juhe** 函数方法

![image](https://github.com/issper/UE5-juhe/assets/165617368/bcd305ff-f099-4d57-b110-b9ce9b843dbe)
