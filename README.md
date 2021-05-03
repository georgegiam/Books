# University of Southampton Book Exchange

This project aims to build a React application that allows Southampton students to buy and sell books. The application will allow sellers to advertise book they wish to sell, and buyers can browse the available book and request to buy it. The application host all the relevant details regarding the book, such as name, price and category buyer/seller information and the exchange detail. The platform does not deal with payments. However, the exchange appointment is managed by the application. 

## Implemented features
- Browse available books, search a book by title and view a book to buy (auto-complete functionality)
- Add a book to advertise with title, price, condition, type, description and image
- View all purchased books or books requested with their status
- Buyers can leave a review 
- Sellers can view their notifications
- Users can create an account with their university email or sign in with their Google account
- The seller can see a list of their available books to either delete them or edit them


## Dependancies
1. You will first need to install [Node.js](https://nodejs.org/en/)
2. Then you have to download [Create React App](https://github.com/facebook/create-react-app).
3. Finally you will need to install the following packages:

### Bootstrap 
```sh
npm install react-bootstrap bootstrap
```
### React Icons 
```sh
npm install react-icons --save
```
### React Aux 
```sh
npm i react-aux
```
### Google Firebase
```sh
npm install firebase@8.4.3 --save
```
## Running the App
In the project directory, you can run:

```sh
npm start
```

This command will runs the app in the development mode and you can view it by opening [http://localhost:3000](http://localhost:3000) in the browser.
