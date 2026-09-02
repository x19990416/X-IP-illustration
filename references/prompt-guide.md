# 生图与改图提示指南

## 新图模板

为每张图单独组织提示词，并把 `../assets/x-ip-reference.png` 作为参考图传给图像工具：

```text
Create one standalone 16:9 horizontal illustration for a Chinese article.

Use the attached X character sheet as the identity reference. Keep X recognizable: round white head, round glasses, tiny hair tuft, thin black stick-figure body, cobalt-blue neckerchief, gentle focused expression. X must perform the core conceptual action, not decorate the scene.

Core idea: {一句话观点}
Composition: {X 在哪里、做什么、对象如何变化或连接}
Short Chinese labels: {0-6 个短词；不需要时为空}

Visual style: pure white background, loose black hand-drawn linework, cobalt-blue accents, lots of empty space, clear editorial sketch, calm and intelligent. Keep the scene sparse and readable.

Do not create a PPT slide, dense infographic, formal architecture diagram, commercial vector mascot, 3D render, realistic scene, or children's illustration. No top-left title, no page number, no logo, no “一毛半”. Do not print “X” unless explicitly requested. One image communicates one idea.
```

## 连续多图

每张都使用同一角色参考图，并重复不可丢失的识别点。保持线条、蓝色、留白和角色比例一致；改变动作与构图，不要只换文字。

## 局部修正

- **角色漂移**：要求只修正脸型、圆框眼镜、发梢、蓝领巾和细线身体，其余构图保持不变。
- **错字**：只替换错误标注；若错字很多，删除非必要文字再生成。
- **旧名字残留**：明确删除所有“一毛半”，必要时用 `X` 替换；其余内容保持不变。
- **过度拥挤**：删除次要模块、箭头和标注，保留一个核心动作与最多 3-5 个对象。
