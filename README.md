# Inventory Management Python

Sistema simples de controle de estoque e ponto de venda feito com Python/Tkinter e MySQL. O projeto permite buscar produtos, adicionar itens a uma venda, calcular total e registrar alteracoes no estoque.

## Tecnologias

- Python
- Tkinter
- MySQL
- Bootstrap/HTML para interface auxiliar

## Como executar

Instale as dependencias Python:

```bash
pip install mysql-connector-python
```

Crie o banco MySQL esperado pela aplicacao e ajuste as credenciais no codigo, se necessario.

Execute:

```bash
python main.py
```

## Estrutura

- `main.py` - interface principal de venda/consulta.
- `add_to_db.py` - cadastro de produtos.
- `update.py` - atualizacao de produtos.
- `web/` - arquivos auxiliares de interface web.

## Status

Projeto de estudo em evolucao. Antes de usar em producao, vale extrair configuracoes do banco para variaveis de ambiente e melhorar validacoes.
