<!-- 🌐 INSTALL & DEPLOY WINDOWS SERVER 2022 IN VIRTUALBOX -->

<h1 align="center"><strong>🖥️ Installing & Deploying Windows Server 2022 in Oracle VirtualBox</strong></h1>
<p align="center">Step-by-step instructions for creating the Domain Controller (DC01)</p>
<hr>

<h2><strong>➡️ 1. Download the Windows Server 2022 ISO</strong></h2>
<p>You can download the evaluation ISO from Microsoft’s official site:</p>
<p><strong>https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022</strong></p>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_download.png" alt="Windows Server 2022 Download Page"&gt;
</pre>

<hr>

<h2><strong>➡️ 2. Create a New Virtual Machine (DC01)</strong></h2>
<p>Open VirtualBox and click <strong>New</strong>. Use the following settings:</p>

<ul>
    <li><strong>Name:</strong> DC01</li>
    <li><strong>Type:</strong> Microsoft Windows</li>
    <li><strong>Version:</strong> Windows 2022 (64-bit)</li>
    <li><strong>Memory:</strong> 4096–8192 MB</li>
    <li><strong>Processors:</strong> 2+ CPUs</li>
    <li><strong>Storage:</strong> 60 GB (VDI)</li>
    <li><strong>Network:</strong> Internal Network</li>
</ul>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/dc01_vm_creation.png" alt="DC01 VM Creation"&gt;
</pre>

<hr>

<h2><strong>➡️ 3. Attach the Windows Server 2022 ISO</strong></h2>
<p>After creating the VM:</p>
<ol>
    <li>Select <strong>DC01</strong> in VirtualBox</li>
    <li>Click <strong>Settings → Storage</strong></li>
    <li>Select the empty optical drive</li>
    <li>Click the disc icon → <strong>Choose a disk file</strong></li>
    <li>Select your Windows Server 2022 ISO</li>
</ol>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/dc01_attach_iso.png" alt="Attach Server 2022 ISO"&gt;
</pre>

<hr>

<h2><strong>➡️ 4. Start the Virtual Machine</strong></h2>
<p>Click <strong>Start</strong> to boot from the ISO and begin installation.</p>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_boot.png" alt="Booting Server 2022 Installer"&gt;
</pre>

<hr>

<h2><strong>➡️ 5. Begin Windows Server 2022 Installation</strong></h2>
<p>Follow the on-screen prompts:</p>

<ol>
    <li>Select your language and keyboard layout</li>
    <li>Click <strong>Install Now</strong></li>
    <li>Choose: <strong>Windows Server 2022 Standard (Desktop Experience)</strong></li>
    <li>Accept license agreement</li>
    <li>Select <strong>Custom: Install Windows only</strong></li>
    <li>Choose the virtual disk and continue</li>
</ol>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_install_options.png" alt="Server 2022 Installation Options"&gt;
</pre>

<hr>

<h2><strong>➡️ 6. Create the Local Administrator Password</strong></h2>
<p>Once installation completes:</p>
<ul>
    <li>Server will reboot</li>
    <li>Set your <strong>Administrator</strong> password (Ex: <code>Passw0rd!</code>)</li>
</ul>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_admin_setup.png" alt="Administrator Password Setup"&gt;
</pre>

<hr>

<h2><strong>➡️ 7. Log Into Windows Server 2022</strong></h2>
<p>Press <strong>Ctrl + Alt + Delete</strong> inside VirtualBox and login as:</p>

<pre>
Username: Administrator
Password: (your password)
</pre>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_logged_in.png" alt="Windows Server 2022 Desktop"&gt;
</pre>

<hr>

<h2><strong>➡️ 8. (Recommended) Rename the Server</strong></h2>

<p>Rename the computer to <strong>DC01</strong>:</p>

<ol>
    <li>Open <strong>Server Manager</strong></li>
    <li>Click <strong>Local Server</strong></li>
    <li>Click the computer name</li>
    <li>Rename it to: <strong>DC01</strong></li>
    <li>Restart</li>
</ol>

<h3><strong>📸 Screenshot Placeholder</strong></h3>
<pre>
&lt;img src="screenshots/server2022_rename_dc01.png" alt="Rename Server to DC01"&gt;
</pre>

<hr>

<h2><strong>➡️ Windows Server 2022 Installation Completed 🎉</strong></h2>
<p>Your virtual machine is now ready to be promoted to a Domain Controller.</p>

<p align="center"><em>Next Step: Install Active Directory Domain Services (AD DS)</em></p>
