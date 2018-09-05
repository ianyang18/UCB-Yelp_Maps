# UCB-Yelp_Maps

A visualization of restaurant ratings using machine learning and the Yelp academic dataset. 
In this visualization, Berkeley is segmented into regions, 
where each region is shaded by the predicted rating of the closest restaurant (yellow is 5 stars, blue is 1 star). 
And each dot represents a restaurant. The color of the dot is determined by the restaurant's location. 

>>> python3 recommend.py -u Thaside -k 2 -p -q Sandwiches

Arguments:
-u: User data.
-k: Number of clustters for k-means.
-q: Queries, to filter based on a category
-p: To predict what rating a user would give a restaurant.
-r: To get a list of Berkeley restaurants.

If you hover over each dot (a restaurant) in the visualization, you'll see a rating in parentheses next to the restaurant name.
