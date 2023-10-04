# UNI_SYS CCNA
-------------------
### A semi-project that mimics my university's system (three buildings, each building is made up of departments, and each department has its own equipment).  It took effort, so I created a topological network to achieve the following: 1- The main campus, which includes three buildings.  Building A: Administrative staff in the Administration, Human Resources, and Policy departments.  Each department has its own office with hardware, and all departments communicate with each other via VLANs.  Building B includes two colleges.  Building C includes student laboratories and the IT department.  The department hosts student laboratories

  ### University web server and other servers, There's a section at the top to the north that's an email server hosted externally on the cloud.  2- The smaller campus consists of the College of Engineering building and consists of two sections, students and employees.  All operations done in the larger campus departments will take place here.  In general, all devices in each building are connected to each other, and this includes servers.  I made a separate IP for each section.  All devices got dynamic IP addresses using DHCP.RIPv2 used to provide routing for the routers in the internal network and static routing for the external server.
