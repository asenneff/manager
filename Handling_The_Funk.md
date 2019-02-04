*When Things Are Going Bad*	
	
No matter how talented you are, no matter how good of a leader, no matter how experienced or equipped the team is, and no matter how important the project, it will happen to you: The Funk.
	
The Funk is the period of time when everything seems to just be going slowly.  Sometimes this happens right away at the beginnng of the project, but much more often it happens nearer towards the end - during the long tail - where the project stopped being fun weeks.  Back in the hayday that project clipped through cards at a lightening pace and everything was going great. But then more devs started showing up, testers got involved, customers started looking at it, and somehow during that time it started to feel like every single card was an absolutely slugfest.  Nothing is going right anymore, but if it is,  it is going at a very measured pace and the project feels like it is never going to end. That's The Funk.
	
	
	(Funks happen.  I picked up the term back in my baseball days when an all-star hitter might go on an 3-20 stretch and the plate. Sometimes a good coach might notice something in a players swing to adjust and get them out of the funk by going back to some fundamentals.  Sometimes it might be something entirely in a players head that they have to work out themselves.  And sometime it just happens because baseball is hard).
	
	The question here is what you - a coach - can do when your software team is in a Funk.  Just like in baseball, you might be able to tweak some fundamentals.
	
	**1. Make sure scope is clear**
	There are to ways to think about this. One is on the highest scale: Is it clear to my team what the end game is with this project? Do they now when they are done?  There is no worse feeling that what has come to be called the Death March - the endless stream of little bits of work that just don't seem to ever end.  A team should have a goal, that goal should be as near term as possible, and it should be clear when that goal has been reached to everyone on the team.
	
	The other way to think about this is just on the card or story basis.  When things are going well it's pretty easy to stop being disciplined on talking through the scope.  What things are going bad, sometimes it is that exact discipline that matters.  Don't let a card through where there is even a hint of lack of clarity of the intended outcome for that card.  There's nothing that will crash your team's velocity and spirit than spinning on cards because the end result seems to keep changing. Have a tight conversation on all of them. Even better, this is a great time to practice test driven development: Write the acceptance tests first, and then just pass the tests.   As a strong corrolary, this is much easier to do with smaller cards.
	
	**2.  Break the cards down
	At Church Community Builder we have 5 sizes of stories (2, 4, 8, 16 and 32).  Our job as leaders is to make sure there is never a 32. When someone estimates a card at 32, all that means is that we really don't know how long the card might actually take. Spoiler: It's longer than 32.
	
	Universally across all software development estimates are always wrong - you know that. What is less understood is that larger cards are wronger, more often, and by a larger margin than small cards. Why? It's because we don't as humans have the same cognitive ability to understand the work represented in a 32 hour card as well as we do a 2 hour card.
	
	If I am looking at a 2 hour card,  I can have a 10 minute conversation and completely understand the requirements, goals, edge cases and all of the design nuances.  If I do a 32 hour card,  I can't completely understand any of that in 10 minutes.   So not only is the card estimated to take a long time, the uncertainty around it is an order of magnitude longer.   If a 2 hour card blows up it could take 4 hours. But if a 32 hour card blows up, that could go on for weeks.
	
	Protect your team, your estimates, and your velocity by doing the hard work of breaking things down up front.  Drive out all of the 32s.  When you're done driving out the 32s, drive out the 16s, and if you can drive out the 8s.  Live in the 2s and 4s. Break it all down until it can't be broken down any farther.
	
	Lastly on this topic: THe right way to break up a card is always in customer facing bits. (If the whole feature is to big, break it up into elements a product manager can see and a QA can test).  Occasionally that's not possible at which case then and only then is it OK to break it down by technical work (rather than a whole CRUD API, just estimate create for now and leave the rest stubbed out, for example).  Either way, get it all broken down.
	
	**3. Kill the Zombies
	Zombie cards are cards that just won't die.  First step is recognizing the fact that it is a zombie.  Zombies are clever, because they disguise themselves.  Zombies always look like they are just about done and don't need any more big attention.  But that's how Zombies happen, day after day, week after week they are almost done.  But not completely.
	
	Have a trigger.  Here's a couple of triggers to install:   As a developer, if you're stuck for more than 20 minutes without progress ask for help.  As a leader, if a card takes more than twice as long as it should have - so a 2 hour card has been sitting for half a day - it's officially a zombie card.
	
	Now that you know you have a Zombie,  the way you kill a zombie is by pairing or mobbing on it.
	
	I had a colleague named Deepak that used a different method that I ended up calling The Deepak Rule.  He would always have one senior developer that would be assigned no work during a sprint.  That person's role was nothing other than deciding which developers to help and which cards needed moving along and go there.    If a card sat for some amount of time that was too long, it automatically got the attention of the roving senior dev.
	
	However you do it, kill the zombies quickly.
	
	**4. Shorter Sprints
	We have week long sprints at Church Community Builder, which are no overly long...but sprints can always be shortened. In this case it's not a matter of doing a 2 or 3 day sprint, but just tunring evry day of the week into it's own sprint.
	
	One way to encourage that is the daily standup by just asking the question, "Which cards are going to be in QA by the end of the day?"  Set those goals and check in throughout the day on the progress.   Don't be an overlord, but keep those goals you set up at the beginning of the day in front of the team.
	
	**5. Don't overbudget
	But exceptionally certain that you aren't accidentally overbooking developers time.