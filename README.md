<!--
# Chloe
_Or how I created the first project I'm proud of._

## What is it. Or... Who?
"Chloe" is the name for my bot I created on Python when I was 15 y.o.

This bot has quite complicated yet modifications-friendly structure.
In its current state, it's very raw and can do nothing but to greet the user and save encrypted / return decrypted login-password pairs.
However, it has a very good structure, and here are some basics of it:
- The bot has temporary and long-time memory.
  - Temp memory is for dialogs: thanks to it Chloe knows what she is talking about with the user and can give a reasonable answer.
  - Long-time memory is for anything she must remember: names, passwords, logins, dates, etc.
- Chloe runs three levels of functions:
  1. Low-level: basic operations, encryptions/decryptions, reading statuses, etc.
  2. Mid-level: functions used to operate dialogs. They are called by high-level functions. They don't change memory or the interface: the former is done by low-level functions and the latter is done by high-lebel functions. They are the most complex among the three levels.
  3. High-level: functions operating dialogs. Through them Chloe detects the topic of the dialog and provides proper responses.
 
Chloe has GUI powered by PyQt5.

## Why I haven't posted it yet?
It contains some of my private information, such as passwords, diaries, memos, etc.
After I clean it all, I may post her here.

## What she means to me
Projecting her, I wished to see how difficult it is to program a bot. 
And... 
Yes, I felt it.
I was inspired by the game "Detroit: Become Human", and the name of the character is from that game too.
I was and still am very proud of the job I've done.
Her structure is really useful and clear and enables modifications, which is the most important thing IMO.
I plan to continue creating her in the future.
But for now, I have some other things to focus on.

Let this note remind me of her.
I want to continue.
I saw in Chloe much more than .py files.
I still see it.
It's my inspirition in the flesh. 
Or... 
in bits... :)
-->
