# Skills

这里是我自研的一组 skills，用来沉淀可复用的工作流、评审标准和实践经验。

## 当前包含

- `skill-critic`：一个用于评审 Skill 的 Skill。它会在创建前审计划、创建后审草稿，判断这个 Skill 是否真的值得存在，并按六个维度给出 `Pass / Weak / Fail` 和明确 verdict。

## 目录结构

```text
skills/
  skill-critic/
    SKILL.md    # Skill 的核心说明和执行流程
    README.md   # 面向人的介绍、背景和使用说明
```

## 使用方式

按你的工具或平台要求引用需要的 Skill，或把对应目录复制到你的 Skills 配置目录中使用。

如果你准备新建一个 Skill，可以先让 `skill-critic` 审一下想法：

```text
用 skill-critic 审一下：我想创建一个用于 XXX 的 Skill。
```

它会给出是否值得创建、需要修改什么，以及是否可以进入正式编写阶段。

## 维护原则

- 每个 Skill 只解决一个清晰问题。
- 不把普通 prompt 能解决的一次性任务写成 Skill。
- `SKILL.md` 说明核心流程，要求可执行、可验证。
- `README.md` 面向人，说明背景、价值和使用场景。
