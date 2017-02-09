# bulaga

---

### About

_Bulaga_ is an open-source javascript library using jQuery that shows a content with effect when the page is scrolled. Bulaga is the Filipino version of Peek-a-boo!


### Prerequisite

1. jQuery

### How to use

Using a normal DOM selector in jQuery, call the bulaga() function.

```javascript
$(selector).bulaga(options);
```

You may also add some options depending on your preferences. _options_ is in JSON format. If you want to set the duration of your animation, you can do...

```javascript
$(selector).bulaga({"duration": 2000});
```

### Options
| Key | Description | Type | Values | Default |
|:---:|:-----------:|:----:|:------:|:-------:|
|animation|Sets the type of animation you want for the element|`String`|`FADE_IN` `SLIDE_LEFT` `SLIDE_RIGHT` `SLIDE_UP` `SLIDE_DOWN`|`FADE_IN`|
