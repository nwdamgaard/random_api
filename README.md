This is a very small, simple-to-use API for selecting random items from a list with probabilities.

# How to use
First, create a Random object using Random:new(), then add all your items using Random:add_choice(choice, probability), and finally, call Random:calc_csum().

When you want to get an item from the list, simply call Random:choose(). 
