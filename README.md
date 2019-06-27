# DecUI vscode extension

This is a vscode extension for the VCMP UI library [DecUI](https://github.com/newk5/decui). It contains many snippets that make it easier to do UI development in VCMP using the DecUI library. You need to have the Squirrel support extension installed for this extension to work. You can get it [here](https://marketplace.visualstudio.com/items?itemName=deldrid1.SquirrelLanguageExtension).

## Snippets
- **cp** - prints to the console: Console.Print("")
- **vec** - creates a new Vector
- **col** - creates a new Colour
- **vs** - creates a new VectorScreen
- **lbl** - creates a new GUILabel
- **btn** - creates a new GUIButton
- **prog** : creates a new GUIProgressBar
- **scroll** : creates a new GUIScrollbar
- **canv** : creates a new GUICanvas
- **spr** : creates a new GUISprite
- **tbl** : creates a new DataTable
- **lst** : creates a new GUIListbox
- **window** : creates a new GUIWindow
- **memo** : creates a new GUIMemobox
- **edt** : creates a new GUIEditbox
- **chk** : creates a new GUICheckbox
- **pop** : creates a new Popup
- **combo** : creates a new ComboBox
- **kb** : creates a new KeyBind
- **tabs** : creates a new Tabview
 
All of the snippets above for creating components have a variant where if you prepend "f" to any of them, it will instead output the code for fetching the component instead of creating the component. 

For example, using the **lbl** snippet will output:
```javascript
//creates a new label with id: newLabelID
UI.Label({
   id = "newLabelID"  
   Text = "labelText" 
})
```
Using **flbl** will output:
```javascript
//fetches an existing label with id: newLabelID
UI.Label("newLabelID")
```
