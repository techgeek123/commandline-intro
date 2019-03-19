# File manipulation

Read about file manipulation [here](http://www.cs.colostate.edu/helpdocs/UNIX.html)

## Release 0

Let's start with the most basic function of the Command Line. How do we create files and folders. We have already learnt about `mkdir` and `touch`. Read up some more on these here. What all can you do with `touch` and `mkdir`? 

- Create a directory tree of Geographical Data (Country, States, Cities).
- The directory structure should look like this. (Find 20 major cities of a country of your choice)
  - Country
    - State 1
      - City 1
      - City 2
    - State 2
      - City 1
      - City
      - … and so on
- In the country’s directory, create a file named `details.txt`. Fill it with information from wikipedia.

## Release 1

Create duplicates of `details.txt` in each city directory named as `country_details.txt`. 
Is there any other way of achieving this?
Include a ReadMe.md file in the `~/soal/w1/d1` directory’

You have to remove the `details.txt` file and the state directories that contains `E` in their name but not the first state.

## Realease 2

- Can you think of a more efficient way to do Release 0 and 1?
- Can you write a shell script to carry out all the tasks in Release 0 and 1?
