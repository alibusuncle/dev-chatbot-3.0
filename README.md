Chatbot-3.0
=================

### Table of Contents

* [Publish CSV to CDI](#publish-csv-to-cdi)
* [Recommend Products V2](#recommend-products-v2)

### API Endpoints

#### Publish CSV to CDI
<a name="publish-csv-to-cdi"></a>

This endpoint is designed to publish a CSV file to CDI, supporting both GET and POST methods.

**GET Method**

* URL: `{{host}}/publishCsvToCdi`
* Request Query Parameters:
	+ `modelName`: A string representing the model name.
	+ `where`: A string representing the where clause.

**POST Method**

* URL: `{{host}}/publishCsvToCdi`
* Request Body:
	+ `modelName`: A string representing the model name.
	+ `where`: A string representing the where clause.

#### Recommend Products V2
<a name="recommend-products-v2"></a>

This endpoint is designed to recommend products based on various parameters, supporting the GET method.

**GET Method**

* URL: `{{host}}/recommendProductsV2`
* Request Query Parameters:
	+ `segment`: A string representing the segment, default is 'NT'.
	+ `category_id`: A string representing the category ID, default is 'default'.
	+ `uid`: A string representing the user ID.
	+ `language_code`: A string representing the language code, default is 'en'.
	+ `page_limit`: An integer representing the page limit, default is 3.

To access these functions, simply hit the corresponding endpoints with the required parameters.
