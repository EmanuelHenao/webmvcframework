# webmvcframework
PHP MVC framework for bulding web applications with MySQL database.<br><br>
Web MVC Framework offers to developers a complete set of functionalities for rapid development of data intensive web applications. Generally, it provides services for system decomposition that developers can do at different levels when coding a complex web application. Firstly it entire implements services for realizing the MVC design pattern decomposition. However, this is not the only feature provided by the Framework for acting application decomposition.<br>
The Component Based Development, used for building many Framework’s features, permits to developers another more level of applications decomposition and software reuse. Framework’s components, in fact, realizes common Aspects that can occurs, in a similar way, into different web applications. Many of these aspects are regarding database, for example: data listing, data listing and sorting, data listing and filtering, data listing and pagination, record management and common table’s operations for select, insert, delete and update records. Framework offers a set of pre-built components for implementing the necessary server logic for these common database management aspects.These components are itself MVC objects with a Controller, are easy to use and developers can aggregate them into a root controller by using a composite criteria for building complex application pages. A component GUI can also easily adapted or replaced to reflect the application’s experience simply by modifying or replacing its HTML template with a custom one. Component’s server logic will remain fully reusable without the need of any source code modifications.<br>
See the docs folders for more information<br/><br/>
<h2>How to install</h2>
To install download and copy it into an Apache web folder. Then go to the config directory and modify application.config.php according to your MySQL server configuration and Apache web folder you used to deploy your application.<br/><br/>
By default framework is provided with simple examples.<br>
I will provide further examples in the future to illustrate all its functionalities.<br/><br/>
<h2>How to autogenerate PHP Model classes from your MySQL database</h2>
The util directory contains a file named <strong>app_create_beans.php</strong>. <br>
Run it from your browser or from command line for executing ORM autogeneration engine<br>
Warning ! <br>
Before running it you must configure MySQL access parameters by modifying <strong>util\mysqlreflection\mysqlreflection.config.php</strong> according to your MySQL configuration.<br>
After running the generation utility the autogenerated PHP classes were placed into the models\beans directory.
