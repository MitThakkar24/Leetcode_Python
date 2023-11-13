class Solution(object):
    def climbStairs(self, n):
        first = 1
        second = 2
        if n == 1:
            return n
            
        for i in range(2,n):
            third = first + second
            first = second
            second = third
        return second
        
        
