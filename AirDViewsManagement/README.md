# Extensions Views Management

1. Introduction

Extension name: AirdViewsManagement

This extension makes it easy to manage the opening and closing, and therefore the visibility, of the different views, including a history.

The extension gives the possibility of opening several predefined views in one block during initialization, either by the name of the view or by its position in the initialization list.

In addition, the history provided allows you to go back to previous views (either by an event or by the BACK key)

Version 1

2. Properties of the designer

None

3. Blocks
https://user-images.githubusercontent.com/64545586/92897401-7311d980-f41d-11ea-9371-f6daa27ad2bb.JPG

whenpreview
100%
75%
50%

add
100%
75%
50%

clearhistory
100%
75%
50%

closeall
100%
75%
50%

countHistory
100%
75%
50%
 initialise
100%
75%
50%
 isopen
100%
75%
50%
 openn
100%
75%
50%
 preview
100%
75%
50%

4. Documentation
4.1 Events

whenopen
100%
75%
50%

Triggered when the method Open is started

whenpreview
100%
75%
50%

Triggered when the method Previous is started

4.2 Methods
add
100%
75%
50%

Insert view(s) into the list of views. You can put a list of view or just one view.

clearhistory
100%
75%
50%

Empty history

closeall
100%
75%
50%

Close all views initialized in the listView.

countHistory
100%
75%
50%

Return the number of “pages” in the history.

initialise
100%
75%
50%

Mandatory method before using other methods.
You can put a list of views or just one view.

isopen
100%
75%
50%

Return true or false.
You can test a view, a list of views, or even a position in the listView.

openn
100%
75%
50%

Open a view, a list of views, a group of views according to its position in the listView.

preview
100%
75%
50%

Opens the previously opened view(s), depending on the history.

5. Downloads
GITHUB
AIX
APK

Translated from French
