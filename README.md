# donedone.js
Donedone API wrapper

## Example usage

const Donedone = require("donedone.js");

let donedone = new Donedone({
	subdomain: "your-donedone-subdomain-name",
	username: "bob",
	apikey: "12345"
});

donedone.getCompanies(function(companies){
	console.log(companies);
});
