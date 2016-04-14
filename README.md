# angular2-facebook
##Learn how to integrate Facebook login in angular2 framework. 
As there is no good angular2 component available for same, I struggled a bit searching on internet and tried to figrued out how to do it with angular 2. in the last, after spending more than 10 hours, I figured out by modifying the current integration code and making it suitable for integration with angular 2. Looking back, it is very easy and straight forward. but I am adding the componentized code here so that no one else loses a night on the same problem.

##Pre-requisites:
1. I have used bootstrap css and bootstrap-social css library for the HTML button. include the following lines in your index.html code
"
<link href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-social/4.12.0/bootstrap-social.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
""

2. For facebook, I have used facebook javascript SDK. just add the following line in your index.html
"
<script src="//connect.facebook.net/en_US/sdk.js"></script>
"

##Steps for integration: 
1. Copy the 'facebooklogin.component.ts' file in your components directory of your project.
2. Copy the 'facebooklogin.html' in the place where you keep htmls. In case, you are not using templateUrl but using template in your component , then copy the HTML code in template 
3. copy <cp-facebook-login></cp-facebook-login> HTML tag in the place you want to show the facebook login button.

It should work as it is. If you face errors, let me know or fork it and improve it. I have created this only for my project use, but will be happy to fix any issue if i find time.
 



