# lgtv

Forked from webostv component to add media player state by Rale.

This Modification **will not work** if you have not modified your webOS TV as stated in the GIST below.

Adjusted for internal API adjustments using SSAP for a rooted WebOS TV.
Follow the instructions in this GIST to make your TV broadcast the media states.
https://gist.github.com/Kuchiru/55e1b509a85cbece056dc7196d5c7385

## Installation

### Using HACS

- Add this repository as a custom integration repository, then restart home assistant
- Under settings, devices & services, add integration, and search for "LG TV"
- Enter the ip address for the TV, click submit, and then accept the prompt on TV

### Manually

- Download the repo, then copy the lgtv directory into the custom_components directory 
  in your home assistant config location, then set up the integration same as above
