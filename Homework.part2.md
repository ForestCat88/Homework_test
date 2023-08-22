# Instructions for basic use the GIT from Markdown #

## Num 1: Create title in GIT:

-  For create title in GIT you need use a #. This command will transform entiring text in title.
- If you use ##, you title be a smaller, than previously, etc

## Num 2: Formatting text:

1. For that text is a bold, use a **. For example: **bold text**
2. For that text is a coursive, you need use a *. For example: *coursive*
3. For that text is bold and coursive, use a ***. For example:  ***Text is over***
4. ~~~Text wil be crosed ~~~
In the practice you will meet a lot of difference variants formatting and used this opportunity. Search and open new knowledge

## Num 3: Basic commands:
For the succefful use a GIT, you need to know a basic commands, which contoling working process.

- ``` git init ``` used for initialize local repository
```
git commit -m "message" - used  for create commit

```
- ``` git status``` for informatiom about actual status of git
- ``` git add ``` added file or files to next commit 
```
git log - history of commits whith their hash codes

```
``` git checkout  ``` switch from one commit to other
``` git diff ``` see the difference between current file and commit

## Num 4: Another opportunities

For that in your site or text paste a link or picture, you need enter in [hyperlink], than in (http://webadress)
For example: All info we can put in [GitHUB](http://pages.github.com)

This way can be used and for images. First [image](linkimage)

# Manual for GIT practice and using Markdown

## Headers

## Tables

## Source Code

``` python
def guns(aim):
    bullet = [0]
    magazines = [0]
    for m in range(len(aim)):
        if m[aim] > bullet:
            bullet = m[aim]
    for m in range(len(aim)):
        if m[aim] > magazines and m[aim] != bullet[aim]
        magazines = m[aim]

        return
```

## Using HTML

ожно смешивать Markdown и HTML. Если на какие-то элементы нужно поставить классы или атрибуты, смело используем HTML:

> Выделять слова можно при помощи * и _ . Например, это <em class="a1">italic</em> и это тоже <i class="a1">italic</i>. А вот так уже <b>strong</b>, и так тоже <strong>strong</strong>.

Можно и наоборот, внутри HTML-тегов использовать Маркдаун.

<section class="someclass">

### Пример Маркдауна внутри HTML

Выделять слова можно при помощи `*` и `_` . Например, это _italic_ и это тоже *italic*. А вот так уже __strong__, и так тоже **strong**.

</section>
