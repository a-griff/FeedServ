# FeedServ
FeedServ is a simple, browser-side RSS and Atom feed reader written entirely
in JavaScript. It requires no server-side scripting, databases, or frameworks.
All feed retrieval and display are performed directly by the web browser.

FeedServ must be hosted on a web server. It will not function correctly
when opened directly from local files (e.g., file:// paths), because modern
browsers block external network access from local pages.

FeedServ can show feed headlines in standard graphical browsers (index.html)
or in text-based browsers such as lynx, links, or w3m (index-text.html).
