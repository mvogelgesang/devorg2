# Mark's App
Below are supplemental instructions for customizing an installation of Salesforce's Agile Accelerator. 

- [Add Work Type to Work Status Detail Page]               (#add-work-type-to-work-status-detail-page)
- [Add Tabs for Other AA Objects]                          (#add-tabs-for-other-aa-objects)
- [Update Column Lookup Search Layout]                     (#update-column-lookup-search-layout)
- [Updating Kanban Board to Relfect Work Status]           (#updating-kanban-board-to-reflect-work-status)


## Add Work Type to Work Status Detail Page
Agile Accelerator associates Work Types (Bug, User Story, etc) to specific Work Statuses. However, using a fresh installation, it can be difficult to determine which Work Types are associated to specific Work Statuses. The steps below walk through the process of updating the page layout for Work Status to display the Work Type relationship.

- Navigate to Setup
- From Setup go to Create > Objects > Work Status
- On the Work Status Custom Object Definition Detail Page, scroll to the Page Layouts section
- Click Edit on the Status Layout
- Drag the Type field into the Status Detail layout
- Save

## Add Tabs for Other AA Objects
Out of the box, Agile Accelerator does not create tabs for a number of objects that are important when customizing the installation. We found it helpful to create tabs for the following Agile Accelerator objects: Work Status, Column, and Column Status Assignment. 

- Navigate to Setup
- From Setup go to Create > Tabs > New
- Select the object of your choice and a color
- Click Next
- Associate the tab to any necessary profiles 
- Associate the tab to the Agile Accelerator App
- Save

Once the tab has been created, it can be added to the default display.
- Navigate to Setup
- From Setup go to Create > Apps > Agile Accelerator 
- Click Edit on the Agile Accelerator App Detail Page
- Add the desired tab to the Selected Tabs list
- Save

## Images
![Bicycle](img/bike.jpg "Optional title")

## Tables
|header1|header2|header3|header4|header5|
|---|---|---|---|---|
|row|text|text|222-333-4444|X|
|row|text|text|444-999-7777| |
|row|text|text|555-000-1234| |
