# ViewAny 所见即所得文档套件演示

欢迎使用 **ViewAny**，这是专为 VS Code 打造的全能所见即所得 (WYSIWYG) 办公与 PDF 套件！

## 🎯 核心功能一览

1. **多格式支持**：Markdown (`.md`)、Word (`.docx`)、Excel (`.xlsx`/`.csv`)、PDF (`.pdf`)
2. **实时双向同步**：所见即所得富文本编辑与底层源码无缝双向更新
3. **多格式自由导出**：支持导出为 PDF、Word、Excel、Markdown、HTML 等
4. **智能页数估算与注册授权**：免费版支持任意文档编辑及 $\le 5$ 页导出，超过 5 页时支持输入注册码无限制解锁

---

## 📊 销售业绩统计表示例

| 产品名称 | 季度销售额 (万元) | 同比增长 | 状态 |
| --- | --- | --- | --- |
| ViewAny Pro 桌面版 | 128.5 | +32% | 🟢 畅销 |
| ViewAny Office 插件 | 256.0 | +58% | 🟢 爆款 |
| 团队尊享版定制服务 | 89.2 | +15% | 🟡 稳定 |

> 💡 **提示**：在顶部工具栏可随时点击 **「导出...」** 转换为 PDF、Word 或 HTML。免费版即可查看/编辑任意文档并导出 ≤5 页；解锁无限制导出需在 **「👑 授权中心」** 输入正式注册码（复制机器码向管理员申请）。

```typescript
// ViewAny 导出示例代码
const exportConfig = {
  format: 'pdf',
  quality: 'high',
  pageCount: 3
};
console.log('Exporting document with ViewAny...');
```
