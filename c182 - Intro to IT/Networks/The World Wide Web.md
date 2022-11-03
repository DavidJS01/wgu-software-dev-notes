**Why was the World Wide Web created?**
Tim-Berners-Lee realized that combining hypertext (linked documents) with internet technology could have great potential

**What composes the World Wide Web?**
The World Wide Web is composed of a hypertext document format for embedding hyperlinks to other documents and a server process that supplies hypertext pages upon request

Today, the WWW also supports images, audio, and video

**What are browsers and servers?**
1. Browser
	1. Resides on user's machine to obtain the requested data and present them to the user in an organized way
2. Web Server
	1. The web server resides on the computer containing the hypertext document
		1. HTTP [[Internet Addressing and Applications#^53a777|protocol]] or other ismilar protocols transfer data between web servers and browsers

**What is a URL?**
Every hypertext document available through the World Wide Web is given a unique address called a uniform resource locator (*URL*)

**What do URLs contain?**
URLs contain information that indicates the location of documents on the server. They contain all of the following:
1. protocol
2. domain
3. subdomains
4. resource path ID
5. name of the document

**What is HTML?**
HyperText Markup Language is a way of encoding a document. Tags describe how the document should appear on a display (`<h1>, <p>, etc.`), what multimedia resources should accompany the document, and which elements within the document are linked to other documents

```
<html>

<title> ... </title>

<body> ... </body>

</html>
```

**What is XML?**
XML is an extensible markup language that provides a standardized style for designing notation systems for representing data as text files. JSON is becoming more preferred and used in APIs

```
<note>  
  <to>Tove</to>  
  <from>Jani</from>  
  <heading>Reminder</heading>  
  <body>Don't forget me this weekend!</body>  
</note>
```