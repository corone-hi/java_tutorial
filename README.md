# java_tutorial
JAVA


## Difference of JAVA

1. Array
```
String [] = { "1", "2", "3", "4" };

String [] classGroup = new String[4];

```

- JAVA에서 classGroup.length를 하면 몇개를 가지고 있는지가 아닌, **몇 개까지 수용가능한가**를 알려줌

2. for-each

```
public class ForeachDemo{
  public static void main(String[] args){
    String [] members = { "최진혁", "최유빈", "한이람"};
    for(String e: members){
      System.out.println(e + "이 상담을 받았습니다.");
    }
   }
}
```
