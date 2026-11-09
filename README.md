# 一加 SM8650 通用闭源 blobs 📦

高通 SM8650（pineapple）平台一加机型的公共专有文件，
从 OxygenOS `11.F.58`（Android 16）里扒出来的。

## 谁在管这棵树

**SorasakiHinaHusband** —— 二进制版权不在我，锅也不在我（大概）🙃

## 分支

`Cinderella` —— MikuUI（Android 17 / BP2A）。

## 怎么用

挂载到 `vendor/oneplus/sm8650-common`。`Android.bp` 由通用设备树里的
`extract-files.py` 生成，把每个 blob 声明成 prebuilt 模块。

## 许可证

这里的二进制归 OnePlus、Qualcomm 及其供应商所有。
放在这里只是为了让这台机器能编 ROM，版权仍然归原主。
