# rb-wrangle

## Assigned Play 
[As You Like It](http://shakespeare.mit.edu/asyoulikeit/full.html)
## Speaker 1
Orlando
## Speaker 2
Oliver
## Question
Who speaks More?
## Commands Used
- ```$ curl "http://shakespeare.mit.edu/asyoulikeit/full.html" -o input.txt``` - Used to get input text from web.
- ```$ curl "http://shakespeare.mit.edu/asyoulikeit/full.html" | sed 's/<\/*[^>]*>//g' > rb.txt``` - used to apply regular expression on my text.
- ```$ grep '^OLIVER$' rb.txt -c > oliver_count.txt``` - used to search Speaker 1 and count the number of times 
- ```$ grep '^ORLANDO$' rb.txt -c > orlando_count.txt``` - used to search speaker 2 and count the number of times

## Answer
Orlando speaks more than Oliver as the count of Orlando(120) is greater than Oliver(37)
  
