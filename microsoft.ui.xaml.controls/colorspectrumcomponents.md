---
-api-id: T:Microsoft.UI.Xaml.Controls.ColorSpectrumComponents
-api-type: winrt enum
ms.custom: RS5
---
<!-- Enumeration syntax.
public enum ColorSpectrumComponents : int 
-->

# Microsoft.UI.Xaml.Controls.ColorSpectrumComponents

## -description

Defines constants that specify how the Hue-Saturation-Value (HSV) color components are mapped onto the [ColorSpectrum](../microsoft.ui.xaml.controls.primitives/colorspectrum.md).

## -enum-fields

### -field ValueSaturation:5

Value is mapped to the X axis. Saturation is mapped to the Y axis.

### -field ValueHue:1

Value is mapped to the X axis. Hue is mapped to the Y axis.

### -field SaturationValue:4

Saturation is mapped to the X axis. Value is mapped to the Y axis.

### -field SaturationHue:3

Saturation is mapped to the X axis. Hue is mapped to the Y axis.

### -field HueValue:0

Hue is mapped to the X axis. Value is mapped to the Y axis.

### -field HueSaturation:2

Hue is mapped to the X axis. Saturation is mapped to the Y axis.

## -remarks

The order of the two components in each value indicates the X/Y axis when the spectrum is a box, or the degree/radius when the spectrum is a ring.

## -see-also

[ColorPicker.ColorSpectrumComponents](colorpicker_colorspectrumcomponents.md)
[ColorSpectrum.Components](../microsoft.ui.xaml.controls.primitives/colorspectrum_components.md)

## -examples
