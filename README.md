# How-to-Utilize-.NET-MAUI-OTP-Input-for-Password-Entry

This repository contains a detailed sample explaining how to effectively utilize the .NET MAUI OTP Input control specifically for password entry. This approach enhances security by ensuring passwords are not displayed in plain text.

### Password support in .NET MAUI OtpInput

To ensure robust security when entering sensitive values, you can mask the input by setting the [Type]( https://help.syncfusion.com/cr/maui-toolkit/Syncfusion.Maui.Toolkit.OtpInput.SfOtpInput.html#Syncfusion_Maui_Toolkit_OtpInput_SfOtpInput_Type) property to `Password.` This functionality is critical for applications where user privacy is of utmost importance, particularly in authentication processes.

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

### Troubleshooting path too long exception

If you are facing path too long exception when building this example project, close Visual Studio and rename the repository to short and build the project.
