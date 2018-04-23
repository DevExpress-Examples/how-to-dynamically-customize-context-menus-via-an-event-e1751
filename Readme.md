# How to dynamically customize context menus via an event


<p>This example shows how to customize a context menu for a LayoutPanel via the DockManager.ShowingMenu event. The menu is customized using bar customization actions. In the example, two actions are created:<br />
- a BarButtonItem object represents an action that adds the BarButtonItem object to the menu<br />
- an InsertBarItemLinkAction object represents an action that inserts a bar item link to the menu (in the example, the inserted link represents a separator).</p><p>Actions are added to the event's ActionList parameter and are executed after the ShowingMenu event handler is completed.</p>

<br/>


