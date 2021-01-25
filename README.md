# DNS
DNS
#     DNS.ps1

# Description: 
#     Query a DNS server, and validate the response
#     This function uses the ActiveXperts Network Component, an ActiveXperts product.
#     ActiveXperts Network Component is automatically licensed when ActiveXperts 
#     Network Monitor is purchased
#     For more information about ActiveXperts Network Component, see: 
#       www.activexperts.com/network-component
# Parameters:
#     1) strDnsServer - Host name or IP address of the (remote) DNS server
#     2) strHost - Hostname or domain to query
#     3) strExpectedValue - expected value 
# Usage:
#     .\DNS.ps1 '<Hostname | IP>' 'host' '<expected value>'
# Sample:
#     .\DNS.ps1 'DC01.contoso.com' 'smpp.activexperts-labs.com' '84.53.114.73'
  #   .\DNS.ps1 'DC01.contoso.com' 'google.com' '216.58.201.110'a
