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

![whenopen](https://user-images.githubusercontent.com/64545586/92897401-7311d980-f41d-11ea-9371-f6daa27ad2bb.JPG)

![whenpreview](https://user-images.githubusercontent.com/64545586/92897402-7311d980-f41d-11ea-8afc-30e44d2e5172.JPG)

![add](https://user-images.githubusercontent.com/64545586/92897380-71481600-f41d-11ea-8e69-242377ad6762.JPG)

![clearhistory](https://user-images.githubusercontent.com/64545586/92897386-71481600-f41d-11ea-9187-6f78283d81dc.JPG)

![closeall](https://user-images.githubusercontent.com/64545586/92897388-71e0ac80-f41d-11ea-83af-55705bbc496a.JPG)

![countHistory](https://user-images.githubusercontent.com/64545586/92897389-71e0ac80-f41d-11ea-8c45-59116ece49cf.JPG)

![initialise](https://user-images.githubusercontent.com/64545586/92897391-72794300-f41d-11ea-88ec-80e69061079c.JPG)

![isopen](https://user-images.githubusercontent.com/64545586/92897393-72794300-f41d-11ea-882a-77c325408e36.JPG)

![openn](https://user-images.githubusercontent.com/64545586/92897397-72794300-f41d-11ea-97d6-5b10c10b5ce2.JPG)

![preview](https://user-images.githubusercontent.com/64545586/92897400-7311d980-f41d-11ea-9194-38849dfe51f2.JPG)


4. Documentation
4.1 Events

![whenopen](https://user-images.githubusercontent.com/64545586/92897401-7311d980-f41d-11ea-9371-f6daa27ad2bb.JPG)
Triggered when the method Open is started

![whenpreview](https://user-images.githubusercontent.com/64545586/92897402-7311d980-f41d-11ea-8afc-30e44d2e5172.JPG)
Triggered when the method Previous is started


4.2 Methods

![add](https://user-images.githubusercontent.com/64545586/92897380-71481600-f41d-11ea-8e69-242377ad6762.JPG)
Insert view(s) into the list of views. You can put a list of view or just one view.

![clearhistory](https://user-images.githubusercontent.com/64545586/92897386-71481600-f41d-11ea-9187-6f78283d81dc.JPG)
Empty history

![closeall](https://user-images.githubusercontent.com/64545586/92897388-71e0ac80-f41d-11ea-83af-55705bbc496a.JPG)
Close all views initialized in the listView.

![countHistory](https://user-images.githubusercontent.com/64545586/92897389-71e0ac80-f41d-11ea-8c45-59116ece49cf.JPG)
Return the number of “pages” in the history.

![initialise](https://user-images.githubusercontent.com/64545586/92897391-72794300-f41d-11ea-88ec-80e69061079c.JPG)
Mandatory method before using other methods.
You can put a list of views or just one view.

![isopen](https://user-images.githubusercontent.com/64545586/92897393-72794300-f41d-11ea-882a-77c325408e36.JPG)
Return true or false.
You can test a view, a list of views, or even a position in the listView.

![openn](https://user-images.githubusercontent.com/64545586/92897397-72794300-f41d-11ea-97d6-5b10c10b5ce2.JPG)
Open a view, a list of views, a group of views according to its position in the listView.

![preview](https://user-images.githubusercontent.com/64545586/92897400-7311d980-f41d-11ea-9194-38849dfe51f2.JPG)
Opens the previously opened view(s), depending on the history.



Translated from French
