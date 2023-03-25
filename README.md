# [TILES!](https://github.com/lafelabs/tiles)

GEOMETRIC SOCIAL MEDIA!

## [localhost](http://localhost/)

### [HOME](index.html)

A Board is an array of tiles. 

A tile is an object defined as follows:

```
{
"index": [index of this tile in the board array],
"name":[string. does not have to be unique.],
"trajectory":[geometron glyph which is a string],
"shape":[geometron glyph which is a string],
"message":[string with maximum number of characters],
"hyperlink":[url string with maximum number of characters],
"relationships":[array of relationships]
}
```

A relationship is defined as follows:

```
{
"index":[integer, unique in each board],
"name":[string, does not need to be unique, does not need to be the same as self-name],
"relationship identifier":[string, max number of characters]
}
```