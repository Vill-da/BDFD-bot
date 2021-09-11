# How to get multiple triggers in BDFD

— 1st setting the trigger
- set the trigger to only the bot prefix. or anything you want
 
— 2st paste this code below $nomention

$if[$checkContains[$toLowercase[$message[1]];trigger1;trigger2;trigger3;trigger4;etc..;]==true]

- also put an $endif so it wont error.

EXAMPLE:
i setted my trigger to word/trigger so the usage would be:

word/triggertrigger1
word/triggertrigger2
word/triggertrigger3
