# Time and Date - Lubridate Package

> Automatically recognise common date separators (-, /, ., and ` `)

-	convert to year, month, day

`ymd()`

-	convert to year, month, day, hour, minute, second

`ymd_hms()`

- Extract year from df column

`flights_new$departure %>% year()`

- replace the year component

`year(foo) <- 2020`

- add one hour

`hour(foo) <- hour(foo) + 1`

- Calculate a time intervals

`my_age <- today() - ymd(19810529)`
