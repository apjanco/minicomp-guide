# Static site builders 

In this section, we'll discuss common programs that you can use to build static websites.  You can always write your own content in HTML, but static site generators offer a good way of automating the repetitive parts.  This is especially useful when your site has more than one page. For example, your site probably needs a navigation bar.  We could copy and paste the same code into each and every page.  But if we make a change, then we'll have to go back through each and every page to make the change over and over.  That's not a good use of your time.  Many static site builders also come with themes that have built-in features like search or styling.   

> Further reading:
> [Directory of static site builders](https://jamstack.org/generators/)

## Jekyll 
There are literally hundreds of different site builders out there, but Jekyll is the first stop for most people because of its integration into GitHub Pages. To change your README.md into a full fledged Jekyll site, go back to your repository's `settings`, then `pages`.  In `Theme Chooser` click on `Choose a theme`.  Once you've found a theme that you like, just click on `Select theme`.  When you go back to your site, you'll see that the site has changed and looks much fancier!  In the repository you'll also see a new `_config.yml` file. That file tells GitHub Pages which Jekyll theme to apply, such as `theme: jekyll-theme-cayman`. You can change that value to use nearly any theme on GitHub.  For example, to use the theme here: https://github.com/SalGnt/Travelogue I'd change the theme setting to `theme: SalGnt/Travelogue`. Note that I just drop the whole GitHub URL part and add the `username / theme-name`.  [Here's a great directory](http://drjekyllthemes.github.io/) with more themes.


In this section, we'll discuss two Jekyll themes from the Alex Gil and Marii Nyrop.  
Jekyll Essays Ed Exhibits Wax

11ty https://github.com/chrissy-dev/awesome-eleventy Not Wordpress: Hylia is a lightweight Eleventy starter kit with Netlify CMS pre-configured, so that you can one-click install a progressive, accessible blog in minutes.

lume https://github.com/lumeland/lume
