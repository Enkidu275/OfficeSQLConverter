# OfficeSQLConverter
converts excel documents to mysql-initializing commands.

To use this, place the other document text into the excel vba modules.
Super simple code. This is only here for display purposes for Delloite.

The mysql commands would then be run in a shell script or whatever it is you're using to host your database.

Once you have the module installed, make the top row column names and tabs different tables. Tables will be named after the tab names, and column names will be named after the headers. By default, the primary key is the first one. Override this behavior by making a column header bold. Use =MYSQL("databasename") to run it, and the resulting code will be created in a file in your directory.
