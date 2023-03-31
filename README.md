# HomeAssistant and Nextcloud through Nginx

Lets say you wish to have two services: HomeAssistant and Nextcloud running, but you have only one 443 and 80 port on your router to forward.

Using Nginx as "reverse proxy" is just the solution for you.

1. You port forward 443 and 80 to the device hostig your Nginx
1. Configure Nginx to redirect calls to either HomeAssistant or Nextcloud (based on domain name)
1. Configure Nextcloud and HomeAssistant.

Done :D

That's the high level picture.

I have a video where I go through details of this configuration:

<link to be added when I finish making the video>
