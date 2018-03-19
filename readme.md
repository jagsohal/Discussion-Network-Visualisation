# Reddit Discussion Network Visualisation
## Info
This is a network visualisation of Reddit discussions.  You can choose a post
from the front page, or add a link from a reddit discussion, for example:
"http://www.reddit.com/r/IAmA/comments/1jd005/we_are_engineers_and_scientists_on_the_mars/"

The data is obtained from the Reddit API, the network is built with
[D3js](http://d3js.org/), and
the content previews are generated with
[Embedly](https://github.com/embedly/embedly-jquery).

OP is colored orange, all other nodes are black. If they post more than once, I
give them a random color.  The URL updates to reflect the conversation you are
viewing, so you can share that URL to share the network.


## Why I made this - I love the bottom half of the internet but want to explore it more
I also wanted a quick way to find top comments
through a conversation.  A network visualisation linking responses to parent
posts made sense.

I also love looking social data and conversations online. Reddit is a natural
place to explore.

## Cool things I've noticed so far
It's fun to use this to browse Reddit and find patterns, some confirming what
you would expect.  Looking at an AMA you see much more upvoting and OP responses, as expected.
Looking at an AskReddit you see a lot more upvoting.  Sometimes threads extend
far from the original post, those usually contain several posts by the same
user.

### Some dependencies
This uses Foundation, an icon library from Foundation, jQuery, D3, and Embedly jQuery
