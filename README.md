# Markdown-parctice


Headers
---
```
# Header1
Header1(alternatively)
===
## Header
Header2(alternatively)
---
### Header
#### Header
##### Header
###### Header
```
# Header1
Header1(alternatively)
===
## Header
Header2(alternatively)
---
### Header
#### Header
##### Header
###### Header

Emphasis
---
```
italic : *text1*, _text2_
bold : **text1**, __text3__
italic+bold : [*_]{3}text1[_*]{3}
scratch : ~~text1~~
```

italic : *text1*, _text2_  
bold : **text1**, __text3__  
italic+bold : *__text1__*  
scratch : ~~text1~~  

List
---
```
- item1
+ item2
  - subitem1
    * subitem2
* item3

1. item1
1. item2
1. item3
```

- item1
+ item2
  - subitem1
    * subitem2
* item3

1. item1
1. item2
1. item3

Links
---
```
[GitHub](https://github.com/)
<https://github.com/>
[GitHub][1]
[GitHub][reference]
[Go GitHub]

[1]:https://github.com/
[reference]:https://github.com/
[Go GitHub]:https://github.com/
```
[GitHub](https://github.com/)  
<https://github.com/>  
[GitHub][1]  
[GitHub][reference]  
[Go GitHub]  

[1]:https://github.com/
[reference]:https://github.com/
[Go GitHub]:https://github.com/

Image
---
```
![sakura](sakura.jpg)
![sakura_reference][pretty]

[pretty]:sakura.jpg
```
![sakura](sakura.jpg)
![sakura_reference][pretty]

[pretty]:sakura.jpg


Blockquotes
---
```
> quotes text
> github
```
> quotes text  
> github

Inline code
---
```
I think you should use an
`<addr>` element here instead.
```
I think you should use an
`<addr>` element here instead.


Code Block
---

```
```python
def func():
  print("Hatsune")
  print("Miku")
  pass
\```
```


```python
def func():
  print("Hatsune")
  print("Miku")
  pass
```
Supported programing languages from <https://highlightjs.org/static/demo/> 

InLine Code
---
```
this is `InLine Code`
```
this is `InLine Code`

Task Lists
---
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

Table
---
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

Horizontal Rule
---
```
---
***
+++
===
___

```
---
***
+++
===
___

YouTube Videos
---
```
[![IMAGE ALT TEXT HERE](miku.jpg)](https://youtu.be/jhl5afLEKdo)
```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/jhl5afLEKdo)
$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$
