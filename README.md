# Airbnb Analysis with PowerBI
This project leverages the power of Power BI to deliver data-driven insights on Airbnb listings, empowering you to make informed decisions.

[**Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiODgzM2IwZWUtYTQ1OC00MzhkLTgzMjMtYjk3MGZhNmU4YzQzIiwidCI6IjA5MWYwZTcxLWIzMTAtNGMzYy1hMzI5LWYwNDNkNmRhM2IyZSJ9)

[**Demo**](https://app.powerbi.com/view?r=eyJrIjoiODgzM2IwZWUtYTQ1OC00MzhkLTgzMjMtYjk3MGZhNmU4YzQzIiwidCI6IjA5MWYwZTcxLWIzMTAtNGMzYy1hMzI5LWYwNDNkNmRhM2IyZSJ9)

<br>


## Airbnb: A Marketplace for Unique Stays
Airbnb (short for AirBedandBreakfast) is a leading online marketplace for short-term homestays and experiences. Launched in 2008, it has revolutionized the travel industry by connecting people who have space to share (hosts) with those seeking unique accommodation options (guests).

The Airbnb data serves as the foundation for various analyses, including:

**Market trends:** Understanding pricing, property types, and amenities in specific locations.

**Guest preferences:** Identifying trends in what guests look for (e.g., location, price range, amenities).

**Host strategies:** Analyzing how hosts optimize their listings for bookings.

<br>

## Basic Information:
Here's a breakdown of what you might find in an Airbnb listing sample dataset:

**Listing ID:** Unique identifier for each listing.

**Listing Title:** Descriptive title chosen by the host.

**Property Type:** Category of the property (e.g., entire apartment, private room, house).

**Location:** City, state/province, country.

**Accommodation:** Number of bedrooms, bathrooms, and guests the property can accommodate.

**Amenities:** List of features offered, such as Wi-Fi, kitchen, laundry facilities, etc.

**Price:** Nightly rate set by the host.

**Host Information:** Hostname or ID (anonymized).

**Description:** Detailed description of the property and surrounding area.

**House Rules:** Specific rules set by the host for guests.

**Reviews:** Ratings and comments left by previous guests.

**Availability:** Calendar showing available dates for booking.

<br>

## Approach
### Step 1: Data Collection
- Create a MongoDB Atlas account and deploy a database cluster.
- Connect with **MongoDB Compass** to view data locally.
- Later, load sample data into the database.

<br>

### Step 2: Data Exploration
- **Effortless Data Access:** We leverage the *Pymongo* library to seamlessly retrieve sample Airbnb data from the database.
- **Transforming Data for Clarity:** Each listing's details are extracted and organized into a user-friendly format using a Pandas DataFrame.
- **Data Cleansing for Accuracy:** The data undergoes a meticulous cleaning process to ensure it's free of missing values and duplicates, guaranteeing reliable analysis.
- **Ready for Exploration:** The processed data is conveniently saved as an Excel file for further in-depth analysis at your fingertips.

<br>

### Step 3: Dashboard Creation
- Download and install the free Power BI Desktop app. Sign in using your secure Microsoft 365 work or school account.
- Import your processed data into Power BI Desktop for effortless analysis.
- Craft compelling visualizations that showcase key details, empowering users to effortlessly identify the perfect Airbnb listings.
- Select a visually appealing theme for your dashboard to enhance user experience.
- For public access, publish your dashboard to the web and generate an embed code to seamlessly integrate it into your website or platform.
  
<br>

![Dashboard](https://github.com/aishwarya-10/airbnb-analysis-with-powerbi/assets/48954230/01737d04-8909-4fe0-93a7-0ebebbc327d8)
