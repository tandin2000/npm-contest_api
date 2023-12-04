# Contest Api

it returns a list of contests like hackathons, programming contests, etc..


## Installation

```bash
npm i contest_api
```

## Usage

```JavaScript
const clist = require("contest_api"); // import the installed package

clist()
  .then((res) => {
    // If the function successfully retrieves the data, it enters this block
    console.log(res); // Print the contest data on the console
  })
  .catch((err) => {
    console.log(err); // Error handler
  });
```