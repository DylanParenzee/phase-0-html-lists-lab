# HTML Lists

### Cloning Down Your Repository

If you already have a personal repository:

* In the terminal, type `git clone https://github.com/<your_username_here>/exceptional-realty`
* A folder with your previous work will appear in the IDE file tree.

If you want to use the demo repository to follow along:

* In your terminal, type `git clone https://github.com/learn-co-curriculum/exceptional-realty-demo`.
* Type `cd exceptional-realty-demo` to navigate into the folder.
* Type `git fetch html-lists`, the branch for this lesson.
* Type `git checkout html-lists`, and you're good to go!

**Remember to use `httpserver` to live test your webpage**

<iframe width="640" height="480" src="//www.youtube.com/embed/2IIhsgcNU-M?rel=0&modestbranding=1" frameborder="0" allowfullscreen></iframe>

<p><a href="https://www.youtube.com/watch?v=2IIhsgcNU-M">HTML Lists</a></p>.

### `<ul>`, `<li>`

In our `real-estate-listings.html` page, under the `<h4>2014</h4>` tag we added in the previous lesson, we should add some months in a list. In HTML, we can list things using the `<ul>` tag, which stands for _unordered list_, along with the `<li>` tag, _list item_.

To make a list, we write out the opening and closing `<ul>` tags, and inside them, we'll add `<li>` tags, each listing a single month.

`<ul>

  <li>Dec</li>
  <li>Nov</li>
  <li>Oct</li>
</ul>`

Lists are very flexible and we can even nest lists inside of lists, so if we wanted to add specific dates to a month, we could put a list inside of our October list:

```
<ul>
  <li>Dec</li>
  <li>Nov</li>
  <li>Oct
    <ul>
      <li>17th</li>
      <li>18th</li>
    </ul>
  </li>
</ul>
```

If we save this and check it out in the browser, we'll see that `ul` produces a bulleted list on the page, and will display nested lists indented further from the left.

### `<ol>`

The other type of list is the _ordered list_, which is written as `<ol>` instead of `<ul>`. Both will include `<li>` tags inside, but this time, `<ol>` will display a numbered list instead of bullets:

```
<h3>Popular Listings</h3>
<ol>
  <li>348 Stockton St.</li>
  <li>3742 Belevadere Rd.</li>
  <li>41 Cleaton Ave.</li>
</ol>
```

### Add, Commit, Push

If you're working from your own repository, make sure to add, commit and push up your work before moving on!

```
git add .
git commit -m 'started real-estate-listings.html'
git push
```

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/html-lists' title='HTML Lists'>HTML Lists</a> on Learn.co and start learning to code for free.</p>
