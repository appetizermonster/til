# Precision / Recall

참고: [Wikipedia](https://en.wikipedia.org/wiki/Precision_and_recall)

예) 100마리의 개와, 8마리의 고양이가 있는 사진이 있다.

내가 만든 분류기가 그 사진에서 30마리의 개를 찾았다.  
하지만, 그 중에서 25마리가 실제 개(**True Positive**)였고, 5마리는 고양이(**False Positive**)였다.

```
Precision = True Positive / (True Positive + False Positive) = 25 / 30 = 0.83
Recall = True Positive / (True Positive + False Negative) = 25 / 100 = 0.25
```
