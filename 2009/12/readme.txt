h2. Solium Programming Competition - December 2009 - Secret Santas

Honoring a long standing tradition everyone likes to play a Secret Santa game around Christmas time. You draw names and spend a week trying to figure out what to buy someone that is both under $20 without being completely worthless.

To choose Santas, we used to draw names out of a hat. This system was tedious, prone to many "Wait, I got myself..." problems. This year, we made a change to the rules that further complicated picking and we knew the hat draw would not stand up to the challenge. Naturally, to solve this problem, we will script the process.

This month's Solium Programming Challenge is to implement a Secret Santa selection program.

Your script will be fed a file with a list of names (you can pick how you want to process these files).  An example might be:

Luke Skywalker   <luke@theforce.net>
Leia Skywalker   <leia@therebellion.org>
Toula Portokalos <toula@manhunter.org>
Gus Portokalos   <gus@weareallfruit.net>
Bruce Wayne      <bruce@imbatman.com>
Virgil Brigman   <virgil@rigworkersunion.org>
Lindsey Brigman  <lindsey@iseealiens.net>

The format for these names is:

FIRST_NAME space FAMILY_NAME space <EMAIL_ADDRESS> newline

We'll keep things simple and say that people only have two names, so you don't have to worry about tricky names like Gray II.

Your program should then choose a Secret Santa for every name in the list. Obviously, a person cannot be their own Secret Santa. In addition, we do not allow people in the same family to be Santas for each other and your program should take this into account.

Output should be a list of email addresses and who that person's Santa is.

While programs should be able to process the sample input above, they should be scalable to a file of any size with any number of legal inputs.

Have fun\!
