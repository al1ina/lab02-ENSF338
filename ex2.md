1. Mention at least two aspects that make interpolation search better than binary search [0.1 pts]
Interpolation search does fewer comparisons (O(log(logn))) compared to binary search’s (O(logn))
Interpolation search is more efficient than binary search
2. Interpolation search assumes that data is uniformly distributed. What happens if this data follows a different distribution? Will the performance be affected? Why? [0.2 pts]
Yes the performance will be affected going from its average to worst-case (O(n))
This happens because interpolation search assumes that the data is evenly distributed, if it isn't then the formula used in the algorithm works poorly
3. If we wanted to modify interpolation search to follow a different distribution, which part of the code would be affected? [0.1 pts]
The line of code where we calculated pos
4. When is linear search your only option for searching data as binary and interpolation search may fail? [0.2 pts]
When data is unsorted or isn't in a list-like format
5. In which case will linear search outperform both binary and interpolation search, and why? [0.2 pts]
When the data is unsorted or small
6. Is there a way to improve binary and interpolation search to solve this issue? [0.2 pts]
Yes, the data can be sorted first
