This is a simple HTML5-based application that loads, parses and analyzes a MySQL slow query log and provides the ability to browse it visually.

![http://mysql-slow-query-log-visualizer.googlecode.com/svn/trunk/images/screenshot-orig.png](http://mysql-slow-query-log-visualizer.googlecode.com/svn/trunk/images/screenshot-orig.png)

There are two main components: The chart and the list.

The chart uses [jQuery Visualize](https://github.com/filamentgroup/jQuery-Visualize) to display a weekly (averaged) graph of the number of slow queries per hour. This will help you to see what times of the day, and what days of the week your database is under the most strain.

The list uses [list.js](https://github.com/javve/list) to display the parsed results from your query log. Using list.js functionality, you can sort by a particular column by clicking on a heading. You can also search and filter your results by entering text in the search box above the list. The chart will update interactively as you search. This way, you can visualize only a particular slice of data.

**Requirements** An HTML5-capable browser. If you are using Google Chrome, the app must be hosted and accessed via a local (or remote) web server in order to parse the log. Firefox 8 works. This currently does not work in Safari 5, and this has not been tested this in IE9.

Many thanks to:

List.js author Jonny Strömberg (www.jonnystromberg.se, www.listjs.com)
https://github.com/javve/list

jQuery Visualize author Scott Jehl, Filament Group scott@filamentgroup.com
https://github.com/filamentgroup/jQuery-Visualize