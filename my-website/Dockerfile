# Nginx use kar rahe hain ek simple static web server ke liye
FROM nginx:latest

# Static website files ko Nginx default directory mein copy karna
COPY index.html /usr/share/nginx/html/

# Nginx ko port 80 par run karne dena
EXPOSE 80

# Nginx process ko start karna
CMD ["nginx", "-g", "daemon off;"]
