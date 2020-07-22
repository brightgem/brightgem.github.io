> K번째수 (https://programmers.co.kr/learn/courses/30/lessons/42748)

```java
import java.util.Arrays;

class Solution {
    public int[] solution(int[] array, int[][] commands) {
		int[] answer = new int[commands.length];
		int idx = 0;

		for(int[] command : commands) {
			int[] rangeArr = Arrays.copyOfRange(array, command[0]-1, command[1]);
			Arrays.sort(rangeArr);

			answer[idx++] = rangeArr[command[2]-1];
		}

		return answer;
    }
}
```
