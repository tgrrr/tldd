# Sequence

> my_age <- today() - ymd(19810529)
my_age

- Create a sequence of years from 1980 to 2018 by 2

`seq(from = 1980, to=2018, by = 2)`

`c(ymd_hm("2018-1-1 9:00"), ymd_hm("2018-1-1 12:00"))
    %>% seq(by = "hour")`
