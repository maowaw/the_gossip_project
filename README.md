			Welcome to the The Gossip Project application
Please download the whole folder. After entering into the downloaded folder, please type in your terminal :

		$ bundle install
Then you need to make the migrations go from down to up, to make the app active, so type in the terminal :

		$ rails db:migrate
This app is a gossip platform between THP's students. As a new user of the platform, you will need to fill in the following information : first name, last name, email and city. You can add a gossip, comment gossips of others or comments of gossips, and also like a gossip or a comment. A gossip can be linked to one or several tags, and vice-versa.

The app contains fake data, to test its functionnality. To play with it, you can type in your terminal :

		$ rails db:seed
		$ rails console

And then feel free to check all the data in there. A gem called tape_print has been added into the app, so if you type in the rails console "tp" before the data you want to show, it will be nicely organized. For example "tp Dog.all"

Enjoy !
