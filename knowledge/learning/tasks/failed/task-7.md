---
task_type: "compile"
status: "pending"
created_at: "2026-07-15T13:44:35.361544+00:00"
params:
  item_ids: ['2bcc67a1ae5b', '6a7a0bc848b1', '8aa045e93fbb', '357d5032ce99']
reason: "superseded:Phase 1j batch compile complete; queue cleanup"
failed_at: "2026-07-17T02:13:20.118892+00:00"

---

# 编译任务

请对以下知识条目执行编译：

- [[2bcc67a1ae5b]]
- [[6a7a0bc848b1]]
- [[8aa045e93fbb]]
- [[357d5032ce99]]

## 编译步骤
1. 分类 + 打标（domain/topic/type/difficulty + tags）
2. 概念提取（写入 concepts/{slug}.md）
3. 概念关联（更新条目 frontmatter.concepts）
4. 标记 compiled=true
