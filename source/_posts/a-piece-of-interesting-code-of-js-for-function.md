title: 一段有意思的JS For循环代码
categories: javascript
date: 2016-02-25 17:10:43
tags:  [js]

---

```
var a =0;
for (var i =0,j =0; i <10,j<6;i++,j++) {
	a = i+j;
	console.log("i="+i);
	console.log("j="+j);
	console.log("a="+a);
}
```

朋友面试，遇到的面试题，电话跟我说完就回来写下来试了一下，结果与自己预想的一样。

没写之前，电话里说的思路是，因为 j 限制了 小于 6，那么应该只循环6次，实际上也确实是这样。

所以最终结果，a = 10。

###### 但是想不明白为什么会有这样的面试题，或者说，什么样的情况会需要写这样的代码呢？