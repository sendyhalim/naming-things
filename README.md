# Naming things
Just my convention for naming things in code


## Variables

### Iterable
Use plural for iterable data type such as `Array` and `List`
Good
```
posts
users
```

Bad
```
post
user
```

### Map / Dictionary
Use `<value>By<Key>` format for `Map` / `Dictionary` type

Good
```
// If we supply email as key, we will get a user
userByEmail

// If we supply product type as key, we will get an iterable products
productsByProductType
```

Bad
```
users
user
products
product
```

## File Nodes
Use hyphen `-` or underscore `_` to separate words

Never use
- space, makes it harder for autocompletion in terminal
- camelCase, macOS is not case sensitive.

Good
```
some-file.txt
some_file.txt
```

Bad

```
someFile.txt
some file.txt
```


## Urls
Use `-` to separate words
Good

```
http://example.com/some-example/post
```

Bad

```
http://example.com/some_example/post
http://example.com/some example/post
```

