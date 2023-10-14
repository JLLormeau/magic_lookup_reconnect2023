# Automate business analitycs with DQL lookup command
![Delay_payment](https://github.com/JLLormeau/reconnect2023/blob/main/payment_delay.png?raw=true)

## Upload Notebook

![image](https://github.com/JLLormeau/magic_lookup_reconnect2023/assets/40337213/bd703ab3-f146-47ce-a5df-b1a9e0e58cd0)

Copy paste this URL directly in your upload : 
  
    https://raw.githubusercontent.com/JLLormeau/magic_lookup_reconnect2023/main/magic_lookup%20_reconnect2023.json  


## DEMO in 3 steps 
1) Calculate the payment delay  

- With 2 lookups through 3 datasources  

3) Calculate the SLO   

- Objectif : 99% of payment delay < 6m on default period  

3) Create the workflow  

- If SLO is not successful  
Send the result on the webhook.site  
Ingest the values on your tenant.  
![image](https://github.com/JLLormeau/magic_lookup_reconnect2023/assets/40337213/97715d42-c287-4cf5-9360-b20a9a14cdd9)
