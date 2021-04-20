# Create SubMenu

- Create SubMenu
    - [Create a sub menu](#create-submenu)
    - [Settings available](/docs/{{version}}/menu-settings)
    
<a name="create-submenu"></a>
### Create a SubMenu

To create your sub menu you can use the [RMenu](/docs/{{version}}/rmenu) utility supplied with RageUI or else use a variable, if you want to understand how it works I invite you to check for yourself on the documentation.

1. #### New method (variable)
		local subMenu = RageUI.CreateMenu(mainMenu, "Menu title", "Menu description")
2. #### Old method (RMenu)
		RMenu.Add('showcase', 'submenu', RageUI.CreateSubMenu(RMenu:Get('showcase', 'main'), "RageUI", "showcase"))
