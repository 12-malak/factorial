# factorial

/
class Solution {
  public int trailingZeroes(int n) {

    int trailingZeroesCount = 0;

    while(n >= 5){
      trailingZeroesCount += n / 5;
      n /= 5;
    }

    return trailingZeroesCount;
  }
}
