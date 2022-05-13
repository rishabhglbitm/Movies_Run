########################Process to setup virtual environment


###creating the VE###############
 python -m venv .venv
 
#########Running VE###############
 . .venv/Scripts/activate
 
 
######installig REQUEST in VE###############

pip3 install requests

######shows all package####
pip freeze



###move out of VE###############

deactivate

######### creating a project #############

django-admin startproject movie .

dot represent that project will be created in current directory.
