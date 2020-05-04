# Similar Patterns function 
## Done in collaboration with [Anaïs Ahmed](https://github.com/ananari)
You can find her code at [this repo] (https://github.com/ananari/ravelry-rec-backend)

## You can use this program [here](https://pure-peak-95236.herokuapp.com/)

This function is an offshoot of the Ravelry project currently being worked on.

Using the read only ravelry permissions, this function takes an input of a pattern url, and the output is a search url for patterns with similar attributes. 

`similar_patterns.py` this is the main function

`read_only.py` this contains the read_only permissions

`yarn_id_dict.p` pickle file that contains the dictionary that has all yarn weights and ID numbers I've assigned to them based on ascending order (i.e. the smallest weight is 0 and the largest weight is 12)
