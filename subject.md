<h2>deep-in-net</h2>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/serverRoomMeme.jpg" alt="serverRoomMeme"></p>
<h3>Overview</h3>
<p>This project introduces you to fundamental networking concepts using
Cisco Packet Tracer, a practical simulation tool widely used in network
design and troubleshooting. Through a series of guided exercises, you will
explore how networking devices, protocols, and models work together to enable
reliable communication in modern infrastructures.</p>
<h3>Learning Objectives</h3>
<p>By completing this project, you will be able to:</p>
<ul>
<li>Identify and work with common networking devices used to build computer
networks.</li>
<li>Explain and apply essential networking services and communication protocols.</li>
<li>Analyze network behavior using the OSI model.</li>
<li>Use basic Linux networking commands to configure and troubleshoot network
interfaces.</li>
</ul>
<h3>Instructions</h3>
<p>This project will be divided into 8 exercises where we will introduce you to the <code>Cisco Packet Tracer</code>, a valuable networking tool. Additionally, as a cloud and DevOps learner, you will gain insight into key networking concepts as follows:</p>
<ul>
<li><p><code>Discovering and dealing with networking devices</code>, this is fundamental in order to understand how networks are built and maintained.</p>
</li>
<li><p><code>Understanding and using important services and protocols</code>, this is also critical as they provide the framework for communication and data transfer between devices on a network.</p>
</li>
<li><p><code>The OSI Model</code> is a conceptual framework that describes the different layers of network communication and is an essential concept to master when learning about computer networks.</p>
</li>
<li><p><code>Discover some important networking commands in Linux</code>, knowing them is valuable, as Linux is a widely used operating system in networking and server environments. These commands are used to configure and troubleshoot network settings and interfaces, making them essential tools for network administrators and engineers.</p>
</li>
</ul>
<h4>Command Line Prerequisites</h4>
<p><strong>Terminal Navigation:</strong></p>
<ul>
<li><code>pwd</code>, <code>ls</code>, <code>cd</code> - Navigate the Linux file system</li>
<li><a href="https://linuxcommand.org/lc3_lts0020.php">Linux Navigation Basics</a> - LinuxCommand.org</li>
</ul>
<p><strong>File Viewing:</strong></p>
<ul>
<li><code>cat</code> - View configuration files and logs</li>
<li><a href="https://ubuntu.com/tutorials/command-line-for-beginners#3-opening-files-and-folders">File Display Commands</a> - Ubuntu Official</li>
</ul>
<p><strong>Getting Help:</strong></p>
<ul>
<li><code>man [command]</code>, <code>[command] --help</code> - Understand Cisco IOS commands</li>
<li><a href="https://man7.org/linux/man-pages/man1/man.1.html">Using Man Pages</a> - Man7.org Official</li>
</ul>
<p><strong>System Info:</strong></p>
<ul>
<li><code>hostname</code> - Verify device names in exercises</li>
<li><a href="https://www.gnu.org/software/coreutils/manual/coreutils.html#System-context">Basic System Commands</a> - GNU Official</li>
</ul>
<h3>Guideline</h3>
<blockquote>
<p>You must respect the defined netmask and IP address for each network!</p>
</blockquote>
<h4>Cisco Packet Tracer:</h4>
<p>The Cisco Packet Tracer is a powerful network simulation tool used for teaching and learning complex networking concepts. It allows users to design, configure, and troubleshoot network setups, without the need for physical networking equipment. The tool can simulate a wide range of network devices, including routers, switches, servers, and endpoints, and enables users to create, configure, and connect network topologies in a virtual environment.</p>
<p>You have to install <code>Cisco Packet Tracer</code> on your machine or VM:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/PacketTracer.jpg" alt="Packet Tracer"></p>
<p>Take your time to discover it!</p>
<blockquote>
<p>You will need it in the audit.</p>
</blockquote>
<h4>Exercise 1:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex01.jpg" alt="ex01"></p>
<ul>
<li><code>PC0</code> can communicate with <code>PC1</code>.</li>
<li><code>PC2</code> can communicate with <code>PC3</code>.</li>
<li><code>PC4</code> can communicate with <code>PC5</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex01-scenario.jpg" alt="ex01-scenario"></p>
<p><strong>Knowledge:</strong></p>
<ul>
<li>What is an RJ-45 cable?</li>
<li>Understand what is the difference between straight-through and crossover RJ-45 cables.</li>
</ul>
<h4>Exercise 2:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex02.jpg" alt="ex02"></p>
<ul>
<li>All computers connected to the switch must be able to communicate with each other.</li>
<li>All computers connected to the hub must be able to communicate with each other.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex02-scenario.jpg" alt="ex02-scenario"></p>
<p><strong>Knowledge:</strong></p>
<ul>
<li>Understand the function of a <code>switch</code> and a <code>hub</code>, how they operate and their role in networking.</li>
<li>Differentiate between the <code>switch</code> and the <code>hub</code>.</li>
<li>Identify the <code>OSI model layer</code> that the <code>switch</code> and <code>hub</code> operate on.</li>
</ul>
<h4>Exercise 3:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex03.jpg" alt="ex03"></p>
<ul>
<li>Static IP addresses are mandatory for all servers.</li>
<li>Services provided by each server should be limited to their designated purpose.</li>
<li>The <code>DHCP server</code> must be responsible for assigning IP addresses to all PCs.</li>
<li>The <code>HTTPS server</code> must display a hello message and <code>HTTP</code> must be disabled.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex03-https.jpg" alt="ex03-https"></p>
<ul>
<li>You must create a user account with the name &quot;deepinnet&quot; and provide <code>RWDNL</code> access on your <code>FTP server</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex03-ftp.jpg" alt="ex03-ftp"></p>
<ul>
<li>Configure the following records in your <code>DNS server</code>:<ul>
<li>Map &quot;deep-in-net.local&quot; to IP address 192.168.1.99.</li>
<li>Map &quot;deep-in-net.com&quot; to &quot;deep-in-net.local&quot;.</li>
</ul>
</li>
</ul>
<pre><code class="language-bash">deep-in-net.local &gt; 192.168.1.99
deep-in-net.com &gt; deep-in-net.local
</code></pre>
<ul>
<li>Ensure that &quot;<a href="https://deep-in-net.com">https://deep-in-net.com</a>&quot; redirects to your <code>HTTPS server</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex03-dns.jpg" alt="ex03-dns"></p>
<p><strong>Knowledge:</strong></p>
<ul>
<li>Define a <code>server</code> and its purpose in networking.</li>
<li>Explain <code>DHCP</code> and how it operates in a network.</li>
<li>Define <code>DNS</code> and its role in network communication.</li>
<li>Understand the purpose of <code>HTTP</code> and how it is used in networking.</li>
<li>Explain <code>HTTPS</code> and how it is different from <code>HTTP</code>.</li>
<li>Understand the purpose of <code>FTP</code> and how it operates in network communication.</li>
<li>Define <code>TCP</code> and <code>UDP</code> communication and differentiate between them.</li>
<li>Identify the <code>OSI model layer</code> where <code>TCP</code> and <code>UDP</code> operate.</li>
<li>Define a <code>port</code> in networking and its function.</li>
<li>Identify the <code>port</code> and <code>OSI model layer</code> for each protocol used.</li>
<li>Understand the different types of <code>DNS</code> records.</li>
</ul>
<h4>Exercise 4:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex04.jpg" alt="ex04"></p>
<ul>
<li>Both PCs must communicate with each other.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex04-scenario.jpg" alt="ex04-scenario"></p>
<p><strong>Knowledge:</strong></p>
<ul>
<li>What is a <code>router</code> and what is its role?</li>
<li>Differentiate between the switch and the router.</li>
<li>Identify the <code>OSI model layer</code> where a <code>router</code> operates.</li>
<li>Understand the term &quot;default gateway&quot;.</li>
</ul>
<h4>Exercise 5:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex05.jpg" alt="ex05"></p>
<ul>
<li>All devices connected to the same switch must be able to communicate with each other.</li>
<li>All devices in <code>subnet 1</code> can communicate with all devices in <code>subnet 2</code>.</li>
<li>All devices in <code>subnet 2</code> can communicate with all devices in <code>subnet 1</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex05-scenario.jpg" alt="ex05-scenario"></p>
<h4>Exercise 6:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex06.jpg" alt="ex06"></p>
<ul>
<li>The PC in <code>subnet 1</code> can communicate with the PC in <code>subnet 2</code>.</li>
<li>The PC in <code>subnet 2</code> can communicate with the PC in <code>subnet 1</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex06-scenario.jpg" alt="ex06-scenario"></p>
<p><strong>Knowledge:</strong></p>
<ul>
<li>What is a routing table and explain its role in routing network traffic.</li>
</ul>
<h4>Exercise 7:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex07.jpg" alt="ex07"></p>
<ul>
<li>All devices connected to the same <code>switch</code> must be able to communicate with each other.</li>
<li>All devices in <code>subnet 1</code> can communicate with all devices in <code>subnet 2</code>.</li>
<li>All devices in <code>subnet 2</code> can communicate with all devices in <code>subnet 1</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex07-scenario.jpg" alt="ex07-scenario"></p>
<h4>Exercise 8:</h4>
<p>In your <code>Cisco Packet Tracer</code> create this network:</p>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex08.jpg" alt="ex08"></p>
<ul>
<li>All devices connected to the same switch must be able to communicate with each other.</li>
<li>All devices in <code>subnet 1</code> can communicate with all devices in <code>subnet 2</code>.</li>
<li>All devices in <code>subnet 1</code> can communicate with all devices in <code>subnet 3</code>.</li>
<li>All devices in <code>subnet 2</code> can communicate with all devices in <code>subnet 1</code>.</li>
<li>All devices in <code>subnet 2</code> can communicate with all devices in <code>subnet 3</code>.</li>
<li>All devices in <code>subnet 3</code> can communicate with all devices in <code>subnet 1</code>.</li>
<li>All devices in <code>subnet 3</code> can communicate with all devices in <code>subnet 2</code>.</li>
</ul>
<p><img src="https://learn.zone01oujda.ma/api/content/root/01-edu_module/content/deep-in-net/pictures/ex08-scenario.jpg" alt="ex08-scenario"></p>
<h3>Bonus</h3>
<p>If you complete the mandatory part successfully and you still have free time, you can implement anything that you feel deserves to be a bonus.</p>
<p>Challenge yourself!</p>
<h3>Documentation</h3>
<p>Create a <code>README.md</code> clarification of all the knowledge you have learned and the steps you passed to create the network architectures, thorough descriptions of components, and an explanation of the network architectures, presented clearly and concisely. Ensure it contains all the necessary information about the architectures (devices, addresses, subnets, ...). This file must be submitted as part of the solution for the project.</p>
<h3>Tips</h3>
<ul>
<li>It is recommended that you do not rely on IP Subnet Calculator tools.</li>
<li>To configure the devices, utilize the command-line interface (CLI) available in the <code>Cisco Packet Tracer</code>.</li>
<li>Test connectivity for different protocols using appropriate commands.</li>
<li>Use command-line debugging techniques to troubleshoot communication issues instead of relying on graphical user interface (GUI) tools.</li>
</ul>
<blockquote>
<p>Networking plays a critical role in various IT specialties, and is particularly essential for cloud and DevOps engineering.
Be curious and never stop searching!</p>
</blockquote>
<h3>Resources</h3>
<ol>
<li><p><strong>Cisco Packet Tracer</strong>
<a href="https://www.netacad.com/courses/packet-tracer">Download from NetAcad</a> - Cisco Official
<em>Main simulation tool + built-in CLI tutorials</em></p>
</li>
<li><p><strong>Command Line Basics</strong>
<a href="https://ubuntu.com/tutorials/command-line-for-beginners">Ubuntu Command Line Tutorial</a> - Ubuntu Official
<em>Learn basic CLI navigation and commands</em></p>
</li>
<li><p><strong>Cisco IOS Commands</strong>
<a href="https://www.cisco.com/c/en/us/td/docs/ios-xml/ios/fundamentals/command/cf_command_ref.html">Official IOS Command Reference</a> - Cisco Official
<em>Router and switch configuration commands</em></p>
</li>
<li><p><strong>Linux Networking Commands</strong>
<a href="https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/configuring_and_managing_networking/">Red Hat Networking Guide</a> - Red Hat Official
<em>ping, traceroute, netstat, ifconfig commands</em></p>
</li>
<li><p><strong>Networking Fundamentals</strong>
<a href="https://www.cisco.com/c/en/us/solutions/small-business/resource-center/networking/networking-basics.html">Cisco Networking Basics</a> - Cisco Official
<em>OSI model, TCP/IP, subnetting concepts</em></p>
</li>
<li><p><strong>Hands-on Practice</strong>
<a href="https://devnetsandbox.cisco.com/">Cisco DevNet Sandbox</a> - Cisco Developer Network
<em>Free lab environment to practice CLI commands</em></p>
</li>
</ol>
<h3>Submission and audit</h3>
<p>You must save your Exercises solutions as &quot;ptk&quot; files, and then push them to your repository with your documentation file.</p>
<p>Your repository must look like this:</p>
<pre><code class="language-console">user:~/deep-in-net$ ls
ex01.pkt
ex02.pkt
ex03.pkt
ex04.pkt
ex05.pkt
ex06.pkt
ex07.pkt
ex08.pkt
bonus.pkt
README.md
user:~/deep-in-net$
</code></pre>
<blockquote>
<p>In the audit you must answer a group of questions, and recreate a network in the <code>Cisco Packet Tracer</code>, be prepared.
You must also explain any calculations that you have made without the use of tools!
Failure to meet any of these requirements will result in the project being marked as failed. Make sure to take sufficient time to learn and practice before the audit.</p>
</blockquote>
