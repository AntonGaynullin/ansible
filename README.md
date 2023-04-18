# ansible
ansible -i hosts.txt all -m ping

# инфа о всех сервераx
ansible  all -m setup
ansible-inventory --list
# запуск шел
ansible all -m shell -a "uptime"
ansible all -m command -a "echo rer"












git init
git add .
git commit -m "first commit"
git remote add origin git@github.com:AntonGaynullin/ansible.git
git push -u origin main
