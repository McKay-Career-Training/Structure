#Structure

For this assignment you will be creating a **properly structured HTML page** on a topic of your choosing. Since **HTML** is a language for marking up text, you will be creating a page with lots of text and will be required to mark it up correctly. To give you an idea of what I want to see in your web page for information, you must have at least:

- 1 main heading
- 3 subeadings
- 3 paragraphs within each subeading (total of 9 paragraphs)

Getting Started
---

Now to get you started, we need to come up with a blank **HTML** template. The first thing we need to add is the dotype declaration.

	<!DOCTYPE **html**>

The doctype declaration must be the very first thing that appears in any **HTML** document. Although it isn't an **HTML** element, it is very important that it be included. The doctype declaration's purpose is to tell the browser what version of **HTML** the page is written in.

The doctype we added above is for **HTML5**. There are many other doctypes, but in this day and age, you are completely safe using this nice shiny doctype.

Opening Up
---

The next element in our basic **HTML** skeleton is the `<html></html>` element itself. This element tells the browser that it is indeed an **HTML** document. Under the doctype declaration, add our opening and closing **HTML** tags.

	<html></html>

The next part consists of two seperate sections that every web page has. An invisible section that contains information about the web page and a section that shows all the pages content to the user.

These sections are the `<head></head>` and the `<body></body>`. The `<head>` section is what contains information such as the title of our web page, the description, any links to **CSS** files, etc. The `<body>` of our page will hold all of our marked up content to show our users.

End Head;Start Body
---

Inside of our `<html></html>` element let's add the following markup.

	<head>
	</head>
	<body>
	</body>

We are almost done constructing a basic **HTML** skeleton. The last thing we need to include is some information for the browser. Specifically a title and a character set. Inside the `<head></head>` element, add the following markup.
	
	<meta charset="UTF-8">
	<title></title>

Yo dawg! I heard you like information
---

Before we get into what the charset is for, we need to understand what a `<meta>` element does and why it doesn't have a closing tag.

Metadata is information about data...**DATACEPTION**! We use the `<meta>` tag to provide the browser with information such as page description, author information, etc. For now all you need to know is that you need to include the charset set above in every document you create.

In **HTML** we have a few elements that are sometimes refered to as empty elements. These elements do not markup any text, so they do not have a closing tag, for example the `<meta>` element you saw above. Speaking of that meta element, your probably wondering what charset means.

In the old days of the internet when people were stuck with **HTML4** and **XHTML 1**, the way to tell the browser what charset and type of content you were serving it was a little more complicated. You would have to use the meta tag below.

	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

**HTML5** cleans this mess up for us by allowing just charset to be declared and best of all, its backwards compatible so we do not lose old browser support.

Just about done
---

Whew! That was alot of reading, but we should be pretty well set up for our first assignment. Take a look at your code now and make sure you have the following.

	<!DOCTYPE html>
	<html>
		<head>
			<meta charset="UTF-8">
			<title></title>
		</head>
		<body>

		</body>
	</html>

If you followed along correctly, you should have a nicely formatted document like above. (Don't forget to indent your code!).

TL;DR
---

One last thing before you go, your requirements for this assignment are as follows.

- 1 HTML page named index.html
- 1 main heading (`<h1></h1>`)
- 3 subheadings (`<h2-6></h2-6>`)
- 3 paragraphs per subheading

If you are interested in **bonus marks** you could try doing the following.

- Insert 1 or more relevant images in your HTML page
- Insert 1 or more properly marked up lists in your HTML page.

You may now begin writing your **HTML**. Have fun!!