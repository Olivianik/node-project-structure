# Node Project Structure
The philosophy of this repository is to provide templates for creating projects with node. Create something amazing! without worrying about the little things.

## Branches
Each of the branches of this repository except the main branch has a project template adapted to different technologies.

# main 📂
This branch provides a template for creating projects with [Node](https://nodejs.org). You can adapt it to the technologies you want to use.

## Table of Contents
* [Folder and File Structure](#folder-and-file-structure)
* [Getting Started](#getting-started)
	* [Use this template](#use-this-template)
	* [Git](#git)
	* [Download ZIP](#download-zip)
* [Project Setup](#project-setup)
* [License](#license)

## Folder and File Structure
```
▽ 📁 node-project-structure
  ▽ 📁 src
    ▽ 📁 app
      ▽ 📁 Controllers
          📄 UserController.js
      ▽ 📁 Helpers
          📄 Jwt.js
      ▽ 📁 Middleware
          📄 VerifyToken.js
      ▽ 📁 Models
          📄 User.js
      ▽ 📁 Services
          📄 UserService.js
    ▽ 📁 config
      	📄 database.js
    ▽ 📁 public
        📄 robots.txt
    ▽ 📁 routes
        📄 api.js
    ▽ 📁 views
        📄 index.ejs
      📄 app.js
  ▽ 📁 tests
      📄 user.test.js
    📄 .env
    📄 .env.example
    📄 .gitignore
    📄 index.js
    📄 LICENSE
    📄 README.md
```
> The files found in each folder were created so that the folders were uploaded to the repository.

## Getting Started
Use the option that suits you.

### Use this template
This repository is a template so you can use it by clicking on `Use this template` and following the steps.

### Git
Locate with the console in the directory where you want to clone the repository and execute the following:

Clone the `main` branch of the `Node Project Structure` repository:
```console
git clone --branch main https://github.com/santiagor0jas/node-project-structure.git
```

### Download Zip
Download the repository of this branch.

Visiting the following link:
```
https://github.com/santiagor0jas/node-project-structure/archive/refs/heads/main.zip
```
Or using the `Github Download Function`.

## Project Setup

1. After cloning or downloading the repository, a folder named `node-project-structure` will be created in the selected directory, remember to rename this folder, for example `my-app`.
	> **Please note that** if your project needs to be licensed, modify the `my-app/LICENSE` file, otherwise delete it.

2. Now go to the `my-app` folder using the console and run the following to configure git to point to your repository.
	```console
	git remote set-url origin <repository-url>
	```

3. Initialize project:

	> It is recommended to set git to point to your repository before running this command.

	```console
	npm init -y
	```

## License
This project is licensed under the [MIT License](./LICENSE).
