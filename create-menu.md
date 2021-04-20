# Create Menu

- Create Menu
    - [Create a menu](#create-menu)
    - [Settings available](/docs/{{version}}/menu-settings)
    
<a name="create-menu"></a>
### Create a menu

To create your menu you can use the [RMenu](/docs/{{version}}/rmenu) utility supplied with RageUI or else use a variable, if you want to understand how it works I invite you to check for yourself on the documentation.

1. #### New method
		local mainMenu = RageUI.CreateMenu("Menu title", "Menu description")

5. #### Old method
 		RMenu.Add('showcase', 'main', RageUI.CreateMenu("RageUI", "showcase"))
