# Amazon JP Product Research SOP

这是一个用于 Amazon.co.jp 选品调研的 SOP 工作台。

## 目录

- `sop/`：分阶段选品调研 SOP
- `projects/`：每个新品调研项目
- `templates/`：状态文件、输出模板
- `scripts/`：后续用于 pandas / openpyxl 自动出表的脚本

## 使用方式

1. 先在 `projects/` 下创建一个新品项目文件夹；
2. 填写 `00_项目状态.md`；
3. 把市场数据、关键词数据、供应链报价放入 `input/`；
4. 让 Codex 按阶段执行 SOP；
5. 每个阶段输出保存到 `output/`；
6. 中间清洗数据保存到 `work/`。
