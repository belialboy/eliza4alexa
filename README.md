# eliza4alexa
A port of the Eliza code into Amazon Alexa

This takes code written by Evan Dempsey (https://www.smallsurething.com/implementing-the-famous-eliza-chatbot-in-python/) and massages it into the Alexa framwork so that you can litterally talk to Eliza.

All the code and configuration is found in this repo. AWS won't certify because they believe that there is an outstanding copyright on Eliza (http://psych.fullerton.edu/mbirnbaum/psych101/Eliza.htm) and also it permits too free-er text to be entered... which is kind of the point, right?

NB You'll need to change the "amzn1.ask.skill.93c5811d-1785-47c1-b499-bee2367ad071" in my lamda_handler to match the one assigned to your skill, otherwise it'll just reject the API call.
