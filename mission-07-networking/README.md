# mission 7 - how computers communicate

## 1. task / objective
explain network concepts, test network commands, and describe how a website opens

## 2. work completed
completed network concepts table, recorded ping and nslookup observations, and wrote step by step website loading process

## 3. commands / tools used
ping, nslookup

## 4. my understanding

### task 7.1 - explain network concepts

| concept | explain it in your own words | example |
| :--- | :--- | :--- |
| lan | local network covering small area like a room or office | home wifi network |
| man | network covering a city or university campus | campus network |
| wan | network covering large geographic areas or countries | the internet |
| dns | translates website names into ip addresses | converting example.com to ip address |
| router | device that forwards data between different networks | home wifi router |
| protocol | set of rules devices follow to communicate | http and https |
| packet switching | breaking data into smaller packets that travel across network | sending data across internet |
| client-server | client requests services and server provides them | browser asking website from web server |

### task 7.2 - observe network information
tested ping and nslookup commands:
- ping checks if a remote server can be reached and measures response time
- nslookup displays the ip address associated with a domain name
- role of dns: when you type a website name, dns finds the server ip address so the browser knows where to connect

privacy-safe observation:
domain: example.com
ip address: [redacted]
packet loss: 0%

### task 7.3 - what happens when you open a website?
1 user types website url in client browser
2 client asks dns server to find ip address of domain name
3 dns server returns destination server ip address to client
4 client sends request packet to local router using http or https protocol
5 router sends packets across network using packet switching to reach web server
6 server processes request and sends back webpage data packets
7 client browser receives data packets and displays webpage to user

## 5. difficulties faced
no major difficulties

## 6. how i resolved them
not applicable

## 7. evidence / files
network notes in this readme

## 8. commit details
commit message: explain networking concepts and website communication
