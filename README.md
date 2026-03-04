# System-Administration-and-IT-Infrastructure-Services

- **htdocs** – Default web root folder for Apache  
- **MyLocalServer** – Custom folder for test website  
- **index.html** – HTML file served by the server

---

## Steps to Set Up the Server

1. **Install XAMPP**
   - Download from [https://www.apachefriends.org](https://www.apachefriends.org)  
   - During installation, select **Apache**  
   - Install in `C:\xampp`  

2. **Start Apache Server**
   - Open **XAMPP Control Panel**  
   - Click **Start** next to Apache  
   - Ensure it turns **green (Running)**

<img width="661" height="422" alt="XAMPP CONTROL PANEL" src="https://github.com/user-attachments/assets/a65543f4-370f-4c32-8f33-a2231ef1d480" />

3. **Test the Server**
   - Open a browser  
   - Go to: `http://localhost`  
   - XAMPP welcome page should appear

<img width="1010" height="658" alt="webpage 2" src="https://github.com/user-attachments/assets/b080dd6d-d457-45fa-8db6-fac55745bf11" />

4. **Create Test Website**
   - Navigate to `C:\xampp\htdocs`  
   - Create folder `MyLocalServer`  
   - Inside, create `index.html` with the following code:

<img width="772" height="575" alt="folder" src="https://github.com/user-attachments/assets/85944dc1-6355-4ad4-b468-1851afe1eedd" />

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Local Server</title>
</head>
<body>

<img width="985" height="406" alt="image" src="https://github.com/user-attachments/assets/c2d6fa9a-1601-49f5-bf4e-5de79d59d7e7" />

    <h1>Server is Working Successfully!</h1>
</body>
</html>

<img width="985" height="406" alt="image" src="https://github.com/user-attachments/assets/37e822af-17ae-494b-b973-a1c82d78d86b" />
