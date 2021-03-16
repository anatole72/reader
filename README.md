# reader
RSS_reader

app which will be able to fetch,
process, and show the user several RSS feeds. RSS is a web feed,
which allows users to access updates to online content in a
standardized and computer-readable format. They are normally used
in news websites, news aggregators, forums, and blogs to represent
updated content and it fits very well to the mobile world, as we can
have all the content from different blogs or newspapers just by
entering the feed's URL in one app.
An RSS feed reader will serve as an example on how to fetch
external data, store it, and display it to the user, but at the same time,
will add a bit of complexity to our state tree; we will need to store
and manage lists of feeds, entries, and posts. On top of that, we will
introduce MobX as a library to manage all those state models and
update our views, based on the user's actions. Therefore, we will
introduce the concept of actions and stores, which is widely used in
some of the most popular state management libraries, such as Redux
or MobX.
