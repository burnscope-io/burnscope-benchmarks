# ESP32 最小示例固件

用于烧录工具一致性测试。

## 编译

```bash
. $IDF_PATH/export.sh
idf.py build
```

## 烧录（官方工具）

```bash
idf.py -p /dev/ttyUSB0 flash
```

## 烧录（zyrthi-flash）

```bash
zyrthi flash
```
