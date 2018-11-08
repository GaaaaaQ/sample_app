
1. install RubyGems
```
$ bundle install --without production
```
2. migrate up the database
```
$ rails db:migrate
```
3. check out system work
```
$ rails test
```
4. introduce server
```
$ rails server
```
5. generate ssh-key
```
$ cd ~/.ssh
$ ssh-keygen
$ cat ~/.ssh/id_rsa.pub
```
6. register ssh-key to your Github account
```
Login Github Web
=> push an icon on the right of the navbar
=> push "Settings" on the pulldown list
=> push "SSH and GPG keys" on the table on the leftside
=> copy & paste the key into the textbox
```
7. register ssh-key to your Heroku account
```
Login Heroku Web
=> push an icon on the right of the navbar
=> push "Account Settings" on the pulldown list
=> push "Add" btn on the container of "SSH Keys"
=> copy & paste the key into the textbox
```
8. push to heroku

# create a new app on heroku
```
$ heroku create
```
# push to heroku
```
$ git push heroku master
```
# if you can't use heroku command
```
https://qiita.com/bdogrep/items/8620dbba5e4c3fd859df
```