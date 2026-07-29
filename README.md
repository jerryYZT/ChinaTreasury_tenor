# ChinaTreasury_tenor

关键期限国债（5Y / 10Y / 30Y）发行时间规律可视化页面，以及配套外挂 CSV 数据。

在线预览（GitHub Pages）：https://jerryyzt.github.io/ChinaTreasury_tenor/

## 致谢与授权说明

本仓库参考了 **Fletcher Feng** 的相关成果，并在此基础上进行了修改与整理。

**仅供学习与研究使用，不得商用。**

未经权利人明确授权，请勿将本仓库内容用于任何商业目的。

## 本地查看

```bash
python3 -m http.server 8765
```

浏览器打开 `http://127.0.0.1:8765/` 或 `key_tenor_timeline.html`。  
也可直接双击打开 HTML（页面内嵌了 CSV 回退副本）。

## 目录结构

- `key_tenor_timeline.html`：主页面
- `index.html`：Pages 根路径跳转
- `data/*.csv`：图表外挂数据
