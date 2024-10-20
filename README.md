# Mobile-Applications

## Short Description

This is a mobile application where people can post ads to sell various items, like cars, clothing, and more, and also check out listings from other users. Users can easily create ads by providing details of their items, making it simple to connect with potential buyers. It allows users to manage their ads effectively, enabling to update, delete or view their listings at any time. 

## Domain Details
### Ad entity:
- ```Title:``` String - A short description of the item
- ```Description:``` String - A detailed explanation of the item, including features, condition, and any other relevant information
- ```Price:``` Double - The selling price of the item in €
- ```Location:``` String - The seller's location
- ```Contact:``` String - The seller's contact details

## Crud operations
- Create - Users can add a new ad by entering the title, description, price, location and contact info
- Read - Users can browse the list of the available ads
- Update - Users can edit an ad they created
- Delete - Users can remove existing ads from the list

## Persistence details
All the available operations will be persisted on the local db and on the server

## Details on what is happening when the device is offline
- Create - If the device is offline, the ad is saved locally and will be uploaded to the server when the connection is restored
- Read - Users can view the ads even when the device is offline since they are stored locally. New data will only be fetched when the device is back online
- Update - The device is offline, so the operation cannot be performed at the moment
- Delete - The device is offline, so the operation cannot be performed at the moment

## App mockup
<p align="center">
<img src="https://github.com/VladutPasare/Mobile-Applications/blob/main/screenshots/list.png" height="500">
<img src="https://github.com/VladutPasare/Mobile-Applications/blob/main/screenshots/add.png" height="500">
</p>
