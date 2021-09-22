# ansible-devops

for i in frontend mongodb catalogue redis user cart mysql shipping rabbitmq payment ; do bash create-instance.sh $i ; done

ansible-playbook -i rb-inv -u centos -e ansible_password=DevOps321 roboshop.yml 