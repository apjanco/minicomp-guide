There are two common ways to create a minimal webpage.  The simplest is to use hypertext markup or [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML). Markup uses a system of tags to add information to plain text. For example, to make some text bold, you'd add an opening `<b>` tag followed by a closing `</b>` tag.  The tags indicate where the markup begins and ends: `<b>I am bold</b> I am not bold`. In recent years, [markdown](https://www.markdownguide.org/) has become a convenient way to compose text for the web. It's a shorthand that uses symbols to represent HTML tags. For the example above, we'd write: `**I am bold** I am not bold`. Markdown is easier to write and feels less like code. A script is used to convert the markdown to HTML, so it's entirely a matter of the author's preference.  

In this section, we with publish some simple content on the web using markup and markdown. Both will require a free GitHub account. Please go to this page and create an account: https://github.com/join  

Once you sign in to GitHub, you can now create a space to manage files called a repository.  In the upper right, click on the plus symbol and select "New 
repository." 

You can then:
1. enter a repository name
2. check "Add a README file"
3. click the green "Create Repository" button. 

Finally, we want to publish our files to the web, so we enable GitHub Pages in our new repository.
1. click on the Settings tab. 
2. select the Pages menu
3. In the source section, select `main` and `/(root)`
4. click save. You should now see a message. For me, it shows `Your site is ready to be published at https://apjanco.github.io/sturdy-journey/`
6. click on the link and you should see a blank page with the title of your repository. 

Now let's add some content!  

# Markdown 
To change the content on the page we've created, edit the README.md file in your repository.  The `.md` suffix indicates that this file is markdown. Click on the pencil icon ("Edit this file") to open the file editor. You'll see `#` followed by the repository name.  This is markdown-speak for header, which is the largest text on the page.  You can make it smaller by changing it to `##` or `###`.  In the HTML-land, this equates to `<h1>`,`<h2>` and `<h3>`. For this initial introduction, we'll just make a basic personal page. 
```markdown 

## Andrew Janco
- lives with two cats
- person of the mountains
- travels when able

```
When done writing, click on the green "Commit changes" button. In about 30 seconds, your new content will appear on the page (in my case https://apjanco.github.io/sturdy-journey/).  

From here you can add anything you like:
```markdown
links: [Penn](https://www.upenn.edu)  
images: ![is cat](https://placekitten.com/g/200/300)  
**bold text**
*italics*
```
For more options, see the markdown cheatsheet here: https://www.markdownguide.org/cheat-sheet/

# Markup 
 
