
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


## Cloud9 IDE-ის გამოყენებით განხორციელებული საცდელი პროექტი:

ტუტორიალის მიხედვით:
http://railstutorial.ru/chapters/4_0/beginning

To get started, just do the following:

1. Run the project with the "Run Project" button in the menu bar on top of the IDE.
2. Preview your new app by clicking on the URL that appears in the Run panel below (https://first-rubyonrails-ariani1967.c9users.io/).


## To run a Rails application:

https://community.c9.io/t/running-a-rails-app/1615

Open the terminal and type -- gem install rails

When done, type -- rails new example -d mysql

Edit your database configuration in -- config/database.ym

Type--- rails s -b $IP -p $PORT

## GIT

მაგ:

git commit -a -m "readme ფაილის შევსება"

git push

### 1.4 Развертывание


$ rake assets:precompile

$ git add .

$ git commit -m "Add precompiled assets for Heroku"

$ git push heroku master


იძლევა შეცდომას- აჩმახებს ბაზაზე 'sqlite3, ამიტომ Gemfile-შიდავაკომენტარე:

               # gem 'sqlite3'
              
გაეშვა ამ მისამართზე:   https://sleepy-fjord-37819.herokuapp.com/ 

შევუცვალე სახელი:

heroku rename rails-from-c9 

ახლა უკვე ეშვება მისამართზე : https://rails-from-c9.herokuapp.com/
               











## Support & Documentation

Visit http://docs.c9.io for support, or to learn more about using Cloud9 IDE. 
To watch some training videos, visit http://www.youtube.com/user/c9ide
