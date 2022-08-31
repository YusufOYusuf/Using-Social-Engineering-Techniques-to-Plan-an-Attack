<h1>Using Social Engineering Techniques to Plan an Attack</h1>


<h2>Description</h2>
In this lab, I learned to use social engineering techniques to plan an attack. Social engineering is a technique to gather information about the target. This information can be used to access systems, networks, physical locations, or for financial gain. Here, you will use a social engineering technique to plan an attack.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux Rolling</b> 
- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar click Terminal: <br/>
<img src="https://i.postimg.cc/XqVgw4Bn/Screen-Shot-2022-08-30-at-5-20-29-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
In the Terminal window type the "service apache2 stop" command  <br/>
<img src="https://i.postimg.cc/NfbQ84St/Screen-Shot-2022-08-30-at-5-22-41-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
  
<br />
From the sidebar open up a new terminal window and execute the following commands <br/>
1. setoolkit <br/>
2. 1 <br/>
3. 2 <br/>
4. 3 <br/>
5. 1 <br/>
<img src="https://i.postimg.cc/7Ly300Rg/Screen-Shot-2022-08-30-at-5-28-46-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Switch back to the first terminal window and type in the "ifconfig eth0" command <br/>
<img src="https://i.postimg.cc/FFcJg7jp/Screen-Shot-2022-08-30-at-5-29-53-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
In the second terminal window type in the Inet Ip address from the first terminal.  <br/>
<img src="https://i.postimg.cc/vH2JXH7q/Screen-Shot-2022-08-30-at-5-38-40-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />





<br />
when asked select a template, select option 2.  <br/>
<img src="https://i.postimg.cc/KY3JPtxf/Screen-Shot-2022-08-30-at-5-39-42-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
When asked "press return if you understand what we're saying" press return.  <br/>
<img src="https://i.postimg.cc/6qMmjwSf/Screen-Shot-2022-08-30-at-5-42-44-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
Open the internet browser and then type in "http://inet ip address from before". Once on the webpage type in the credentials .  <br/>
<img src="https://i.postimg.cc/yx2FYbSz/Screen-Shot-2022-08-30-at-5-46-33-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />






<br />
Return to the second terminal and observe the exploits.  <br/>
<img src="https://i.postimg.cc/BZd3GBw5/Screen-Shot-2022-08-30-at-5-50-18-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />




<br />
In the terminal window Type ctrl+c to stop the attack.  <br/>
<img src="https://i.postimg.cc/wjWHnYKM/Screen-Shot-2022-08-30-at-5-53-42-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />



















  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
