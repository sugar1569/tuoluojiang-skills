# 陀螺匠 Skills 技能包集合

🎯 **让 AI 助手更懂陀螺匠！**

## 📖 简介

这是一个专为[陀螺匠](https://tuoluojiang.com)项目开发的 AI 技能包集合，为 AI 助手提供陀螺匠的**后端 API** 和**前端管理后台**的完整开发知识。

## 🎯 包含的技能包

### 1️⃣ tuoluojiang_api - 后端 API 技能包

**Laravel 9 后端 API 开发技能**，包含：

- 📚 **10个详细参考文档**：项目概述、开发规范、数据库、API、路由、事件、定时任务等
- 💻 **6个代码模板**：控制器、模型、Dao、Service、Request 等
- 🚀 **代码生成器**：`create_api.php` 一键生成完整 API 代码
- ✅ **规范检查工具**：`check_api.php` 检查代码是否符合规范

📖 [查看详情](tuoluojiang_api/README.md)

### 2️⃣ tuoluojiang_admin - 前端管理后台技能包

**Vue 2 + Element UI 前端开发技能**，包含：

- 📚 **8个详细参考文档**：项目概述、开发规范、组件说明、API 接口等
- 💻 **4个代码模板**：页面、组件、API、Store 模板
- 🚀 **代码生成器**：快速创建页面和组件
- ✅ **规范检查工具**：检查前端代码规范

📖 [查看详情](tuoluojiang_admin/README.md)

## 🔧 安装

### 使用 Git Clone（推荐）

```bash
# 克隆仓库
git clone https://github.com/sugar1569/tuoluojiang-skills.git

# 进入目录
cd tuoluojiang-skills

# 将技能包复制到项目
cp -r tuoluojiang_api /path/to/your/project/.trae/skills/
cp -r tuoluojiang_admin /path/to/your/project/.trae/skills/
```

### 或使用 skills CLI

```bash
# 安装后端 API 技能
npx skills add sugar1569/tuoluojiang-skills/tuoluojiang_api

# 安装前端管理后台技能
npx skills add sugar1569/tuoluojiang-skills/tuoluojiang_admin
```

## 🎯 使用场景

### 后端开发 (tuoluojiang_api)

- 🤔 需要了解 Laravel 后端架构？
- 📝 快速创建新的 API 接口？
- ✅ 检查代码是否符合规范？
- 📚 查阅开发文档和代码模板？

### 前端开发 (tuoluojiang_admin)

- 🤔 需要了解 Vue 前端架构？
- 🎨 创建新的管理页面？
- ✅ 检查前端代码规范？
- 📚 查阅组件使用文档？

**只需向 AI 助手询问相关问题，技能包会自动提供专业的陀螺匠开发知识！**

## 🛠️ 快速开始

### 后端 API 开发

```bash
cd /path/to/project

# 生成新的 API 接口
php .trae/skills/tuoluojiang_api/scripts/create_api.php User user ent/user

# 检查代码规范
php .trae/skills/tuoluojiang_api/scripts/check_api.php User
```

### 前端页面开发

```bash
cd /path/to/project

# 创建新页面
node .trae/skills/tuoluojiang_admin/scripts/create-page.js UserList

# 创建组件
node .trae/skills/tuoluojiang_admin/scripts/create-component.js UserCard

# 代码规范检查
node .trae/skills/tuoluojiang_admin/scripts/lint-check.js
```

## 📚 技术栈

### 后端 (tuoluojiang_api)

- **框架**: Laravel 9.x
- **PHP**: 8.0+
- **数据库**: MySQL 5.7+ / 8.0+
- **缓存**: Redis
- **认证**: JWT
- **授权**: Casbin RBAC

### 前端 (tuoluojiang_admin)

- **框架**: Vue 2.6.10
- **UI**: Element UI 2.15.14
- **状态管理**: Vuex 3.1.0
- **路由**: Vue Router 3.0.2
- **构建**: Webpack 4.44.2

## 📖 文档导航

### 后端 API 文档

| 文档 | 说明 |
|------|------|
| [tuoluojiang_api/SKILL.md](tuoluojiang_api/SKILL.md) | 技能说明 |
| [tuoluojiang_api/references/01-项目概述.md](tuoluojiang_api/references/01-项目概述.md) | 项目简介 |
| [tuoluojiang_api/references/02-开发规范.md](tuoluojiang_api/references/02-开发规范.md) | 开发规范 |
| [tuoluojiang_api/references/03-数据库说明.md](tuoluojiang_api/references/03-数据库说明.md) | 数据库说明 |
| [tuoluojiang_api/references/04-API接口说明.md](tuoluojiang_api/references/04-API接口说明.md) | API 文档 |
| [tuoluojiang_api/references/05-目录结构.md](tuoluojiang_api/references/05-目录结构.md) | 目录结构 |
| [tuoluojiang_api/references/06-常用命令.md](tuoluojiang_api/references/06-常用命令.md) | 常用命令 |
| [tuoluojiang_api/references/07-路由说明.md](tuoluojiang_api/references/07-路由说明.md) | 路由配置 |
| [tuoluojiang_api/references/08-事件系统.md](tuoluojiang_api/references/08-事件系统.md) | 事件系统 |
| [tuoluojiang_api/references/09-定时任务.md](tuoluojiang_api/references/09-定时任务.md) | 定时任务 |
| [tuoluojiang_api/references/10-中间件说明.md](tuoluojiang_api/references/10-中间件说明.md) | 中间件 |

### 前端 Admin 文档

| 文档 | 说明 |
|------|------|
| [tuoluojiang_admin/SKILL.md](tuoluojiang_admin/SKILL.md) | 技能说明 |
| [tuoluojiang_admin/references/01-项目概述.md](tuoluojiang_admin/references/01-项目概述.md) | 项目简介 |
| [tuoluojiang_admin/references/02-开发规范.md](tuoluojiang_admin/references/02-开发规范.md) | 开发规范 |
| [tuoluojiang_admin/references/03-目录结构.md](tuoluojiang_admin/references/03-目录结构.md) | 目录结构 |
| [tuoluojiang_admin/references/04-组件说明.md](tuoluojiang_admin/references/04-组件说明.md) | 组件说明 |
| [tuoluojiang_admin/references/05-API接口说明.md](tuoluojiang_admin/references/05-API接口说明.md) | API 接口 |
| [tuoluojiang_admin/references/06-常用功能.md](tuoluojiang_admin/references/06-常用功能.md) | 常用功能 |
| [tuoluojiang_admin/references/07-构建部署.md](tuoluojiang_admin/references/07-构建部署.md) | 构建部署 |
| [tuoluojiang_admin/references/08-常见问题.md](tuoluojiang_admin/references/08-常见问题.md) | 常见问题 |

## 🚀 未来计划

- [ ] tuoluojiang_uniapp - 移动端（UniApp）技能包
- [ ] tuoluojiang_wechat - 微信小程序技能包
- [ ] tuoluojiang_cli - 命令行工具技能包

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

专有许可证

## 🙏 致谢

[陀螺匠](https://tuoluojiang.com) - AI+低代码双引擎智能办公系统

---

**用心做开源，我们也很需要你的鼓励！右上角 Star🌟，等你点亮！**
