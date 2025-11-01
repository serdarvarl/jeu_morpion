# resume de course

## introduction

```js
<script> 
    alert("hello world")
</script>
```

```js
<script type="text/javascript" src="script.js"></script>

```

## variables

### numbers

```js
var a = 3;
alert(typeof a);

```

+, -, /, *, %; =

```js
 var a;
 var b;
 var c ;
c= a+b // a*b// a/b // a-b etc

i++ // =+1 // =i+1
i-- // =-1 // =i-1
```

### Boolen

```python
var a = false // true

== 
!=
<= , < , > ,  >=

&& and
|| or
! not

```

### String

 = , +, +=

```js
var a = "Bonjour ";
var b = "monsiuer";
a+=b


a.lenght // a[i]


```

[liste de methodes](https://playcode.io/javascript/methods)

### Array (Dizi)

```js
var d = [1,2, true, "array"]
```

<https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array>

#### object

```js
var famille ={
    p1 = 'per1',
    p2 = 'per2',
}

famille['p1']
alert(famille['p1'])
```

### iterative

#### while

```js
var text = '' 
var i = 0

while (i<10) {
    text = text + i + '' + ;
    i+=1
}

alert(text)
```

#### do

itération avant la condution

password ve tekar durumlarinda bir kez gerceklesir

```js
let password;
do {
  password = prompt("Şifre girin (en az 4 karakter):");
} while (password.length < 4);

```

```js
var i = 0;
var text = ""
do {
    text= text + i + " ";
    i+=1;
}while(i<5)
alert(text)
```

#### for

```js
var text = "";
var i ;
for (i=0,i<10, i++){
    text = text + i + " "
}
alert(text)

```

dictionary

```js

var list = {
    p1 :"per1",
    p2 :"per2",
    p3 :"per3",
    p4 :"per4",
}

var i;

for(i in list){
    alert(list[i]);
}
```

## Fonction

```js

function conver(p_Euro){
    var p_LivreT = p_Euro * 50;
    console.log(p_LivreT)
}

convert(50).....
```

