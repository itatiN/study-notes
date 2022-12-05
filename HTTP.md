# Resume
Is a transafer protocol that allows people who enter a URL to your website to view the content and data on your website. The acronym is for Hypertext Transfer Protocol.

## HTTP vs HTTPS
HTTPS offers encryptation for the site. The S stands for Secure. He's often offers to a SSL certificade. The connection of the browser and the server is encrypt to make user can insert informations with more security.
HTTP do not offer end-to-end encryptation.

## HTTP Request
A http request is a way that client can make a request to the server. That request often contents a serie of things that are used to describe what exactly the client need. There are a basic list of comand that represend the CRUD ( create, read, update, delete) but there a lot more request than this list. If you need a more especific command go to the [documentation](http://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods) .

	Get: Used to obtain resources from the server.
	Post: Is when the client need to send informatin to the server.
	Put: Used to update the proprerties of a request.
	Delete: As the name sugest, is used to delete a information.

## HTTP Response
WIth every request comes a response, in HTTP the response is usually a code that represents a situation about the request. 

	1XX: Informative
	2XX: Indicatives of sucess
	3XX: Redirection
	4XX: Error on client-side
	5XX: Error on server-side

The most communs responses is: 

	200 - Everything fine
	301 - Permanent redirection
	401 -  Not authorized
	404 - Resource not exist