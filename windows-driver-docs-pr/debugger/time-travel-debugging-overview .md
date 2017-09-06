---
title: Time Travel Debugging - Overview
description: This section describes time travel debugging.
ms.author: windowsdriverdev
ms.date: 09/06/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

> [!NOTE]
> The information in this topic is preliminary. Updated information will be provided in a later release of the documentation. 
>


# ![Small logo on windbg preview](images/windbgx-preview-logo.png) Time Travel Debugging - Overview

TBD TBD TBD

What is Time Travel Debugging?
What is a trace? 
    How big can they get and such
What is an index - .IDX file and it could be big

Basics of incompatibilities 


WinDbg Preview is a brand-new version of WinDbg with more modern visuals, faster windows, a full-fledged scripting experience, built with the extensible debugger data model front and center. WinDbg Preview is using the same underlying engine as WinDbg today, so all the commands, extensions, and workflows you're used to will still work as they did before.

Review these topics to install and configure WinDbg Preview.

- [Time Travel Debugging - Recording](time-travel-debugging-recording.md)
- [Time Travel Debugging - Playback](time-travel-debugging-playback.md)
- [Time Travel Debugging - Working with trace files](time-travel-debugging-trace-files.md)
- [Time Travel Debugging - Troubleshooting](time-travel-troubleshooting.md)

These topics describe addtional advanced fucnctionality in time travel debugging. 

- [Time Travel Debugging - Extension commands](time-travel-debugging-extension-commands.md)
- [Time Travel Debugging - JavaScript Automation](time-travel-debugging-javascript-automation.md)
- [Time Travel Debugging - TTDAnalyze](time-travel-debugging-ttdanalyze.md)
- [Time Travel Debugging - Trace File object model](time-travel-debugging-object-model.md)
- [Debugger Object model reference - Time Travel Debugging](debugger-object-model-reference-time-travel-debugging.md)


## <span id="providingfeedback"></span>Providing feedback

Your feedback will help guide timt travel development going forward. 

- If you have feedback such as a feature that you really want to see or a bug that makes something difficult, use the Feedback Hub.

![Screen shot of feedback hub showing feedback options including the add new feedback button](images/windbgx-feedback.png)


## Major Features of Time Travel

Here's some of the most notable things that have changed or are new.



### Enhanced data model support

- **Built in data model support** - WinDbg Preview is written with built in data model support and the data model is available through out the debugger.
- **Model window** - The model window gives you an expandable and browsable version of ‘dx’ and ‘dx -g’, letting you create powerful tables on-top of your NatVis, JavaScript, and LINQ queries. 

For more information, see [WinDbg Preview - Data model](windbg-data-model-preview.md).



### New Scripting development UI 

- **Script development UI** - There is now a purpose built scripting window to make developing JavaScript and NatVis scripts easier, with error highlighting and IntelliSense.

For more information, see [WinDbg Preview - Scripting](windbg-scripting-preview.md).




--- 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20[debugger\debugger]:%20Debugging%20Using%20WinDbg%20%20RELEASE:%20%285/15/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



