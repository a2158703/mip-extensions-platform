# mip-zmall-bmap

百度地图组件，用于显示地图，定位，计算距离等。

标题|内容
----|----
类型|业务组件
所需脚本|https://c.mipcdn.com/static/v1/mip-zmall-bmap/mip-zmall-bmap.js

## 更新

### 2018.05.30 (1.0.1)
- 增加距离计算显示中英文选择，以及支持自定义显示文案（采用模板实现）
- 修改如果是直接导航的，不渲染地图
- 修改定位图标的大小（marker)

## 示例

### 基本用法
```html
<mip-zmall-bmap data-type="distance" data-ak="" data-zoom="14" data-gps="true" data-lng="" data-lat="" data-address="" data-title=""></mip-zmall-bmap>
```

## 属性

### data-type

说明：类型是地图显示、还是计算距离。   
必选项：是    
取值范围：`distance`, `map`, `gps`   

### data-ak

必填，百度地图ak  

### data-zoom

非必填。地图缩放级别

### data-lng 

必填。经纬度

### data-lat

必填。经纬度

### data-gps

非必填。是否需要点击跳转到导航界面。取值为 `true` or `false`  

### data-title

非必填。当 `data-gps` 为 `true` 时为必填。

### data-address

非必填。当 `data-gps` 为 `true` 时为必填。

## 注意事项

