# TripAdvisor Crawler 2020
This is a TripAdvisor crawler to extract all the information from a hotel's review for all of its reviews.

The crawler extracts:
- user_name
- user_origin
- stay_date
- trip_type
- user_contributions
- user_helpful_votes
- review_date
- user_rating
- review_title
- review
- amenities_ratings

The crawler was developed in September of 2020. As of November 2020 it is working fine.

In case TripAdvisor changes class names then those new class names should be provided in the `trip_advisor_map` dictionary inside crawler module.

Run TA_Crawler_Single providing the necessary information and it will extract all the data.
Run TA_Crawler_Multiple, provided that you have entered every hotel you want to parse in the `hotels_to_parse.xlsx` and all the reviews will be extracted from all the hotels.

! TA_Crawler_Multiple may throw errors from time to time. Just save your data up to this point. Restart the kernel, delete all the parsed hotels from the excel file and continue from there. Should errors be thrown to you again just repeat the above described process.
