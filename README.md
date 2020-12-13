# DevNet Documentation
This dependency is the Documentation repository of **DevNet Framework**

> **Note :** This is an early release, not recommended for production use.

Devnet framework is free open-source, PHP software and cross-platform, with high-performance, for building console and modern web application, with rapid application development tools.

## Requirements
Befor installing DevNet Framework, make sure you have [Composer](https://getcomposer.org/) and [PHP 7.4](https://www.php.net/) or higher version installed in your computer.

## Installation
1. Download or clone **DevNet Installer** repository
2. Rename the folder of the project installer any name you want
3. Navigate to the root folder of your project and run the following scripts :

```bash
$ composer install
```

### Create a new application
To create a **Console Application**, run the following script :

```bash
$ ./devnet new console
```

To create a **Web Application**, run the following script :

```bash
$ ./devnet new web
```

> **Note :** Do not forget to give execute permission to the command ./devnet in linux "chmod +x ./devnet"

### Run your application
To run your application, run the following script :

```bash
$ ./devnet run
```

If your project is a *Web Application*, the built-in server will start listening on: http://localhost:8000  
Alternately you can run the following script :

```bash
$ php -S localhost:8000 -t webroot
```

> **Note :** For full documentation on how to use **DevNet Framework** see [Documentation](https://github.com/DevNet-Framework/Docs)

That's it! Enjoy coding and build cool things :)
