

# Formations classification

Final project for the Building AI course

## Summary

What if we at any time can start our football tactics ever ongoing discussion knowing the type of formation?
This is an attempt to automaticaly classify the formation of a football team provided by a picture of them playing.

## Background

It is often a problem to understand which formation a football team uses at a specific game. Sometimes it even changes between offense and defense.


## How is it used?

This solution can decide which class of formation a team has from the input of a picture. Different classes of formations are 4-3-3, 4-4-2, 3-5-2 etc.

![AC Milan lineup](https://upload.wikimedia.org/wikipedia/commons/a/a4/Ac_milan.svg)

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods

[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

## What next?
Covering Bandy formations are just behind the corner.


## Acknowledgments
University of Helsinki, Fredrik Heintz, Peltarion, AI Sweden. Thank you for the inspiration!
