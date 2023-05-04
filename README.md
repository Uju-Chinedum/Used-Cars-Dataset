> The dataset consists of over 370000 used cars scraped with Scrapy from Ebay-Kleinanzeigen.

> Fields in the data set:
> - `dateCrawled` : when this ad was first crawled, all field-values are taken from this date
> - `name` : "name" of the car
> - `seller` : private or dealer
> - `offerType` : type of listing
> - `price` : the price on the ad to sell the car
> - `abtest` : whether the listing is included in an A/B test
> - `vehicleType` : the vehicle type
> - `yearOfRegistration` : at which year the car was first registered
> - `gearbox` : transmission type
> - `powerPS` : power of the car in PS
> - `model` : car model name
> - `kilometer` : how many kilometers the car has driven
> - `monthOfRegistration` : at which month the car was first registered
> - `fuelType` : type of fuel the car uses
> - `brand` : brand of the car
> - `notRepairedDamage` : if the car has a damage which is not repaired yet
> - `dateCreated` : the date for which the ad at ebay was created
> - `nrOfPictures` : number of pictures in the ad
> - `postalCode` : postal code for the location of the vehicle
> - `lastSeenOnline` : when the crawler saw this ad last online

> The content of the data is in German, so one has to translate it first if one can not speak German The fields lastSeen and dateCrawled could be used to estimate how long a car will be at least online before it is sold.

Source: [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database)