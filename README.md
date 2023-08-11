# Personal Website Hosted on Raspberry Pi


## About

Welcome to the repository for my personal website, which I have successfully hosted on a Raspberry Pi! This README will guide you through the process of creating the website, purchasing a domain name, and setting up the Raspberry Pi for hosting.

## Creating the Website

I designed and developed my personal website using HTML, CSS, and JavaScript. The website showcases my portfolio, projects, and a blog section where I share my experiences and insights. I optimized the website for responsiveness, ensuring a seamless experience across various devices.

## Purchasing a Domain Name from GoDaddy

To make my website accessible under a custom domain name, I registered a domain name from GoDaddy. I chose the domain name "marvinresume.com" for simplicity. Here's how I linked it to my Raspberry Pi:

1. I logged into my GoDaddy account.
2. In the domain settings, I edited the DNS records to point the A record to the public IP address of my home network.

## Setting Up Port Forwarding

For external users to access my website hosted on the Raspberry Pi, I configured port forwarding on my router:

1. I accessed my router's settings page through a web browser.
2. In the port forwarding section, I added a rule to forward incoming traffic on port 80 (HTTP) to the local IP address of my Raspberry Pi on my home network.

## Hosting the Website on Raspberry Pi

I set up my Raspberry Pi as a web server to host the website:

1. I installed a web server software (such as Apache or Nginx) on the Raspberry Pi.
2. I copied the website files to the appropriate directory on the Raspberry Pi.
3. I configured the web server to serve the website files when users access my domain.

## Accessing the Website

Now, my personal website is accessible to the world by visiting [resume.com](http://www.marvinresume.com). The domain name points to my Raspberry Pi, and users can view my portfolio and blog posts from anywhere.

## Conclusion

Hosting my personal website on a Raspberry Pi and linking it to a custom domain name has been a rewarding experience. It showcases my technical skills while also providing a platform to share my achievements and insights with a wider audience.

If you have any questions or would like to know more about the setup, feel free to reach out!

