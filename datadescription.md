# Class Project Details

1. [Project Background](#project-background)
2. [The Modeling Problem](#the-modeling-problem)
3. [Data Download](#download-link)
4. [Data Description](#dataset-description)

## Project Background
Public schools in the United States face large disparities in funding, often resulting in teachers and staff members filling these gaps by purchasing classroom supplies out of their own pockets. DonorsChoose is an online crowdfunding platform that tries to help alleviate this financial burden on teachers by allowing them to seek funding for projects and resources from the community (projects can include classroom basics like books and markers, larger items like lab equipment or musical instruments, specific experiences like field trips or guest speakers).

Projects on DonorsChoose expire after 4 months, and if the target funding level isn't reached, the project receives no funding. Since its launch in 2000, the platform has helped fund over 2 million projects at schools across the US, but about 1/3 of the projects that are posted nevertheless fail to meet their goal and go unfunded.

## The Modeling Problem
For the purposes of the class project, \DonorsChoose has hired a digital content expert who will review projects and help teachers improve their postings and increase their chances of reaching their funding threshold. Because this individualized review is a labor-intensive process, the digital content expert has ** time to review and support only 10% of the projects posted to the platform on a given day**.

You are working with DonorsChoose, and your task is to help this content expert focus their limited resources on projects that most need the help. As such, you want to build a model to identify projects that are least likely to be fully funded before they expire and pass them off to the digital content expert for review.

## Download link
The data is in four different tables/csv files that you need to download. You can put it into a database (good life practice) or live in csv world (at your own risk).
 
[**Dataset Download Link**](https://dsapp-public-data-migrated.s3.us-west-2.amazonaws.com/10718F25data.zip) 

## Dataset Description

For this project, you have access to data from DonorsChoose about projects, teachers, schools, and donations. In the dataset, you'll find four tables:

- `projects` contains basic information about all the projects posted on the site, including characteristics of the teacher who posted (e.g., name, subject area, grade level, whether they participate in Teach for America, etc) it and their school (e.g., location, charter status, poverty level, NCES ID, etc).

- `essays` contains the title, short description, and full essay that is posted with project to provide potential donors with information about what the teacher is asking for and what they plan to do with the resources, how it will benefit students, etc.

- `resources` contains information about the specific resources being requested for the project (e.g., books, technology, etc), including their costs, quantities, and types.

- `donations` contains transaction-level information about the donations to each project (e.g., amount, how it came in, etc), as well as some characteristics of the donor (e.g., whether the donor is a teacher, their location, whether they left a message, etc)

A very rough data dictionary of the specific fields in each table is provided below:

#### Data fields
Below is a brief explanation of the provided data fields. Descriptions of self-explanatory names are omitted.

#### projects.csv
- projectid - project's unique identifier
- teacher_acctid - teacher's unique identifier (teacher that created a project)
- schoolid - school's unique identifier (school where teacher works)
- school_ncesid - public National Center for Ed Statistics id
- school_latitude
- school_longitude
- school_city
- school_state
- school_zip
- school_metro
- school_district
- school_county
- school_charter - whether a public charter school or not (no private schools in the dataset)
- school_magnet - whether a public magnet school or not
- school_year_round - whether a public year round school or not
- school_nlns - whether a public nlns school or not
- school_kipp - whether a public kipp school or not
- school_charter_ready_promise - whether a public ready promise school or not
- teacher_prefix - teacher's gender
- teacher_teach_for_america - Teach for America or not
- teacher_ny_teaching_fellow - New York teaching fellow or not
- primary_focus_subject - main subject for which project materials are intended
- primary_focus_area - main subject area for which project materials are intended
- secondary_focus_subject - secondary subject
- secondary_focus_area - secondary subject area
- resource_type - main type of resources requested by a project
- poverty_level - school's poverty level.
- highest: 65%+ free of reduced lunch
- high: 40-64%
- moderate: 10-39%
- low: 0-9%
- grade_level - grade level for which project materials are intended
- fulfillment_labor_materials - cost of fulfillment
- total_price_excluding_optional_support - project cost excluding optional tip that donors give to DonorsChoose.org while funding a project
- total_price_including_optional_support - see above
- students_reached - number of students impacted by a project (if funded)
- eligible_double_your_impact_match - project was eligible for a 50% off offer by a corporate partner (logo appears on a project, like Starbucks or Disney)
- eligible_almost_home_match - project was eligible for a $100 boost offer by a corporate partner
- date_posted - data a project went live on the site

#### donations.csv
- donationid - unique donation identifier
- projectid - unique project identifier (project that received the donation)
- donor_acctid - unique donor identifier (donor that made a donation)
- donor_city
- donor_state
- donor_zip
- is_teacher_acct - donor is also a teacher
- donation_timestamp
- donation_to_project - amount to project, excluding optional support (tip)
- donation_optional_support - amount of optional support
- donation_total - donated amount
- dollar_amount - donated amount in US dollars
- donation_included_optional_support - whether optional support (tip) was included for DonorsChoose.org
- payment_method - what card/payment option was used
- payment_included_acct_credit - whether a portion of a donation used account credits redemption
- payment_included_campaign_gift_card - whether a portion of a donation included corporate sponsored giftcard
- payment_included_web_purchased_gift_card - whether a portion of a donation included citizen purchased giftcard (ex: friend buy a giftcard for you)
- payment_was_promo_matched - whether a donation was matched 1-1 with corporate funds
- via_giving_page - donation given via a giving / campaign page (example: Mustaches for Kids)
- for_honoree - donation made for an honoree
- donation_message - donation comment/message. Used to calcualte great_chat

#### essays.csv
- projectid - unique project identifier
- teacher_acctid - teacher id that created a project
- title - title of the project
- short_description - description of a project
- need_statement - need statement of a project
- essay - complete project essay

#### resources.csv
- resourceid - unique resource id
- projectid - project id that requested resources for a classroom
- vendorid - vendor id that supplies resources to a project
- vendor_name
- project_resource_type - type of resource
- item_name - resource name (ex: ipad 32 GB)
- item_number - resource item identifier
- item_unit_price - unit price of the resource
- item_quantity - number of a specific item requested by a teacher
