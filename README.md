# Google Closure Library Snippets

Sublime plugin with snippets for the [Google Closure Library](https://developers.google.com/closure/library/)

## Install

Install with [Package Control](http://wbond.net/sublime_packages/package_control)

## Getting started

Just type `cl` on a javascript document and work with autocomplete.

The snippets are namespaced based on functionality, at most you'll have to type 4 chars and `Enter`:

<table>
  <tr><th>snippet</th><th>Category</th><th>Description</th></tr>
  <tr><td>***clareach***      </td><td>Arrays   </td><td>goog.array.forEach()</td></tr>
  <tr><td>***clevlisten***    </td><td>Events   </td><td>Event listener (goog.event.listen())</td></tr>
  <tr><td>***clevdispatch***  </td><td>Events   </td><td>Dispatch an event, verbose version</td></tr>
  <tr><td>***clevcb***        </td><td>Events   </td><td>Callback function declaration for events, including block docs</td></tr>
  <tr><td>***cldispose***     </td><td>Generic  </td><td>dispose internal declaration (.disposeInternal = function())</td></tr>
  <tr><td>***clfn***          </td><td>Generic  </td><td>Default function declaration with a logger</td></tr>
  <tr><td>***clsingle***      </td><td>Generic   </td><td>Singleton declaration (goog.addSingletonGetter())</td></tr>
  <tr><td>***cltypedef***     </td><td>Generic   </td><td>A very verbose type definition with weird annotation cases</td></tr>
  <tr><td>***clenum***        </td><td>Generic   </td><td>Enum declaration</td></tr>
  <tr><td>***clclassev***     </td><td>New files</td><td>New class boilerplate with events inheritance</td></tr>
  <tr><td>***clobjeach***     </td><td>Objects  </td><td>goog.object.forEach()</td></tr>
</table>

## Contributing
I am using this package as a helper for my workflow with Closure Library, feel free to do the same by submitting snippets that you use in yours.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
(c) [Thanasis Polychronakis](https://github.com/thanpolas)
