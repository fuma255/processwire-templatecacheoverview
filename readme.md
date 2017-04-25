# ProcessWire Template Cache Overview

Caching can help significantly with page render time on resource-heavy pages.
But caching should not be used on templates that need to process constantly changing data,
like from forms or sessions. Also note that URL segments are cachable, but GET and POST vars are not.

Using this module you can view the template cache settings at once. 
E.g. cache status, cache time.
Furthermore it adds the functionality to clear the entire template cache or just the template cache for a given template.
Note that this may cause a temporary delay for one or more requests while pages are re-cached.

!["Screenshot of the module's interface"](https://raw.githubusercontent.com/justb3a/TemplateCacheOverview/master/screen.png)
