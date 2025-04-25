# Meu projeto DevOps


# Diagrama base:

Usuário -> Azure Application Gateway -> AKS Cluster
                                         |-> Frontend Pod (React)
                                         |-> Backend Pod (API)
                                         |-> Secrets via Key Vault
                                         |-> DB via Azure PostgreSQL
