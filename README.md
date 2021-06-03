# A.C.E (Automated COVID Emailer)



Using Python modules and extensions, the app runs through the database to find passengers on the same flight as a suspected COVID case and sends templated email notifying the passengers via SMTP connection to the company mail server (requires account log in).

There are three different messages depending at the vicinity of the passenger and the suspected case:
- Within one seat - We regret to inform you that you've been within immediate vicinity with a suspected case of COVID-19.
- Within three seats - We regret to inform you that you've been in close vicinity of a suspected case of COVID-19.
- Within the same cabin - We regret to inform you that you've been on the same flight as a suspected case of COVID-19.

### A sample of the automated email 
<img width="1100" alt="image" src="https://user-images.githubusercontent.com/56251951/120663979-1f6c8200-c4bd-11eb-8be5-dae0389a8a6f.png">



### The Concept
- Use automated systems to notify customers in order to minimize manpower and increase efficiency.

### The Proposition
- Directly send out mass emails via extracting addresses from the database.

### The Value
- Diligent notification increases brand trust, and would incentivize customers to choose SIA.
- Make full use of resources in the state of reduced manpower.
