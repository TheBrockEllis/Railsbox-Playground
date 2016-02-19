# To Install
- [] Install Virtual Box and Vagrant
- [] Download this repo to a directory
- [] `vagrant up` to provision and/or start the server
- [] `vagrant ssh` to log into the virtual server
- [] `cd /vagrant` to get to the shared folder 
- [] run `sudo mysql_install_db`
- [] `sudo mysql_secure_installation` with default root password of "root"
- [] Create new rails app with MySQL driver: `rails new appname -d mysql .`
- [] Edit `config/database.yml` to update MySQL root password
- [] Add `#\ -b 0.0.0.0` as the first line in config.ru in project root
- [] Update projects `.gitignore` file to [this](https://github.com/github/gitignore/blob/master/Rails.gitignore)
- [] `rake db:create` to create databases
- [] `rails s` to start rails server

# To Run
- `cd path_to_my_local_code`
- `vagrant up`
- `vagrant ssh`
- `cd /vagrant`
- Profit
