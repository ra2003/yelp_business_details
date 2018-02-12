# Yelp Business Details Scraper

Extracts business details from yelp.com

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

 - lxml
 - requests

### Installation

To install python request module

```
pip install requests
```

Installing lxml

```
pip install lxml
```

## Running the scraper

```
python yelp_business_details.py https://www.yelp.com/biz/frances-san-francisco
```
## Sample Output
```
{
    "info": [
        {
            "Takes Reservations": "Yes"
        }, 
        {
            "Delivery": "No"
        }, 
        {
            "Take-out": "No"
        }, 
        {
            "Accepts Credit Cards": "Yes"
        }, 
        {
            "Accepts Apple Pay": "No"
        }, 
        {
            "Accepts Android Pay": "No"
        }, 
        {
            "Accepts Bitcoin": "No"
        }, 
        {
            "Good For": "Dinner"
        }, 
        {
            "Parking": "Street"
        }, 
        {
            "Bike Parking": "Yes"
        }, 
        {
            "Good for Kids": "No"
        }, 
        {
            "Good for Groups": "No"
        }, 
        {
            "Attire": "Casual"
        }, 
        {
            "Noise Level": "Average"
        }, 
        {
            "Music": "Juke Box"
        }, 
        {
            "Good For Dancing": "No"
        }, 
        {
            "Alcohol": "Beer & Wine Only"
        }, 
        {
            "Happy Hour": "No"
        }, 
        {
            "Best Nights": "Thu, Fri, Sat"
        }, 
        {
            "Smoking": "No"
        }, 
        {
            "Outdoor Seating": "No"
        }, 
        {
            "Wi-Fi": "No"
        }, 
        {
            "Has TV": "No"
        }, 
        {
            "Caters": "No"
        }, 
        {
            "Gender Neutral Restrooms": "Yes"
        }
    ], 
    "ratings": "4.5", 
    "website": "http://www.frances-sf.com/", 
    "working_hours": [
        {
            "Mon": "Closed"
        }, 
        {
            "Tue": "5:00 pm - 10:00 pm"
        }, 
        {
            "Wed": "5:00 pm - 10:00 pm"
        }, 
        {
            "Thu": "5:00 pm - 10:00 pm"
        }, 
        {
            "Fri": "5:00 pm - 10:30 pm"
        }, 
        {
            "Sat": "5:00 pm - 10:30 pm"
        }, 
        {
            "Sun": "5:00 pm - 10:00 pm"
        }
    ], 
    "name": "Frances", 
    "claimed_status": "Claimed", 
    "url": "https://www.yelp.com/biz/frances-san-francisco", 
    "longitude": "-122.432276", 
    "reviews": "1388 reviews", 
    "phone": "(415) 621-3870", 
    "address": "3870 17th St San Francisco, CA 94114 b/t Pond St & Noe St Castro", 
    "latitude": "37.762722", 
    "ratings_histogram": [
        {
            "5 stars": "749"
        }, 
        {
            "4 stars": "385"
        }, 
        {
            "3 stars": "187"
        }, 
        {
            "2 stars": "43"
        }, 
        {
            "1 star": "24"
        }
    ], 
    "price_range": "$31-60", 
    "health_rating": "96 out of 100", 
    "category": "American (New),Desserts,Wine Bars"
}
```
