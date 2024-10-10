# Campaigns_web (Done with Vue.js)

<strong>DISCLAIMER: </strong>Due to a Non-Disclosure Agreement (NDA) I have signed, I am unable to display or share the application code. Thank you for your understanding.


This video shows the general operation of the web: https://drive.google.com/file/d/1Knqk4n4fPIG2AZgM06l2QOTo4-ArpEu0/view?usp=sharing

This web application is a portal for managing missions and campaigns. From this website, an administrator user has control to create, view, and delete campaigns with the aim of creating a dataset that can be used on other platforms. Each campaign and mission can also be customized and parameterized so they can be tailored to our specific goal.


<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/b3c1ebec-6c2e-42af-8a21-2f974e3a4530" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.1: Web login screen.


As the web administrator, the first screen we will access is the login screen (Figure 1.1). Here, the administrator must authenticate with their personal credentials.
Once authenticated correctly, the administrator will have an overview of all the campaigns that are active at that moment (Figure 1.2). They will also be able to see the basic characteristics of each one, such as the title, start and end dates, or reward points. This allows for a lot of information to be obtained in an organized manner with just a glance at the list.


<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/2e9d3664-9905-4a14-83f3-f5700c020dfb" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.2: Active campaigns display screen.

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/2a47c4c2-9a3e-42cb-bc73-5a6bedd1fc4f" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.3: Campaign creation screen.

From here, the administrator has two options. First, they can view more information about a campaign using the button available to the left of each one.
Alternatively, they can move to the campaign creation screen (Figure 1.3). On this screen, the administrator can fill in the fields that make up a campaign. If any fields are left blank, a message will appear at the top of the screen. This screen also provides a list of all available points of sale, allowing us to select those we wish to add to the campaign. Since there are a large number of points of sale, a filtering system has been implemented. These filters can be used simultaneously, meaning that points of sale can be filtered by several fields at once.
Once we have finished adding points of sale to a campaign, we can view it in the main list.

From there, we will access the campaign to define the missions. On this screen (Figure 1.4), existing missions within the campaign can be viewed, as well as new ones added. Currently, there are two different types of missions, either text or image-based. To define them, we must select the type of mission and provide instructions for its completion.

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/87a677d9-93c6-4d65-8e67-77855a79cf1d" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.4: Screen for viewing and adding missions to a campaign.

If the administrator wants to view or remove any points of sale from the campaign, they can do so using the "View PDVs" button located at the top. This button will open a page with a list of points of sale where the campaign is active.
When a campaign has been active for a while, we will start receiving user results. The "View users" button from the previous screen (Figure 1.4) will take us directly to the list of all users who have participated in the campaign (Figure 1.5). In this list, we can see relevant user information, such as their name and email address.

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/b3eb8187-a5f6-44f3-95cd-06c9334257db" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.5: Screen for users who have participated in a campaign.

The results can be viewed individually for each participating user through the "View Results" button (Figure 1.5). This will redirect us to the results screen, where we can see the missions completed at each point of sale where the campaign was conducted (Figure 1.6). In this list, both text and image-based missions can be seen, allowing us to verify the result obtained after image processing.
If the administrator needs to contact a user, the results screen (Figure 1.6) has a button to send emails to the user (Figure 1.7). On this screen, we can compose the message that will be sent to the user's email address.



<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/0737e30f-1f23-4b2f-b105-84aeb845d7bb" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.6: Screen with a user's results in a campaign.

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/user-attachments/assets/21553561-0c9e-4dcd-923d-9e9b954c890b" width="850" alt="Registro 1" hspace="10"/>
</div>
Figure 1.7: Screen for sending an email to a user.
