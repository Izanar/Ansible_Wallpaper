# Ansible Wallpaper Setup
Цей Ansible-плейбук автоматично встановлює корпоративні шпалери на робочий стіл Windows Server 2019.

## 🚀 Як користуватися
1. Створіть віртуальне оточення та встановіть залежності:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
2. Налаштуйте IP та пароль у файлі hosts.ini.
3. Запустіть плейбук:

bash
ansible-playbook -i hosts.ini WallpaperServer.yaml

🛠 Технології
Ansible (winrm)
WSL2 (Ubuntu)
Windows Server 2019