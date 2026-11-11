# StarWeave Air 支持
最后更新：2026-11-10

## 联系方式
hudongsheng356@gmail.com
请在邮件主题中写明“StarWeave Air 支持”，并提供应用版本、iPad 型号、iPadOS 版本及复现步骤。请只发送你愿意分享的截图和最小示例；不要发送密码或无关敏感资料。

## 快速开始
- 载入内置示例，或导入满足条件的单色二维 FITS。
- 选择参考帧，确认同视场、尺度与滤镜后执行配准。
- 检查原图/对齐/闪烁及配准指标。
- 需要时选择均值或中位数、最小覆盖率并叠加。
- 导出对齐结果及处理报告。

## 数据和使用边界
要求单色、同视场、相同尺度与滤镜；不估计缩放、反射或非线性畸变。叠加要求相等且为正的曝光时间，不做亮度归一化、加权叠加或背景归一化。预览拉伸不改变导出像素；请在结束会话前导出结果。

## 保存与备份
输入图像在本机读取，配准与叠加使用本地会话缓存。会话缓存用于处理，不构成永久原始文件备份；需要保留的 FITS 和报告应由用户导出。
卸载或删除应用前，请先导出重要资料并保留原始文件。仅卸载应用与删除应用的系统行为可能不同；请按 iPad 的实际选项确认。

## 常见问题

### 为什么有图像被排除？
匹配数、空间分布、残差或重叠率可能不满足条件。检查指标，并确认输入视场、尺度与滤镜一致。

### 为什么不能叠加？
叠加需要足够的成功配准帧和相等、为正的曝光时间。请检查输入元数据。

### 文件选择器里找不到文件，或云文件无法读取？
先在系统“文件”中确认文件已完整下载、你有访问权限，且格式受本应用支持。重试时优先使用“我的 iPad”中的本地副本。扩展名相同不保证内部数据结构一致。

### 怎样报告问题？
说明你执行的操作、预期结果与实际结果，并提供不含敏感信息的截图。若需要样例，优先构造小型合成文件。没有源文件也可以先报告，我们会根据描述继续沟通。

## 隐私
本应用不要求账户，主要处理在设备本机完成。请阅读同目录的隐私政策，了解本地存储、文件服务和主动支持邮件的处理方式。

---

# StarWeave Air Support
Last updated: 2026-11-10

## Contact
hudongsheng356@gmail.com
Use “StarWeave Air Support” in the subject. Include the app version, iPad model, iPadOS version, and reproduction steps. Send only screenshots and minimal examples you are comfortable sharing. Do not send passwords or unrelated sensitive information.

## Quick start
- Load the built-in demo or import suitable monochrome 2D FITS frames.
- Select a reference, confirm matching field, scale, and filter, and align.
- Inspect Original/Aligned/Blink views and registration metrics.
- Optionally choose mean/median and minimum coverage, then stack.
- Export aligned products and processing reports.

## Data and scope
Requires monochrome images of the same field, scale, and filter. It does not estimate scale, reflection, or nonlinear distortion. Stacking requires equal positive exposures and does not perform brightness normalization, weighted stacking, or background normalization. Preview stretching does not alter exported pixels. Export results before ending the session.

## Saving and backups
Inputs are read locally, and registration/stacking use local session caches. These caches support processing and are not permanent source-file backups. Export FITS files and reports you want to retain.
Export important work and retain source files before offloading or deleting the app. Offload App and Delete App can have different effects; check the actual system option on your iPad.

## Frequently asked questions

### Why were some frames excluded?
Match count, spatial distribution, residual, or overlap may fail acceptance criteria. Inspect metrics and confirm matching field, scale, and filter.

### Why is stacking unavailable?
Stacking needs enough accepted frames with equal positive exposure times. Check input metadata.

### A file is missing from the picker, or a cloud file will not open
In Files, confirm the file is fully downloaded, accessible, and in a supported format. Try a local copy under On My iPad. A matching filename extension does not guarantee a supported internal structure.

### How should I report a problem?
Describe the action, expected result, and actual result, with screenshots free of sensitive information. If an example is needed, prefer a small synthetic file. You may report the problem without a source file first; we can follow up from your description.

## Privacy
No account is required and core processing takes place on your device. Read the privacy policy in this folder for local storage, file services, and voluntary support communications.
