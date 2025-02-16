# Instalación de openvas en Kali Linux

Comandos necesarios para instalar la versión gratuita de Greenbone en Kali linux

### 1. Ejercutar los comandos en el orden mostrado.

```bash 
sudo apt install openvas
```

```bash 
sudo gvm-setup
```

```bash 
sudo apt gvm-check-setup
```

### 2. Luego de ejecutar el siguiente comando guardar la contraseña generada.

```bash 
sudo runuser -u _gvm -- gvmd --create-user=admin --new-password=password
```

### 3. Acceder por medio del navegador a la siguiente URL

https://127.0.0.1:9392/login

