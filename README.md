# Creating Google Credentials for Deploying Whitelabel apps

1.  Open the [Google Play Console](https://play.google.com/apps/publish/)
2.  Click the **Settings** menu entry, followed by **API access**
    ![2](./img/google-credentials/2.png)
3.  Click the **CREATE SERVICE ACCOUNT** button
    ![3](./img/google-credentials/3.png)
4.  Follow the **Google Developers Console** link in the dialog, which opens a new tab/window:
    ![4](./img/google-credentials/4a.png)
    ![4](./img/google-credentials/4b.png)

    1.  Click the **CREATE SERVICE ACCOUNT** button at the top of the Google Developers Console
        ![4.1](./img/google-credentials/4.1.png)
    2.  Provide a Service account name
    3.  Click Select a role and choose **Service Accounts** > **Service Account User**
        ![4.3](./img/google-credentials/4.3.png)
    4.  Check the Furnish a new private key checkbox
    5.  Make sure JSON is selected as the Key type
    6.  Click **SAVE** to close the dialog
        ![4.2-4.6](./img/google-credentials/4.2-4.6.png)
    7.  Make a note of the file name of the JSON file downloaded to your computer

5.  Back on the Google Play Console, click **DONE** to close the dialog
6.  Click on **Grant Access** for the newly added service account
    ![6](./img/google-credentials/6.png)
7.  Choose **Release Manager** from the Role dropdown
    ![7](./img/google-credentials/7.png)
8.  Click **ADD USER** to close the dialog
    ![8](./img/google-credentials/8.png)
9.  Send the `app-***********.json` file that was downloaded to us
