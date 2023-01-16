Web-server with Axum and nginx proxy

1. Install nginx
    sudo pacman -S nginx

2. Type "cd /etc/nginx" and open nginx.conf
    cd /etc/nginx

3. Copy code from "/home/folder/where/you/download_lab13/lab13/proxy/todos.conf" to nginx.conf
    cp /home/mitrash/Projects/Mitrash/lab13/proxy/todos.conf /etc/nginx/nginx.conf

4. Type "sudo systemctl start nginx"
    sudo systemctl start nginx

5. Open terminal in lab13 folder

6. Type "cargo run"
    cargo run

7. Open browser and type "http://localhost:80/v1/todos/63443a02-2137-48e8-8db5-79fa54e8bfdf"
    http://localhost:80/v1/todos/63443a02-2137-48e8-8db5-79fa54e8bfdf