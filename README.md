## **Tegger BlockChain App**


This project contains following:
+ Gets Data from **coincap api** and display them.
+ You can see the top 20 token data in the table.
+ You can see the detailed price information if you click the row of table.
+ Also you can filter tokens by their name.
+ http://37.122.209.216:3177/ You can access the app here(available for next 2 days)

### **Framework**
It is built using the following Framework
+ Built using **MERN stack**.
+ **Backend** - Node/express.js and **Frontend** - React.js.

_____________________________________
-------------------------------------
#### **Running the code**

To Run the Development frontend server, please open the terminal in the project root directory and run the following commands.

     cd frontend
     npm install
     npm start (yarn start)


To build the frontend project you can run the following command.

```
npm run build (yarn build)
```

To run backend (node.js) server, please run the following commands in the project root directory.

``` 
cd backend
npm install
npm start (yarn start)
```


### **Other details**

+ The frontend project is bootstrapped from create-react-app.
It uses redux for state management and all components are functional components and uses hooks.

+ It sends request to the node.js backend to get required data.
In the layouts directory, you can see main layouts.

+ In the pages directory, you can see main pages. (Currently there are 2 pages.) and in the components directory, you will see the components.

+ In the backend, it calls apis to get required data.
