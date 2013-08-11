jOrder
=====

*This project is a fork of [old jOrder by Dan Stocker](https://github.com/danstocker/jorder/tree/legacy)*

**JavaScript data management redefined**

jOrder is a lightweight client side database featuring index-based queries and update operations on JSON tables.

Its aim is to shift data manipulation towards the client side by being fast and efficient.

Current version: **1.2.2**

What's new
---------------

- You can search for a lot of words at once + specify if they should occur together or at least one of them (AND, OR). See jOrder.table API (method where(...)) in [wiki](https://github.com/mateuszmazurek/jorder/wiki).
- Now if index type is $constants.text field can be a function. It means that keys to index can be generated on-the-fly. More in [wiki](https://github.com/mateuszmazurek/jorder/wiki) examples.

Highlights
------------

- Fast, index based queries on JSON tables
- Data manipulation preserving index integrity

Why?
-------

**Thick clients are back in fashion.**

Because having the cake and eating it too is nice:

- **User experience**: Querying data locally is faster than fetching from the server. Yes, even at 50.000 rows. And yes, in practically any browser.
- **Saving money**: Massively reduced traffic and CPU time cost less.

What for?
-------------

Here's a few examples of what jOrder is ideal for:

- Populating grid controls
- Insanely fast paging
- Live search
