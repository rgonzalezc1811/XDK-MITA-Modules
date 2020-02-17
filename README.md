# XDK-Workspace: MITA

Project examples of XDK only in MITA. This language is excellent to use when learning XDK and for rapid prototyping processes like hackathones and courses.

## General requirements

1. XDK-Workbench v.3.6.0
2. Bootloader v.0.0.9 or v.1.2.0

## Instructions

#### Using GIT

* To use the modules and projects of repository, clone the current repository into your **XDK-Workspace** folder, usually, the path follows the same pattern on Windows like *`C:\Users\User\XDK-Workspace`* or *`C:\User\XDK-Workspace`* (be careful, not confused with the installation folder, its pattern follows the structure *`C:\XDK-Workbench`*), use the next command:

     * `git clone https://github.com/BlackZuN/XDK-Workspace.git`

* Go to the branch called *development-mita*, use the next command:

     * `git checkout development-mita`

* Open your **XDK-Workbench**.
* Close the *Welcome* page.
* Go to *File* > *Open Projects from File System...*
* On the *Import Projects from File System or Archive* window click on *Directory...*
* Go to the *XDK-Workspace*
* In the *Browse for Folder* window, select the desired project on MITA (the projects follow the structure *projectName****Mita***) and click on *OK*.
* On the *Import Projects from File System or Archive* window click on *Finish*
* Do right click on the MITA project main folder and go to *Properties*.
* Select *C/C++ Build*.
* Click on *Behavior*.
* Click in *Enable parallel build*.
* Select *Use optimal jobs (#)*, that option has the better performance.
* Select the root project folder and right click.
* Select *Build Project*
* When building is finished, go to **XDK Devices** and click in *Flash*

#### Using the ZIP download

* Download the branch *`development-mita`* as a ZIP file.

* Unzip the file.
* Copy the content of *XDK-Workspace-development-mita* folder to the **XDK-Workspace** folder, usually, the path follows the same pattern on Windows like *`C:\Users\User\XDK-Workspace`* or *`C:\User\XDK-Workspace`* (be careful, not confused with the installation folder, its pattern follows the structure *`C:\XDK-Workbench`*)
* Open your **XDK-Workbench**.
* Close the *Welcome* page.
* Go to *File* > *Open Projects from File System...*
* On the *Import Projects from File System or Archive* window click on *Directory...*
* Go to the *XDK-Workspace*
* In the *Browse for Folder* window, select the desired project on MITA (the projects follow the structure *projectName****Mita***) and click on *OK*.
* On the *Import Projects from File System or Archive* window click on *Finish*
* Do right click on the MITA project main folder and go to *Properties*.
* Select *C/C++ Build*.
* Click on *Behavior*.
* Click in *Enable parallel build*.
* Select *Use optimal jobs (#)*, that option has the better performance.
* Select the root project folder and right click.
* Select *Build Project*
* When building is finished, go to **XDK Devices** and click in *Flash*

#### Copying the *application.mita* file

* Open your **XDK-Workbench**.

* Close the *Welcome* page.
* Create a new *MITA project* in the **XDK-Workbench**
    1. Go to *File* >  *New* > *Project...*
    2. Select *XDK* > *Eclipse Mita project* and click on *Next >*
    3. Name it as the current MITA project to copy in the text box *Project name:*
    4. Click on *Finish*
* Browse to the desired project in the remote repository.
* Copy the text of the *application.mita* file
* Paste the text into your *application.mita* generated in the local MITA project.
* Do right click on the MITA project main folder and go to *Properties*.
* Select *C/C++ Build*.
* Click on *Behavior*.
* Click in *Enable parallel build*.
* Select *Use optimal jobs (#)*, that option has the better performance.
* Select the root project folder and right click.
* Select *Build Project*
* When building is finished, go to **XDK Devices** and click in *Flash*

## Version notes v.1.0.0

* Bootloader v.0.0.9 has better performance than v.1.2.0, try to use always the previous version.

* Some WiFi codes are not working in some XDK hardware, some of the causes are still unknown.

## Project status

The project is a own work to have all the XDK codes for events, work and hack developments.
