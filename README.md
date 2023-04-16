# Alfred-workflow-Postbox-mail-link
Create markdown link to selected Postbox message

# Introduction

Note that to use this workflow you must have [Postbox](https://www.postbox-inc.com/) installed.

This workflow takes a selected email in Postbox and creates from it a markdown link in the following format:

[Birthday greetings](x-postbox-message://f05a9a04-f297-0234-989a-82e4ddefe4a4%40blahblah.com) from Freda <freda@blahblah.com>

That means, of course, that when displaying the markdown you can click on the subject of the message and go directly to the message in Postbox.

# Usage

Select a single message in Postbox and type the keyword in Alfred (the default is `pblink`). The result is displayed in a dialog and also copied to the clipboard.

# Acknowledgement

I am indebted, for the idea, to @sepulchra on the [Alfred forum](https://www.alfredforum.com/) who wrote [the original workflow](https://alfred.app/workflows/sepulchra/mail-link/) to work with Apple Mail. It is rather trickier to use the `message://` protocol in Postbox so this workflow uses the URL protocol instead.
