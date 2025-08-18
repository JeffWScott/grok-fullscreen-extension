# Purpose
I was sick of scrolling the the right all the time when Grok was displaying code. I just wanted the chats to take up the entire width of the browser window so I created this extension which just overwrites a few lines of CSS to accomplish the goal.

# Implementation
This is the entire extension:

Forces --content-max-width to be 100%.
```CSS
:root {
	--content-max-width: 100% !important;
}

```


## Install
Install from store and refresh your Grok tab.

## Privacy Policy
This browser extension does not collect, process, or transmit any user data. It only modifies the appearance of Grok.com pages using CSS to make the interface full screen for better usability. All code is open source an verifiable.
