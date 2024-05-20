# Attacking port 80 on metasploitable2 using kali linux

## Objective
The goal is to gain access to port 80 (http) 

This Lab project aimed at gaining acess to http service that is active on the metasploitable2 frame work 


### Skills Learnt

- Web Application security
- Penetration Testing Methodologies like reconnaissance
- Using penetration tools like nmap
- Network fundamentals
- Script writing and automation
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- nmap
- msfconsole
- metasploitable2

## Steps
 start metasploitabble2 in the terminal and find out its ip address using the command ip a or ifconfig
  <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta.png" /></br>
 <br>
 start msfconsole on your attacking machine and search for the exploit 'php_cgi' using the command search php_cgi
 </br>
  <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta1.png" /></br>
  <br>
  use the command 'use 0' which will tell msfconsole that you want to use the exploit by highlighting it in red
  </br>
   <br>
     <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta2.png" /></br>
   </br>
 <br>  use the command show options to see all the available options then set the RHOSTS to the target ip address you want to attack with the set RHOSTS command </br>
    <br>
     <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta3.png" /></br>
   </br>
   <br>
   Now u can type run to run the exploit and as you can see ive successully gained acess to the machine because im in the root directory and all files are similar
   </br>
   <br>
     <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta4.png" /></br>
   </br>
<br>
     <br>  <img src="https://github.com/collinsbigomba/metasploitable2/blob/main/images/meta5.png" /></br>
   </br>






Example below.

*Ref 1: Network Diagram*
