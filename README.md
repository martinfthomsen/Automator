# Automator
Creating useful automator scripts for automating workflows and providing quick tranformation of text files 


## Create aumomator workflow ##
This example creates an aumomator workflow that sort lines in the selected text alphabetically and remove doublicates

**Steps**
1. Open Automator on your Mac.
2. Click on "New Document".
3. Select "Quick Action" and click "Choose".
4. In the new window, set "Workflow receives current" to "text".
4. In the new window, tick the box "Output replaces selected text".
5. In the search bar at the top, search for "Run Shell Script" and drag it into the workflow area on the right.
6. In the "Run Shell Script" action, set "Pass input" to "to stdin".
7. In the script area, enter the following script:
   sort -u
8. Save the workflow as "Sort and Unique".

## Use aumomator workflow ##

**Steps**
1. Open any application with selectable text, such as TextEdit or Safari.
2. Select some text.
3. Right-click on the selected text, hover over "Services", and select "Sort and Unique" (or whatever you named the workflow).

The selected text will now be replaced with the sorted and unique output (or whatever your workflow does).

