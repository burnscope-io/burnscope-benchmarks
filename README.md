# burnscope-benchmarks

基准固件源码，用于验证烧录工具一致性。

## 目录结构

```
esp32/
├── hello/         # 最小固件
├── blink/         # GPIO 闪烁
└── uart_echo/     # 串口回显

stm32/             # 预留
```

## 使用方法

1. 用官方工具（idf.py）编译并烧录
2. 用 burnscope 采集黄金记录
3. 用待测工具烧录并对比
