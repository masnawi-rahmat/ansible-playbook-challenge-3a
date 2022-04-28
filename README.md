\# ansible-playbook-challenge-3a <br />
\# class challenge creating ansible playbook to fetch and unpack csv zip file from data.gov.sg and create a custom list by jmesquery without the use of a python script <br />
\# this ansible playbook is created with learning purpose more than optimisation in mind <br />
\# this anisble playbook is created in submission of class challenge no 3 <br /> 
\# in Generation SG/Temasek Poly SGUPMSCT Cloud Support and DevOps Bootcamp cohort no 4 Yr 2022 <br />
\# this ansible playbook assumes that you: <br />
\# (1) have the NOPASSWD auth in the remote node to execute commands otherwise please insert line <br />
\# "your_username ALL=(ALL:ALL)       NOPASSWD: ALL" in /etc/sudoers.d <br />
\# (2) have jmespath package installed to execute 'jmesquery' otherwise do a 'pip/apt install jmespath' <br />
\# the objectives of this ansible playbook: <br />
\# (1) fetch csv data from data.gov.sg in zip format <br />
\# (2) unzip csv data <br />
\# (3) make correction to the formatting of a value in the csv data <br />
\# (4) read csv raw data <br />
\# (5) parse data with jmesquery without using python script <br />
\# (6) generate custom json list and make arithmetic calculaation <br />
\# tasks covered in this playbook: <br />
\# (1) creating directory and subdirectories by looping <br />
\# (2) fetching and unpacking csv data from data.gov.sg into a file <br />
\# (3) make correction of the formatting of a value in the csv data <br />
\# (4) parsing data with jmesquery and generate custom json list <br />
\# (5) saving parsed data into new files <br />
\# (6) calculating the sum of uni/poly IT graduates and writing the value into a pre-existing file <br />
\# (7) optional - removing all directory, subdirectories and files created by this ansible playbook and to activate 'uncomment' line 239 to 249
