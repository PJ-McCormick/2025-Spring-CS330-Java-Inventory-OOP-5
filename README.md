This is the starting code for Assignment 7.

  1. If you are comfortable with Git and GitHub... consider forking this
     repository.

  2. If you would prefer not to work with Git and GitHub... download the
     starting code as a
     [zip file](https://github.com/Old-Dominion-Univ-CS-Dept/2025-Spring-CS330-Java-Inventory-OOP-5/archive/refs/heads/main.zip).

Changes from Assignment 6 (2025-Spring-CS330-Java-Inventory-OOP-4)

Armour:
   Attributes inherited from Equipable are now declared as final and cannot be modified.

Tool:
   Attributes inherited from Equipable as well as speed attrribute are now declared as final and cannot be modified.

Consumable:
   Attributes all now declared as final and cannot be modified.

Item:
   Interface no longer extends Cloneable.  setName() and clone() methods removed.

ArmourCreation:
   fromTokens and fromExisting methods must be changed to use constructor instead of setters that are no longer available.

ToolCreation:
   fromTokens and fromExisting methods must be changed to use constructor instead of setters that are no longer available.

ConsumableCreation:
   fromTokens and fromExisting methods must be changed to use constructor instead of setters that are no longer available.
