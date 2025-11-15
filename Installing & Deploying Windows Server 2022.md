<!-- 🌐 INSTALL & DEPLOY WINDOWS SERVER 2022 IN VIRTUALBOX -->

<h1 align="center"><strong>🖥️ Installing & Deploying Windows Server 2022 in Oracle VirtualBox</strong></h1>
<p align="center">Step-by-step instructions for creating the Domain Controller (DC01)</p>
<hr>

<h2><strong>➡️ 1. Download the Windows Server 2022 ISO</strong></h2>
<p>You can download the evaluation ISO from Microsoft’s official site:</p>
<p><strong>https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022</strong></p>

<hr>

<h2><strong>➡️ 2. Create a New Virtual Machine</strong></h2>
<p>Open VirtualBox and click <strong>New</strong>. Use the following settings:</p>

<ul>
    <li><strong>Name:</strong> Server 2022</li>
    <li><strong>OS:</strong> Microsoft Windows</li>
    <li><strong>Version:</strong> Windows Server 2022 (64-bit)</li>

<pre>
<img width="1293" height="752" alt="Screenshot 2025-11-15 091338" src="https://github.com/user-attachments/assets/d060e0c3-e3dd-41cf-83b3-6be4f10d3036" />

<hr>

<h2><strong>➡️ 3. Specify Virtual Hardware</strong></h2>
<p>Set it up however you like <strong>New</strong>. I Used the following settings:</p>
    
<ul>
    <li><strong>Base Memory:</strong> 8MB</li>
    <li><strong>Number of CPUs:</strong> 2</li>
    <li><strong>Disk Size:</strong> 30.77GB</li>

<img width="818" height="390" alt="Screenshot 2025-11-15 091831" src="https://github.com/user-attachments/assets/6f036635-e035-4174-be26-415822bc285f" />

<hr>

<h2><strong>➡️ 4. Start the Virtual Machine</strong></h2>
<p>Click <strong>Start</strong> Press start and a menu will appear for you to add the server iso. After you upload the iso press "Mount and Retry Boot". </p>

<img width="1284" height="751" alt="Screenshot 2025-11-15 091928" src="https://github.com/user-attachments/assets/407c005e-8879-4eea-8de4-ec888acf684c" />


<hr>

<h2><strong>➡️ 5. Microsoft Server Operating System Setup </strong></h2>
<p>Follow the on-screen prompts:</p>

<img width="1021" height="853" alt="Screenshot 2025-11-15 092126" src="https://github.com/user-attachments/assets/23b04369-98a4-4259-9b7f-9cc2eefed5e7" />

<p>Make sure to select "Windows Server 2022 Standard Evaluation (Desktop Experience)":</p>
    
<img width="1024" height="844" alt="Screenshot 2025-11-15 092234" src="https://github.com/user-attachments/assets/fc83141f-d73c-47b3-82b5-b786865af289" />

<p>Next select "Custom: Install Microsoft Server" :</p>

<img width="1019" height="849" alt="Screenshot 2025-11-15 092342" src="https://github.com/user-attachments/assets/c2468b59-d846-4622-b2dd-c048ed9955ff" />

<p>You can chose to allocate space but for this tutorial I did not</p>

<img width="611" height="457" alt="Screenshot 2025-11-15 092532" src="https://github.com/user-attachments/assets/288487da-517e-46f4-8f53-4b94fdedb071" />

<hr>

<h2><strong>➡️ 6. Create the Local Administrator Password</strong></h2>
<p>Once installation completes:</p>
<ul>
    <li>Server will reboot</li>
    <li>Set your <strong>Administrator</strong> password (Ex: <code>Passw0rd!</code>)</li>
</ul>

<img width="1020" height="850" alt="Screenshot 2025-11-15 092805" src="https://github.com/user-attachments/assets/699c5154-299c-479b-aa77-3c58f7639039" />

<hr>

<h2><strong>➡️ 7. Log Into Windows Server 2022</strong></h2>
<p>Press <strong>Ctrl + Alt + Delete</strong> inside VirtualBox and login as:</p>

<pre>
Username: Administrator
Password: (your password)
</pre>

<p>Now you should see your Server Manager</p
<p>🎉Installation of Server 2022 is complete🎉</p

<hr>

<img width="1021" height="853" alt="Screenshot 2025-11-15 093659" src="https://github.com/user-attachments/assets/8bca4a4d-1045-480f-9332-1b2113d296f9" />
