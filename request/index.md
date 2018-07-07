---
layout: default
---

<h1>engrXiv Request Button</h1>

The engrXiv Request Button, also known as the Open Engineering Button, is a simple bookmarklet for drafting an email request for the article you want access to. You fill in the required details and hit send.

### Requirements
1. You must be on the page of the article you want access to.
2. The article should be from engineering.
3. Fill out all of the information in the drafted email.

### Usage
1. Drag the following link to your bookmark bar: [engrXiv request](javascript:(function(){location.href='mailto:request@engrxiv.org?SUBJECT=Open%20Engineering%20Request&BODY=URL%3A%20'+escape(location.href)+encodeURI('\r\nAuthor%20Email:%20\r\n\r\nYour%20Name:%20\r\nYour%20Affiliation:%20\r\nReason%20for%20request:%20')})();)
2. Navigate to the article you'd like to request.
3. Click the bookmarklet.
4. A draft email should open in your default email client. Complete the fields of this email.
5. Hit send.
6. We will request the article from the author and notify you if and when they upload a copy to engrXiv.

## Bookmarklet: [engrXiv request](javascript:(function(){location.href='mailto:request@engrxiv.org?SUBJECT=Open%20Engineering%20Request&BODY=URL%3A%20'+escape(location.href)+encodeURI('\r\nAuthor%20Email:%20\r\n\r\nYour%20Name:%20\r\nYour%20Affiliation:%20\r\nReason%20for%20request:%20')})();)
