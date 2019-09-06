# ios-sdk-google-mediation-adapter

This repository contains adapters for integrating the Criteo Publisher SDK with your Admob mediation solution

Refer [integration document](https://publisherdocs.criteotilt.com/sdk-ios/3.1/admob-mediation/) on how to setUp Custom Events and integrate Admob for Mediation.

Criteo Direct Bidder can be integrated via the __CriteoPublisherSdk__ framework using Manual installation.

__Note__: CriteoPublisherSdk framework does not include adapters. The adapter source code will have to be manually copied from this repository and added to your project sources.

## Manual Installation

You can download the __CriteoPublisherSdk__ framework from [here](https://publisherdocs.criteotilt.com/sdk-ios/3.1/admob-mediation/). 

You will need to add this framework under __Linked Frameworks and Libraries__ in Build Settings of your app
as mentioned [here](https://publisherdocs.criteotilt.com/sdk-ios/2.2/googleadmanager/#add-criteo-module)
