r5reuse
=======

**Model (r4refine) - View (r6release) - Controller (r5reuse)**

User actions are passed (as HTTP requests, GET or POST methods) to the controller [**r5reuse**]. The controller is a piece of code that handles and processes user input and then reads and makes necessary changes to the model [**r4refine**], which is responsible for the storage and modification of data. (In simple terms, the model consists of the database structure and contents, and the code used to access it.) Then, the controller generates the proper view that will be sent and displayed to user [**r6release**].
[http://www.smashingmagazine.com/2011/10/17/getting-started-with-php-templating]
