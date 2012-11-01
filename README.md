# Google Closure Library Snippets

Sublime plugin with snippets for the [Google Closure Library](https://developers.google.com/closure/library/)

## Install

Install with [Package Control](http://wbond.net/sublime_packages/package_control)

## Getting started

Just type `cl` on a javascript document and work with autocomplete.

The snippets are namespaced based on functionality, at most you'll have to type 4 chars and `Enter`:

<table>
  <tr><th>snippet</th><th>Category</th><th>Description</th></tr>
  <tr><td><strong>clareach</strong>      </td><td>Arrays   </td><td><code>goog.array.forEach()</code></td></tr>
  <tr><td><strong>clevlisten</strong>    </td><td>Events   </td><td>Event listener (<code>goog.event.listen()</code>)</td></tr>
  <tr><td><strong>clevdispatch</strong>  </td><td>Events   </td><td>Dispatch an event, verbose version</td></tr>
  <tr><td><strong>clevcb</strong>        </td><td>Events   </td><td>Callback function declaration for events, including block docs</td></tr>
  <tr><td><strong>cldispose</strong>     </td><td>Generic  </td><td>dispose internal declaration (<code>.disposeInternal = function()</code>)</td></tr>
  <tr><td><strong>clfn</strong>          </td><td>Generic  </td><td>Default function declaration with a logger</td></tr>
  <tr><td><strong>clsingle</strong>      </td><td>Generic   </td><td>Singleton declaration (<code>goog.addSingletonGetter()</code>)</td></tr>
  <tr><td><strong>cltypedef</strong>     </td><td>Generic   </td><td>A very verbose type definition with weird annotation cases</td></tr>
  <tr><td><strong>clenum</strong>        </td><td>Generic   </td><td>Enum declaration</td></tr>
  <tr><td><strong>clclassev</strong>     </td><td>New files</td><td>New class boilerplate with events inheritance</td></tr>
  <tr><td><strong>clobjeach</strong>     </td><td>Objects  </td><td><code>goog.object.forEach()</code></td></tr>
</table>

## Contributing
I am using this package as a helper for my workflow with Closure Library, feel free to do the same by submitting snippets that you use in yours.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
© [Thanasis Polychronakis](https://github.com/thanpolas)
