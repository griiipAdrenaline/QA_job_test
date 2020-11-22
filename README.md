# QA job test

## Test requirements
This test have 3 parts to it, for each part you need to implement the solution 
in the relevant file.

**The solution should be implemented inside the attached relevant file, don't add
arguments to the functions already defined**

**The solution should be implemented _without_ imports - 
just pure python (specifically Python 3.7)**

1. **Advanced sort list**:

    Create a function that takes a list of numbers or strings and returns a list with the items from the original list
    stored into sublists. Items of the same value should be in the same sublist.
    
    Examples
    
    advanced_sort([2, 1, 2, 1]) :arrow_right: [[2, 2], [1, 1]]    
    advanced_sort([5, 4, 5, 5, 4, 3]) :arrow_right: [[5, 5, 5], [4, 4], [3]]    
    advanced_sort(["b", "a", "b", "a", "c"]) :arrow_right: [["b", "b"], ["a", "a"], ["c"]]    
    advanced_sort(["6", "1", "l", "g", "d", "1", "s", "d"]) :arrow_right: [["6"], ["1", "1"], ["l"], ["g"], ["d", "d"], ["s"]]
    
    **Notes:** The sublists should be returned in the order of each element's first appearance in the given list.
 
2. **Employee class**

    Create a class Employee that will take a full name as argument, as well as a set of none, one or more keywords.
    Each instance should have a name and a lastname attributes plus one more attribute for each of the keywords, if any.
    
    Examples
    
    john = Employee("John Doe")    
    mary = Employee("Mary Major", salary=120000)    
    richard = Employee("Richard Roe", salary=110000, height=178)    
    giancarlo = Employee("Giancarlo Rossi", salary=115000, height=182, nationality="Italian")
    
    john.name :arrow_right: "John"    
    mary.lastname :arrow_right: "Major"    
    richard.height :arrow_right: 178    
    giancarlo.nationality :arrow_right: "Italian"
    
    **Notes:** First and last names will be separated by a whitespace. The test will not include any middle names or initials.
    The value of the keywords can be an int, a str or a list.
    
3. **Numbers to english**

    Write a function that accepts a positive integer between 0 and 999 inclusive and returns a string representation
    of that integer written in English.
    
    Examples
    
    num_to_eng(0) :arrow_right: "zero"    
    num_to_eng(18) :arrow_right: "eighteen"    
    num_to_eng(126) :arrow_right: "one hundred twenty six"    
    num_to_eng(909) :arrow_right: "nine hundred nine"
    
    **Notes:** There are no hyphens used (e.g. "thirty five" not "thirty-five").
    The word "and" is not used (e.g. "one hundred one" not "one hundred and one").
    
## Solution submission
To submit the solution put the entire folder in a ZIP file and send to `alonk@griiip.com`