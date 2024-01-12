## Lab 07 - Create Incidents 

## Lab scenario
In this lab the key tasks related to create incident in Microsoft Defender. The exercises include creating a Microsoft Entra ID user with Global Reader permissions, enabling all incidents alerts, and simulating an incident by downloading the Tor Browser. The objective is to enhance proficiency in incident identification, response, and resolution within the Microsoft Defender environment.

## Lab objectives (Duration: 50 minutes)


In this lab, you will complete the following tasks:
- Exercise 1: Create Microsoft Entra ID User
- Exercise 2: Turn on All Incidents Alert
- Exercise 3: Create an Incident

## Architecture Diagram

   ![Picture 1](../Media/lab7-arch.png)

### Exercise 1: Create Microsoft Entra ID User

In this task, you will create a Microsoft Entra ID User with Global Reader Permission. 

1. On Azure Portal page, in **Search resources, services and docs (G+/)** box at the top of the portal, enter **Microsoft Entra ID**, and then select **Microsoft Entra ID** under services.

   ![Picture 1](../Media/Lab0701.png)

1. Select **Users** under **Manage** tab.
   
   ![Picture 1](../Media/Lab0702.png)
   
1. Click on **New user** and select **Create new user**.

   ![Picture 1](../Media/Lab0703.png)

1. Under the **Basic** tab give you **User principal name** as **TestUser** and enter the **Display name** as **testUser** now give your **Password** and click on **Assignment** tab.

   ![Picture 1](../Media/Lab0704.png)

1. In **Assignments** page, Click on **Add role** and select **Global Reader** and click on **Select**.

   ![Picture 1](../Media/Lab0705.png)

1. Click on **Review + create** and save your **User principal name** and **Password** for login and click to **create** the user.

   ![Picture 1](../Media/Lab0716.png)

### Exercise 2: Turn on All Incidents Alert

1. Go to Microsoft Defender Portal at https://security.microsoft.com/.

1. Under **Incidents and Alerts**, select **Incidents** and click on **Alert service settings**.

   ![Picture 1](../Media/Lab0706.png)

1. Under **Alert service settings**, click on **All Alerts**.

   ![Picture 1](../Media/Lab0707.png)
   
1. Enable **We are monitoring all Microsoft Entra ID Protection alerts** and click on **Confirm**.

   ![Picture 1](../Media/Lab0708.png)

### Exercise 3: Create an Incident

1. Open a New Tab in browser and search for **tor browser download**, Click on the **Tor Project | Download**.

   ![Picture 1](../Media/Lab0709.png)

1. Once the website loads scroll down and click on the **Download for Windows** to download the Tor Browser.

   ![Picture 1](../Media/Lab0710.png)

1. Once the browser downloaded successfully, Click to **Open file** and press **OK**, When it ask for Installer Language.

   ![Picture 1](../Media/Lab0711.png)

1. From **Choose Install Location** page, Click on **Install**.

   ![Picture 1](../Media/Lab0712.png)

1. Click on **Finish**.

1. Now launch your browser it will ask for **Connect to Tor** and click on **Connect**.

   ![Picture 1](../Media/Lab0713.png)

1. In your browser search for the **portal.azure.com**. You'll see the Sign into Microsoft Azure tab. Provide **Email/Username** of the user which you have created with **Global Reader** role and **Password** which you have specified while creating the user and click on **Sign in**.

   ![Picture 1](../Media/incident-tor-1.png)

   ![Picture 1](../Media/incident-tor-5.png)

1. You will either get the **NoScript XSS Warning** message or message in Microsoft tab that **You don't have access to this**. Close the tab.

   ![Picture 1](../Media/Lab0714.png)

   ![Picture 1](../Media/incident-tor-2.png)

1. Now navigate back to the Microsoft Defender Portal at [Microsoft Defender Portal](https://security.microsoft.com/) and login with the **Global Admin** access user which you can find in the Environment details tab.

1. Under **Incidents and Alerts**, select **Incidents**. You will see that a incident is created **Anonymous IP address involving one user**.

   ![Picture 1](../Media/Lab0715.png)

 >**Note**: Generating the incident may require 10-15 minutes. If the incident is not visible, please refresh the page after 10-15 minutes.

11. You can uninstall the Tor browser now.

## Review
In this lab, you will complete the following tasks:
- Created Microsoft Entra ID User
- Turned on All Incidents Alert
- Created an Incident
