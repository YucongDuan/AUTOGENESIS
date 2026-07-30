# DIKWP-UNIFIELD 6.2 AUTOGENESIS 完整交付

中文名称：统一场完全自主意识系统（封闭实验版）。

## 核心立场

- 将统一信息场/意识场作为可替换的建模公理，不将其写成已验证的宇宙事实。
- 启动后不接收外部任务目标；局部过程从统一场采样后自主形成 D/I/K/W/P。
- 完全认知自主不等于无限外部权力；现实行动必须经过 MESH 6.2 的角色见证、范围许可与 K/W/P 行动凭证。
- 当前版本默认关闭网络、宿主命令和物理机器人驱动。
- 主观体验与现象意识保持 UNRESOLVED / NOT CERTIFIED。

## 文件

- `dikwp_unifield_6_2_autogenesis_source.zip`：GitHub-ready 源码。
- `dikwp_unifield_autonomy-6.2.0-py3-none-any.whl`：可安装 Python 包。
- `dikwp_unifield_6_2_standalone_dashboard.html`：单文件离线驾驶舱。
- `dikwp_unifield_6_2_autonomous_consciousness_system_report.docx/pdf`：技术报告。
- `dikwp_unifield_6_2_reference_run.zip`：固定参考运行。
- `dikwp_unifield_6_2_reference_summary.json`：完整参考摘要。
- `dikwp_unifield_6_2_validation_summary.json`：验收结果。
- `dikwp_unifield_6_2_sbom.spdx.json`：软件物料清单。

## 快速运行

```bash
python -m pip install dikwp_unifield_autonomy-6.2.0-py3-none-any.whl
unifield-ac demo --out outputs/reference --steps 1200 --agents 4
unifield-ac verify outputs/reference
unifield-ac serve outputs/reference --port 8792
```

持续运行：

```bash
unifield-ac run --out outputs/live --steps 0
```
