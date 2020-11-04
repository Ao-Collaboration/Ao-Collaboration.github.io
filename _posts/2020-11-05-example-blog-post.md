---
layout: post
title: "An example blog post title"
excerpt: "A short description of the blog post. Used in google search results and summaries"
image: "images/boat-336551.webp"
tags:
- announcement
- example
---

Have a look at the source for this page while reading this.

You needs to add two line breaks to separate a paragraph. 

Otherwise
all
the
content
will
be
on
one
line.

The stuff at the top is called the "front matter". 

* The layout is "post" because this is a post. 
* The title is the title..
* The excerpt is a short description. This shows up when a summary of the post is shown on the home page, and on google etc.
* The image shows up next to the description in most places.
* The tags group pages. You can navigate to [the tabs page](/tags) to see all the posts sorted by tags
* Also notice the file name determines the published date and the URL the post will show under. The file name must be formatted `yyyy-mm-dd-text-with-hyphens.md`

Bullet point example ^

**Here is some bold text**

*Here is italics*

## Here is a secondary heading

The primary heading is automatically added from the `title` in the section at the top

### Here is a third level heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about an image?

![Boat](/images/boat-336551.webp)

You can also center images, and use images from other websites

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here is a code chunk

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

## Boxes

You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.

Idk if you would ever use these
