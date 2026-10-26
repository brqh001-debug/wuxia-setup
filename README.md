# 天涯明月刀 客户端安装包（速装版）

本仓库仅存放一个文件：

| 文件 | 大小 | SHA-256 |
| --- | --- | --- |
| `WuXiaSetup_V2.0.1.22_Full_TDL_speeded_signed.exe` | 3,533,080 字节（3.37 MB） | `AA319E2A2D348504159636DB539F0DA387264CD2B02F24B96683A9D71124447F` |

## 文件信息

- **产品**：天涯明月刀（腾讯）
- **安装包版本**：V2.0.1.22 Full
- **数字签名**：`CN=Tencent Technology(Shenzhen) Company Limited`，签名状态 **Valid**（已通过验证）
- **签发机构**：VeriSign Class 3 Code Signing 2010 CA
- **文件修改时间**：2026-10-22 21:46:50

## 说明

- 这是安装包的**引导程序 / 启动器**，体积小（3.37 MB）。
- 原始的完整离线包由分卷 `WuXiaSetup_V2.0.1.22_Full.7z.001` ～ `.7z.008` 组成，合计约 **13.42 GB**，**未包含在本仓库中**（GitHub 单文件上限 100 MB，仓库上限约 5 GB，Git LFS 免费额度仅 1 GB）。
- 如需分发完整离线包，建议使用网盘或对象存储（阿里云 OSS、腾讯云 COS、Cloudflare R2 等）。

## 校验方式

```powershell
Get-FileHash -Algorithm SHA256 .\WuXiaSetup_V2.0.1.22_Full_TDL_speeded_signed.exe
Get-AuthenticodeSignature .\WuXiaSetup_V2.0.1.22_Full_TDL_speeded_signed.exe
```

## 版权

安装包版权归腾讯公司所有，本仓库仅作存档备份用途，不主张任何权利。
