# Evidências - INSERT, UPDATE e DELETE no banco db_em 
## Identificação 
Nome: 
Turma: 
Data: 
--- 
# 1. SELECT final - Leituras do dia 2026-04-04 
Execute no DBeaver:
Trilha CRUD SQL - db_em - DBeaver 
```sql 
SELECT * 
FROM leituras 
WHERE timestamp >= '2026-04-04'  AND timestamp < '2026-04-05' 
ORDER BY timestamp ASC; 
``` 
Cole abaixo a saída obtida: 
```text 
cole aqui a saída do SELECT 
``` 
--- 
# 2. SELECT final - Conferência do UPDATE Execute no DBeaver: 
```sql 
SELECT * 
FROM leituras 
WHERE station_id = 'EM-ARACATUBA-01'  AND timestamp = '2026-04-04 09:00:00'; ``` 
Cole abaixo a saída obtida: 
```text 
cole aqui a saída do SELECT 
``` 
--- 
# 3. SELECT final - Conferência do DELETE Execute no DBeaver: 
```sql 
SELECT * 
FROM leituras 
WHERE station_id = 'EM-ARACATUBA-01'  AND timestamp = '2026-04-04 11:00:00'; ``` 
Cole abaixo a saída obtida: 
```text
Trilha CRUD SQL - db_em - DBeaver 
cole aqui a saída do SELECT 
``` 
Se o DELETE foi feito corretamente, esse SELECT não deverá retornar registros. --- 
# 4. SELECT final - Todas as leituras ordenadas 
Execute no DBeaver: 
```sql 
SELECT * 
FROM leituras 
ORDER BY id ASC; 
``` 
Cole abaixo a saída obtida: 
```text 
cole aqui a saída do SELECT 
``` 
--- 
# 5. Teste pela API 
Acesse no navegador: 
```text 
http://localhost:3000/api/leituras/data/2026-04-04 
``` 
Cole abaixo o resultado retornado pela API: 
```json 
cole aqui o resultado da API 
``` 
--- 
# 6. Conclusão 
Explique com suas palavras a diferença entre INSERT, UPDATE e DELETE. Resposta: 
```text 
cole aqui sua resposta
