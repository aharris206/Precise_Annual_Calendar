### A concept by Andrew Harris • `2023-06-28T21:20`[−07:00](https://en.wikipedia.org/wiki/UTC%E2%88%9207:00)
# Precise Annual Calendar ⁍ Version 1.0.0
## *A more precise annular calendar that uses the Equinoxes and Solstices as “Anchor-Points.”*
# About
- This is a project I have been working on for some time now; it is a new way of representing Time and functions both as a clock and calendar.

# [No *Open Source* License](https://choosealicense.com/no-permission/)
- Having carefully looked over [GitHub's various licensing options](https://choosealicense.com/licenses/), I have decided **not** to give this project an “Open-Source License.” 
    - The main reason for this is in regard to ***Commercial Use,*** **but extends further.* 
    - The concept behind creating this calendar has been an undertaking years in the making and is something I care very deeply about. 
- **Because of this**, at least for the time being, **I withhold all of my rights as sole contributor of this project.** *Feel free though to message me though if you would like use this* ***for private use***.

# How This Calendar Works
- The first thing in understanding how this Calendar works is understanding that is utilizes a [dozenal](https://en.wikipedia.org/wiki/Duodecimal) counting system. 
    - In an attempt to make this easier to understand, I have fashioned the interface like an analog clock *but without the numbers,* but it basically just means that this calendar counts in dozens. This shouldn't be too foreign of a concept, as we are already used to having a dozen months in a year.
### The **Year** is defined as
- beginning on the [March Equinox](https://www.timeanddate.com/calendar/march-equinox.html), containing a dozen months of relatively equal size.
- In actuality, the year breaks up into 4 parts, using the [Equinoxes and Solstices](https://www.timeanddate.com/astronomy/equinox-solstice.html) as ***"Anchor-Points"***. This ensures that every third month begins on an Equinox or Solstice, and because of this,
##### we know that any value in-between will line up precisely with its counterpart in another given year.  

### Months are defined as
- One third of the distance between any Equinox or Solstice. Or, in other words, the time between an Equinox and Solstice is exactly 3 months in length.
    - Month 0 begins on the [March Equinox](https://www.timeanddate.com/calendar/march-equinox.html)
        - Months 0, 1, and 2 make the distance between **the March Equinox** and **the June Solstice**.
    - Month 3 begins on the [June Solstice](https://www.timeanddate.com/calendar/june-solstice.html)
        - Months 3, 4, and 5 make the distance between **the June Solstice** and **the September Equinox**.
    - Month 6 begins on the [September Equinox](https://www.timeanddate.com/calendar/september-equinox.html)
        - Months 6, 7, and 8 make the distance between **the September Equinox** and **the December Solstice**.
    - Month 9 begins on the [December Solstice](https://www.timeanddate.com/calendar/december-solstice.html)
        - Months 9, δ, and λ make the distance between **the December Solstice** and **the *next* March Equinox**.
            - δ *"dek"* and λ *"el"* are [dozenal](https://en.wikipedia.org/wiki/Duodecimal) numbers. They are both single-digit numbers that come after 9.

### Each Month breaks up into [one gross](https://en.wikipedia.org/wiki/Gross_(unit)) **"Shifts"**
    - *"One Gross"* is a dozen dozen. If you buy a dozen boxes of a doughnuts, or a dozen cartons of eggs, one gross is the number of individual doughnuts or eggs you have, since we buy both of these by the dozen.
    - **A Shift** is *about* 5 hours long, give or take. *(remember again that these values change slightly from season to season)*

### Each Shift breaks up into one gross **"Spans"**
    - From here on out, each value breaks up into one gross *(a dozen dozen)* pieces to make smaller units.
    - **A Span** is *about* two minutes long.

### Each Span breaks up into one gross **"Seconds"**
    - **This second hand** ticks a little bit faster than the second hand you may be used to. It varies in length depending on the season but is roughly 80% the size of a second.

# On the analog display
*Each value moves around the display clockwise.*
### The Month is represented as `a blue dot` on the **analog display.
### The Shift is the smallest hand, followed by the Span and the Second.
*As you can see, there are a dozen ticks in-between each large "o-clock" tick. I have made smaller ticks in-between to better show this. The first and last ticks are the edges of the large tick before or after it.*

## The Year is shown on the top. *(remember that this number is [dozenal](https://en.wikipedia.org/wiki/Duodecimal), not decimal.)*
- The current year is 119λ *"One dozen and One Gross, Nine dozen and El".* This began on the March Equinox on 2023 and will end on the March Equinox of 2024.
    - Instead of *decades* and *centuries,* years are grouped into ***dozens*** and ***grosses.***
        - Grosses: *Remember that grosses are a dozen dozen, so equate to nearly a century and a half!*
            - The current **"gross of years"** *(1100; One dozen and One Gross)* began with the March Equinox of [1904](https://en.wikipedia.org/wiki/1904.)
            - The next **"gross of years"** *(1200; One dozen and Two Gross)* will begin in with the March Equinox of 2048 and will end with the March Equinox of 2192.
        - Dozens:
            - At the time I am writing this, we are nearing the end of our ninth dozen in the current **"gross of years"**.
            - This means we have two dozen more: **11δ0 – 11δλ** and **11λ0 – 11λλ**.
                - 11δ0 *"One dozen and One Gross, Dek dozen"* begins with the March Equinox of 2024. 
                - 11λ0 *"One dozen and One Gross, El dozen"* begins with the March Equinox of 2036.

# Year Zero, One Dozen, and the beginnings of several Grosses of Years
- Year 0 is [AD 32](https://en.wikipedia.org/wiki/AD_32) *(Technically, the March Equinox of **AD 32** to the March Equinox of **AD 33**)*
    - Year 10 is the **year One Dozen**. It corresponds with the year [AD 44](https://en.wikipedia.org/wiki/AD_44) *(the March Equinox of **AD 44** to the March Equinox of **AD 45**)*
    - Year 100 is the **year One Gross**. It corresponds with the year [AD 176](https://en.wikipedia.org/wiki/176) *(the March Equinox of **AD 176** to the March Equinox of **AD 177**)*
    - Year 200 *"Two Gross"* began with the March Equinox of [AD 320](https://en.wikipedia.org/wiki/320)
    - Year 300 *"Three Gross"* began with the March Equinox of [AD 464](https://en.wikipedia.org/wiki/464)
    - Year 400 *"Four Gross"* began with the March Equinox of [AD 608](https://en.wikipedia.org/wiki/608)
    - Year 500 *"Five Gross"* began with the March Equinox of [AD 752](https://en.wikipedia.org/wiki/752)
    - Year 600 *"Six Gross"* began with the March Equinox of [AD 896](https://en.wikipedia.org/wiki/896)
    - Year 700 *"Seven Gross"* began with the March Equinox of [1040](https://en.wikipedia.org/wiki/1040)
    - Year 800 *"Eight Gross"* began with the March Equinox of [1184](https://en.wikipedia.org/wiki/1184)
    - Year 900 *"Nine Gross"* began with the March Equinox of [1328](https://en.wikipedia.org/wiki/1328)
    - Year δ00 *"Dek Gross"* began with the March Equinox of [1472](https://en.wikipedia.org/wiki/1472)
    - Year λ00 *"El Gross"* began with the March Equinox of [1616](https://en.wikipedia.org/wiki/1616)
- Year 1000 *"One dozen Gross"* began with the March Equinox of [1760](https://en.wikipedia.org/wiki/1760)
    - Year 1100 *"One dozen and One Gross"* began with the March Equinox of [1904](https://en.wikipedia.org/wiki/1904)
    - Year 1200 *"One dozen and Two Gross"* will begin with the March Equinox of 2048.
    - Year 1300 *"One dozen and Three Gross"* will begin with the March Equinox of 2192.
    - Year 1400 *"One dozen and Four Gross"* will begin with the March Equinox of 2336.
    - Year 1500 *"One dozen and Five Gross"* will begin with the March Equinox of 2480.
- Year 1600 *"One dozen and Six Gross"* will begin with the March Equinox of 2624.
