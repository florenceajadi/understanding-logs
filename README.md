<h4>Understanding Logs </h4>

<p>
  <img src="https://github.com/user-attachments/assets/97539b5d-e06e-49bd-bd94-a545117ceaff" height="80%" width="80%" />
   <img src="https://github.com/user-attachments/assets/f8a40665-f28b-4974-81d2-ecfa9255f052" height="80%" width="80%" />

</p>
<h5>SecurityEvent</h5>
<p> SecurityEvent is a table in log management systems like Azure Sentinel that stores security-related logs from Windows systems. 
  It includes information on security activities such as login attempts, account changes, and access control events.
  In this case, you have time, account, ip address, and eventlevelname shown.
 </p>

  <p>
     <img src="https://github.com/user-attachments/assets/9e944453-ab8d-4b84-ab51-ed10d58ba7b3" height="80%" width="80%" />
    <img src="https://github.com/user-attachments/assets/4734cb1b-c2a4-440a-98c5-556ea3ee8b88" height="80%" width="80%" />
   <h5>Syslog</h5>
    <p>
Syslog is a standard protocol used for sending and receiving log and event messages in networked environments. 
      It is widely used for system logging and monitoring across various types of devices and systems.
    Projected the timestamp, name of the host that generated the log, the severtity of the log msg, the actual log msg, and the IP Address used.</p>
  </p>

  
<p>
  <img src="https://github.com/user-attachments/assets/ab4a44cb-7ece-4a84-a6d4-e0e24849641d" height="80%" width="80%" />
  <img src="https://github.com/user-attachments/assets/25ce1375-b1f6-4193-9ac2-c5563603991a" height="80%" width="80%" />
 
</p>
<h5>SecurityAlert</h5>
<p>A table that stores alerts related to potential security threats detected by Azure Sentinel's analytics and monitoring rules.


</p>


  <p>
 <img src="https://github.com/user-attachments/assets/235d3683-dabc-4e53-80bb-b29cf9fa6aef" height="80%" width="80%" />
    <img src="https://github.com/user-attachments/assets/a1f4ce5a-cc6f-466b-8b5a-22e47cf71091" height="80%" width="80%" />
    <h5>SecurityIncident</h5>
    <p>A table that aggregates and organizes multiple related security alerts into a single incident for easier management and investigation.</p>
  </p>

  
   <p>
 <img src="https://github.com/user-attachments/assets/8c2d819f-7f1a-4a9d-a9de-7b7092b7f67d" height="80%" width="80%" />
       <h5>AzureNetworkAnalytics_CL</h5>
    <p>A custom log table that stores network-related data collected from various Azure network services and devices. </p>
  </p>
 
