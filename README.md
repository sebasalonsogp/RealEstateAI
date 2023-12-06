# RealEstateAI

#Prolog program to return best properties from knowledge base according to user preferences and corresponding weights.


How to run queries for the 4 “find” predicates.

p=preference ( preference(*insert_corresponding_value*) ), w=weight (pref_name-val)

find_property([p1, … ,pi],[w1, … , wk], Property, Attribute, Score).

find_properties([p1, … ,pi],[w1, … , wk], SortedProperties).

find_properties_heap([p1, … ,pi],[w1, … , wk], Heap).

find_best_property([p1, … ,pi],[w1, … , wk], BestProperty, BestPropertyAttributes, BestScore).

Example:
find_best_property([city('Key Biscayne'), price(400000)], [city-1.5, price-2], BestProperty, BestPropertyAttributes, BestScore).


