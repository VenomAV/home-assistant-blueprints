# home-assistant-blueprints
My blueprints for Home Assistant

## How to use

In your Home Assistant server, using add-ons like "Terminal & SSH" or "Studio Code Server", follow these steps:

1. clone this repository in `/config/git_repositories`
1. create a folder `venom`, or whatever you like, in `/config/blueprints/automation`
1. link the blueprints you would like to use from the cloned repository to the folder previously created, e.g.:

   `ln -s /config/git_repositories/home-assistant-blueprints/automation/camera_telegram_notifications.yaml /config/blueprints/automation/venom/camera_telegram_notifications.yaml`
