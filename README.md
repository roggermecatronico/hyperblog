### Proyecto de curso Profesional de Git y Github

- Aprendimos a crear un repositorio
- Aprendimos a usar GIT Bash
- Los comandos de Git
- La diferencia entre el Directorio, Staging y Repositorio
- Aprendimos a trabajar en diferentes ramas
- Trabajar en equipo
- Configuramos nuestro proyecto con SSH
- Hacer fork para contribuir a los proyectos
- Usar tags
- Realizar pull request

####Comandos

* git init
* git status
* git add (archivo).txt
* git rm --cached
* git commit -m "(mensaje)"
* git config
* git config --global user.name "Rogger"
* git config --global user.email "rogger.mecatronica@gmail.com"
* git log (documento).txt
* git show
* git diff 
* git log --stat
* git checkout (frghrtbdfsb, log) (documento).txt
* git rm --cached
* git rm --force
* git reset --soft
* git reset --hard
* git reset HEAD
* git clone (url)
* git pull origin master
* git push origin master
* git remote add origin (url)
* git remote -v 
* git pull origin master --allow -unrelated -histories
* git remote set-url origin (url ssh)
* git log --all --graph
* git log --all --graph --decorate --online
* alias arbolito="git log --all --graph --decorate --online
* git tag -a V0.1 -m "mensaje"
* git tag
* git show--ref --tags
* git push origin --tags
* git tag -d (tag)
* git push origin :refs/tags/(tag)
* git show-branch
* gitk
* git rebasse
* git stash
* gitstash list
* git stash pop
* git stash drop
* git clean --dry-run
* git clean -f

![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)


**Table of Contents**

[TOCM]

[TOC]


###Links

[Links](http://localhost/)

[Links with title](http://localhost/ "link title")

`<link>` : <https://github.com>

[Reference link][id/name] 

[id/name]: http://link-url/

GFM a-tail link @pandao


####HTML code

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Hello world!</title>
    </head>
    <body>
        <h1>Hello world!</h1>
    </body>
</html>
```

###Images

Image:

![](https://pandao.github.io/editor.md/examples/images/4.jpg)

> Follow your heart.

###Lists

####Unordered list (-)

- Item A
- Item B
- Item C
     
####Unordered list (*)

* Item A
* Item B
* Item C

####Unordered list (plus sign and nested)
                
+ Item A
+ Item B
    + Item B 1
    + Item B 2
    + Item B 3
+ Item C
    * Item C 1
    * Item C 2
    * Item C 3

####Ordered list
                
1. Item A
2. Item B
3. Item C
                
----
            
###TeX(LaTeX)
   
$$E=mc^2$$

Inline $$E=mc^2$$ Inline，Inline $$E=mc^2$$ Inline。

$$\(\sqrt{3x-1}+(1+x)^2\)$$
                    
$$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$$
                
###FlowChart

```flow
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
```

###Sequence Diagram
                    
```seq
Andrew->China: Says Hello 
Note right of China: China thinks\nabout it 
China-->Andrew: How are you? 
Andrew->>China: I am good thanks!
```

###End
