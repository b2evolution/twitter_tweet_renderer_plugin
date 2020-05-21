# Twitter Tweet Renderer Plugin

This plugin automatically renders embedded Tweets in place of Twitter Tweet URLs.

### Priority Requirements for this Plugin

The plugin priority is set to 60 by default. Please note that this plugin could have issues when combined with other Text renderers and the following situations needs to be taken in care:

The priority must be set less than the Autolinks Plugin priority, because Auto Links replaces all links, including "https://twitter.com/myaccount/status/1234567890123456789" with clickable links, and it prevents this plugin from properly rendering the embedded Tweet.
