class Solution:
    def kidsWithCandies(self, candies: List[int], extraCandies: int) -> List[bool]:
        x = max(candies)
        y =[]
        for i in candies:
            y.append(i + extraCandies >=x)
        return y
