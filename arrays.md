1.Contains Duplicate  
    the simple two loop
    sort and then adjacent element
    set (if st.sount() == n return false;


2. Valid Anagram
    Create a vector for evry alphabet count and simple

3.Two sum
    The simple two loop solution
    define remaining for every element and then mp the indexes with number return (mp{return],i}

4.Group  Anagrams
    Sorting every element(string) creates a key
    map that key to the original strings (.push_back)
    build result

5. Top K frequent elements
    Obvious step {Frequency map of each element will be prepared}
    a vector of pair<int,int> {frequecy vector of every element
    reverse sort it and iterate upto k and prepare result

6.Encode and decode strings
    Encode upto size of the string array bulid string
    string as (length of string + # + string)
    Decode (string to vector) So upto string siz4e take two pointer i and j
    initially i = 0; j = 1 movw j while j != # subtsr i to j -i to get length
    substr j + 1 and length 
    push_back to result move i to j + length + 1


7. Product of Array except self
    [With devision operator] Count zeroes
   if no zeros then nums[i] = product/nums[i]
   if 1 zero then nums[i]!=0 = 0 and the zero nums[i] is product
   if 2 zeros then every nums[i] = 0
   [Without division operator] Calculate the prefix and suffiz product of every nums[i] and push_back in ans


8. Valid Sudoku
    Just have to check three things 
    every row unique number
    evry column unique number 
    every 3*3 grid has unique number

9.Longest Consecutive Sequence
    Sort the array,handle all the three cases (=,+1,other) also edge cases when no element is present
    ****Learn that hash one*****
    
   
