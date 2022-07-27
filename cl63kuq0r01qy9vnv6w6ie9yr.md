## Django Notes

## What is the different between `null` and `blank` in model fields?
These two terms are easy to confuse, but quite distinct:

- `null` is **database-related**. When a field has `null=True` it can store a database entry as NULL, meaning no value. (Nullable DB Entry)
- `blank` is **validation-related**. If `blank=True` then a *form allows an empty value*, whereas if `blank=False` then a value is *required*. 

> This Post gets updated regurlaly, meanwhile I'm learnning new things related to Django. 🚀

## Thank You ❤️
I wish this post be useful to anyone new to Django or anybody curious! If you found the content useful to you, please comment your thoughts, I would love to learn from you all. **Thank you for your loving directions.**