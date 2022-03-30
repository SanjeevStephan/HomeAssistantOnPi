# First Home Automation
<img src="https://github.com/SanjeevStephan/HomeAssistantOnPi/blob/main/automations/assets/first-home-assistant-automation.png"/>


### Automation : Lights OFF
* Name : Lights DOWN when charger unplugged
* Mode : Restart 
* Triggers Type : Device
* Device : Redmi 5A
* Trigger : Redmi 5A Is Charging unplugged
* Action Type : Call Service
* Service : Light:Turn off
* Targets : Night Light

### Automation : Lights ON
* Name : Lights DOWN when charger plugged in
* Mode : Restart 
* Triggers Type : Device
* Device : Redmi 5A
* Trigger : Redmi 5A Is Charging plugged in
* Action Type : Call Service
* Service : Light:Turn on
* Targets : Night Light

#### MODE
The mode controls what happens when the automation is triggered while the actions are still running from a previous trigger. Check the <a href="https://www.home-assistant.io/docs/automation/modes/">automation documentation</a> for more info.)
#### Conditions
Conditions are optional and will prevent the automation from running unless all conditions are satisfied.
#### Actions
The actions are what Home Assistant will do when the automation is triggered.
