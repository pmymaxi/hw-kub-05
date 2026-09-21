# Хранение в K8s

## Задание 1. Volume: обмен данными между контейнерами в поде
Манифесты:
- containers-data-exchange.yaml

<img width="1408" height="1644" alt="hw-kub-05-01" src="https://github.com/user-attachments/assets/502a3611-73f4-4e6a-9e97-b700bfd4e05d" />
<img width="950" height="402" alt="hw-kub-05-02" src="https://github.com/user-attachments/assets/abdd4577-799c-401f-98f4-ce950bbdd50a" />

## Задание 2. PV, PVC
Манифесты: 
- pv-pvc.yaml

Удаление Kubernetes-объекта PV не означает удаление каталога hostPath на Linux-хосте. То есть:

kubectl delete pv data-pv ---> Удаляется объект PV в Kubernetes ---> opt/k8s/data НЕ удаляется
  
<img width="1004" height="1780" alt="hw-kub-05-03" src="https://github.com/user-attachments/assets/2b9cf596-0468-49d4-823e-4aa5bbbcfc6e" />

## Задание 3. StorageClass
Манифесты: 
- sc.yaml

<img width="1516" height="770" alt="hw-kub-05-04" src="https://github.com/user-attachments/assets/05530620-b952-40a0-9c7a-f4c542630cf5" />




