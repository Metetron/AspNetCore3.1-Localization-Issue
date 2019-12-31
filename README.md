# AspNetCore3.1-Localization-Issue
Project for displaying the issue with IStringLocalizer

## Problem description

When an IStringLocalizer<T> is injected into a Razor page or a controller, the localizer does not find the corresponding resources.
Instead only the key is displayed in the rendered views.
  
## Sample project

This repository contains three projects:

* Localization_Version_2_2: Project containing the source code that worked with ASP.Net Core 2.2
* Localization_Version_3_1: Project containing the source code that does not work anymore when targeting ASP.Net Core 3.1
* Workaround: Contains a workaround suggested here https://github.com/aspnet/AspNetCore/issues/17733#issue-535676711
