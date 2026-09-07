# UniFi Network Application & MongoDB Stack

Stack em Docker Compose para o UniFi Network Application integrado com banco de dados MongoDB 7.0 otimizado para alta performance.

## 🚀 Otimizações de Desempenho Aplicadas

- **UniFi Controller**: Heap Java otimizado (`MEM_LIMIT: 1792M`, `MEM_STARTUP: 768M`) para eliminação de travamentos por Garbage Collection.
- **MongoDB 7.0**: Limite de CPU elevado para 1.0 core e cache WiredTiger ajustado para `0.40GB` para consultas de alta velocidade.
- **Segurança**: Senhas de ambiente isoladas via arquivo `.env`.

## 🛠️ Tecnologias Utilizadas

- **UniFi Controller**: `lscr.io/linuxserver/unifi-network-application:10.0.162`
- **Database**: MongoDB 7.0
- **Infraestrutura**: Docker & Docker Compose
