---
title: MultipleLocale
description: MultipleLocale
ms.assetid: 95590875-2797-4a73-a211-6102305098f9
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# MultipleLocale


The MultipleLocale element specifies if the service metadata package supports multiple locales or not.

## <span id="Usage"></span><span id="usage"></span><span id="USAGE"></span>Usage


``` syntax
<MultipleLocale>
  text
</MultipleLocale>
```

## <span id="Attributes"></span><span id="attributes"></span><span id="ATTRIBUTES"></span>Attributes


There are no attributes.

## <span id="Text_value"></span><span id="text_value"></span><span id="TEXT_VALUE"></span>Text value


A boolean value that is true if the service metadata package supports multiple locales.

## <span id="Child_elements"></span><span id="child_elements"></span><span id="CHILD_ELEMENTS"></span>Child elements


There are no child elements.

## <span id="Parent_elements"></span><span id="parent_elements"></span><span id="PARENT_ELEMENTS"></span>Parent elements


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>[MetadataKey](metadatakey.md)</p></td>
<td><p>The [MetadataKey](metadatakey.md) element specifies the attributes of the device metadata package. These include the following:</p>
<ul>
<li><p>The identifier for each hardware function supported by the device.</p></li>
<li><p>The language-specific locale for the text strings within the package.</p></li>
</ul></td>
</tr>
</tbody>
</table>

 

## <span id="XSD"></span><span id="xsd"></span>XSD


``` syntax
<xs:element name="MultipleLocale" type ="xs:boolean" />
```

## <span id="Remarks"></span><span id="remarks"></span><span id="REMARKS"></span>Remarks


-   To support multiple locales in the service metadata package , Set the MultipleLocale element to **true**. This element is not supported on Windows 7. If this element is not specified, the default value is true.

-   If there is both a single locale service metadata package and a multiple-locale service metadata package on a user's computer, Windows uses the multiple-locale service metadata package, if all other ranking values are the same.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_mb\p_mb%5D:%20MultipleLocale%20%20RELEASE:%20%281/18/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")




