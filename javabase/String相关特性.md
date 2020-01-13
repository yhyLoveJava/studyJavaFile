

## String相关特性

#### 1、String*创建与赋值*

```java
char a[]={'s','t','u','d','e','n','t'};
String str=new String(a);
或
String str=new String(a,2,4);//截取字符数组的一段作为字符串
```

|           方法名            |                       用法                       | 返回值  |                             说明                             |
| :-------------------------: | :----------------------------------------------: | :-----: | :----------------------------------------------------------: |
|           length            |                    str.length                    |  数值   |                       返回字符串的长度                       |
|          charAt()           |                str.charAt(index)                 |  char   |            获取字符串指定位置的字符，index为位置             |
|         subString()         | str.subString(index),str.subString(index,length) | String  |                    截取字符串中的部分字符                    |
| equals(),equalsIgnoreCase() |                str1.equals(str2)                 | boolean | 比较字符串大小，equals区分大小写，equalsIgnoreCase不区分大小写 |
|   indexOf(),lastIndexOf()   |                str.indexOf("as")                 |  数值   |          查询字符串第一次在此字符串第一次出现的序号          |
|          isEmpty()          |                  str.isEmpty()                   | boolean |                  当str的长度为0时，字符为空                  |
|          replace()          |               str.replace('a','b')               | String  |                 用新字符替换字符串中的老字符                 |
| toLowerCase(),toUpperCase() |                str.toLowerCase()                 | String  |                 将字符串中字母变成大写或小写                 |
|        toCharArray()        |                str.toCharArray()                 | char[]  |                     将字符串变成字符数组                     |
|                             |                                                  |         |                                                              |
|                             |                                                  |         |                                                              |
|                             |                                                  |         |                                                              |

