FROM bitnami/postgresql:16

CMD PGPASSWORD=${POSTGRESQL_PASSWORD} pgbench -i -s 10 --host=${POSTGRESQL_HOSTS} --port=${POSTGRESQL_PORT} --username=${POSTGRESQL_USERNAME} ${POSTGRESQL_BENCH_DB}