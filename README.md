# Final-Project--Cybersecurity-
    An intrusion detection system utilizes incorporated interruption marks for recognizing potential vindictive exercises fit for harming your organization. IDS are either introduced in your organization or a customer framework. It should run constantly without human management. The framework should be sufficiently solid to permit it to run behind the scenes of the framework being noticed.Average interruption discovery frameworks search for known assault marks or unusual deviations from set standards. These irregular examples in the organization traffic are then sent up in the stack for additional examination at the convention and application layers of the OSI (Open Systems Interconnection) model. Detective systems is put out of the ongoing correspondence band inside your organization framework to fill in as a discovery framework. It productively distinguishes tainted components with the possibility to affect your general organization execution, like distorted data parcels, DNS poisonings, and so forth. 
The final project has the accompanying segments: 
Carry out the alerts and limits you decided would be compelling in Project 2. 
Survey two more weak VMs and check that the standards fill in true to form. 
Use Wireshark to investigate live vindictive traffic on the wire.
  Our assignment was to screen how the framework cautions were working in the Kibana framework. From this, we had control of any approaching traffic on the wire to distinguish any irregularities that aren't reflected in the alarming framework and report back the entirety of your discoveries. For the principal casualty machine (Target 1), we ran the accompanying order in the Hyper V-Manager: 
 root with sudo - s 
/opt/setup
We had to run these commands on the primary objective to ensure it is effectively introduced and it can advance logs in Kibana.In expansion, it empowers Filebeat, Metricbeat, and Packetbeat on the Target VM. In Target 1, we needed to filter for and distinguish any uncovered reports or ports.
    For Target 2, we were approached to do the accompanying: 
 Scan the organization to distinguish the IP locations of Target 1 
Document every single uncovered port and administrations 
Enumerate the WordPress site 
Locate any unknown files/directories
Utilizing SSH, we had the option to recognize the two banners and uncover and break the data set secret word. For the Kali VM, we figured out how many machines from unknown subnets are sending traffic to the network. From this, you were able to see a range of IP ranges. 
