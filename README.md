# [Foundation for Emails](http://foundation.zurb.com/emails)

Foundation for Emails (previously known as Ink) is a framework for creating responsive HTML emails that work in any email client&mdash;even Outlook. Our HTML/CSS components have been tested across every major email client to ensure consistency. And with the [Inky](https://github.com/zurb/inky) templating language, writing HTML emails is now even easier.

## Getting Started

Foundation for Emails 2 is not yet fully released, so for now, the main way to get started is with our [email template stack](https://github.com/zurb/foundation-emails-template). To use the stack, you'll need [Node.js](https://nodejs.org/en/) installed on your machine.

To set up the emails template, run these commands:

```bash
git clone https://github.com/zurb/foundation-emails-template project
cd project
npm install
```

Then run `npm start` to run the project. A new browser window will open with a BrowserSync server showing the finished files.

Run `npm run build` to do a full email inlining process.

## Documentation

The documentation is not yet live online (or finished!), but you can compile what we have on your own machine.

Run these commands to set up the documentation:

```
git clone https://github.com/zurb/foundation-emails.git
cd foundation-emails
npm install
```

Then run `npm start` to compile the documentation. When it finishes, a new browser window will open pointing to a BrowserSync server displaying the documentation.

## Inky

[Inky](https://github.com/zurb/inky) is our new templating language that converts simple HTML into the complex tables required for email layout.

The parser converts a set of custom HTML tags, expanding them out into full HTML syntax. Below is a list of every custom element.

### Grid

```html
<container>
  <row>
    <column small="12" large="4"></column>
    <column small="12" large="8"></column>
  </row>
</container>
```

### Block Grid

```html
<block-grid up="3">
  <td></td>
  <td></td>
  <td></td>
</block-grid>
```

### Components

```html
<button href="http://zurb.com"></button>
```

```html
<menu>
  <item href="one.html">Item One</item>
  <item href="one.html">Item Two</item>
  <item href="one.html">Item Three</item>
</menu>
```

## Contributing

As an open source project, we looooove our community support. Please file issues, or better yet pull requests on the [Foundation for Emails Repo](https://github.com/zurb/foundation-emails). We're stoked to hear your feedback, make improvements, and release this to the public soon!

Copyright (c) 2016 ZURB, inc.
