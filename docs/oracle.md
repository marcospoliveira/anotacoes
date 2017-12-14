##Descobrir tabelas do GATEC

Se logado com usuário `gatec_saf`

```SQL
SELECT * FROM USER_TABLES WHERE TABLE_NAME LIKE '%PEDIDO%' 
```

Se logado com usuário `queryti`

```SQL
SELECT * FROM ALL_TABLES WHERE TABLE_NAME LIKE '%PEDIDO%' AND OWNER = 'GATEC_SAF';
```