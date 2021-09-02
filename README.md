
# Project Title

A brief description of what this project does and who it's for


## Acknowledgements

 - [deep fake](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [tutorial 1](https://github.com/matiassingers/awesome-readme)
 - [tutorial 2](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)

  
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.
