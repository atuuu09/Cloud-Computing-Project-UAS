# Gunakan image Nginx resmi
FROM nginx:alpine

# Hapus file default Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copy semua file ke direktori html di dalam container
COPY . /usr/share/nginx/html

# Buka port 80
EXPOSE 80
