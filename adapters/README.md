# 平台适配器

为不同平台提供通信适配代码。

## 目录结构

```
adapters/
├── arduino/        # Arduino 平台适配
└── mcs51/          # 51 单片机平台适配
```

## Arduino

通过串口接收指令，控制本地外设。

```cpp
#include <AwakenCore.h>

void setup() {
  AwakenCore.begin(9600);
}

void loop() {
  AwakenCore.process();
}
```

## 51 单片机

标准 C 语言实现，适配 STC89C52 等型号。
