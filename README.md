#PageLime Simple Blog Tutorial

Bloggidy blog blog boo.

Hey there! So rumor has it you want to blog? And you want it powered by PageLime. Hmm. Let's figure it out!

So PageLime has to most magical feature ever made by man-kind... Repeating Regions! This voodoo is so versatile that it can be use to make all sorts of great UX for your website, including blogs, image galleries, image sliders, site navigation, lists, itineraries and even cool yummy lime-ade. Okay maybe not that last one.

## With great power comes great responsibility. 

Lets be intelligent for a second shall we? Here at PageLime we always try to use the right tool for the right job. That's why we built PageLime. So many of today's popular CMS apps have way to much... shhhtuff. They have so much stuff they are just a chore to integrate. We don't want that for PageLime.

If you have a client that's asking you to build them the next award winning tech blog or you are looking for a pro blogging application, you may want to look for a different tool. Pagelime is designed for static web pages and is a great choice if your client wants a very basic blog to keep the masses up to date. Cool beans? 

We expect you to have a bit of HTML & CSS chops. You should be comfortable creating html pages, working with divs, classes, IDs, etc. You should also have a basic knowledge of CSS. If you also have a bit of PHP knowledge great, but not required. 

## Building a basic one page blog

Life in the fast lane? A blog doesn't need to be over complicated. If your client is a restaurant, accountant or small business do they really need categories, permalinks, trackbacks and gremlins? They may just need a single page where they can post their recent news and updates. 

As the designer/developer you'll want to create the blog in code first to get the look and feel setup. At the basic level a blog post is just a title, some body text, date and author info.

```html
<article>
    <h1>Blog article title</h1>
    <span>January 30th, 2015</span>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
    <div class="posted">
        <img src="images/superlimeman.jpg" title="superlimeman">
        Posted by Super Lime Man
    </div>
</article>
```

You can use CSS to style this really nice and voila you have the start of a great and very basic blog! Lets make it editable.

```html
<article id="editableBlogPost" class="cms-editable">
    <h1>Blog article title</h1>
    <span>January 30th, 2015</span>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    <div class="posted">
        <img src="images/superlimeman.jpg" title="superlimeman">
        Posted by Super Lime Man
    </div>
</article>
```

This entire block is now editable. Your clients can edit it to their hearts desire. What if your client wants to add more blog posts? Easy cheesy. Adding the cms-repeat class makes the post repeatable. Your clients can move, create and delete posts. Wow!

```html
<article id="editableBlogPost" class="cms-editable cms-repeat">
  <h1>Blog article title</h1>
  <span>January 30th, 2015</span>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.    </p>
 <div class="posted">
              <img src="images/superlimeman.jpg" title="superlimeman">
              Posted by Super Lime Man
</div>
</article>
```

At this point you can publish your new blog, call your client and pat yourself on the back! For many clients this is all they will ever need and you'll be their new hero... Super LimeMan!

