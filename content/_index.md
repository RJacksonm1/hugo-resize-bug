+++
image = "/uploads/cat.jpg"
+++

I should be 16px wide.

I'm not on my first build (`resources/_gen` is empty).

But I am on subsequent builds (`resources/_gen` contains the 16px variant).

```
rm -rf resources/_gen
hugo serve
# See full size image

# ctrl+c
hugo serve
# See 16px image
```