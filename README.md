<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube coming soon, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>
-Create an admin user
- create a help desk employee
- create users to log in and create tickets
- create SLA's to prioritize tickets
- create basic reasons for tickets
- use http://localhost/osTicket/scp/login.php for agent logins
- use http://localhost/osTicket/ for user login to create tickets


<h2>Configuration Steps</h2>

<p>
1\. Login with your primary admin user account

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8435cae6-69c3-4763-981f-7b6fecda212f/screenshot.jpeg?tl_px=883,279&br_px=1743,760&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


2\. Click on admin panel

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/4acf2ca9-d11c-49a3-b00c-2555678ce1ab/screenshot.jpeg?tl_px=1107,0&br_px=1967,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,73)


3\. Go to agents-&gt;roles

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/d04b6e6e-1469-48e0-a4a1-009c44476d9b/screenshot.jpeg?tl_px=971,41&br_px=1831,522&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


4\. Add new role

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/df5ede98-7814-4ea7-977f-0e67718348ff/screenshot.jpeg?tl_px=1091,30&br_px=1951,511&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


5\. Give it a name

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/0fb2c40c-13b0-4c49-8898-250cb16b056e/screenshot.jpeg?tl_px=563,92&br_px=1423,573&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


6\. Select permissions, click add role

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/a5fa794a-d01b-4fe7-90d5-6d10d4522183/screenshot.jpeg?tl_px=738,562&br_px=1598,1043&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


7\. Go to departments

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/b706c8c9-bf09-4ec2-b158-d331eebccd0f/screenshot.jpeg?tl_px=666,0&br_px=1526,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,190)


8\. Add new department

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/344d3d0b-632a-468f-807d-b4df03530cd1/screenshot.jpeg?tl_px=1031,23&br_px=1891,504&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


9\. Give it a name

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/fb52a4a5-dd2b-407b-aeab-8db7b451e0eb/screenshot.jpeg?tl_px=652,176&br_px=1512,657&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


10\. Create department

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/6267d7d5-1f9f-4f30-a699-6e443f1ab367/screenshot.jpeg?tl_px=737,331&br_px=1597,812&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


11\. Go to teams

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/77e3257d-bcfa-4a85-a4b8-f047d1ffb8c7/screenshot.jpeg?tl_px=471,0&br_px=1331,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,198)


12\. Add new teams

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/9f98a84b-6169-4efe-b7fb-a63c7b7744f6/screenshot.jpeg?tl_px=1113,7&br_px=1973,488&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


13\. Give it a name

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/95e521f6-dd48-4baa-908b-92d9f4578709/screenshot.jpeg?tl_px=683,0&br_px=2403,961&force_format=png&width=1120.0)


14\. Create team

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/1daddc74-8a34-4345-adad-a1912087e9ca/screenshot.jpeg?tl_px=776,491&br_px=1636,972&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


15\. Go to users

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8154b072-dc67-45b3-86f8-811b65592424/screenshot.jpeg?tl_px=539,117&br_px=1399,598&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


16\. Click 'Require registration to create tickets' and save

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/b9f3aee3-9ff4-4453-ab67-6c1e63bff0d9/screenshot.jpeg?tl_px=874,229&br_px=1734,710&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


17\. Go to agents-&gt;agents

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8f52b2ea-db8d-4573-865e-a4854f421dde/screenshot.jpeg?tl_px=940,0&br_px=1800,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,192)


18\. Add new agent

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/a1bb6508-e6ef-4de0-a728-37ff6c7c9a86/screenshot.jpeg?tl_px=1081,60&br_px=1941,541&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


19\. Create your admin user

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/609c993e-7901-42a1-ab07-61984470485b/screenshot.jpeg?tl_px=989,307&br_px=1849,788&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


20\. Click 'send the agent a password reset email' and 'require password change at next login' (unless you want to)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/b0f37a15-76de-43dd-b2ea-3d91d4557bb6/screenshot.jpeg?tl_px=594,182&br_px=1454,663&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


21\. If you don't want to send your agent a password, create one here

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/65b4745d-5c1c-4a6d-a263-7180bef83a40/screenshot.jpeg?tl_px=200,0&br_px=1919,961&force_format=png&width=1120.0)


22\. Click "Input Capture Window"

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/3f6c9244-1bfc-4eca-9101-a512c746406d/screenshot.jpeg?tl_px=690,287&br_px=1550,768&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


23\. Add to the primary department and role(s)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/9a94cd01-1334-4de7-9669-c5b36c49d168/screenshot.jpeg?tl_px=731,58&br_px=1591,539&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


24\. Give them permissions and click create

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/1d239ff2-0376-4975-a5b4-a4451b2d966c/screenshot.jpeg?tl_px=733,317&br_px=1593,798&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


25\. Create your non admin account

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/a620360e-c371-40a7-b19e-7e887b78cb34/screenshot.jpeg?tl_px=948,117&br_px=1808,598&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


26\. Set the password like above

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/7fed008f-0be9-4503-a678-728e0a2fb3cf/screenshot.jpeg?tl_px=594,326&br_px=1454,807&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


27\. Add to primary department and role(s)

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/74347bfd-8a62-402e-bcf3-f674a0b6f961/screenshot.jpeg?tl_px=461,236&br_px=1321,717&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


28\. Add to teams

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/b4edff49-e8b3-4bc7-898b-3aa592298e2b/screenshot.jpeg?tl_px=452,229&br_px=1312,710&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


29\. Go to agent panel

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/a7f3d911-b119-4a60-ad7a-49020440a21f/screenshot.jpeg?tl_px=1146,0&br_px=2006,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,99)


30\. Go to users-&gt;user directory

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/f4292a9c-a260-422b-bfda-4639a86dc6a4/screenshot.jpeg?tl_px=554,0&br_px=1414,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,168)


31\. Add user

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/32b051fe-2cfb-434f-8a70-9461bce66ea3/screenshot.jpeg?tl_px=1037,40&br_px=1897,521&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


32\. Create a user account

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/34a04e38-1be2-4b42-be31-d6613bd9fcd8/screenshot.jpeg?tl_px=1070,384&br_px=1930,865&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


33\. Click register and follow similar steps to the agents to create a password

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8de40a03-1669-4f12-9b88-2069d5fdd845/screenshot.jpeg?tl_px=1028,0&br_px=1888,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,207)


34\. Go back to the user directory

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/05d7c035-f296-444d-8b1f-2e926ed5ddb9/screenshot.jpeg?tl_px=561,0&br_px=1421,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,133)


35\. Add user

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/80b184da-256f-40b4-a731-c710576f4a6b/screenshot.jpeg?tl_px=1027,30&br_px=1887,511&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


36\. Create another user

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/618451bb-eccf-4c61-abcd-3b3b5ea907f0/screenshot.jpeg?tl_px=1109,387&br_px=1969,868&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


37\. register this user as well

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/94c37335-bd85-4b8d-8010-b82472959473/screenshot.jpeg?tl_px=1128,0&br_px=1988,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,66)


38\. click on admin panel at the top-&gt;manage-&gt;SLA

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/0df0d1a3-5ae6-43ca-b15d-5ea9bff6f68e/screenshot.jpeg?tl_px=664,35&br_px=1524,516&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


39\. add new SLA plan

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/5b42b5cc-2de3-4b5e-8b45-a60960d95e9a/screenshot.jpeg?tl_px=1064,17&br_px=1924,498&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


40\. Add desired SLA details and click add plan

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/12044184-c0ed-4b07-8d60-82731c281beb/screenshot.jpeg?tl_px=594,231&br_px=1454,712&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


41\. Add a second SLA plan if needed and click add plan

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8f9957b9-d9c4-4c04-b7c0-49f71136ae14/screenshot.jpeg?tl_px=603,229&br_px=1463,710&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


42\. Add a third SLA plan if needed and click add plan

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/5515084d-de83-4819-b48e-87a32e9a1978/screenshot.jpeg?tl_px=610,249&br_px=1470,730&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


43\. Go to help topics

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/7dfb3214-f3d9-44e1-959e-6964431c9a19/screenshot.jpeg?tl_px=419,0&br_px=1279,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,185)


44\. Add ne topic

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/b4534f82-5ee1-4a76-abbd-823e162ba55b/screenshot.jpeg?tl_px=1087,13&br_px=1947,494&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


45\. fill out the info as needed and create add topic. Repeat as needed for topics for tickets.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/8367c822-2d7a-42b0-b6d5-0bf495cde5fc/screenshot.jpeg?tl_px=657,0&br_px=2377,961&force_format=png&width=1120.0)

46\. go to 'http://localhost/osTicket/' click open ticket

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/e626a990-d7bc-4425-9788-3fdd6a5285fc/screenshot.jpeg?tl_px=1062,0&br_px=1922,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,182)


47\. login  as one of thje user accounts

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/4a9e4489-77ca-40cd-8484-1e8872e9c637/screenshot.jpeg?tl_px=214,0&br_px=1933,961&force_format=png&width=1120.0)

<h2>Create Tickets</h2>

48\. Click create new ticket

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/dac3e8eb-8412-4843-ad14-11fca732a783/screenshot.jpeg?tl_px=607,160&br_px=1467,641&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


49\. Select  a help topic

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/ab1a714b-59a5-4498-a8a0-647dd5ab773f/screenshot.jpeg?tl_px=579,192&br_px=1439,673&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


50\. Click create ticket

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/021fb510-7875-4fb8-b770-df210f595379/screenshot.jpeg?tl_px=772,228&br_px=1632,709&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


51\. add a issue summary and description

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/43da08e9-edc6-4987-ae2a-846f4c0ebc86/screenshot.jpeg?tl_px=52,77&br_px=1772,1038&force_format=png&width=1120.0)


52\. Click create ticket

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/1b347601-c6d8-4bc0-ae62-2decc7471e5d/screenshot.jpeg?tl_px=772,710&br_px=1632,1191&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)


53\. follow the above instructions to create more tickets

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/7a2b1270-506e-4401-85f6-f37bad8f570e/screenshot.jpeg?tl_px=342,219&br_px=2062,1180&force_format=png&width=1120.0)


54\. Switch users if you want to

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/7300b5c3-5a88-4dc5-88c8-915e021f1014/screenshot.jpeg?tl_px=1186,0&br_px=2046,480&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,63)


55\. Follow the above steps to create more tickets

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-11-02/f14e1612-f436-4e6c-a069-375526439cf1/screenshot.jpeg?tl_px=615,152&br_px=1475,633&force_format=png&width=860&wat_scale=76&wat=1&wat_opacity=0.7&wat_gravity=northwest&wat_url=https://colony-recorder.s3.us-west-1.amazonaws.com/images/watermarks/FB923C_standard.png&wat_pad=402,212)







