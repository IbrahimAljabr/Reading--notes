## Read 13

# SENDING FORM DATA

Once the form data has been validated on the client-side, it is okay to submit the form.

### What happend when you submit a form

- An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.
- The names and values of the non-file form controls are sent to the server as name=value.
- The action value should be a file on the server that can handle the incoming data, including ensuring server-side validation.
- handling the data and loading the URL defined by the action attribute, causing a new page load (or a refresh of the existing page, if the action points to the same page).

## The GET method

The GET method is the method used by the browser to ask the server to send back a given resource,  if a form is sent using this method the data sent to the server is appended to the URL.

## The POST method 

The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.
the data is appended to the body of the HTTP request.

## Retrieving the data

Whichever HTTP method you choose, the server receives a string that will be parsed in order to get the data as a list of key/value pairs. The way you access this list depends on the development platform you use and on any specific frameworks you may be using with it.



