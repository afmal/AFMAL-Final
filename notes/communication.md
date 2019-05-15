# Communication
GET and POST requests are sent from the sample to the C&C in the form the URL: http://domain/path/?parameters=value1&parameter2=value2&...mark-token&...

The path of the request is one of a few different hard-coded and randomly selected values (i.e. open, close, find, search, watch...). The parameters are selected from a hard-coded list of values as well. The values of those parameters are randomly selected characters from a URL-safe base64 alphabet.
![enter image description here](https://github.com/afmal/projectp/blob/master/notes/images/eset-sednit-fig7.png?raw=true)



**Sources:**
eset - [https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf](https://www.welivesecurity.com/wp-content/uploads/2016/10/eset-sednit-part-2.pdf)

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjUyNTk4MzM1LDE5NzM2NjgwMzMsLTg2Nj
UxMTQ0OF19
-->