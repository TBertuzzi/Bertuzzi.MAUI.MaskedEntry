# Bertuzzi.MAUI.MaskedEntry

Use mask in your MAUI apps

When we need to use masks in MAUI we end up customizing a control or using behaviors.

MaskedEntry is a custom entry to use any type of mask. just use X between the sequence of characters you want to configure.

X can be used both to demonstrate where values ​​should be in the masks, and to limit the amount of characters in a field.

###### This is the component, works on iOS, Android and UWP.

**NuGet**

|Name|Info|
| ------------------- | :------------------: |
|Bertuzzi.MAUI.MaskedEntry|[![NuGet](https://img.shields.io/badge/nuget-1.0.0-blue.svg)](https://www.nuget.org/packages/Bertuzzi.MAUI.MaskedEntry/)|


**Platform Support**

Bertuzzi.MAUI.MaskedEntry is a MAUI library.

## Setup / Usage

Does not require additional configuration. Just install the package in the shared project and use.

You just need to add the reference in your xaml file.

```csharp
     xmlns:control="clr-namespace:Bertuzzi.MAUI.MaskedEntry;Bertuzzi.MAUI.MaskedEntry"
```

**Sample**

```csharp
    <StackLayout>
        <Label Text="Phone"></Label>
        <control:MaskedEntry Placeholder="Phone" Mask="(XX)XXXX-XXXX" Keyboard="Numeric" ></control:MaskedEntry>
        <Label Text="Number of registration"></Label>
        <control:MaskedEntry Placeholder="Number of registration" Mask="XXXXX.XXXXX.XX-XX  (XX)" ></control:MaskedEntry>
    </StackLayout>
```

The complete example can be downloaded here: <https://github.com/TBertuzzi/Bertuzzi.MAUI.MaskedEntry/tree/master/MAUIMaskedEntrySample>


