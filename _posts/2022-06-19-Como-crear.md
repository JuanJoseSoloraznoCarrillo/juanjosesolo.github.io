---
layout: post
title: List Comprehensions en Python.
---

Una _List Comprehension_ es una forma de iterar una lista basandose en otro tipo de elementos iterambles, por ejemplo, _Tuplas_, _otras listas_, etc. Estas tipo de listas pueden ser descritas como un ciclo _for_, pero con una sintaxis más atractiva. Las _List Comprehensions_ son relativamente mas rápidas que los ciclos _for_ normales.

La estructura básica de una _List Comprehension_ es la siguiente:

List = [**expresion** for **item** in **iterable** (**if conditional**)]

```python
words = ['datos', 'ciencia', 'maquina', 'aprendizaje']


#Ciclo for normal
a = []
for word in words:
	a.append(len(word))
#List Comprehension
b = [len(word) for word in words]

#Resultado:

print(f" a is {a}")  # a is [5, 7, 7, 11]
print(f" b is {b}")  # b is [5, 7, 7, 11]

```


## Función de una emoción

Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum. In arcu magna, aliquet vel pretium et, molestie et arcu.

Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

### Blockquotes (h3)

Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

> This quote will _change_ your life. It will reveal the <i>secrets</i> of the universe, and all the wonders of humanity. Don't <em>misuse</em> it.

### Code blocks (h3)

Vestibulum lacus tortor, ultricies id dignissim ac, bibendum in velit. Proin convallis mi ac felis pharetra aliquam. Curabitur dignissim accumsan rutrum.

```javascript
function sayHello(name) {
  if (!name) {
    console.log("Hello World");
  } else {
    console.log(`Hello ${name}`);
  }
}
```

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

##### Inline code, `pacman` (h5)

```python
import matplotlib.pyplot as plt

class myClass:

  def __init__():
    self.name = "juanjosesolorzanocarrillo"
```

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

### Oh hai, an unordered list!!

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

- First item, yo
- Second item, dawg
- Third item, what what?!
- Fourth item, fo sheezy my neezy

### Oh hai, an ordered list!!

In arcu magna, aliquet vel pretium et, molestie et arcu. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris.

1. First item, yo
2. Second item, dawg
3. Third item, what what?!
4. Fourth item, fo sheezy my neezy

### Tables

| Title 1               | Title 2               | Title 3               | Title 4               |
| --------------------- | --------------------- | --------------------- | --------------------- |
| lorem                 | lorem ipsum           | lorem ipsum dolor     | lorem ipsum dolor sit |
| lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit |
| lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit |
| lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit |

[^1]: This is the footnote.
