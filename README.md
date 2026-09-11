# tincd‑static-build

使用 GitHub Actions + Alpine‑musl 编译 **纯静态版本 tincd 1.0.36**。

## 支持架构
- `aarch64 (arm64)`
- `armhf (armv7)`

## 特性
✅ 基于 Alpine musl 静态编译
✅ **无任何运行时系统库依赖**，直接复制到设备即可运行
✅ 已剥离调试符号，体积精简

## 使用方法
1. 在 [Releases](../../releases) 下载对应架构压缩包
2. 解压得到 `tincd‑xxx‑static`
3. 添加执行权限：
```bash
chmod +x tincd-aarch64-static
