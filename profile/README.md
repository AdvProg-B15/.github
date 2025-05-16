# B15 Advprog Organization - Papikos

Group members:
- Carleano Ravelza Wongso (2306213022)
- Muhammad Albyarto Ghazali (2306241695)
- Fadhli Raihan Ardiansyah (2306207594)
- Adam Caldipawell Sembiring (2306227160)
- Muhammad Adiansyah (2306244980)

# Deliverables G.1

## Context Diagram
![B15 - Application Diagrams-C4 - System Context Diagram](https://github.com/user-attachments/assets/0642f189-265c-4444-b9c0-fa99140111a1)

## Container Diagram
![B15 - Application Diagrams-C4 - Container Diagram](https://github.com/user-attachments/assets/cef96fe1-5b03-47c6-983e-3cf12db4c3e1)

## Deployment Diagram
![B15 - Application Diagrams-C4 - Deployment Diagram](https://github.com/user-attachments/assets/ec5cf505-19f5-47d8-a2bc-e69b6948d7b1)

# Deliverables G.2
![B15 - Application Diagrams-C4 - Deployment Diagram (2)](https://github.com/user-attachments/assets/7ca03d6f-bbdb-42d7-8c1c-8ede51e54e36)

Karena aplikasi saat ini hanya mengandalkan service Auth sebagai cara mengautentikasi pengguna. Karena sifat bawaan JWT yang stateless, hal ini mungkin saja dapat menjadi celah untuk Session Hijacking. Akhirnya, kami memutuskan mungkin nanti kami akan menambahkan Authenticator Eksternal dari Google untuk me-manage setiap User. Jadi, session management akan menjadi lebih aman. Kami juga berencana untuk menambahkan message queue untuk mengatasi Race Condition jika setiap service bersifat synchronous.

# Deliverables G.3
