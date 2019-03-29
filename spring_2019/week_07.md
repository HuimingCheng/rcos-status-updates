## Last Week's Accomplishments

Built a simple website and a test database with phantom data.

## This Week's Plan

Learn how to use Javascript to access data from firebase.

## Anything Blocking?

I'm not really familiar with Javascript syntax and sometimes I spend too much time figuring out how to implement just one function correctly.
Also, with firebase there's a code segment I need to put into the script section of our html file but for some reason this code segment
is not working as expected with other components I added to the website. It may just be the order of the script but I'm not too certain.

## Notes

Firebase creates a random hash value for a table at initiation if a specific key is not given so we need to make sure all the tables have
custom keys otherwise we wouldn't be able to use the ref() function to iterate through all the sub-dictionaries.
