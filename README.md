# react-watermark
A watermark for react

### 1、Reason
This Project refactor from a general javascript file about watermark. And I convert it to a React Project.

### 2、How to Use:


```
    const options = {
      wm_txt: <span>{`ID:${id}`}<br/>{` \n Nick: ${nick}`}</span>,
    }
    return <Watermark options={options} />;
```


### 3、defaultOptions:

```
    options = {
      wm_txt: 'String' || component,
      wm_x: 20, // 水印起始位置x轴坐标
      wm_y: 20, // 水印起始位置Y轴坐标
      wm_rows: 200, // 水印行数
      wm_cols: 200, // 水印列数
      wm_x_space: 10, // 水印x轴间隔
      wm_y_space: 90, // 水印y轴间隔
      wm_color: '#000000', // 水印字体颜色
      wm_alpha: 0.005, // 水印透明度
      wm_fontsize: '12px', // 水印字体大小
      wm_font: '微软雅黑', // 水印字体
      wm_width: 200, // 水印宽度
      wm_height: 30, // 水印高度
      wm_angle: 25 // 水印倾斜度数
    };
```

![react-watermark](./capture.png)

### 4、next want to do:

- refactor function handleColOrRowWhenZero. [finish at version-0.0.3]
- render mark in a target element.
- change option name in a right way.
- use svg not a div element.

### 5、origin source:
[watermark](http://www.cnblogs.com/GongQi/p/4074609.html?utm_source=tuicool&utm_medium=referral)
