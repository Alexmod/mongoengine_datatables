================
mongoengine-datatables
================
A script for using the jQuery plug-in DataTables server-side processing  with MongoEngine.

Works with Flask and Django. Supports column sorting and filtering by multiple search terms.
Supports ReferenceFields &  EmbeddedDocumentField.


Install
=======
You can install with pip::

pip install mongoengine-datatables

..

Basic Usage (Flask)
===================

param model: The MongoEngine model
param request_args: Passed as Flask request.values.get('args')
param embed_search: For specific search in EmbeddedDocumentField
param q_obj: Additional search results in reference collection
param custom_filter: Additional filter


