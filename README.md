# Wordalist Ghost Theme 0.0.1

Responsive, minimalist and open-source company blog theme for Ghost blogging platform. Based on the Willow Theme by https://raivis.com.

## Theme Demo

This theme is used on Wordalist blog: http://blog.wordalist.com

## Compiling SASS & Minifying JavaScript

Requires Grunt task runner & NPM to be installed.

    $ cd content/themes/[theme-folder]
    $ npm install
    $ grunt

## Editing Social Links and Promo Links

Edit the `content/themes/[theme-folder]/partials/sidebar.hbs` file.

## Enabling Disqus Comments Box

1. Edit the `content/themes/[theme-folder]/post.hbs` file, uncomment "comments" partial
inclusion.

2. Replace Disqus embed code with your site code - https://disqus.com/admin/universalcode/
