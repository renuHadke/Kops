FROM k8s.gcr.io/redis:e2e
#COPY redis.conf /usr/local/etc/redis/redis.conf
ENV REDIS_PASSWORD default-password
CMD ["sh", "-c", "exec redis-server --requirepass \"$REDIS_PASSWORD\""]
EXPOSE 6379
