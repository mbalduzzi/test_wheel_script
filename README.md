# jurine_odoo

Requirements
------------


        pip install invoke --user

or
 

        sudo pip install invoke


Steps
-----

1. Clone the github repository

        git clone git@github.com:camptocamp/camptocamp_openerp.git


1. Initialize the tasks repo required by invoke: 


        git submodule update --init


1. Buildout the wheel: 

    
        invoke env.init -s -r -p profiles/dev.cfg
 

1. Finally: 


        ./bin/buildout


