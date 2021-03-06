<p align="right">  
  <a href="https://github.com/Blugin/PaymentPool/blob/master/docs/kor/HowTo-use.md">  
    <img src="https://img.shields.io/static/v1?label=%ED%95%9C%EA%B5%AD%EC%96%B4&message=%EB%A1%9C+%EC%9D%BD%EA%B8%B0&labelColor=success">  
  </a>  
</p>  
  
## :book: How to use? - for user  
  
## How to use commands? `/payment <Set | Payments | Links | Install>`  
> All commands support Minecraft's autocomplete feature  
<img src="https://ghcdn.rawgit.org/Blugin/PaymentPool/master/docs/in-game-command-screenshot.png" width="100%">
----------  
<br>    
  
### /payment Set <Link: `PaymentLink`> <Payment: `Payment`>  
- This command sets which payment method to connect to each link (plug-in)    
> If you want to connect a shop plugin called `PayShop` to `economyapi`:  
````  
/payment set PayShop economyapi  
````  
  
- The link name for the default payment method is `@`  
- If the default payment method is not set, it is connected to a random payment method, so if there are multiple payment methods, you must set it    
> If `economyapi` is your default payment method:  
````  
/payment set @ economyapi  
````  
<img src="https://ghcdn.rawgit.org/Blugin/PaymentPool/master/docs/command-set-demo.png" width="100%">
----------  
<br>  
  
#### /payment Payments [Page: `int`]  
- This command displays the list of registered payment methods  
<img src="https://ghcdn.rawgit.org/Blugin/PaymentPool/master/docs/command-payments-demo.png" width="100%">  
----------  
<br>  
  
#### /payment Links [Page: `int`]  
- This command displays the list of registered links (In general, the plugin)  
<img src="https://ghcdn.rawgit.org/Blugin/PaymentPool/master/docs/command-links-demo.png" width="100%">  
----------  
<br>  
  
#### /payment Install  
- This command is automatically installed when the payment method plug-in on the server is registered  
<img src="https://ghcdn.rawgit.org/Blugin/PaymentPool/master/docs/command-install-demo.png" width="100%">  
  