# Assignment 3.1 on Routing

## My notes -
This is class assignment - the original instructions are below. Then I marked these up with my notes, observations, etc. Mainly notes are for myself!

1. Fork the project from this location: [Fork source] (https://github.com/vasaristudio/cf_week_three)
2. In your newly forked copy, get the clone URL and paste it into your terminal like so:
        git clone (clone url from github)
So first create a week3 project level directory, cd to it, then do the clone work as described above, it creates a directory called cf_week_three for you, and note, it is already set up with github, and shows one logged commit already.

3. Generate and seed the database, and start Rails:


        rake db:migrate
        rake db:seed
        rails s

4. Add a resources line for contacts in the config/routes.rb file. This should allow you to see your contacts at: http://localhost:3000/contacts/

5. Generate a controller name of Pages and an action name of home. Edit the routes file to make the new controller action show up as the root page. This page should be viewable here: http://localhost:3000/

6. Add any new files you created to git:
git add .

7. Commit your work:
    git commit -a -m "(give a description of what you just did)"

8. Push your committed changes to Github:
    git push origin master

(note: git knows where the origin because you started this whole mess with a clone command. If you want to know what the origin is
        git remote -v

9. Attach the browser URL (not clone URL) for your forked project to your assignment to this assignment.

10. You're done. Post a comment with your submission with a well formed question.

Hints
Create new controller and actions: rails g controller YourControllerName action1 action2 etc
See config/routes.rb for numerous examples of how to do routes
[The Ruby on Rails site provides a Routing Guide:]( http://guides.rubyonrails.org/routing.html.)
***
##Instructions as given:
https://github.com/vasaristudio/cf_week_three
1. Fork the project.
2. In your newly forked copy, get the clone URL and paste it into your terminal like so:
git clone (clone url from github)
3. Generate and seed the database, and start Rails:
rake db:migrate
rake db:seed
rails s
4. Add a resources line for contacts in the config/routes.rb file. This should allow you to see your contacts at: http://localhost:3000/contacts/
5. Generate a controller name of Pages and an action name of home. Edit the routes file to make the new controller action show up as the root page. This page should be viewable here: http://localhost:3000/
6. Add any new files you created to git:
git add .
7. Commit your work:
git commit -a -m "(give a description of what you just did)"
8. Push your committed changes to Github
git push origin master
9. Attach the browser URL (not clone URL) for your forked project to your assignment to this assignment.
10. You're done. Post a comment with your submission with a well formed question.
Hints
Create new controller and actions: rails g controller YourControllerName action1 action2 etc
See config/routes.rb for numerous examples of how to do routes
The Ruby on Rails site provides a Routing Guide: http://guides.rubyonrails.org/routing.html.


