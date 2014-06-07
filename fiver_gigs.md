# fiver gigs

———

By now , I think you finished the 2 gigs (Forecastunit menu to URL ) , I will clean code , but now this time no coding needed for the gig.

Ok, Obviously the idea of the app is showing a surf timeline in all the fragments , not just in the 1srt one.

So, right now we have 5 Fragments, 5 layouts ,5 Nav. Drawers , one for each option/beach.
The “working” code is now all in Beach1Fragment.java , I know its not the best way to paste all the code or repeat it , so , How can we “extract” or reuse or make our own class from the working code in Beach1Fragment , so Beach2Fragment and Beach2Fragment and all the others can use it .

So gig #1 is , please just think in a solution this. How can we do it , a new class is the way to go ? what do you think ?


At the end I want all the fragments to show the timeline of the Beach they selected in the menu , but using the less code I can and optimising it .


Gig #2 , also only think this time :)

 by now you resolve one part of the API url , the Units , using the value fro the menu, but Obviously now we need the get the BeachId (spot_id=) to complete the URL .
  The user add a beach in the navigation drawer, Now we only have 5 beaches names ,and they come from an simple array . But we need to complete the BeachId for the API from the beach the user select … How can we “give” or “get” for each beach name from the array an ID .
For Example:
Hawaii  - 001
Maui    - 002
Honolulu- 003
Olahu   - 004
Waikiki - 004
Kauai   - 005

So when the user selects “Waikiki” from the spinner in the drawer, the ID is 004 ,so BeachId (spot_id=) will be 004, so the the url we need to request will be : http://magicseaweed.com/api/key/forecast/?spot_id=004&units=uk.

(*in the final version, user will have maybe 100 beach options, not just 5)


For This 2 gigs I only need from you to sit back, relax, meditate and think in this 2 solutions :)  … ( am pretty cool to work with sometimes ! )

We talk about your ideas for solutions and then I can order 2 gigs for each solution , for a total of 6 gigs for all the work involved.

—

Gig#3


——
