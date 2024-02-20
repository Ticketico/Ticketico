# TicketManager-Backend

## Successful Response Code Agreements

+ LS => logged in successfully //Not Used
+ SS => signed up successfully

+ UES => user editted successfully

+ PAS => product added successfully
+ PES => product editted successfully
+ PDS => product deleted successfully

+ TAS => ticket added successfully
+ TES => ticket editted successfully
+ TDS => ticket deleted successfully

## Error Response Code Agreements

+ PAICDM => password and its confirmation don't match
+ PAIW => password is weak
+ UOPIW => username or password is wrong
+ NEF => not enough fields
+ PAF => product add failed
+ ISE => internal server error

## Configs

+ docker-compose exec postgres psql -U admin -d newdb -f /tmp/seed.sql
+ git clone --recurse-submodules [git remote address]

## How To Run Project
