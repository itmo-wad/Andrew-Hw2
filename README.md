# Andrew-Hw2

this code creates a login system and uses Mongo db as the backend
when logged in, sessioms are active.new users can be created. 
database used/set is logged in the login_exmple.py file.
the files in templates makes the login form and rgisteration form looks better.
after login, a message is displayed. incating the user is logged in as(username)/profile
if the login is wrong, it simply doest login(returns the idex.html form).

it renders authentication form at http://localhost:5000/

after registration, data is stored in database, and if user tries to register with same information, an error occures saying user already exist.
if a none registered user tries to login, in simply returns an erro message(invalid user/password combination

 
