University: ITMO University

Faculty: FICT

Course: Network programming

Year: 2024/2025

Group: K3320

Author: Mostafa Abdallah

Date of create: 10.04.2025

Date of finished: 10.04.2025

**Настройка виртуальной машины в YC**

Развернул виртуальную машину в YC
![image](https://github.com/user-attachments/assets/9ae64db5-6e22-45df-9d3b-457de7429083)
**Установил на нее Wireguard, сгенерировал сертификаты.**

sudo apt install wireguard -y

wg genkey | sudo tee /etc/wireguard/private.key

sudo cat /etc/wireguard/private.key | wg pubkey | sudo tee /etc/wireguard/public.key

**Задал файл конфигурации WG conf**

![image](https://github.com/user-attachments/assets/787b076b-53a3-464b-bcdf-59d2b4030676)

**Настройка CHR**

Настроил конфигурацию микротик

![image](https://github.com/user-attachments/assets/82dbcfef-7071-4faa-a17e-96e4ab1ff86b)

**Проверка работоспособности**

Из CHR в виртуалку в клауде

![image](https://github.com/user-attachments/assets/0fe79414-865e-4247-9740-45f93cfd98f4)

Из ВМ в CHR.

![image](https://github.com/user-attachments/assets/af8b87fa-2fd1-426f-a3cb-7ec6a92bb163)


