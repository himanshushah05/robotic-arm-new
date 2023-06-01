# robotic-arm-new # 
![Banner](./banner.png)

<p>
A robotic arm with 4 dof is controlled remotely with the help of esp32 webserver which is hosted locally.  
</p>

## What it does

![What it does?](./whatitdoes.png)

## Setup

- Go to repo Settings/Secrets and add a new repository secret with name as MTQT_BROKER_PASSWORD and value as key.
- Now edit the .yaml files in .github/workflows with your details of mqqt broker for each topic i.e Issue Open , Pull Requet Open and Pull Request Closed.
- Connect your Oled display to NodeMCU or any WiFi module compatible with Arduino.
- Change the SSID, Password, MQTT user ID and key as per your account.
- Upload the <code> github_actions_graph.ino </code> on your board

## Usage

- Plug in your NodeMCU and connect the Oled display
- The graph will be displayed and update on regular interval of time.

![Images](./hardware.png)

## Contributions

- Feel Free to Open a PR/Issue for any feature or bug(s).
- Make sure to follow the [community guidelines](https://docs.github.com/en/github/site-policy/github-community-guidelines) when contributing.
- Please open an issue if you want to ask a question/discuss anything about ActivityOverYou.
- Want to add an action? add a feature? Open an Issue!

## License

Licensed under [MIT License](https://opensource.org/licenses/MIT)
