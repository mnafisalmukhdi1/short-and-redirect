# sr; Short and Redirect
Short and Redirect link for mnafisalmukhdi1, based on codepo8/github-redirection-demo
## Guidance from codepo8/github-redirection-demo

This just sends the user directly to the URL you provide.

```markdown
---
layout: default
target: https://example.com
---
```

## Other options

You have a few more options to set to customise your redirect:

```markdown
---
layout: default
target: https://example.com
targetname: Example.com
targettitle: Taking you to example.com
time: 10
message: This isn't here any more!
---
```

* `target` is the URL to redirect to. This defaults to the `target` URL
* `targetname` is the text to display for the URL
* `targettitle` is the title shown in the heading and the page title. This defaults to "Redirecting to `targetname`"
* `time` is the time in seconds
* `message` is the message to show above the link provided as a fallback
