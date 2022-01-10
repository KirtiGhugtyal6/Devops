Service File

## newfile.service

###### [Unit]
###### Description=My First service file
###### [Service]
###### type=simple
###### ExecStart=/home/knoldus/newfile.sh
###### [Install]
###### WantedBy=multi-user.target

  
  ##### **[Unit]** carries generic information about units that are not dependent on the type of unit.
  ##### **[Service]** which carries information about the service and the process it supervises.
  ##### **[Install]** section carries installation information for the unit.
