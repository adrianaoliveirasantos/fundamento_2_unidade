# type conversion ( converão de tipo ) / type coercion ( coerção de tipo)
```js
  var x = number("0") //Type Conversion, nessa linha é feita uma conversão de tipo explicita
```

varv y ="2" +3 // type coercion,nessa linha é feita uma converção implicito do valor 3 que é númerico(number) para
texto(string)

//onde usa expressões condicional e repitição,faz necessário um valor boolen (verdadeiro ou falso)
//ex.
if(true) {
}

//caso não for informada uma expressão ou um valor boolean diretamente,ele fará um type coercion (coerção de tipo)
//ex.
if(0) { //nessa linha ele iria fazer uma conversão do 0 para um boolean (verdadeiro ou falso),nese caso 0 será falso
}
...
