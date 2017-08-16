---
layout:     post
title:      Hello World in jekyll
date:       2017-08-16 10:00:00
summary:    This is first post on my blog. As usual for "hello world" tutorial
            this post is about creating a new post in jekyll.
categories: blog
---

This is first post on my blog. As usual for "hello world" tutorial this post
is about creating a new post in jekyll.

## How to add a new post to jekyll blog?

#### 1. Create new file in `_posts` folder.   
File must be named in the following format: `YEAR-MONTH-DAY-title.md`

#### 2. Open created file, add heading
```
---
layout:     post
title:      Hello World
date:       2017-08-16 10:00:00
summary:    Short summary to display on the first page.
categories: blog
---
```

#### 3. Write post in markdown
```
# Hello world heading ...

... and a hello world paragraph :)
```

#### 4. Push to github
1. add new file to git `git add _post/{filename}`
2. create commit `git commit -m "add Hello World post"`
3. push commit to github `git push origin master`

#### 5. Finished :)
