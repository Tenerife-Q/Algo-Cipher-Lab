# Algo-Cipher-Lab 🔐

算法与密码学的实验室 —— 竞赛算法训练 + 密码学研究的双轨成长空间

## 📋 项目简介

Algo-Cipher-Lab 是一个综合性的算法与密码学学习仓库，主要服务于：
- **ICPC 竞赛训练**：C++ 算法模板库与题解
- **考研机试准备**：精选算法模板与知识点总结
- **密码学研究**：基于 Rust 的数论库与零知识证明实验
- **数学推导**：核心定理的证明过程与学习笔记

## 🗂️ 项目结构

```
Algo-Cipher-Lab/
├── .vscode/               # 存放 C++/Rust 的编译调试配置文件
├── cpp_arena/             # C++ 竞技场（ICPC & 考研机试）
│   ├── templates/         # 算法武器库（只放经过验证的、极致优化的代码）
│   │   ├── math/          # 数论、组合数学、线性代数（你的主场）
│   │   ├── ds/            # 基础数据结构（栈、树、图）
│   │   └── base/          # 排序、搜索、二分模板
│   ├── luogu/             # 洛谷题解（建议按题号命名：P1226_qpow.cpp）
│   └── codeforces/        # CF 竞赛代码
├── rust_crypto/           # Rust 密码学实验室（长期科研目标）
│   ├── Cargo.toml         # 采用 Workspace 模式管理多个子项目
│   ├── crates/
│   │   ├── num_theory/    # 自主实现的数论库（支持大数运算）
│   │   └── zkp_proto/     # 尝试复现的小型零知识证明协议
│   └── notebooks/         # 存放基于 Rust 的交互式实验代码
└── docs/                  # 知识大脑（西蒙学习法的核心）
    ├── proofs/            # 核心数学定理的推导过程（Markdown + LaTeX）
    ├── icpc_strategy/     # 队内分工、数论板块常见坑点总结
    └── exam_2028/         # 考研密码学专项知识点归纳
```

## 📝 Commit Message 规范

为了保持提交历史的清晰，请遵循以下提交信息约定：

- **`feat:`** 代表新增了算法模板或功能
  ```
  feat: 添加快速幂算法模板
  feat(math): 实现扩展欧几里得算法
  ```

- **`fix:`** 代表修复了某个算法模板的 Bug（比如边界溢出）
  ```
  fix: 修复快速幂模板的整数溢出问题
  fix(ds): 修正线段树区间查询边界错误
  ```

- **`docs:`** 代表更新了推导笔记
  ```
  docs: 添加费马小定理证明过程
  docs(proofs): 完善中国剩余定理推导
  ```

- **`refactor:`** 代表优化了代码逻辑（例如把 $O(n)$ 优化到了 $O(\log n)$）
  ```
  refactor: 将素数判定优化为 Miller-Rabin 算法
  refactor(math): GCD 算法从递归改为迭代实现
  ```

## 🎯 使用指南

### C++ 算法模板

1. 所有模板代码位于 `cpp_arena/templates/` 目录
2. 代码已经过严格测试和优化
3. 建议复制模板时保留注释和时间复杂度标注

### Rust 密码学实验

1. 进入 `rust_crypto` 目录
2. 使用 `cargo build` 构建项目
3. 使用 `cargo test` 运行测试

### 学习笔记

查看 `docs/` 目录下的 Markdown 文件，包含：
- 数学定理的详细推导
- 算法设计的思路总结
- 竞赛经验与技巧

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/Tenerife-Q/Algo-Cipher-Lab.git
cd Algo-Cipher-Lab

# 构建 Rust 项目
cd rust_crypto
cargo build

# 运行 Rust 测试
cargo test
```

## 📚 学习路径建议

1. **基础阶段**：从 `cpp_arena/templates/base/` 开始，掌握基础算法
2. **进阶阶段**：深入 `cpp_arena/templates/math/` 和 `ds/`，攻克数论与数据结构
3. **实战阶段**：在 `luogu/` 和 `codeforces/` 目录下刷题实践
4. **研究阶段**：探索 `rust_crypto/` 中的密码学实现

## 🤝 贡献指南

欢迎提交 Pull Request！请确保：
- 遵循项目的 Commit Message 规范
- 代码经过充分测试
- 添加必要的注释和文档
- 保持代码风格一致

## 📄 许可证

本项目采用 MIT 许可证，详见 LICENSE 文件。

## 📧 联系方式

如有问题或建议，欢迎通过 Issue 反馈。

---

**Keep Learning, Keep Growing! 🌱**
