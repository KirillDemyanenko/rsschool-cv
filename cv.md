# Kirill Demyanenko

***

![Me](me.jpg)

***

### Contacts

**Phone:** *+375 (29) 155-63-13*

**Phone:** *demyanenkokg@gmail.com*

**Phone:** *Discord - KirillDemyanenko*

***

***

### Code example

```
function findMissing(arr1, arr2) {
    if (arr1.length > arr2.length) {
        let s = arr1.join('')
        arr2.forEach(value => s = s.replace(value.toString(), ''))
        return parseInt(s, 10)
    } else {
        let s = arr2.join('')
        arr1.forEach(value => s = s.replace(value.toString(), ''))
        return parseInt(s, 10)
    }
}
```

