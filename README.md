## Creating a Web Page in Codio
Creating a web page (and a website) is easy in Codio so let's get started...

We're going to need two files: `index.html` and `styles.css`.
To create a file, right-click on the SAMPLE-web folder in the file tree on the left side of the screen. Choose **New File...** and enter the filename `index.html`.
Now do the same for `styles.css`

**index.html**
Between the `<head></head>` tags add the following line of code to connect it to our `styles.css` stylesheet:

    <head>
      <link rel="stylesheet" href="styles.css" />
    </head>
    
Now add some content between the `<body></body>` tags such as a paragraph: `<p>My First Codio Website</p>`

**styles.css**
Let's make the background of the web page red and the paragraph text blue. Add the following:

    body {
      background: red;
    }
    
    p {
      color: blue;
    }


**View Website**
Click the **Project Index (static)** button and your homepage will open. You can also open in a new browser tab if you wish.

**Want to learn web development?** Try our [Introduction to Web Development](https://codio.com/home/courses/55e47d1780f8e32518cc9b42) course.