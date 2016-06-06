# cmath

This started out as a private collection of maths functions, many will be quite simple. Over time I've got quite a few, and I thought it should be shared. Nothing is too complicated - I hope.

__tl;dr__ Maths functions.

## Code Example

'''Python
import cmath

print cmath.primes(10):
#Output [2, 3, 5, 7] 
'''

Each function comes with a suffiecient docstring, including what arguments it takes and what it returns.

## Motivation

Each function here has at some point been written and used by me to solve various maths problems, from ProjectEuler, to PythonChallenge, to my own recreational maths work.

## Installation

'''Bash
sudo pip install cmath
'''
'''Python
import cmath
# as you normally would...
'''

## Tests

Each one has gone through a decent amount of testing before finally being put into this proper collection. If you find any bugs contact me at the email provided and I'll look into it. 
'''Python
def test_primes():
	assert_equal(primes(100),[2,3,5,7,11,13,17,19,23,29,31,37,41,43,47,53,59,61,67,71,73,79,83,89,97])
	assert_equal(primes(2),[2])
	assert_equal(primes(-10),[])
	assert_equal(primes(1),[])
'''

## Contributors

So far just me. I'd like to thank any of my friends who will have without a doubt readover at least one of these files just to make sure it has no typos or anything else stupid.

## License

MIT.
__Basically__ I don't care what you do with the code so long as you 
- []don't ~~try to pass it off as your own~~ _(lol, I know just how basic it is.)_
- [x] give me credit

##TODO
- [] Finish porting all of this from everywhere into one place
- [] Work on more common maths functions
- [] Speed - _not the drug or the film_
- [] Sort out the README page
- [] ???

Contact me if you want to add more things to that list.

#### Known Bugs
Each bug I find is with the function, but still a general list for those unwilling to read (including me)
- isAP is not very numerically accurate
- isGP is not at all numerically accurate, this needs lots of work and fixing

