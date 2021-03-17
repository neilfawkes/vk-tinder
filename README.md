# VK Tinder

This script helps finding new people at vk.com.

The input is VK access token (if the user doesn't have one the script offers the opportunity to obtain it) and search parameters (country, city, gender, age).

The output is written to json-file and contains the list of 10 users, each of them has links to top3 photos by likes.
The obtained data is stored in Mongo DB and the user has an opportunity to search for another 10 results.

The script is written using VK API and following libraries:
- requests;
- time;
- json;
- alive_progress;
- urllib.parse;
- pymongo.

The code was written according to PEP8.
