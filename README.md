# SMStoDatabase
SMStoDatabase is an android application that can update any firebase database using a SMS as a trigger.

## Why SMStoDatabase?
SMStoDatabase can update any specified Firebase database using any specific SMS from a specific phone number as a trigger.

## The Motovation
For project [StaySafe](https://github.com/arnav-deeo/StaySafe), my team needed to update a database in Firebase from an IoT device in a remote loation. There was no access to internet, but GSM was accessible. So, a GSM Module was attached with the IoT device that was able to send SMS.

Using SMS, it was tricky to update the Firebase database. Hence, this app was build where a number and a code can be encoded such that whenever some specific text(s) are received in the mobile from some specific number(s), the firebase database will be updated in some specific way, automatically.
