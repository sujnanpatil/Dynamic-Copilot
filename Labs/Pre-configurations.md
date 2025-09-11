# Pre-configurations

## Overview

This task will guide you through setting up an environment in Microsoft Power Apps, which provides storage for apps, flows, data, and other resources. You will learn how to create a database to use Dataverse as a data store. Dataverse is a cloud-scale database used to securely store data for business applications. It not only offers data storage but also allows you to implement business logic, enforce business rules, and automate processes against the data.

## Lab Objectives

In this lab, you will perform:

- Task 1: Create an environment in Power Apps
- Task 2: Install Copilot for Sales in Outlook
- Task 3: Install and pin Copilot for Sales in Teams 

### Task 1: Create an environment in Power Apps

1. Navigate to [Power Platform admin center](https://admin.powerplatform.microsoft.com/) and click on **Sign In** and sign in with the credentials provided under **Environment Details** Tab.

1. Click on **Environments (1)** from the left pane and click on **+ New (2)**.

   ![](../media/L01.png)

1. Provide a name **Copilot for Sales** and make sure **Add a Dataverse data store** is selected to **Yes (2)** , leave **Group** as it is, no need to select as it is optional and click on **Next (3)**.

   ![](../media/L2.png)

1. In **Security Group**, click on **+ Select**.

    ![](../media/dyn2.png)

1. Provide **None (1)** for security roles and click on **Done (2)**.

   ![](../media/dc39.png)

1. Make sure **Enable Dynamics 365 apps** is set to **Yes (1)**, select **Sales Pro (2)** for **Automatically deploy these apps** and click on **Save (3)**.

   ![](../media/dc40.png)

1. Once the environment is in **Ready** state, select the environment and click on **Settings**.

   ![](../media/1-6.png)

1. Click on **Users** under **Users and permissions**.

   ![](../media/1-7.png)

1. Select the **user** and click on **Manage security roles**.

   ![](../media/dyn3-1.png)

1. Make sure **Basic User**, **Salesperson** and **Sales Copilot User** is checked and click on **Save**.

### Task 2: Install Copilot for Sales in Outlook 

### Overview

In this task, you will learn how to install Copilot for Sales as an integrated app from the Microsoft 365 admin center. By default, the app is installed in Fixed mode, where users receive the app automatically and cannot remove it. You will also explore how to manage the app's configuration, add and remove users, and monitor its usage within the Microsoft 365 admin center. 

1.	Sign into the **[Microsoft 365 admin center](https://admin.microsoft.com/)**.
   
2.	In the left pane, click on Show all and select

      - **Settings (1)**
      - Select **Integrated Apps (2)**
      - Click on **Available Apps (3)**
      - In the AppSource window, search for **Copilot for Sales (4)** and select it.

        ![](../media/p-1.png)

3. Click on **Deploy App**.

   ![](../media/p-2.png)

4.	In the **Configuration** step, it will display the apps to be deployed, and then select **Next**.

      ![](../media/dyn4.png)

5.	In the **Users** step, select **Just me**, and then select **Next**.

      ![](../media/just-me.png)

6. Click on **Accept permissions**.

      ![](../media/dyn5.png)

7. Select the **Account**.

      ![](../media/dyn6-1.png)
   
8.	In the **Deployment(Permissions)** step, once it displays as **Permission accepted** ,select **Next**.

      ![](../media/dyn21.png)

9.	In the **Deployment (Finish)** step, review the selected settings, and then select **Finish deployment**.

      ![](../media/dyn7.png)

10. When the deployment is complete, click on **Done**.

11. Verify **Copilot for Sales (2)** is available under **Deployed Apps (1)**.

      ![](../media/dc41.png)

### Task 3: Install and pin Copilot for Sales in Teams 

### Overview

This task will guide you through installing the Copilot for Sales app in Microsoft Teams. You will learn how to navigate the Teams admin center and create setup policies. 

1. Sign into the **[Teams admin center](https://admin.teams.microsoft.com/)**.
   
1. In the left pane, select

   - **Teams apps (1)**
   - Select **Setup policies (2)**
   - Click on **Add (3)**

      ![](../media/t-1.png)     

1. Enter a name for the policy and verify if **User pinning** is on.

   ![](../media/t-2.png) 
   
1. Under Installed apps, select **Add apps**.  In the **Add installed apps** panel, search for the **Copilot for Sales** app and click **Select**

      **Note:** You can also filter apps by app permission policy.

   ![](../media/add-apps.png) 

1. Select **Add** again to install the listed apps.

   ![](../media/t-4.png) 

1. Under ****Pinned** apps**, select **Add apps**. In the **Add pinned apps** panel, search for the **Copilot for Sales** app and select **Add**.

   ![](../media/t-6.png) 

1. Select **Add** again to pin the listed apps. 

1. Under App bar or Messaging extensions, arrange the apps in the order that you want them to appear in Teams. 

1. Select **Save**.

   ![](../media/t-5.png)

1. Click on **Save** for User pinning.

    ![](../media/dyn9.png)


### Task 4: Pre-configuration to Analyze sales meetings with AI-generated meeting summaries

1. Navigate to https://admin.teams.microsoft.com/. If promted sign in with the ODL credential provided in the Environment tab.

1. Navigate to **Manage users (1)** under ***Users,*** then click on the ODL user **(2).**

   ![](../media/dc51.png)

1. Click on **Policies (1)**, scroll down to ***Calling policy*** and then click on **Org-wide default settings (2).** 

   ![](../media/dc52.png)

1. Naviage to ***Transcription*** toggle button, switch it **On** and click on **Save.**

   ![](../media/dc53.png)

1. Navigate back to **Policies (1),** scroll down to **Live event policy**  and then click on **Org-wide default settings (2).**

   ![](../media/dc54.png)

1. Switch the ***Transcription for attendees*** toggle button **On (1)** and then click on **Save (2).**   

   ![](../media/dc55.png)

1. Navigate back to **Policies (1),** scroll down to **Meeting policy**  and then click on **Org-wide default settings (2).**    

   ![](../media/dc56.png)

1. Scroll down to ***Recording and Transcription,*** then switch the ***Transcription*** toggle button **On** and then click on **Save.**

   ![](../media/dc57.png)

1. Navigate back to **Policies (1),** scroll down to **Voicemail policy**  and then click on **Org-wide default settings (2).**       

   ![](../media/dc59.png)

1. Switch the ***Voicemail Transcription (1)*** and ***Translation for transcription (2)*** toggle button **On** and then click on **Save.**

   ![](../media/dc58.png)


## Summary

In this exercise, you have created an environment in Power Apps ,installed Copilot for Sales in Outlook and in Teams.

### You have successfully completed the lab
