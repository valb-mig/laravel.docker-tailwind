# 📖 Example to use Laravel with Docker and Tailwind
This project objective is to show how to use Laravel with Docker and Tailwind!

## 📌 Requirements

![](https://img.shields.io/badge/Laravel-9.x-orange?style=for-the-badge&logo=laravel&logoColor=white)
![](https://img.shields.io/badge/Docker-20.10.12-blue?style=for-the-badge&logo=docker&logoColor=white)
![](https://img.shields.io/badge/Tailwind-3.0.24-green?style=for-the-badge&logo=tailwindcss&logoColor=white) 
![](https://img.shields.io/badge/PHP-8.3-yellow?style=for-the-badge&logo=php&logoColor=white)
![](https://img.shields.io/badge/Node.js-16.x-blue?style=for-the-badge&logo=node.js&logoColor=white)

## 📌 Installation

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/)
- [PHP](https://www.php.net/)
- [Composer](https://getcomposer.org/)

## 📌 Laravel

> [!WARNING]
> _**Change {project} to to your project name on most of the files**_

```composer create-project --prefer-dist laravel/laravel project```

### 🔧 Ambient configuration

- **Copy the .env.example file to _.env_**<br>
```cp .env.example .env. ```

> [!TIP]
> _user the **./.env.edit** file to see the default values._

### 🔧 Docker configuration

#### 🔩 Ngnix & Mysql

> [!TIP]
> _You can copy the **./docker-compose** file to see set the default values._

#### 🔩 Docker compose

> [!TIP]
> _You can copy the **./docker-compose.yml** file to see set the default values._

## 📌 Tailwind

```npm install -D tailwindcss postcss autoprefixer```

```npx tailwindcss init -p```

### 🔧 Vite configuration
> [!TIP]
> _You can copy the **./vite.config.js** file to see set the default values._


## 🚀 Start the project

- **Inside the project folder run the command:**<br>
```docker-compose up -d --build```

- **Enter the docker bash to run tailwind:**<br>
```docker-compose exec app bash```

- **Run the command:**<br>
```npm run dev```