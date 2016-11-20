# Q0: Why is this error being thrown?

The pokemon model is not yet created/migrated. 

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

In the index.html.erb, the pokemon name is being printed out. The pokemon names are selected from the data in seeds.rb. 

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

This is a button that connects to the capture method in pokemon_controller. In regards to capture_path, capture is the name of the method and _path is a helper that provides a relative path to the method. 

# Question 3: What would you name your own Pokemon?

Jared. In reference to Silicon Valley. 

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

I redirected to current_trainer. No path is needed because of Devise. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

Putting the line shows an error in the form by because in views/layouts/application.html.erb it checks what type of error it is and displays the correct error. At the end of the file it renders the message. 

# Give us feedback on the project and decal below!

It was a great first decal. Although it was a little fast for me, I was able to manage to complete a sufficient amount of tasks. The project was a good choice for begginners. 

Github URL: https://github.com/HengLoose12/proj1

# Extra credit: Link your Heroku deployed app
