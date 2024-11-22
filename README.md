# Maizey-Email-Responder
Project made at Umich ITS 2024 (Nov 14&15) Hacks with Friends - Group 5 group members - Thomas Stockwell (dearborn ITS), Joshua Froberg (finance - Procurement), Mellisa Clive (mich med - HITS), Chris Hansen (finance- Treasury), Lingxiao Zhong (School of Information - Grad student), Jason Low (mich med)

the files here are to set up and deploy your own AI email responder - for University of Michigan departments.

prequisites - create your own Maizey https://umgpt.umich.edu/maizey/shared create project token and get the relevant authorizaiton tokens

use the system prompt in this project package for the maizey system prompt
steps to deploy:

create new google sheet
open app script
copy AutoResponder.gs, auth.gs, code.gs, dialogue.html into the appscript authorize access in google drive when prompted
update auth.gs with maizey API credentials.
create 2 sheets in the google sheet - sheet 1 named: Dashboard sheet 2 named: Config
in the config file - in cell a2 define the gmail search criteria of which emails will be pulled in. i.e. label:inbox
menu items called "Maizey" will have 2 options to execute project.
Maizey My Email - this will pull in all emails specified in the config sheet
Open Email Responder - this will allow the editing and sending of AI email responses.
