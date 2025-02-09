# Python API

## Introduction

The Python API are the set of class, functions and methods that are available to the user to interact with the autorigging system. The API is designed to be simple and easy to use, all the tools that were used to create the rig can be accessed through the API.

## Namespace

The API is divided in two main namespaces: `WombatAutoRig.src.core` and `WombatAutoRig.src.ui`. The first one contains all the classes and functions that are used to create the rig, the second one contains all the classes and functions that are used to create the UI.

## WombatAutoRig.src.core
| Namespace                                                  | Description                                                                              |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
|  [`WombatAutoRig.src.core.AutorigHelper`](#)               | A set of functions that are used to interact with the autorigging system.                |
|  [`WombatAutoRig.src.core.Bookmark`](#)                    | A class that is used to store nodes into maya's bookmarks.                               |
|  [`WombatAutoRig.src.core.CartoonEye`](#)                  | A class that is used to create a cartoon eye system.                                     |
|  [`WombatAutoRig.src.core.Color`](#)                       | A class that is used to set the color of an object or a list of objects.                 |
|  [`WombatAutoRig.src.core.ColumnRibbon`](#)                | A class that is used to create a column ribbon system.                                   |
|  [`WombatAutoRig.src.core.Controllers`](#)                 | A class that is used to create and replace a bunch of pre-defined controllers.           |
|  [`WombatAutoRig.src.core.FileHelper`](#)                  | A set of functions that are used to interact with the file system.                       |
|  [`WombatAutoRig.src.core.JointPlacement`](#)              | A set of functions that are used to help with joint placement.                           |
|  [`WombatAutoRig.src.core.MatchingIkFk`](#)                | A set of functions that are used to match the ik and fk systems.                         |
|  [`WombatAutoRig.src.core.MatrixConstraint`](#)            | A class that is used to create a matrix constraint system.                               |
|  [`WombatAutoRig.src.core.NonRollMatrix`](#)               | A class that is used to create a non roll matrix system.                                 |
|  [`WombatAutoRig.src.core.Offset`](#)                      | A set of functions that are used to create offset groups.                                |
|  [`WombatAutoRig.src.core.PoleVector`](#)                  | A class that is used to create a pole vector system.                                     |

## WombatAutoRig.src.ui
| Namespace                                                  | Description                                                                              |
| ---------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
|  [`WombatAutoRig.src.ui.DlgAddToShelf`](#)                 | A dialog that is used to add the autorigging system to maya's shelf.                     |
|  [`WombatAutoRig.src.ui.DlgCartoonEye`](#)                 | A dialog to create a cartoon eye system.                                                 |
|  [`WombatAutoRig.src.ui.DlgColor`](#)                      | A dialog To set the color of an object or a list of objects.                             |
|  [`WombatAutoRig.src.ui.DlgControllers`](#)                | A dialog that is used to create and replace a bunch of pre-defined controllers.          |
|  [`WombatAutoRig.src.ui.DlgMatchIkFk`](#)                  | A dialog that is used to match the ik and fk systems.                                    |
|  [`WombatAutoRig.src.ui.DlgMatrixConstraint`](#)           | A dialog that is used to create a matrix constraint system.                              |
|  [`WombatAutoRig.src.ui.DlgNewTemplate`](#)                | A dialog that is used to create a new autorigging template.                              |
|  [`WombatAutoRig.src.ui.DlgRibbon`](#)                     | A dialog that is used to create a simple ribbon.                                         |
|  [`WombatAutoRig.src.ui.DlgRibbonOnCurves`](#)             | A dialog that is used create a ribbon on curves.                                         |
|  [`WombatAutoRig.src.ui.DlgSpineRibbon`](#)                | A dialog that is used create a spine ribbon.                                             |
|  [`WombatAutoRig.src.ui.DlgTransferSkinToNewGeo`](#)       | A dialog that is used to transfer the skin from one geometry to another.                 |
|  [`WombatAutoRig.src.ui.MainWindow`](#)                    | The main window of the autorigging system.                                               |