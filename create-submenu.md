# Create SubMenu

- Create SubMenu
    - [Create a menu](#create-submenu)
    - [Settings available](#settings-available)
    
<a name="create-submenu"></a>
### Create a SubMenu

To create your menu we will use the [RMenu](/docs/{{version}}/rmenu) utility provided with RageUI, if you want to understand how it works I invite you to check by yourself on the documentation.

    RMenu.Add('showcase', 'submenu', RageUI.CreateSubMenu(RMenu:Get('showcase', 'main'), "RageUI", "showcase"))

<a name="settings-available"></a>
### Settings available

<div class="content-list" markdown="1">
 - RMenu:Get('showcase', 'submenu'):DisplayHeader(bool)
 - RMenu:Get('showcase', 'submenu'):DisplayGlare(bool)
 - RMenu:Get('showcase', 'submenu'):DisplaySubtitle(bool)
 - RMenu:Get('showcase', 'submenu'):DisplayNavigation(bool)
 - RMenu:Get('showcase', 'submenu'):DisplayInstructionalButton(bool)
 - RMenu:Get('showcase', 'submenu'):SetTitle(string)
 - RMenu:Get('showcase', 'submenu'):SetSubtitle(string)
 - RMenu:Get('showcase', 'submenu'):SetPageCounter(string)
 - RMenu:Get('showcase', 'submenu'):SetPosition(int, int)
 - RMenu:Get('showcase', 'submenu'):SetSizeWidth(int)
 - RMenu:Get('showcase', 'submenu'):GetStyleSize()
 - RMenu:Get('showcase', 'submenu'):SetCursorStyle(int)
 - RMenu:Get('showcase', 'submenu'):ResetCursorStyle()
 - RMenu:Get('showcase', 'submenu'):UpdateCursorStyle()
 - RMenu:Get('showcase', 'submenu'):RefreshIndex()
 - RMenu:Get('showcase', 'submenu'):SetTotalItemsPerPage(int)
 - RMenu:Get('showcase', 'submenu'):SetRectangleBanner(int, int, int, int)
 - RMenu:Get('showcase', 'submenu'):SetSpriteBanner(string, string)
 - RMenu:Get('showcase', 'submenu'):Closable(boolean)
</div>
