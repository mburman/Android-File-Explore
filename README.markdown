#Android File Explore Implementation

###This is an android file explorer implementation. Features include:
 *  Ability to navigate through multiple heirarchial levels
 *  Ability to select a file & or directory
 *  Currently does not support adding or deleting files
 *  Also does not support opening files once selected. This feature can be implemented very seasily using intents. [Display applications that handle a particular filetype](http://stackoverflow.com/questions/5305731/display-applications-that-can-handle-a-particular-filetype). 

###How to use:
 *  Copy the FileExplore.java source file into your project
 *  Copy the res folder. This contains graphical elements to improve file browsing
 *  In FileExplore.java, search for the comment //Perform action with file picked
 *  Just add your own functionality in there

###Note: 
 *  This is not (yet) an Android Library project. I plan to make it one though in the future and add a few more features. Until then you can get by by modifying the source file. 
 *  A similar library can be found at https://github.com/vaal12/AndroidFileBrowser, which provides a separate Activity (not Dialog) to browse and select files and directories on the phone. That library is based on the code from Android File Explore.

###Licence: 

>   Copyright 2011 Manish Burman

>  Licensed under the Apache License, Version 2.0 (the "License");
>  you may not use this file except in compliance with the License.
>  You may obtain a copy of the License at

>      http://www.apache.org/licenses/LICENSE-2.0

>   Unless required by applicable law or agreed to in writing, software
>   distributed under the License is distributed on an "AS IS" BASIS,
>   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
>   See the License for the specific language governing permissions and
>   limitations under the License.

