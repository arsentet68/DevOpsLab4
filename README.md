# Полынский Арсений. ФИТ-2-2024 НМ. Методы и инструменты DevOps. ЛР по лекции 4

## Установка ansible
Устанавливаем ansible на первой машине
```
sudo apt install ansible
```

## Подготовка плейбука
Создадим файл playbook.yml в директории lab-ansible

```
cd lab-ansible/
touch playbook.yml

```
<img width="398" height="325" alt="image" src="https://github.com/user-attachments/assets/626a365b-dc77-41eb-81cf-5483490044b1" />

## Подготовка inventory
Создадим файл inventory.ini в директории lab-ansible

```
cd lab-ansible/
touch inventory.ini

```
<img width="99" height="35" alt="image" src="https://github.com/user-attachments/assets/201b047a-04b6-4359-a992-daf0b850fdb5" />

## Запуск плейбука
Запустим плейбук и увидим что он выполнился успешно
<img width="1276" height="261" alt="image" src="https://github.com/user-attachments/assets/e66a19bd-e1a0-4b8d-a51e-a3c91ada084e" />
Проверим результат в браузере на хостовой машине
<img width="537" height="158" alt="image" src="https://github.com/user-attachments/assets/d27d90bd-64d3-4901-aba4-f9fa2521ed75" />
