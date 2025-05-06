# How-to-Utilize-.NET-MAUI-OTP-Input-for-Password-Entry

This repository contains a sample explaining how to utilize .NET MAUI OTP Input for password entry.

### Password support in .NET MAUI OtpInput

To ensure security when entering sensitive values, you can mask the input by setting the [Type]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Type) property to `Password`.

The following code example illustrate how to utilize password entry in SfOtpInput.

### XAML
```
<syncfusion:SfOtpInput Type="Password" Value="e3c7"/>

```
### C#

```
var otpInput = new SfOtpInput
{
    Type = OtpInputType.Password,
    Value = "e3c7"
};

```