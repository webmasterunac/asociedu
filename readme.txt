USING THE MAILCHIMP FORM:

To use the mailchimp form you need a mailchimp url. To get the mailchimp url, login to 
your mailchimp account, click the list menu, click the stats download menu and select signup forms. 
Then choose embedded forms and select naked form. In the generated form code get the value of 
the form ACTION attribute and use it as your mailchimp url. Open the main.js file located
in the template's "js" folder and look for this line of code: 

var cfg = {
    scrollDuration : 800, // smoothscroll duration
    mailChimpURL   : 'https://facebook.us8.list-manage.com/subscribe/post?u=cdb7b577e41181934ed6a6a44&amp;id=e6957d85dc'   // mailchimp url
},






