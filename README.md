#### A template for selling your unused domains via Flippa
___

A simple, self-hosted alternative to Flippa's [domain sales page](https://salespage.flippa.com/), powered by Jekyll and Github Pages.   

##### Usage

1. Get your [Flippa account](https://flippa.com/) and add your domains  
1. Update `_config.yml`  
1. Update `CNAME`  
1. Create A records at your DNS provider pointing to `192.30.252.153` and `192.30.252.154` per the [docs](https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/#configuring-an-a-record-with-your-dns-provider)  

##### Analytics  

- To enable Google Analytics, enter your ID in `_config.yml`, otherwise leave blank  
- Each of the three buttons will send click events  
- For funnels, the click event is structured as follows: `ga('send', 'event', 'FlippaButton', 'Click', 'yourdomainname-MakeOffer')`  

##### TODOs  

- ~~Add Google Analytics~~  
- Add license (MIT, pending Flippa approval)  

##### Troubleshooting

[Setting up a custom domain on Github Pages](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/)  
