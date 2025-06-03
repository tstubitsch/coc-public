---
title: Setup Multi-Factor Authentication (MFA)
weight: 1
---
# Setup Multi-Factor Authentication (MFA)

{{< rawhtml >}}
<p><span style="color:red">Audience:</span> All remote users who have not set up Multi-factor Authentication (MFA) for city access.
</p>
{{< /rawhtml >}}

## MFA Definition

The City uses multifactor authentication (MFA) to establish confidence in person's electronic identity when attempting to access City computer resources from outside the City's networks.  Using Microsoft's Authenticator App is the only supported MFA method.  Using MS Authenticator has no extra charge for push notifications to the owner of the mobile phone.

MFA requires three elements or factors:
1.  Using something to uniquely identify yourself as someone authorized to access the City of Chicago’s resources.  The City's unique identifier is an Active Directory (AD) account in the format **First_Name.Last_Name@cityofchicago.org**
2.  Something only you know to prove who you are (your network domain password)
3.  Something only you have to prove who you are (a temporary MFA personal identification number (PIN)

## Prerequisites

Download and install The Microsoft Authenticator App on your phone.For Android-based devices, go to the Google Play Store on your phone.

For iOS-based devices, go to the Apple App Store on your phone.In the store, search for "Microsoft Authenticator".  

Be certain to download the app with an icon similar to the one below.

{{< rawhtml >}}
  <p>
    <img src="../images/auth.webp" style="width:25%">
  </p>
{{< /rawhtml >}}

Follow the steps on your phone to install the App:

* **Note:** Multiple City and non-City MFA PINs can be stored within the Microsoft Authenticator mobile app. If you already use the app with another organization, you do not need to load it again.
* Be careful to only download the official Microsoft Authenticator app (and not simply what your app store promotes at the top of the search results).  The Microsoft Authenticator mobile app icon will look like this:
* Once you have the App on your phone, click NEST on the More Information Required screen that is shown above.
* **Note:** Multiple City and non-City MFA PINs can be stored within the Microsoft Authenticator mobile app.

## Sign In

On your desktop computer browse to either of the following:

* myapps.microsoft.com
* login.microsoft.com
* portal.cityofchicago.org  – and use your City of Chicago domain credentials* to sign into the Microsoft Sign-In Screen below and click **Next.**

<mark>*Domain credentials are in **firstname.lastname@cityofchicago.org** format. Using the numerical person ID is not supported in this login scenario.</mark>

![](../images/image010.png)

Enter your City of Chicago domain credential password* into the Microsoft Sign-In Screen and click Sign In.<br>
<mark>*This password will be the same as your password you use with your numerical person ID account, only the username format changes as detailed in the prior step.</mark>
![](/images/image012.png)

After credentials are entered you will be prompted with the following screen stating you need more information to keep your account secure. Click **Next.**
![](/images/image014.png)

On the next screen will be the MFA registration workflow. if you already have the Microsoft Authenticator App installed on your mobile device, Click **Next.**
{{< rawhtml >}}<mark>If you have not installed the Microsoft Authenticator App on your phone, please refer to the <a href="#prerequisites">prerequisites</a> at the top of this document for instructions on how to get the Microsoft Authenticator App and install it as you would any other App.</mark>
{{< /rawhtml >}}

## MFA Registration Workflow

**Please refer to the [prerequisites](#prerequisites) at the top of the page for instructions on how to get the Microsoft Authenticator App.**


![](/images/image016.png)<br>

Have your mobile device ready with the Microsoft Authenticator App opened. On the More Information Required screen on your PC, Click **Next.**

![](/images/image018.png)

{{< rawhtml >}}
<mark>The Next steps are performed from the mobile device that you have the Microsoft Authenticator App installed on.</mark>
{{< /rawhtml >}}

1. If it isn't open already, open the Microsoft Authenticator App on your mobile device and click the + icon in the top right corner.
2. Click the **Work or school account** option on the following page.
3. Click the **Scan QR code** option. *Approve any pop ups requesting camera permission on your mobile device.
4. The camera will open to scan a QR code and you can proceed to the next step.

![](/images/image020.png)

Use the Microsoft Authenticator Apps camera from the prior step to scan the QR code on your screen. After you scan the QR code the Microsoft Authenticator Apps camera will close and you can click **Next.**

![](/images/image022.png)

On the next screen you will perform a number matching test to complete the registration.


On your desktop screen there will be a two-digit number, in the sample screenshot below that number is 16.


On your **mobile device** screen enter the number that is shown on your desktop screen and click **Yes.**
![](/images/image024.png)

If the steps were performed correctly, you should see the below screen*. Click Next.


*If not, you will need to restart the process or follow the instructions on the next screen.

![](/images/image026.png)

The following page will have you register a second method of authentication. You can use your mobile phone number or a personal email as the second method.

![](/images/image028.png)

## Phone Number Setup

1. Enter your 10-digit phone number starting with the area code in the phone number field and click **Next.**
2. You will receive a text at the number provided with a 6-digit code. Enter the code in the field and clock **Next.**
3. If done correctly you will see a Success screen. Click **Done** and you have finished the setup.

![](/images/image030.png)

## Email Setup for Backup Purposes:

1. Click **I want to set up a different method**
2. Select **email** from the drop down and click **Confirm**
3. Enter in the email you want to use. *This cannot be your cityofchicago.org email. Click **Next**
4. Check the inbox for the email you entered. You will have an email with a 6-digit code from an @microsoftonline.com email address. Enter the code in the field and click **Next.**
5. If done correctly you will see a Success screen. Click **Done** and you have finished the setup.


You have now set up your mobile phone to receive temporary MFA PINs via the Microsoft Authenticator app.  You will need an MFA PIN each time you remotely login to the City's networks.

Please contact the IT Service Center at 312-744-3282 (4DATA) if you need additional assistance.
