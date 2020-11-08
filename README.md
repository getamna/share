# Share Links
This is an easy way to share multiple links on the website, and name a group of Tabs. It is used by [Amna](https://getamna.com) to generate tab share links.

You may try it out at [share.getamna.com](http://share.getamna.com/share/?code=Z3JvdXA9TmV3cyBXZWJzaXRlcztbbmV3cy5nb29nbGUuY29tXWh0dHA6Ly9uZXdzLmdvb2dsZS5jb207W25ld3MueWNvbWJpbmF0b3IuY29tXWh0dHA6Ly9uZXdzLnljb21iaW5hdG9yLmNvbTtbdGltZXMuY29tXWh0dHA6Ly90aW1lcy5jb207W3dzai5jb21daHR0cDovL3dzai5jb207W2Nubi5jb21daHR0cDovL2Nubi5jb207)

### How it Works

All Data is stored in the URL as a Base64 encoded string of this format:
````
group={Group Name};[website title]http://{url};[website title]{http://url}"
````

Favicons are fetched via the [Google Favicon API](http://www.google.com/s2/favicons?domain=google.com)

### Future
We plan to add URL shortening in the future with a helper service. We may have to stand up our own server to help with this.
