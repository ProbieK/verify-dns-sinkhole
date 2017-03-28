# verify-dns-sinkhole    
Execute script either by:

$ for LINE in $(cat ./domainblacklist.txt); do ./verify-dns-sinkhole $LINE; done

OR

$ ./verify-via-list
