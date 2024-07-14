# Trofi: Food Delivery Agent
A webapp for food ordering built with PHP and MySQL and front end implemented with pure HTML CSS.

### Built With
* ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=FFFFFF)
* ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=FFFFFF)

### Prerequisites
* PHP Development Server
* MySQL Server
* Configure the XAMPP server to run on port 8080

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/RinzlerN26/Trofi-Food-Delivery-Agent.git
   ```
2. Run MySQL command line client and execute the sql scripts.
  ```sh
  source ${fileDirname}\SQLScripts\Food.sql
  source ${fileDirname}\SQLScripts\Cart1.sql
  source ${fileDirname}\SQLScripts\Cart2.sql
  source ${fileDirname}\SQLScripts\Cart3.sql
  source ${fileDirname}\SQLScripts\Cart4.sql
   ```
3. Start PHP development server
   ```sh
   php -S localhost:8080 -t ${fileDirname}
   ```
4. Run the app in a browser by executing the command in powershell.
   ```sh
    & 'C:/Program Files/Google/Chrome/Application/chrome.exe' http://localhost:8080/loginhtmlcss.php 
    ```























