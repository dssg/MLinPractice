## Download links



## Dataset Description
The data is provided in a relational format and split by dates. 


### File descriptions
donations.csv - contains information about the donations to each project. 
essays.csv - contains project text posted by the teachers. 
projects.csv - contains information about each project.
resources.csv - contains information about the resources requested for each project. 
outcomes.csv - contains information about the outcomes of projects

Data fields
Below is a brief explanation of the provided data fields. Descriptions of self-explanatory names are omitted.

#### outcomes.csv
is_exciting - ground truth of whether a project is exciting from business perspective
at_least_1_teacher_referred_donor - teacher referred = donor donated because teacher shared a link or publicized their page
fully_funded - project was successfully completed
at_least_1_green_donation - a green donation is a donation made with credit card, PayPal, Amazon or check
great_chat - project has a comment thread with greater than average unique comments
three_or_more_non_teacher_referred_donors - non-teacher referred is a donor that landed on the site by means other than a teacher referral link/page
one_non_teacher_referred_donor_giving_100_plus - see above
donation_from_thoughtful_donor - a curated list of ~15 donors that are power donors and picky choosers (we trust them selecting great projects)
great_messages_proportion -  how great_chat is calculated. proportion of comments on the project page that are unique. If > avg (currently 62%) then great_chat = True
teacher_referred_count - number of donors that were teacher referred (see above)
non_teacher_referred_count - number of donors that were non-teacher referred (see above)

#### projects.csv
projectid - project's unique identifier
teacher_acctid - teacher's unique identifier (teacher that created a project)
schoolid - school's unique identifier (school where teacher works)
school_ncesid - public National Center for Ed Statistics id
school_latitude
school_longitude
school_city
school_state
school_zip
school_metro
school_district
school_county
school_charter - whether a public charter school or not (no private schools in the dataset)
school_magnet - whether a public magnet school or not
school_year_round - whether a public year round school or not
school_nlns - whether a public nlns school or not
school_kipp - whether a public kipp school or not
school_charter_ready_promise - whether a public ready promise school or not
teacher_prefix - teacher's gender
teacher_teach_for_america - Teach for America or not
teacher_ny_teaching_fellow - New York teaching fellow or not
primary_focus_subject - main subject for which project materials are intended
primary_focus_area - main subject area for which project materials are intended
secondary_focus_subject - secondary subject
secondary_focus_area - secondary subject area
resource_type - main type of resources requested by a project
poverty_level - school's poverty level.
highest: 65%+ free of reduced lunch
high: 40-64%
moderate: 10-39%
low: 0-9%
grade_level - grade level for which project materials are intended
fulfillment_labor_materials - cost of fulfillment
total_price_excluding_optional_support - project cost excluding optional tip that donors give to DonorsChoose.org while funding a project
total_price_including_optional_support - see above
students_reached - number of students impacted by a project (if funded)
eligible_double_your_impact_match - project was eligible for a 50% off offer by a corporate partner (logo appears on a project, like Starbucks or Disney)
eligible_almost_home_match - project was eligible for a $100 boost offer by a corporate partner
date_posted - data a project went live on the site

#### donations.csv
donationid - unique donation identifier
projectid - unique project identifier (project that received the donation)
donor_acctid - unique donor identifier (donor that made a donation)
donor_city
donor_state
donor_zip
is_teacher_acct - donor is also a teacher
donation_timestamp
donation_to_project - amount to project, excluding optional support (tip)
donation_optional_support - amount of optional support
donation_total - donated amount
dollar_amount - donated amount in US dollars
donation_included_optional_support - whether optional support (tip) was included for DonorsChoose.org
payment_method - what card/payment option was used
payment_included_acct_credit - whether a portion of a donation used account credits redemption
payment_included_campaign_gift_card - whether a portion of a donation included corporate sponsored giftcard
payment_included_web_purchased_gift_card - whether a portion of a donation included citizen purchased giftcard (ex: friend buy a giftcard for you)
payment_was_promo_matched - whether a donation was matched 1-1 with corporate funds
via_giving_page - donation given via a giving / campaign page (example: Mustaches for Kids)
for_honoree - donation made for an honoree
donation_message - donation comment/message. Used to calcualte great_chat

#### essays.csv
projectid - unique project identifier
teacher_acctid - teacher id that created a project
title - title of the project
short_description - description of a project
need_statement - need statement of a project
essay - complete project essay

#### resources.csv
resourceid - unique resource id
projectid - project id that requested resources for a classroom
vendorid - vendor id that supplies resources to a project
vendor_name
project_resource_type - type of resource
item_name - resource name (ex: ipad 32 GB)
item_number - resource item identifier
item_unit_price - unit price of the resource
item_quantity - number of a specific item requested by a teacher
