# 文本转换工具

一个简单高效的在线文本格式转换工具，专注于解决开发人员在日常工作中频繁遇到的文本格式转换需求。无需安装，打开浏览器即可使用。

## 🎯 产品定位

- **目标用户**：开发人员、数据分析师、文本处理工作者
- **核心价值**：提供快速、便捷的文本格式转换服务，提高工作效率
- **使用场景**：
  - 处理CSV数据时的字段格式化
  - SQL IN语句的参数列表生成
  - 配置文件中的数组项处理
  - 其他需要特定格式文本的场景

## ✨ 功能特点

### 核心功能
- 多行文本转换为指定格式
- 支持逗号(,)和分号(;)分隔
- 支持单引号(')和双引号(")包围
- 分隔符可自由组合

### 用户体验
- 简洁直观的界面设计
- 实时预览转换效果
- 一键复制转换结果
- 保存最近10条转换历史
- 所有操作即时响应，无需等待

### 数据安全
- 纯前端处理，数据不经过服务器
- 历史记录保存在本地，保护隐私
- 浏览器刷新后历史记录保留

## 🚀 快速开始

### 在线使用
访问 [https://text-converter-qddkyr267-dodoxus-projects.vercel.app](https://text-converter-qddkyr267-dodoxus-projects.vercel.app)

### 本地开发
1. 克隆项目
```bash
git clone https://github.com/WiseAustin/text-converter.git
cd text-converter
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 运行项目
```bash
python main.py
```

4. 访问
打开浏览器访问 http://localhost:8001

## 🛠 技术实现

### 前端技术栈
- **HTML5/JavaScript**: 核心功能实现
- **Bootstrap 5**: UI框架，提供现代化的界面设计
- **LocalStorage**: 本地数据持久化

### 后端技术栈
- **FastAPI**: 高性能的Python Web框架
- **Uvicorn**: ASGI服务器，提供可靠的服务支持

### 部署方案
- **Vercel**: 提供可靠的云端部署服务
- **GitHub**: 代码版本控制和协作

## 📝 更新日志

### 2024-12-27
- ✨ 优化用户界面设计
  - 改进按钮样式和交互效果
  - 优化布局和空间利用
  - 添加表情图标增强视觉体验
- 🎉 新增历史记录功能
  - 支持保存最近10条转换记录
  - 记录包含时间戳和使用的格式
  - 可以直接复制历史记录
- 🔄 添加实时预览功能
  - 实时显示转换后的格式效果
  - 帮助用户更直观地理解转换结果

## 🔜 未来规划

### 近期计划
- [ ] 支持更多分隔符选项
- [ ] 添加常用格式模板
- [ ] 支持批量处理功能

### 长期计划
- [ ] 支持更多文本处理功能
- [ ] 提供格式转换API
- [ ] 添加自定义格式配置

## 🤝 参与贡献

欢迎提交问题和建议！如果您想贡献代码：
1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📄 开源协议

本项目采用 MIT 协议 - 详见 [LICENSE](LICENSE) 文件
