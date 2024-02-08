# TicketManager-Backend

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
