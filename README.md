# ZLFZ-JEANS-11.12

## 2026-11-14 背景统一待审核版

本次候选将同款 2–4 号图的背景匹配到该款 1 号图。121 张候选使用独立目录 `images-bg-20261114/{SKU}/{编号}.jpg`；已一致的 59 张图、全部 1 号图和 5 号尺码图沿用原文件及原 URL。旧版 `images/` 的 300 张图和旧清单均保留。

本版本用于审核，尚未全部通过“仅更换背景、主体不变”的要求。部分生成结果仍有水洗、肤色或局部织纹差异，请先查看逐图审核状态，再决定是否用于上架。

- [待审核 Excel 图片清单](SKU_IMAGE_URLS_BG_20261114.xlsx)
- [待审核 CSV 图片清单](SKU_IMAGE_URLS_BG_20261114.csv)
- [逐图审核状态](BACKGROUND_REVIEW_STATUS_20261114.csv)

121 张候选均为 2048 × 2048 的 RGB、sRGB JPG。其中 119 张通过赛维浏览器图生图生成；QFX-6612/2 和 QFX-2583/2 因赛维拦截，按用户明确授权仅这两张使用原图主体抠图与背景合成。所有尺码图保持原来的 2500 × 2500 JPG。

## 2026-11-12 原审核通过版本

2026-11-12 审核通过的牛仔服装商品图：60 个 SKU，共 300 张 JPG。

## 图片与清单

- 商品图：`images/{SKU}/1.jpg` 至 `images/{SKU}/5.jpg`。
- 1–4 号图：2048 × 2048 像素；5 号尺码图：2500 × 2500 像素，单位为 INCH。
- [Excel 清单](SKU_IMAGE_URLS.xlsx)
- [CSV 清单](SKU_IMAGE_URLS.csv)

清单每个 SKU 一行，列顺序为 `SKU, IMAGE1, IMAGE2, IMAGE3, IMAGE4, IMAGE5`。
IMAGE 列为可直接访问 JPG 的 Raw URL，例如：

`https://raw.githubusercontent.com/2449674090zlj/ZLFZ-JEANS-11.12/main/images/1021/1.jpg`

两款外套 XY8410-2、XY8459 的尺码图包含原表的胸围、肩宽、衣长、袖长；其他款式包含腰围、臀围、内长、外长。
