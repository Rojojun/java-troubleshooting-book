# Chapter 1 앱에서 모호한 부분 밝히기
개발자가 디버깅을 하는 이유
* 새로운 프레임 워크 배우기
* 문제의 근본 원인 찾기
* 기존 로직을 이해하여 새로운 기능으로 확장하기
## 1.1 앱을 더 쉽게 이해하는 방법
```java
public int m(int f, int g) {
  try {
    int[] far = new int[f];
    far[g] = 1;
    return f'
  } catch(NegatoveArraytSizeException e) {
    f = -f;
    g = -g;
    return (-m(f, g) == -f) ? - g : -f;
  } catch(IndexOutOfBoundsException e) {
    return (m(g, 0) == 0) ? f : g;
}
```

위의 코드 같이 분석하기 어려운 코드가 있을 경우에는 디버거를 통해서 조사를 해야함
