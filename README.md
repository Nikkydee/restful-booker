 API Automated Tests


> "This repository contains the automated API task provided in the assessment.

## Built With
- Postman
- newman runner
- Github
- html report
- nodejs
  


## Getting Started
To get a local copy of the program running, follow these simple steps

### Prerequisites
- Postman should be fine too
- To run using CLI, Install nodejs. Once installation of node and npm has been confirmed 
- run 'npm install -g newman
- verify installation with newman -v

  

### Install
- Postman
- newman runner


### Setup- Postman runner
- Open a command line terminal (Git bash preferrably) and navigate to a directory where you would like to save the work folder using cd.
- Clone the repository with git clone https://github.com/Nikkydee/restful-booker.git
- To get the current working tree, git fetch --all, then checkout to "main" branch.
- Finally, import the project to postman 
- Open, right-click on the collection ans select run collection
### Setup- newman runner

   - Invariably, tests can be run on CLI using newman runner
   -Open terminal or cmd >> navigate to the JSON file location
   - run this command 'newman run Restful-booker.postman_collection -e Booking.postman_environment
   - generate report using this command 'newman run Restful-booker.postman_collection -e Booking.postman_environment -r html

### Output
- After the execution of the test, the result will be generated.
    - Report: it will be located at src/Reports/ It is an HTML file that contains the status of each test case run with screenshots of failed test cases.


## Author

👤 **Adenike Olapetan**

- GitHub: [@Nikkydee](https://github.com/Nikkydee)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!


## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments
- Shout out to [Onafriq](https://onafriq.com/) for the opportunity

## 📝 License

This project is [MIT](./LICENSE) licensed.
