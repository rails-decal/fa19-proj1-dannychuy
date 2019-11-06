# Q0: Why are these two errors being thrown?
The first one, the error is thrown since the database wasn't migrated. The second one arises since we state Pokemon.where... but Pokemon isn't defined yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
The pokemon are appearring each time you land on the page, generated randomly by db:seed. They are all Gen 1 Starters.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
capture_path allows the function to take in the pokemon (referenced by the id) and pass it along to capture so it can assign a trainer to the pokemon.

# Question 3: What would you name your own Pokemon?

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
