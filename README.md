Analysis of mtcars!
-------------------

here is my data

    str(mtcars)

plot the data

    plot(as.factor(mtcars$cyl), mtcars$mpg)

And my findings

    tt <- t.test(mtcars$cyl, mtcars$mpg)
    print(tt)
