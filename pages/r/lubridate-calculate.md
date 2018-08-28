# Time and Date Calculations - Lubridate Package

> Automatically recognise common date separators (-, /, ., and ` `)

- add one hour

`hour(foo) <- hour(foo) + 1`

- Calculate a time intervals

`my_age <- today() - ymd(19810529)`

-

`x + dhours(10) + dminutes(33) + dseconds(54)
[1] "2015-09-22 22:33:54 UTC"
`
