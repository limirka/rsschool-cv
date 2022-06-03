# **Elizaveta Mirchuk**
## My Contact Info:


* __E-mail:__ limirka@icloud.com
* __GitHub:__ limirka
***
## __Summary__


*Hi There, I’m Liza and I am a newcomer in Frontend development. It's been 0,5 year, I'm learning it. My goal is to gain more knowledge in this field.*
***
## __Programming skills:__
* __HTML5__
* __CSS__
* __JavaScript__ *(still in progress)*
---
## __Code Example:__
```
function digital_root(n) {
  let num = String(n);
  let sumDig = 0;
  for (let i =  0; i < num.length ; i++){
    sumDig += parseInt(num[i]);
  }
  if (sumDig<10){
    return sumDig
  } else {  
  return digital_root(n - n + sumDig)
  }
}
```
---