# AzureDevOps-Extension---Dependencies
An extension for Azure DevOps to view a work item and the chain of all predecessors and successors around it.


## Project Title: Azure Dev Ops Extension – Dependency Viewer

## Main Goal:
•	View the chain of predecessors and successors connected to a selected work item

## Desired functionality:
•	From any selected work item (on backlog, sprints, etc.), the ellipsis context menu will have a new menu item “View Dependencies”
•	Opens a popup window to show the map
•	Searches recursively for items that are linked by way of predecessor/successor
•	For an infinite loop, just draw another line.
•	Each node is clickable to be opened
•	Ability to export map as image

## Development roadmap:
•	Get a new menu item added to a work item’s ellipsis
•	On menu item click, pop open a window
•	Draw a node representing the selected item
•	Query for predecessors and successors
•	Store chain in a memory list, with column levels
•	Draw all nodes on the map, aligning to columns and levels
•	Draw lines between the nodes according to their relationships
•	Apply zooming in/out
•	Apply exporting to image, pdf, visio, etc.
•	Apply advanced logic to improve layouts
•	Allow for dragging items around while maintaining the drawn links
