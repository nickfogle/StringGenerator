
A truly random string generator written in JavaScript. My solution for more reliable randomness than math.random().

I designed this for a tracking system, and rather than worrying about creating a database to check for unique ids, I thought I'd write a function to statistically perform the same thing. Basically, my goal was to create a generator capable of making duplicates statistically impossible. In the basic function, the odds of generating the same random string twice are less than: 1 in 10,000,000,000,000,000,000,000,000,000,000,000,000
