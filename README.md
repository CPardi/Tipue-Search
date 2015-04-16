Tipue Search
------------

Tipue Search is a site search engine jQuery plugin. Tipue Search only needs a browser that supports jQuery. It doesn't need MySQL, PHP or similar. In Static mode it doesn't even need a web server.

To get started, see <http://www.tipue.com/search/>. There's a demo at <http://www.tipue.com/search/demos/static/>.

Modifications
-------------
A auto-completion dialog has been added to the original functionality. The auto-complete suggests pages included in the `tipuesearch` variable. When the user clicks on a suggestion they are taken directly to the relavent page. 

Two additional options have been added:
 * autocomplete, this can take the values true or false. If true, then an autocomplete dialog will appear as the user is typing.
 * categorized, This groups the search results into categories. To specify categories, add a `category : <category_name>` component to the`tipuesearch` variable.

If `autocomplete : true`, then the jquery ui auto-complete widget and all its dependencies must be referenced.

An extra demo has been added to the project to show the new feature.

Documentation
-------------

There's full documentation at <http://www.tipue.com/search/docs/>.

Copyright and license
---------------------

Tipue Search Copyright (c) 2015 Tipue, under the The MIT License.



