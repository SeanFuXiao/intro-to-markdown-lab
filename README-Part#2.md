# How to Write an HTML Boilerplate

![HTML](https://www.ionos.ca/digitalguide/fileadmin/_processed_/0/d/csm_html-tagst_e5866a824c.webp)

Creating a standard HTML boilerplate is the first step when starting any web project. This template provides a basic structure for your HTML document, ensuring that your page is well-formed and ready for content

## 1.  What is an HTML Boilerplate?

An HTML boilerplate is a starting template that includes the essential tags and attributes required to set up a basic HTML document. It serves as a foundation, ensuring that all necessary elements like the document type, character set, and basic meta tags are included.

![HTML](./Markdown-html-image.png)

## 2. The Structure of an HTML Boilerplate

The basic structure of an HTML document includes the following components:

- ***DOCTYPE Declaration***
- ***HTML Tag***
- ***Head Tag***
- ***Body Tag***
- ***Closing Tags***

Let's break down each component.

#### 1. DOCTYPE Declaration

The DOCTYPE declaration defines the document type and version of HTML. It helps the browser to render the content correctly.

```html
<!DOCTYPE html>
```

#### 2. HTML Tag

The `<html>` tag is the root element of an HTML page. It wraps all the content on the page.

```html
<html lang="en">
```

#### 3. Head Tag

The `<head>` section contains meta-information about the HTML document, such as its title, character set, and links to stylesheets or scripts.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

#### 4. Body Tag

The `<body>` tag contains the content that will be displayed on the web page, such as text, images, and other media.

```html
<body>
  <h1>Hello, World!</h1>
  <p>This is a basic HTML boilerplate.</p>
</body>
```

#### 5. Closing Tags

Always close the HTML and body tags to ensure that your document is properly structured.

```html
</html>
```

## 3. Putting It All Together

Here's how the complete HTML boilerplate looks:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is a basic HTML boilerplate.</p>
</body>
</html>
```

## 4. Explanation of Each Section

- **DOCTYPE Declaration**

>Ensures that the browser interprets the document as an HTML5 document.

- **HTML Tag**

    >The lang attribute specifies the language of the document. In this case, it is set to English (en).

- **Head Section**

    *meta charset*: 
    >Specifies the character encoding for the document. UTF-8 is a standard character set that supports most characters from all languages.

    *meta viewport*:
    > Configures the viewport for responsive web design, making sure the page scales correctly on different devices.

    *title*:
    > Sets the title of the document, which appears in the browser's title bar or tab.

    *link rel="stylesheet"*: 
    >Links to an external CSS file for styling the document.

- **Body Section**
Contains the content of the document, like text, images, and other elements that will be visible to the user.



## 5. Additional Tips

![tips](./Markdown-html-tips.png)
- ***Tip***: 
>Always include the meta viewport tag for responsive design, especially for mobile users. It's a best practice to start with a minimal boilerplate and add additional elements as needed for your project.


- ***Here’s a table that outlines the main components:***

    | Component           | Description                                 |
    | ------------------- | ------------------------------------------- |
    | `<!DOCTYPE html>`   | Defines the document as HTML5               |
    |   `<html lang="en">`  | Root element, with language set to English  |
    | `<head>`            | Contains meta-information and links         |
    | `<meta charset="UTF-8">` | Sets the character encoding to UTF-8   |
    | `<meta name="viewport" content="width=device-width, initial-scale=1.0">` | Ensures responsive design |
    | `<title>`           | Sets the title of the document              |
    | `<body>`            | Contains the content to be displayed        |
    | `</html>`           | Closes the HTML document                    |




- *The following meta tag was used for older versions of Internet Explorer*:  
~~`<meta http-equiv="X-UA-Compatible" content="IE=edge">`~~  
With modern browsers, this is no longer necessary.

[HTML Reference(MDN)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)



