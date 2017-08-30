# AngularJS
AngularJS Project
Practise Codes
//.Net Project//
C# and WPF
Make a web form page for user input

Make a simple calculator for addition and subtraction


Core JAVA


Angular JS
Program to validate an email id for a banking client
Download  Angular.min.js  file from angularjs.org
<!doctype html>
<html ng-app>
<Head>
<Script src=”angular.min.js”></script>
<script>
Function ctrl($Scope)
{
$scope.text = ‘abc@example.com’;
}
</script>
</head>
<Body>
<Form name=”myform” ng-controller=”Ctrl”>
Email:
<input type=”email” name=”input” ng-model=”text” required>
<span class=”error” ng-show=”myform.input$error.required>Required!</span>
<span class=”error” ng-show=”myForm.input.$error.email>Notvalidemail!</span>
<tt>{{text}}</tt>
<br/>
</Form>
</Body>
</Html>

Output – When page loads Email – abc@example.com
When Text Box will be empty – Email required
When email address is incorrect – Not valid email
When right email address is entered - Email




IBM DB2

IBM AS 400

Embedded C SQL 

#include<stdio.h>
#include<string.h>
EXEC SQL  BEGIN DECLARE SECTION;
Long station_id;
Long mon;
Float temp;
Float rain;
Char city_name[21];
Long SQLCODE;
EXEC SQL END DECLARE SECTION;
Main()
{
/*the CONNECT statement, if needed, goes here*/
Strcpy(city_name,”Denver”);



Oracle Apps Technical
SQL – Sub-languages, Restricting & Sorting data, Functions, Joins, Sub Queries, Constraints, Views, Sequences & Psuedo Column, Synonyms, Indexes, Set Operators.
PL/SQL – Control Structures, Sub Languages, Error Handling, Procedures, Functions, Packages, Cursors, Triggers, Collections. 
Reports – Objects, Tabular/ Group above/ left reports, XML Publisher, Generate XML file with D2K report/ XML Data Template/ Procedure, Create templates/ Data Definitions, XML Bursting.
Forms – Database Block/ Control Block/ Master Detail Form, Events & Triggers, Calling form from one form to another form, Alerts, Editors, Program Units, Libraries.
Applications – Introduction to ERP, Apps. Architecture, Multi Org. Concepts, Application Object Library (AOL), Functional Flow, Reports, Profile Options & Lookups, Extensions (Forms), Interface, Conversions, Accessing application from backend, Forms Personalisation.
Workflow – Defining process & Components, FYI/ Action Notification, Attributes, Function, HTML Document, Form, Loop, Leave Approval Process, Roles, Customisation.
Oracle Application Framework (OAF) – Architecture, Sample Page Creation, Components, Configuration, Search Pages, DML Pages, Items, Master Details Page, Extensions, Personalisation, Debugging Techniques, Deployment in Instance, Migration from one instance to another, File Upload and Download.
SOA – Implementing SOA with Oracle SOA Suite, Create Composite Application, Manage & monitor SOA Composite Applications, Orchestrating Services with BPEL Component, Working with Human Task Component, Implementing  Business Rules/ Spring Component, File/ FTP/ Database/ JMS/ AQ Adapter, DVM, XREF, MDS/ EDN Networks.

SQL
Create a table to Store weather information station information
CREATE TABLE STATION


