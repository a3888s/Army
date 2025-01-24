# Використовуємо офіційний образ nginx
FROM nginx:latest

# Оновлюємо пакети та встановлюємо nano і vim
RUN apt-get update && apt-get install -y nano vim && apt-get clean

# Виставляємо порт 80
EXPOSE 80

# Запускаємо nginx
CMD ["nginx", "-g", "daemon off;"]
