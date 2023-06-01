# Sample-Trading-App
Sample-Trading-App

Sample trading system using Springboot and Heroku

Something that can :
POST /account to open an account
POST /orders to submit an order
POST /orders to submit a sell order (as a diff account)

Match the two orders if they agree with each other (if seller asking price is lower than buyers bid)

Also GET /positions/:accountId  to see positions

Once order is matched - positions/ should now show that 1 party is long that much stock and another is short that much
