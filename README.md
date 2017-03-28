# verify-dns-sinkhole    
Execute script either by:

$ for LINE in $(cat ./domainblacklist.txt); do ./verify-blocked-domains $LINE; done

OR

$ ./verify-via-list
