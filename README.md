# HTML_Task5
# Simple Mail Linking HTML

This README file provides instructions on how to create a simple HTML link for sending emails.

## Link Structure

To create a mail link in HTML, you can use the `<a>` element with the `href` attribute. Here's an example of how to create a mail link:

```html
<a href="mailto:example@example.com">Send Email</a>
```

In the above example, the `href` attribute starts with `mailto:` followed by the email address. When the link is clicked, it will open the default email client of the user with a new email addressed to the specified email address.

## Linking to Specific Email Fields

You can also include additional fields in the mail link, such as the subject and body of the email. Here's an example:

```html
<a href="mailto:example@example.com?subject=Hello%20World&body=This%20is%20the%20body%20of%20the%20email">Send Email</a>
```

In this example, the `subject` field is set to "Hello World" and the `body` field is set to "This is the body of the email". Note that spaces are represented by `%20` in the URL encoding.

## Usage

To create a mail link in your HTML file, follow these steps:

1. Create a new HTML file or open an existing one in a text editor.
2. Use the `<a>` element with the `href` attribute to create the mail link. For example:

   ```html
   <a href="mailto:example@example.com">Send Email</a>
   ```

   or

   ```html
   <a href="mailto:example@example.com?subject=Hello%20World&body=This%20is%20the%20body%20of%20the%20email">Send Email</a>
   ```

3. Customize the email address, subject, and body according to your needs.
4. Set the link text to your desired text. In the example above, the link text is "Send Email".
5. Save the HTML file.
6. Open the HTML file in a web browser to test the mail link. Clicking on the link should open the default email client with a new email addressed to the specified email address and, if provided, with the subject and body fields pre-filled.

That's it! You have now created a simple mail linking HTML code for sending emails.
