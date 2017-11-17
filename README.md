# Dynamic-Programming
efficient algorithm that determines the optimal sequence of hotels at which to stop during a trip


if you are going in a long trip. You start on the road at mile post 0. Along the way there are 𝑛 hotels, at mile posts 𝑎1 < 𝑎2 <⋯ < 𝑎𝑛, where each 𝑎𝑖 is measured from the starting point. 

The only places you are allowed to stop are at these hotels, but you can choose which of the hotels you stop at. You must stop at the final hotel (at distance 𝑎𝑛), which is your destination.

You would ideally like to travel 200 miles a day, but this may not be possible (depending on the spacing of the hotels). If you travel 𝑥 miles during a day, the penalty for that day is (200− 𝑥)2. You want to plan your trip so as to minimize the total penalty; that is, the sum, over all travels days, of the daily penalties.
Give an efficient algorithm that determines the optimal sequence of hotels at which to stop.


Explanation:

In my programming this problem, I used a data which I entered in main method. Like that:

	int a [] = {0, 200, 250, 400, 600, 620};
	
After that, I called the method “computeTrack(a)” on the data I prepared for the hotels distances in the previous step, which do the main work in computing  and comparing the distances in order to minimize the total penalty. This method call another method which print the optimal path in terms of considering the optimal one.
Every time calling this method, we need comparing the current result to the previous which lead us to use the dynamic programming, and this is useful so much in reducing the time instead of computing the same in every step while the trip.

The java code
<a href="https://ibb.co/kmn4L6"><img src="https://preview.ibb.co/cAXFSm/code.png" alt="code" border="0"></a>

My output analysis: 
<a href="https://ibb.co/jPodf6"><img src="https://preview.ibb.co/mwOB06/My_output_analysis.png" alt="My_output_analysis" border="0"></a>

The output:
<a href="https://ibb.co/m7evSm"><img src="https://preview.ibb.co/ciOdf6/the_output.png" alt="the_output" border="0"></a>
