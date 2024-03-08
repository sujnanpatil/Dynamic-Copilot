# Pre-configurations

## Create an environment in Power Apps

1. Navigate to [Power Platform admin center](https://admin.powerplatform.microsoft.com/) and click on **Sign In** and sign in with the credentials provided under **Environment Details** Tab.

1. Click on **Environments** from the left pane and click on **New**.

   ![](../media/1-1.png)

1. Provide a name and make sure **Add a Dataverse data store** is selected to **Yes** and click on **Next**.

   ![](../media/1-11.png)

1. Provide **None** for security roles and click on **Done**.

   ![](../media/1-3.png)

1. Make sure **Enable Dynamics 365 apps** is set to **Yes**, select **Sales Pro** for **Automatically deploy these apps** and click on **Save**.

   ![](../media/1-4.png)

1. Once the environment is in **Ready** state, select the environment and click on **Settings**.

   ![](../media/1-6.png)

1. Click on **Users** under **Users and permissions**.

   ![](../media/1-7.png)

1. Select the **user** and click on **Manage security roles**.

   ![](../media/1-9.png)

1. Make sure **Basic User**, **Salesperson** and **Sales Copilot User** is checked and click on **Save**.

## Install Copilot for Sales in Outlook 

1.	Sign into the **[Microsoft 365 admin center](https://admin.microsoft.com/)**.
   
1.	In the left pane, select

  	- **Settings (1)**
   - Select **Integrated Apps (2)**
   - Click on **Available Apps (3)**
   - In the AppSource window, search for **Copilot for Sales (4)** and select it.

     ![](../media/p-1.png)

1. Click on **Deploy App**.

      ![](../media/p-2.png)

1.	In the **Configuration** step, select the apps to deploy, and then select **Next**.

      ![](../media/p-3.png)

1.	In the **Users** step, select **Just me**, and then select **Next**.

      ![](../media/p-4.png)

1.	In the **Deployment(Permissions)** step, read the app permissions and capabilities for each of the apps to be deployed, select **Accept permissions** for each app, and then select **Next**.

      ![](../media/p-5.png)

1.	In the Deployment (Finish) step, review the selected settings, and then select **Finish deployment**.

      ![](../media/p-6.png)

1.	When the deployment is complete, select **Done**.

1. Verify **Copilot for Sales** is available under **Deployed Apps**.

      ![](../media/p-7.png)

## Install and pin Copilot for Sales in Teams 

1. Sign into the **[Teams admin center](https://admin.teams.microsoft.com/)**.
   
1. In the left pane, select

   - **Teams apps (1)**
   - Select **Setup policies (2)**
   - Click on **Add (3)**

      ![](../media/t-1.png)     

1. Enter a name for the policy and verify if **User pinning** is on.

   ![](../media/t-2.png) 
   
1. Under Installed apps, select **Add apps**.  In the **Add installed apps** panel, search for the **Copilot for Sales** app and Select **Add**

      **Note:** You can also filter apps by app permission policy.

   ![](../media/t-3.png) 

1. Select **Add** again to install the listed apps.

   ![](../media/t-4.png) 

1. Under ****Pinned** apps**, select **Add apps**. In the **Add pinned apps** panel, search for the **Copilot for Sales** app and select **Add**.

   ![](../media/t-6.png) 

1. Select **Add** again to pin the listed apps. 

1. Under App bar or Messaging extensions, arrange the apps in the order that you want them to appear in Teams. 

1. Select **Save**.

   ![](../media/t-5.png) 
