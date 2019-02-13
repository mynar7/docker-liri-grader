To grade the bamazon HW, use
`docker-compose up --build`
 then when console output stops, open new terminal and run
 `docker-compose exec node sh`
 this opens a bash shell in the container, allowing you to run
 `ls`
 `node bamazonCustomer.js`