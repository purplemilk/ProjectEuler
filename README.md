# ProjectEuler
Where I'm gonna store my solutions to project euler problems n stuff.

#Euler Problem One
main = print result
    where
        result = sum [x |x <- [3..999], x `mod` 3 == 0 || x `mod` 5 == 0]
