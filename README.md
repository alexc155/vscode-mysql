# MySQL

[![Marketplace Version](https://vsmarketplacebadge.apphb.com/version-short/alexc155.vscode-mysql.svg)](https://marketplace.visualstudio.com/items?itemName=alexc155.vscode-mysql) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/alexc155.vscode-mysql.svg)](https://marketplace.visualstudio.com/items?itemName=alexc155.vscode-mysql) [![Rating](https://vsmarketplacebadge.apphb.com/rating-short/alexc155.vscode-mysql.svg)](https://marketplace.visualstudio.com/items?itemName=alexc155.vscode-mysql) [![Build Status](https://travis-ci.org/alexc155/vscode-mysql.svg?branch=master)](https://travis-ci.org/alexc155/vscode-mysql)

MySQL management tool

## Features

* Manage MySQL Connections (support SSL connection)
* List MySQL Servers
* List MySQL Databases
* List MySQL Tables
* List MySQL Columns
* Run MySQL Query

## Usage

* To add MySQL connection: in Explorer of VS Code, click "MYSQL" in the bottom left corner, then click the `+` button, then type host, user, password, port and certificate file path (optional) in the input box.

![connection](images/connection.png)

* To run MySQL query, open a SQL file first then:
  * right click on the SQL file, then click `Run MySQL Query` in editor context menu (Note: you could also run the selected SQL query)
  * or use shortcut `Ctrl+Alt+E`
  * or press `F1` and then select/type `Run MySQL Query`

![run](images/run.png)

* To create a new MySQL query or change active MySQL connection (You could see active MySQL connection in status bar):
  * right click on a MySQL server, then click `New Query`
  * or right click on a MySQL database, then click `New Query`

![newquery](images/newquery.png)

## Settings

* `vscode-mysql.maxTableCount`: The maximum table count shown in the tree view. (Default is **500**)

## Change Log

See Change Log [here](CHANGELOG.md)

## Issues

Currently, the extension is in the very initial phase. If you find any bug or have any suggestion/feature request, please submit the [issues](https://github.com/alexc155/vscode-mysql/issues) to the GitHub Repo.
