In Computer science, padding is usually a term that describes the act of taking a value, and adding pad characters to the left or right (or both) sides of a string in order to fix the length of the string; either for output formatting, processing or encryption (some encryption processes are stable and more secure wen the strings are a fixed length).

In Python, padding is accomplished by :

ljust, rjsust and center methods on the string - for instance :
>>> 'Hello'.center(11) 
'   Hello   ' 
>>> 'Hello'.center(11,'_') 
'___Hello___' 
Using formatting in the output formatting :
>>> greeting = 'Hello' 
>>> f'{greeting:*>10}' # Same as rjust(10,'*') 
'*****Hello
