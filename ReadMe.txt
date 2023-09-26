Simple mobile Quiz game, using the mit app inventor, mysql and php.
The Only thing u ll need is hosting a database (just use a free one, this is a simple project)
as the one used originally is down. Configure your php to connect the app with said database and change
a few lines of code on some blocks in app inventor s screen 2("initialise global url" etc) and screen 3(the
loading of scores). The credentials are cached with app inventor s tinydb client side, to be used for further validations, 
for example when your score is updated
It may sound a bit complicated but all it is, is, the app -which is already built the a database to 
check username, password scores etc and a couple php files hosted along the database to connect the 2.