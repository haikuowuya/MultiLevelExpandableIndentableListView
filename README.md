# MultiLevelExpandableIndentableListView

This library display hierarchical data (e.g. comments) in a list view, so that the user can collapse and expand elements. Every element is indented accordingly to its level in the hierarchy.

Here's a video of the SampleApp demo

[![Screenshot of the demo](http://img.youtube.com/vi/dweRJ4Ukb0Q/0.jpg)](http://www.youtube.com/watch?v=dweRJ4Ukb0Q)

### How to import the library in your probject

1. Clone the repository

   `$ git clone https://github.com/defacto133/MultiLevelExpandableIndentableListView.git`

2. In Android Studio open the Module Settings (press F4)
3. Click on the top left green cross to add a new module
4. Select "Import Existing Project"
5. As Source Directory select the directory where you cloned the repository
6. The module :multilevelexpindlistview contains the library so you have to import this. The module :sampleapp is optional and it's a simple example of how to use the library.
7. Click Finish
8. Now in the Modules listing you see a new library module multilevelexpindlistview (and a project module sampleapp if you decided to import that too). In the Modules listing select your project module (usually is called app) and click on Dependencies.
9. Click on the top right green cross and select Module dependency
10. Select :multilevelexpindlistview

Alternatively you can import just the aar file:

1. Clone the repository

   `$ git clone https://github.com/defacto133/MultiLevelExpandableIndentableListView.git`

2. cd to the direcotry created

   `$ cd MultiLevelExpandableIndentableListView/`
   
3. Set a variable with the path to the Android SDK

   `$ export ANDROID_HOME=<path-to-andoid-sdk>`

4. Build the project

    `$ ./gradlew build`

    This will make multilevelexpindlistview-release.aar in
    
    \<path-to-cloned-repo\>/MultiLevelExpandableIndentableListView/multilevelexpindlistview/build/outputs/aar/

5. In Android Studio open the Module Settings (press F4)
6. Click on the top left green arrow to add an new module
7. Select "Import .JAR or .AAR Package" and select the .aar file from step 4
8. Now in the Modules listing you see a new module multilevelexpindlistview. In the Modules listing select your project module (usually is called app) and click on Dependencies.
9. Click on the top right green cross and select Module dependency
10. Select :multilevelexpindlistview
