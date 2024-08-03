# What is this
A way to get data from delijn by using a fully featured library written in Go(lang).

## How do I use this
Install it like you would any other dependency in your Go project. It will be in the official plugin repository once it is in an usable state. Documentation shall be created in due time.

## Contributions
Yes please - once I've written the core and at base functionalities are in an acceptable state.

## FAQ
- Why are you scraping the website? Can't you just use the API?
No I cannot, and I recommend you don't either. The API is underdocumented and incomplete. Half the defined endpoints do not actually exist. The data you get is extremely unpredictable - since the documentation sucks, there's almost no way to know what you can get. Lastly, depending on the endpoint you get your data sometime between a second and two full minutes for no reason. It also seems like your access to the API is a shared pool with other users. The first request I did with a freshly created token got ratelimitted.

- I don't like this, (web)scraping is illegal / gray area
I don't care. Use the API if you want suffer (read the previous question).
