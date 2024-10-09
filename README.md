# 苍穹外卖后端仓库 (Sky Take-Out Backend Repository)

## Table of Contents
- [描述 (Description)](#描述-description)
- [安装 (Installation)](#安装-installation)
- [使用 (Usage)](#使用-usage)
- [贡献 (Contributing)](#贡献-contributing)
- [许可 (License)](#许可-license)
- [联系 (Contact)](#联系-contact)

## 描述 (Description)
苍穹外卖后端仓库，使用Java构建，提供外卖服务的后端支持。  
The Sky Take-Out backend repository, built with Java, provides backend support for take-out services.

## 安装 (Installation)

### 前提条件 (Prerequisites)
- Java JDK (version x.x.x)
- Maven (version x.x.x)

### 步骤 (Steps)
```sh
# 克隆仓库 (Clone the repository)
git clone https://github.com/zqlit/sky-take-out.git

# 进入项目目录 (Navigate to the project directory)
cd sky-take-out

# 编译项目 (Build the project)
mvn clean install
```

## 使用 (Usage)

### 启动服务 (Start the Service)
```sh
# 使用Maven命令启动服务 (Start the service using Maven command)
mvn spring-boot:run
```

### 分页查询示例 (Pagination Example)
```java
PageHelper.startPage(当前第几页，每多少条数据分一页);
```

## 贡献 (Contributing)
欢迎贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何为该项目做出贡献。  
Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this project.

## 许可 (License)
此项目使用 MIT 许可证 - 请参阅 [LICENSE](LICENSE) 文件了解详细信息。  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 联系 (Contact)
如有任何问题或建议，请在 [GitHub](https://github.com/zqlit/sky-take-out/issues) 上提交问题。  
For any questions or issues, please open an issue on [GitHub](https://github.com/zqlit/sky-take-out/issues).
