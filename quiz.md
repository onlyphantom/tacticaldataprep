1. How many books from our dataset have 5 or less pages?
    - [ ] 174  
    - [ ] 157  
    - [ ] 147  
    - [ ] 13,557  

2. How many books have an average rating of 0 having been reviewed at least once? In other words, ignore the books that have not received any reviews yet and consider only books that have been reviewed. How many of these books have an average rating of 0?  
    - [ ] 1  
    - [ ] 4  
    - [ ] 5  
    - [ ] 0  

For Quiz 3, refer to the code chunk below:

```{r eval=FALSE}
x <- c(0,4,2)
y <- x
y <- c(y, -3)
```

3. Referring to the code chunk, what is the value of `x`?
    - [ ] A vector of 0, 4 and 2  
    - [ ] A vector of 0, 4, 2 and -3  
    - [ ] A vector of -3, 0, 4 and 2  

4. Read the dataset `books_c.csv` in and replace all variants of English (`eng`, `en-US`, `en-GB`, any other possible `en-__` variants) with `eng` in the `language_code` variable. How many books in the database are in English irrespective of its variants?
    - [ ] 13714
    - [ ] 12634
    - [ ] 12643  
    - [ ] 12646  

5. What is a good example of a Diagnostic Question?
    - [ ] "Does English books receive more ratings than books in other languages     in general?"
    - [ ] "Are there any books with a non-numeric ISBN value?"
    - [ ] "What are the best-performing authors based on their reviews?"  
