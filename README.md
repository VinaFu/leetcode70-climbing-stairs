# leetcode70-climbing-stairs

1) Too much time

      def climbStairs(n):
          if n == 0 or n == 1:
              return 1 
              # make the i = n 
          else:
              return climbStairs(n-1) + climbStairs(n-2)
              # need [self.] in leetcode 

      n=5
      print(climbStairs(n)
      
  2)     
