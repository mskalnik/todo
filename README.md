# Todo Repository

## Explanation

Repository for testing new technologies. It contains simple todo apps written by the same criteria. Every folder is a
new standalone project, naming will describe the technology used.

## Criteria

* Items have the following properties:
  * Name
  * Description
  * Two states `done` or `not done`
* Ability to create new items that will be in the `not done` state by default
* Ability to update all item properties
* Ability to delete:
  * One item by ID
  * All items by status
  * All items
* List of all items with an option to filter items by state
* State has to be persisted, once the app it restarted it should restore the previous state
