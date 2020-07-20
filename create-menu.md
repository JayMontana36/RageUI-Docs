# Create Menu

- Create Menu
    - [Create a menu](#create-menu)
    - [Settings available](#settings-available)
    
<a name="create-menu"></a>
### Create a menu

To create your menu we will use the [RMenu](/docs/{{version}}/rmenu) utility provided with RageUI, if you want to understand how it works I invite you to check by yourself on the documentation.

    RMenu.Add('showcase', 'main', RageUI.CreateMenu("RageUI", "showcase"))

<a name="settings-available"></a>
### Settings available

<div class="content-list" markdown="1">
 - RMenu:Get('showcase', 'main'):DisplayHeader(bool)
 - RMenu:Get('showcase', 'main'):DisplayGlare(bool)
 - RMenu:Get('showcase', 'main'):DisplaySubtitle(bool)
 - RMenu:Get('showcase', 'main'):DisplayNavigation(bool)
 - RMenu:Get('showcase', 'main'):DisplayInstructionalButton(bool)
 - RMenu:Get('showcase', 'main'):SetTitle(string)
 - RMenu:Get('showcase', 'main'):SetSubtitle(string)
 - RMenu:Get('showcase', 'main'):SetPageCounter(string)
 - RMenu:Get('showcase', 'main'):SetPosition(int, int)
 - RMenu:Get('showcase', 'main'):SetSizeWidth(int)
 - RMenu:Get('showcase', 'main'):GetStyleSize()
 - RMenu:Get('showcase', 'main'):SetCursorStyle(int)
 - RMenu:Get('showcase', 'main'):ResetCursorStyle()
 - RMenu:Get('showcase', 'main'):UpdateCursorStyle()
 - RMenu:Get('showcase', 'main'):RefreshIndex()
 - RMenu:Get('showcase', 'main'):SetTotalItemsPerPage(int)
 - RMenu:Get('showcase', 'main'):SetRectangleBanner(int, int, int, int)
 - RMenu:Get('showcase', 'main'):SetSpriteBanner(string, string)
 - RMenu:Get('showcase', 'main'):Closable(boolean)
</div>
