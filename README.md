🔒 DISCLAIMER 🔒

This tool is only for **ethical hacking, education, and training**. Do **NOT** use it for spying or malicious intent. The author is not responsible for any misuse. Always get **written permission** before testing on anyone or any system.

# What is CamPhish?
<p>CamPhish is techniques to take cam shots of target's phone front camera or PC webcam. CamPhish Hosts a fake website on in built PHP server and uses ngrok & CloudFlare Tunnel to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device

A GPS location capture feature has been added.</p>

📌 Purpose:
CamPhish is designed to demonstrate how **camera-based phishing attacks** can be simulated for awareness, training, and research purposes. It helps security professionals understand how social engineering and device exploitation may occur, so they can defend against it.

⚠️ WARNING:
This tool must **not** be used for any illegal, unethical, or unauthorized surveillance. Misuse of CamPhish for spying, stalking, blackmailing, or accessing unauthorized camera feeds is a serious offense and may lead to **legal consequences**.

✅ Intended Use Cases:
- Cybersecurity awareness campaigns  
- Ethical hacking workshops and CTFs  
- Red teaming & pentesting (with permission)  
- Educational content creation (YouTube / Courses)  
- Demonstrating client-side attack vectors

🛡️ Always test responsibly, ethically, and with full **informed consent**.

💡 Respect privacy | Stay legal | Hack the right way

Developed by: **Santosh Chhetri**  
YouTube Channel: **Master in White Devil**  
Version: **CamPhish v1.0.0**


# CamPhish
Grab cam shots from target's phone front camera or PC webcam just sending a link.
![Screenshot From 2025-06-29 00-29-09](https://github.com/user-attachments/assets/007d1a9e-3045-4aea-8be5-8d9d5dacf1dc)
<br>
![Screenshot From 2025-06-29 00-29-35](https://github.com/user-attachments/assets/67bd7de3-e062-448d-b636-65119d18d871)

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
  <li>Online Meeting [Beta]</li>
  <li>GPS Location Tracking</li>
</ul>
<p>A cleanup script has been added to remove all unnecessary files and logs.</p>

## This Tool Tested On :
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
  <li>Windows (WSL)</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, and wget for downloading dependencies. First run following command on your terminal</p>

```
apt-get -y install php wget unzip
```

## Installing (Kali Linux/Termux):

```
https://github.com/Santosh9800/CamPhish.git
cd CamPhish
bash CamPhish.sh
```

## Clean logs & unnecessary files :

```
bash cleanup.sh
```
<p>The cam files and saved location will also be removed.</p>

## Change Log:

<p><b>Version: 2.0:</b> Added GPS Location Tracking</p>
<ul>
  <li>Added: GPS location capturing functionality</li>
  <li>Added: Google Maps integration for captured locations</li>
  <li>Added: Location accuracy reporting</li>
  <li>Added: Improved loading screen with location request</li>
</ul>

<p><b>Version: 1.9:</b> Enhanced architecture detection</p>
<ul>
  <li>Added: Improved architecture detection for all CPU types</li>
  <li>Added: Better support for Apple Silicon (M1/M2/M3) Macs</li>
  <li>Added: Automatic detection of ARM, ARM64, x86, and x86_64 architectures</li>
  <li>Fixed: Windows compatibility improvements</li>
  <li>Fixed: CloudFlare Tunnel download issues</li>
</ul>

<p><b>Version: 1.8:</b> Added CloudFlare Tunnel and removed Serveo</p>
<ul>
  <li>Added: CloudFlare Tunnel support for more reliable connections</li>
  <li>Removed: Serveo tunnel (deprecated)</li>
  <li>Fixed: Various code improvements and bug fixes</li>
</ul>

<p><b>Version: 1.7:</b> Fix and add support</p>
<ul>
  <li>fixed: termux failed to get home directory</li>
  <li>Add support for Apple sillicon (M1/M2/M3 ARM64)</li>
  <li>Add support for arm64 like Raspberry Pi</li>
</ul>
<p><b>Version: 1.6:</b> Fix ngrok direct link generate</p>
<p><b>Version: 1.5:</b> Add new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>

### Important Notice
Unauthorized reuploading of this project is prohibited.

#### For More Video subcribe <a href="https://www.youtube.com/@mastersinwhitedevil">Master In White Devil YouTube Channel</a>
<p>CamPhish is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
