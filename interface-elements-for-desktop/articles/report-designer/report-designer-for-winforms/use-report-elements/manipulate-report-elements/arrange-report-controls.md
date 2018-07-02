---
title: Arrange Report Controls
author: Anna Gubareva
---
# Arrange Report Controls

The following tools allow you to control report elements' size, location, alignment and to maintain the distance between them:

* **Rulers**
	
	The Report Designer provides horizontal and vertical rulers to help you determine report elements' size and location.
	
* **Layout Toolbar**
	
	You can align report controls using the **Layout** toolbar tab.

* **Snapping**
	
	A report's **Snapping Mode** property defines whether automatic report control snapping is enabled and allows you to switch between snapping to a grid and/or snap lines.
	
	* **Snap Grid**
		
		The report's editing surface displays a visual grid that allows you to determine elements' size and location in a report. Use the **Snap Grid Size** and **Snap Grid Step Count** properties to customize the grid's settings.
		
		You can hide the grid by setting the **Draw Grid** property to **false**.
		
		> [!NOTE]
		> To select the [measurement units](../../configure-design-settings/change-a-report's-measurement-units.md) applied to the grid size, use the **Report Unit** property.
		
		Use the context menu to align the selected controls to the grid's cells.
				
		Relocating a report control using the mouse or ARROW keys automatically aligns it to the nearest grid cell.
		
		Hold down ALT when using the mouse and CTRL when using the keyboard to avoid snapping to the grid when moving or resizing controls.

	* **Snap Lines**
		
		The Report Designer displays snap lines when you move or resize report controls, which enables you to align these controls to other report elements.
				
		When you move a report control using the ARROW keys or resize it by pressing SHIFT+ARROW, this control is aligned to the nearest report element in that direction using snap lines.
		
		To maintain a uniform distance between elements in a report, use report elements' **Snap Line Margin** property and the band's or panel's **Snap Line Padding** property.
		
		Hold down ALT when using the mouse and CTRL when using the keyboard to avoid snapping controls that are being relocated or resized.