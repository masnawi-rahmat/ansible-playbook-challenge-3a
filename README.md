# ansible-playbook-challenge-3a
an ansible playbook to fetch and unpack csv zip file from data.gov.sg and create a custom list by jmesquery without the use of a python script
# this anisble playbook is created by masnawi rahmat in submission of class challenge no 3 
# in Generation SG/Temasek Poly SGUPMSCT Cloud Support and DevOPs Bootcamp cohort no 4 Yr 2022
# this ansible playbook assumes that you:
# (1) have the NOPASSWD auth in the remote node to execute commands otherwise please insert line 
# "your_username ALL=(ALL:ALL)       NOPASSWD: ALL" in /etc/sudoers.d
# (2) have jmespath package installed to execute 'jmesquery' otherwise do a 'pip/apt install jmespath' 
# the objectives of this ansible playbook:
# (1) fetch csv data from data.gov.sg in zip format
# (2) unzip csv data
# (3) make correction to the formatting of a value in the csv data
# (4) read csv raw data
# (5) parse data with jmesquery without using python script
# (6) generate custom json list and make arithmetic calculaation
# tasks covered in this playbook: 
# (1) creating directory and subdirectories by looping
# (2) fetching and unpacking csv data from data.gov.sg into a file
# (3) make correction of the formatting of a value in the csv data
# (3) parsing data with jmesquery and generate custom json list
# (4) saving parsed data into new files  
# (5) calculating the sum of uni/poly IT graduates and writing the value into a pre-existing file
# (6) optional - removing all directory, subdirectories and files created by this ansible playbook
# and to activate 'uncomment' line 238 to 248
