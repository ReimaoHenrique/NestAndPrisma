# Use a imagem oficial do PostgreSQL como base
FROM postgres:14

# Defina variáveis de ambiente para o banco de dados
ENV POSTGRES_DB=prisma_db
ENV POSTGRES_USER=prisma_user
ENV POSTGRES_PASSWORD=prisma_password

# Copie qualquer arquivo de configuração adicional, se necessário
# COPY ./my-custom-config.conf /etc/postgresql/postgresql.conf

# Exponha a porta padrão do PostgreSQL
EXPOSE 5432
