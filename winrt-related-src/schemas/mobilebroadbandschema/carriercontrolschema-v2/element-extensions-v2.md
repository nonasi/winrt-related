---
Description: Extensions\_v2
MS-HAID: CarrierControlSchema\_v2.element\_Extensions\_v2
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/apps
Search.Product: eADQiWindows 10XVcnh
title: Extensions\_v2
ms.assetid: 698df4b4-94ce-4516-bcbc-92cae505c405
author: mcleblanc
ms.author: markl
keywords: windows 10
---

# Extensions\_v2


Defines additional properties and settings in a subscriber's carrier provisioning file. [**Extensions\_v2**](element-extensions-v2.md) is the unique root element of the [CarrierControlSchema\_v2](schema-root.md) provisioning file.

## Element hierarchy

**&lt;Extensions\_v2&gt;**

## Syntax

``` syntax
<Extensions_v2>

  <!-- Child elements -->
  CarrierNetworkMetadata?,
  AdditionalPDPContexts?

</Extensions_v2>
```

### Key

`?`   optional (zero or one)

## Attributes and Elements


### Attributes

None.

### Child Elements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Child Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>[AdditionalPDPContexts](element-additionalpdpcontexts.md)</td>
<td><p>Defines additional Packet Data Protocol (PDP) contexts in a subscriber's carrier provisioning file.</p></td>
</tr>
<tr class="even">
<td>[CarrierNetworkMetadata](element-carriernetworkmetadata.md)</td>
<td><p>Defines the network properties and settings in a subscriber's carrier provisioning file.</p></td>
</tr>
</tbody>
</table>

 

### Parent Elements

This outermost (document) element may not be contained by any other elements.

## See also


[CarrierControlSchema schema](https://msdn.microsoft.com/library/windows/apps/hh868312)

[CarrierControlSchema\_v2 schema](schema-root.md)

## Requirements

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Namespace</p></td>
<td><p>http://www.microsoft.com/networking/CarrierControl/v2</p></td>
</tr>
</tbody>
</table>

 

 


