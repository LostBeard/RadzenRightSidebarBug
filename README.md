# RadzenRightSidebarBug


Demonstrates issue:  
[radzen/radzen-blazor#1579](https://github.com/radzenhq/radzen-blazor/issues/1579)  
[Right sidebar does not show on smaller screens and ignores Responsive attribute
](https://github.com/radzenhq/radzen-blazor/issues/1579)

Solution as of Raden.Blazor 4.33.2:  
[from akorchev](https://github.com/radzenhq/radzen-blazor/issues/1579#issuecomment-2203380332)

In `MainLayout.razor` add `width: auto` style to `<RadzenBody>`:  
Ex:  
`<RadzenBody style="width: auto">`
