
# Web_Search_Engine

 A Web search engine is a specialized computer server that searches for information on the Web. 
 The search results of a user query are often returned as a list (sometimes called hits). 
 The hits may consist of web pages, images, and other types of files. 
 Some search engines also search and return data available in public databases or open directories. 
 Search engines differ from web directories in that web directories are maintained by human editors whereas search engines operate algorithmically or by a mixture of algorithmic and human input.

## Tech Stack

**:-** Java, Html, Css, Rest-API, Maven, MySql, Jdbc,Java Servlets




## Features

- Store the data from javaTpoint website using DFS algorithm
- Search anything from the website 
- You can get link and some text related to your query
- History bar for save your query as a title and link which is opened by you 


## API Reference

#### Get all items

```http
  GET /javax.servlet:javax.servlet-api4.0.
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. javax.servlet-api4.0.1 |

#### Get item

```http
  GET /api/items/${HttpServlet }
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. HttpServlet  |


## Screenshots
#### Front Page
This is the simple view of over Search engine here we have to options one is Search and another one is History what ever you want you choose.

![App Screenshot](https://github.com/shivam-sharma0/Web-Search-Engine/blob/main/src/main/Screenshot%202023-04-01%20182455.png?raw=true)

#### Search Page
This is our search when you write you query in the search bar and click on the search it will show you some links and text related to your query.

![App Screenshot](https://github.com/shivam-sharma0/Web-Search-Engine/blob/main/src/main/Screenshot%202023-04-01%20182544.png?raw=true)

#### History Page
History page basically store the data what ever you search in the search bar and when you click on this it will redirect to you a page there is history of activities.

![App Screenshot](https://github.com/shivam-sharma0/Web-Search-Engine/blob/main/src/main/Screenshot%202023-04-01%20182618.png?raw=true)
