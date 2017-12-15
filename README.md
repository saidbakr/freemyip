# freemyip
Simple HTML and JavaScript update [**freemyip**](http://freemyip.com) dynamic DNS domains
## Usage
Download the file named `FreeMyIP.html` and just edit the array named `domains` by adding each one of your domains as an object to that array. For example:

```javascript
var domains = [
   {domain: 'example.freemyip.com', label: 'Example Site', token: 'TheTokenStringOfTheDomain', btnClass: 'btn-warning'}
]
```
The last property of the object `btnClass` is optional and it is used to define another class other than `btn-primary` of the bootstrap CSS framework.

After filling the array with your domains data, save the file and then open it using your favorite web browser and click on each of domain button to update its IP with your current public IP.

## Todo
Adding AJAX functionality to parse the response after JSON object response supported by the services.
