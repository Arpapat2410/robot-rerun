robot --output output1.xml ts1_google_search.robot 

robot --rerunfailed output1.xml --output rerun.xml ts1_google_search.robot

rebot --merge --output merged_output.xml output1.xml rerun.xml   
