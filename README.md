# Cyral Splunk App

This app can also be found on [Splunkbase](https://splunkbase.splunk.com/app/5727). If you would like to customize the app for your own purposes, you can make changes to the cyral-x-x-x.tgz file in this repo.

# Installation

You can either choose to install the app from [Splunkbase](https://splunkbase.splunk.com/app/5727) or using the [TGZ File](cyral-2.0.0.tgz) provided in this repo.

## Post Installation

The dashboards within this Splunk App make use of a [Splunk Event Type](https://docs.splunk.com/Documentation/Splunk/latest/Knowledge/Abouteventtypes) called `CyralLogs`. This Event Type is created as part of the app install. You will need to edit the `CyralLogs` Event Type and change its search criteria to match the location of Cyral logs within your own Splunk instance.

# Customizations

The Cyral example dashboards are located within the `cyral/default/data/ui/views/` path in the provide [TGZ File](cyral-2.0.0.tgz). You are welcome to customize these files or create your own to repackage the app. You can also create new dashboards once the app is installed.