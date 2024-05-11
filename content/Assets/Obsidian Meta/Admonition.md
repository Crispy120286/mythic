---
draft: true
---
Admonition Blocks

```ad-note
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
```

The admonition will render with the type of admonition by default. If you wish to customize the title, you can do so this way:

```ad-note
title: This is a Title
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
```

Leave the title field blank to only display the admonition.

```ad-note
title:
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
```

Use the `collapse` parameter to create a collapsible admonition.

`collapse: open` will start the admonition opened on render, but allow collapse on click.

```ad-note
title: This is a Title
collapse: open
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
```

```ad-note
title: triforce
icon: triforce
The admonition icon can be overridden using the icon parameter. The icon name entered must be the exact icon name from FontAwesome or RPGAwesome.
```

`````ad-note
title: Nested Admonitions
collapse: open

Hello!

````ad-note
title: This admonition is nested.
This is a nested admonition!

```ad-warning
title: This admonition is closed.
collapse: close
Housekeeping 
```

````

This is in the original admonition.
`````

```ad-note
```

```ad-abstract
```

```ad-info
```

```ad-tip
```

```ad-success
```

```ad-question
```

```ad-warning
```

```ad-failure
```

```ad-danger
```

```ad-bug
```

```ad-example
```

```ad-quote
```
