# Wordpress Setup Script

> This is a complete startup script That will handle your wordpress install for you. It requires wp-cli
which you can download at the following link [wp-cli](http://wp-cli.org/) and chrome browser, follow the instructions.
Also make sure your `/var/www` folder has the correct ownership and permissions.
![wordpress](https://s.w.org/images/backgrounds/wordpress-bg-medblue.png)
![bash](http://www.unixstickers.com/image/data/stickers/binbash/Bash-new.sh.png)

- Clone this repo or download it to folder of your choice.
- Run the following commands: 
  - `sudo chmod +x wp_install`
  - `sudo cp wp_install /usr/bin/` This will allow you to run the command normally from anywhere.
  - When running the command provide a site name as command line argument `wp_install yoursite`
  - Enter your db details when prompted. 
  - Sit back and relax.
