CornerCouch
===========

CornerCouch - AngularJS module for CouchDB

**Make sure to check the [Wiki](https://github.com/eddelplus/CornerCouch/wiki) on GitHub for more information**

See an example on my [IrisCouch](http://eddelplus.iriscouch.com/gbook1/_design/app/guestbook.html)
or access the same data cross-site (JSONP) from [my web site](http://www.eddelbuettel.net/html5/guestbook_jsonp.html)

CornerCouch wraps the CouchDB core http APIs for documents, attachments, views, and sessions in three
JavaScript object classes: CouchServer, CouchDB, and CouchDoc. The 'CornerCouch' module exposes a
single resource 'cornercouch', which is the factory for CouchServer objects. CouchDoc is an inner
class of CouchDB and CouchDoc objects are automatically associated with a database.

On the Angular side CornerCouch relies on $http, providing a higher level http/REST interface of
its own, separate from $resource. Its sole dependency is the core AngularJS 'ng' module. jQuery is not
required and not utilized.

CornerCouch has been developed based on Angular.js 1.0.3 and CouchDB 1.2.0.
The upload of attachments depends on the HTML5 File API and does not support IE9 or older.
