# Dynamic-Programming
efficient algorithm that determines the optimal sequence of hotels at which to stop during a trip


if you are going in a long trip. You start on the road at mile post 0. Along the way there are 𝑛 hotels, at mile posts 𝑎1 < 𝑎2 <⋯ < 𝑎𝑛, where each 𝑎𝑖 is measured from the starting point. 

The only places you are allowed to stop are at these hotels, but you can choose which of the hotels you stop at. You must stop at the final hotel (at distance 𝑎𝑛), which is your destination.

You would ideally like to travel 200 miles a day, but this may not be possible (depending on the spacing of the hotels). If you travel 𝑥 miles during a day, the penalty for that day is (200− 𝑥)2. You want to plan your trip so as to minimize the total penalty; that is, the sum, over all travels days, of the daily penalties.
Give an efficient algorithm that determines the optimal sequence of hotels at which to stop.
