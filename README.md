# Apex Dynamic Action Plugin
APEX Confirm for Oracle Apex.


# How to Use
1. Create a new Dynamic Action with your desired event
2. As action choose "APEX Confirm [Plugin]"
3. Under Attributes: - you can select :

- Theme : Colors the modal to give the user a hint of success/failure/warning,
available options are: 'blue, green, red, orange, purple & dark'

- Title : Title of the dialog.

- closeIcon: By default closeIcon is visible if both buttons are false. (dialog mode).
closeIcon can be shown by setting this value to true.                                      

- columnClass: Provides a better way to set Custom width and is responsive.                                    

- Action : Javascript code to be execute when click of the left or "OK" button
Example:
```
var callData = function(){
    return 133;
}
alert(callData());

```

- Dialog Content: Content for the dialog.
# Preview

![](https://github.com/allipierre/APEXCONFIRM/blob/master/apexconfirm.gif)
