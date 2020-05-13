# ansible  should be installd ! 


- install vuejs and node js and npm 
ansible-playbook -i inventory/hosts.txt install_vuejs.yml  --ask-become-pass
- remove them 

ansible-playbook -i inventory/hosts.txt remove.yml  --ask-become-pass


creat Project in Vuejs  

# vue create my-project --default --force

enter in this Project 
# cd my-project/
running the Server 
# npm run serve