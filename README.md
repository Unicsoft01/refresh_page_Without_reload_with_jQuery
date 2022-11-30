# HOW TO UPDATE CONTENTS ON A WEB PAGE WITHOUT RELOADING THE PAGE WITH jQUERY AJAX
If you are beginner then this post is for you. For showing the new content on page without refresh we will use JQuery Reload Page without Refresh and server side PHP. In this article, I will demonstrate to show the latest content from server without refreshing the page. This is useful in case of showing like unlike button, showing latest content, changing the data on user request.

In this tutorial we will take example of JQuery Reload Page without Refresh and Changing content of element on click and check status.

Let’s start the tutorial with steps:
## Step 1: Create a html file

First step is to create the html and setup basic elements of page.

```html
<!DOCTYPE html>
<html>
<body>

<h2>Change content without reloading page - Unicsoft Codes</h2>

<div id="content">
  <h1>This is a dummy content, i am going to change it</h1>
  <p>Let's change it with jquery click</p>
</div>
<div class="footer">
  <button id="load_btn">Load New </button>
</div>
</body>
</html>
```
# Step 2: Add jQuery
```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
```
