# Oh Drats, Bats 🦇

## What is this?

This is the simplest possible way to demonstrate how the `bats` testing tool works.

## How do I use it?

- `git clone`
- `./test/bats/bin/bats test/test.bats`


## Demo 

```
❯ ./test/bats/bin/bats test/test.bats                                
test.bats
 ✓ our project shell script runs
 ✗ our tests can FAIL
   (from function `assert_output' in file test/test_helper/bats-assert/src/assert_output.bash, line 186,
    in test file test/test.bats, line 20)
     `assert_output --partial 'oh drats, farts!'' failed
   
   -- output does not contain substring --
   substring : oh drats, farts!
   output    : oh drats, bats!
   --
   

2 tests, 1 failure
```