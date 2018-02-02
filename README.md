[![Build Status](https://travis-ci.org/Automattic/_s.svg?branch=master)](https://travis-ci.org/Automattic/_s)

Fashion Blog
===

* Licensed under GPLv2 or later. :) Use it to make something cool.

Getting Started
---------------

If you want to keep it simple, head over to https://underscores.me and generate your `_s` based theme from there. You just input the name of the theme you want to create, click the "Generate" button, and you get your ready-to-awesomize starter theme.

If you want to set things up manually, download `_s` from GitHub. The first thing you want to do is copy the `_s` directory and change the name to something else (like, say, `megatherium-is-awesome`), and then you'll need to do a five-step find and replace on the name in all the templates.

1. Search for `'fashion-blog'` (inside single quotations) to capture the text domain.
2. Search for `fashion_blog_` to capture all the function names.
3. Search for `Text Domain: fashion-blog` in `style.css`.
4. Search for <code>&nbsp;fashion-blog</code> (with a space before it) to capture DocBlocks.
5. Search for `fashion-blog` to capture prefixed handles.

OR

1. Search for: `'fashion-blog'` and replace with: `'megatherium-is-awesome'`
2. Search for: `fashion_blog_` and replace with: `megatherium_is_awesome_`
3. Search for: `Text Domain: fashion-blog` and replace with: `Text Domain: megatherium-is-awesome` in `style.css`.
4. Search for: <code>&nbsp;fashion-blog</code> and replace with: <code>&nbsp;Megatherium_is_Awesome</code>
5. Search for: `fashion-blog-` and replace with: `megatherium-is-awesome-`

Then, update the stylesheet header in `style.css`, the links in `footer.php` with your own information and rename `fashion-blog.pot` from `languages` folder to use the theme's slug. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say, but harder to do: make an awesome WordPress theme. :)

Good luck!
