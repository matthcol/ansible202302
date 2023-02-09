ansible-playbook -i hosts -u installerauto -b book_install.yml

ansible-playbook -i hosts -u installerauto -b book_desinstall.yml

ansible-playbook -v -i hosts -u installerauto -b -e "appuser=toto" -e "appdir=/opt/appatoto" book_install.yml

