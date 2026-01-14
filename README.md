# ansible-apache-python 🚀

This project demonstrates how to use **Ansible** to automate the installation of **Python** and **Apache Web Server** on remote host machines (AWS EC2).

---

## 📁 Project Structure
---
├── ansible.cfg
---
├── aws
---
│   └── ansible.pem
---
├── inventory
---
│   └── hosts
---
├── playbooks
---
│   └── install_python_apache.yml
---
└── roles
---
▶️ Run the Playbook
---
ansible-playbook -i inventory/hosts playbooks/install_python_apache.yml
---
✅ Verification
---
python3 --version
---
systemctl status httpd
---
✅ Verification
---
python3 --version
---
systemctl status httpd
---
Access Apache in browser:
---
http://<EC2_PUBLIC_IP>
---
