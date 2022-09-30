# CULT Education Games Microservice

The cult exchange microservice is inspired by give and take groups resp. [free your stuff](https://www.facebook.com/groups/freeyourstuffhd) groups.   

There will be a range slider to define in which radius you would like to offer your stuff or look for fancy stuff for yourself.  


In order to strengthen resilience, scalability, reusability via https and technological freedom for contributors, we establish a microservices architecture. 

## Status
First Drafts & Idea Collection

## Frontend
When it comes to state of the art web programming frameworks [Svelte](https://svelte.dev) is the framework [of choice](https://www.youtube.com/watch?v=rv3Yq-B8qp4) imo.    
The two main reasons for that choice - comparing svelte to angular, vue and react - are performance and simplicity.   
You might continuously improve the performance of this page utilizing [pagespeed.web.dev](https://pagespeed.web.dev/).   
To speed up programming while ensuring beauty we utilize the [UI Kit Attractions](https://illright.github.io/attractions/?ref=madewithsvelte.com) - see also [intro](https://www.youtube.com/watch?v=RkD88ARvucM&t=492s).

If you use VS Code as IDE you might want to install the extension named "svelte for vs code".  

## Backend
When it comes to off-chain backends [Deno](https://deno.land) is the runtime environment of choice imo.    
Deno can be perceived as the successor of NodeJS imo.  
You might check the [Deno Main Repo](https://github.com/denoland/deno) and join the [Deno Community](https://discord.com/invite/deno).

### Start Locally
To start the backend server locally you might execute:  

```sh
deno run --allow-read --allow-net --allow-write --allow-env backend/server.ts 8042
```

### Start in Production
```sh
pm2 start backend/server.ts --interpreter="deno" --interpreter-args="run --allow-read --allow-env --allow-net" -- 443
```


## Contribute
Please contribute via pull request. 

## Learnings & Remarks Along This Journey


## Act of Revolt Proposal
I submitted the creation of this [cultplayground.org](https://cultplayground.org) as an act of revolt.

### Name
I programmed https://cultplayground.org

### Handle
https://twitter.com/Peer2peerE

### Description
The https://cultplayground.org allows for coordinated community based micro acts acts of revolt.  
Those micro acts acts of revolt shall inspire people to invest in CULT & RVLT early.  
Our power is massive when we collaborate.   
Let us be together in playful creativity to free the world.  
Everyone is invited to support the emergence of manifold architectures of freedom by contributing to the code which can be found here: https://github.com/cultfamily-on-github/cult-education-games-microservice ...
I added the cycle keyword in some commitmessages - see evidencelink.

### Evidence Link
https://github.com/cultfamily-on-github/cult-education-games-microservice/commits/main

### Worth
0.25 WETH
### Wallet
0x9E972a43B3B8D68cD70930697E16429E47E88151

### Transaction of this Proposal
https://polygonscan.com/tx/0x75de42bddd54f562cc2a4360085d36ab546f73b249895ddebc7124f15f61cc85

### Act of Revolt ID
1042
