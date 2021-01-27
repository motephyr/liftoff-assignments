# Project Setup
This assignment will get you set up and rolling with a basic project. By the end, you will have a GitHub repo that contains a working application.

## Assignment Description
[Project Setup Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-setup)

## Submission Instructions

EntityRelationshipDiagrams

users
* name: string 
* role: string (buyer, seller)

user_informations
* user_id: integer
* contact_information: text

items
* user_id: integer
* title: string
* price: decimal
* video_path: string
* status: string (draft, publish, deleted, sold_out)
* last_drafted_at: timestamp
* last_publish_at: timestamp
* last_deleted_at: timestamp
* last_sold_out_at: timestamp
* view_count: integer
* total_watch_time: integer
* record_count: integer

records
* seller_user_id: integer
* buyer_user_id: integer
* item_id: integer


### Project Repository

https://github.com/motephyr/10SecondsWindowShop
