# reactTutorial
A simple react blog application created while learning React Tutorial. Thanks to Net Ninja for the React tutorial.
https://www.youtube.com/watch?v=j942wKiXFu8&list=PL4cUxeGkcC9gZD-Tvwfod2gaISzfRiP9d

---
In this tutorial, I learnt several thing about React JS such as components, hooks, routing, and even using a JSON server as a local API gateway to fetch data. A basic Create, Retrieve and Delete application is done in this tutorial through the help of API fetching.

Learnt:
- components (navbar, different pages) 👍
- hooks (useState, useEffect) 👍
- props (passing data from one page to another) 👍
- Routing (BrowserRouter, Route, Routes, Link, useParams) 👍
- Custom hooks (useFetch) 👍
- API fetching via ```fetch``` (Create, Retrieve, Delete) 👍
- Form inputs 👍
- Local JSON database (JSON server) 👍

In order to create a local JSON database, create a db.json filled with data and run
```
npx json-server --watch data/db.json --port 8000
```
example db.json screenshot:
![image](https://github.com/Siongyu/reactTutorial/assets/21031725/3d1a594f-8563-4dc0-9c4b-41c534eb6583)

---
React Tutorial application screenshot:
#### Homepage
![image](https://github.com/Siongyu/reactTutorial/assets/21031725/cef61904-6f10-421a-93ce-193797d68e04)

#### New Blog
![image](https://github.com/Siongyu/reactTutorial/assets/21031725/73d4cd28-42c7-4ba7-a243-6e9b39305569)

#### Blog Details (filter by id)
![image](https://github.com/Siongyu/reactTutorial/assets/21031725/96002faa-4ccf-41ca-bd85-5ee30a37f8e6)

#### Error 404 page (accessing pages that is not in the router)
![image](https://github.com/Siongyu/reactTutorial/assets/21031725/b916decf-a13c-4d74-b06e-ab94e2af035c)

---
Before running the project after pulling, 
run ```npm install``` at the root project folder to install the node module dependencies then ```npm start```
