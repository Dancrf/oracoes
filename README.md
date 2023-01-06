# oracoes

API que retorna orações extraídas do portal "Pocket Terço"

## Uso da API
#### Listar todas as orações:

```http
  GET /api/
```
<br>

#### Listar todas as orações de determinada categoria:

```http
  GET /api/categoria/${categoria}
```
<details><summary>Categorias disponíveis:</summary>

| Categorias |
| :---: |
| doutrina |
| meditacao | 
| missal |
| santos |
| diversas |
| papa |
| latim |
| oracoeseucaristicas |
| indulgencia |
| diaadia |
| prefacios |

</details>

<br>

#### Listar oração pelo nome:

```http
  GET /api/nome/${nome}
```

| Parâmetro | Tipo     | Descrição:                       |
| :-------- | :------- | :-------------------------------- |
| `nome`      | `string` | **Obigatório**. Título da oração |

<br>

#### Listar oração pelo ID:

```http
  GET /api/id/${id}
```

| Parâmetro | Tipo     | Descrição:                       |
| :-------- | :------- | :-------------------------------- |
| `ID`      | `number` | **Obigatório**. ID da oração (2~565) |


## Outros:

 - [API que fornece a liturgia diária](https://github.com/Dancrf/liturgia-diaria)

