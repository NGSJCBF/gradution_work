# 开发指南

## 概述
本指南提供项目开发的详细步骤和规范。

## 目录
- [1. 开发环境设置](#开发环境设置)
- [2. 代码规范](#代码规范)
- [3. 开发工作流](#开发工作流)
- [4. 调试技巧](#调试技巧)
- [5. 常见问题](#常见问题)

## 开发环境设置

### 系统要求

**操作系统**: 
- Linux
- macOS
- Windows

**硬件要求**: 
- CPU: 
- 内存: 
- 磁盘: 

### 依赖安装

#### 步骤 1: 克隆项目
```bash
git clone https://github.com/NGSJCBF/gradution_work.git
cd gradution_work
```

#### 步骤 2: 安装依赖
```bash
# 依赖安装命令
```

#### 步骤 3: 验证环境
```bash
# 验证环境命令
```

### IDE配置

**推荐IDE**: 

**插件推荐**: 

## 代码规范

### 命名规范

#### 变量命名
- 局部变量: snake_case
- 全局变量: UPPER_SNAKE_CASE
- 常量: UPPER_SNAKE_CASE

#### 函数命名
- 普通函数: snake_case
- 类方法: snake_case
- 私有方法: _snake_case

#### 类命名
- 类名: PascalCase
- 接口: IPascalCase

### 代码格式

#### 缩进
- 使用4个空格缩进

#### 行长
- 最大行长: 100字符

#### 注释
```python
# 单行注释使用#号

"""
多行注释或文档字符串
使用三个双引号
"""
```

### 文档注释

#### 函数文档
```python
def function_name(param1, param2):
    """
    简短描述
    
    详细描述
    
    Args:
        param1: 参数1说明
        param2: 参数2说明
    
    Returns:
        返回值说明
    
    Raises:
        异常类: 异常说明
    """
    pass
```

## 开发工作流

### 功能开发流程

#### 1. 创建feature分支
```bash
git checkout -b feature/your-feature-name
```

#### 2. 本地开发
- 编写代码
- 编写测试
- 修复问题

#### 3. 提交提交
```bash
git add .
git commit -m "描述性的提交信息"
```

#### 4. 推送到远程
```bash
git push origin feature/your-feature-name
```

#### 5. 创建Pull Request

### 提交消息规范

```
<type>(<scope>): <subject>

<body>

<footer>
```

**type**: 
- feat: 新功能
- fix: 错误修复
- docs: 文档
- style: 代码格式
- refactor: 重构
- test: 测试
- chore: 构建

**scope**: 影响的模块

**subject**: 简短描述(不超过50字符)

**body**: 详细描述

**footer**: 关闭的issue

## 调试技巧

### 调试工具

#### 日志输出
```python
import logging
logger = logging.getLogger(__name__)
logger.debug("调试信息")
logger.info("信息")
logger.warning("警告")
logger.error("错误")
```

#### 断点调试
- 设置断点
- 单步执行
- 观察变量

### 常见调试场景

#### 场景1: 协议消息错误
1. 检查消息序列化
2. 验证消息格式
3. 查看日志输出

#### 场景2: 密钥生成失败
1. 检查密钥导出参数
2. 验证哈希函数输出
3. 检查熵源

## 常见问题

### Q: 如何运行单元测试?
A: 
```bash
# 运行所有测试
# 运行特定测试
```

### Q: 如何生成代码覆盖率报告?
A: 
```bash
# 生成覆盖率报告的命令
```

### Q: 如何更新依赖?
A: 
```bash
# 更新依赖的命令
```

---
*最后更新: 2026-01-01*
