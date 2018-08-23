# HTML (C#)

This extension is a port of the [HTML (C#)][hcs-st] for [Sublime Text][st] extension. It provides syntax highlighting for HTML files with embedded C#, such as `.aspx`, `.cshtml`, and `.master`.

## Features

### Highlighting

- Embedded C# (`<script runat="server">`)
    + The `runat="server"` must immediately follow the tag opening
- Comment blocks (`<%-- foo --%>`)
- The `Response.Write` expressions (`<%=`, `<%#`, `<%:`, `<%$`)

### Functionality

- Toggle comment (<kbd>Ctrl</kbd>+<kbd>/</kbd> or <kbd>Cmd</kbd>+<kbd>/</kbd>)

## Requirements

- An enabled language grammar for `text.html.basic`. Unless your VS Code set-up is exceedingly novel, you should be fine.

## Extension Settings

There are currently no settings.

## Known Issues

- Blocks of `<% %>` do not work. They are currently unhighlighted and should not interfere with other sections of code.

## Release Notes

### 0.0.1

Initial buggy release

[hcs-st]: https://packagecontrol.io/packages/HTML%20(C%23)
[st]: https://www.sublimetext.com/