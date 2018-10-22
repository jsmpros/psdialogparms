# psdialogparms

PeopleCode Dialog Parameters Application Classes

## About

The purpose of this project is to provide structure to PeopleSoft dialog, grouplet, and menu parameters. These parameters are passed as semi-colon/@ delimited key/value pairs. Since fields and values are embedded in strings, the PeopleCode compiler will not validate parameters or syntax.

The contents of this project is for demonstration and training purposes only and comes with no warranty. Use at your own risk.

## Source Structure

The Application Classes in the src directory originally belonged to an application package named `JSM_DIALOGS`. Classes were child members of the path `JSM_DIALOGS:Parameters`. You are welcome to change the class and package structure. Just be sure to update internal code references, such as imports and introspection statements.