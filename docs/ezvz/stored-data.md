---
layout: default
title: Stored Data
parent: EzVz
---

# Your personal data

To make EzVz work it is necassery for us to store certain data about orders. This data will only be used to make EzVz work better and provide a better experience for the user, and not in any commercial way.

## Orders

The data stored to an order are the following:

- User who created the order
- OrderChannelID
- Country
- Continent
- Colors
- User who provided the parts
- Colors
- Filament
- Ordered Kits

Orders are stored after they have been completed.

## Providers

- UserID
- Continent
- Country
- Filaments
- Printeramount
- Finished Orders
- Ratings

Providers are saved with their application. If an application is declined the provider is still stored in the database.

## Rating

Every rating of an finished order is stored in our database. The rating is not directly shared with the provider, but the order id is saved with the rating. Only the VzBoT team can see the all ratings, providers are only able to see their average rating.
