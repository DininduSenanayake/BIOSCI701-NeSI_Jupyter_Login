# BIOSCI701 : NeSI Setup

## 1. Setup Password and Second factor token 

* This is done via https://my.nesi.org.nz/login

??? info "S.1.1 : Set NeSI HPC Password"
     
     1. Log into [mynesi portal](https://my.nesi.org.nz) with your Institutional credentials (OR Tuakiri Virtual Home) and set your **NeSI HPC password** as below


     <br>![image](images/SetPassword.png){width="1200"}


??? info "S.1.2 : Set NeSI HPC Second Factor"

     1. Log into [mynesi portal](https://my.nesi.org.nz) with your Institutional credentials (OR Tuakiri Virtual Home) and set your **NeSI HPC Second factor** as below

     <br>![image](images/new_Set2FA.png){width="1000"}


_ _ _ 

## 2. Log into Jupyterhub with above credentials 

??? jupyter "S.2.1 : NeSI Mahuika Jupyter login"


     1. <p>Follow [https://jupyter.nesi.org.nz/hub/login](https://jupyter.nesi.org.nz/hub/login)</p>
     2. <p>Enter NeSI username, HPC password and 6 digit second factor token </p><br>![image](images/jupyter_login_labels_updated.png){width="720"}</br>
     3. <p>Choose server options as below</p>
     
          >>* make sure to choose the correct project code `uoa03265`, number of CPUs `CPUs=2`, memory `4 GB` prior to pressing ![image](images/start_button.png){width="50"} button.
          
          <br>![image](images/2023_serveroptions.png)</br>


     4. <p>Once logged in, click the **Terminal** tile/icon to make sure a terminal session can be launched without any issues

          <br><center>![image](images/terminal_icon.png)</center>

 - - - 
 - - - 

## 3.Forgot password or having trouble with login : Reset anytime via my.nesi.org.nz

??? backward "S.3.1 : _Reset_ NeSI HPC Password"

     1. Log into [mynesi portal](https://my.nesi.org.nz) with your Institutional credentials (OR Tuakiri Virtual Home) and Reset your **NeSI HPC Second factor** as below

     <br>![image](images/newResetPassword.png){width="1000"}

??? backward "S.3.2 : _Reset_ NeSI HPC Second Factor"

     1. Log into [mynesi portal](https://my.nesi.org.nz) with your Institutional credentials (OR Tuakiri Virtual Home) and Reset your **NeSI HPC Second factor** as below

     <br>![image](images/2faReset.png){width="1000"}