# npm-document
# random-number

### install.
## npm i random-number-generator-masai

JavaScript's Math.random() function tends to generate the same number at times. This random() function has a low chance of returning the same number twice, but still maintains that chance.

JavaScript's Math.random() returns a decimal, which you would then multiply by 10, 100, 1000, ect and then floor. This random() allows you to pass parameters for minimum and maximum number result, and still get a nice and random result.

This function also runs fast, and uses the time in milliseconds to help add variety to its random results. The function, also (optionally, true by default) keeps track of recent random results, and tries to avoid repeating them, but does so randomly.


The exported function takes an option object with 3 meaningful properties

min : smallest possible value to return. defaults to 0 or max - 1 if max is defined
max : largest possible value to return. defaults to 1 or min + 1 if min is defined
integer : do you want whole numbers to be returned, or not. defaults to false

generator( min, max, integer) - all arguments are optional
