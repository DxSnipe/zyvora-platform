DATABASE
PostgreSQL

TABLES

users
id
username
email
password_hash
phone_number
created_at

profiles
id
user_id
display_name
bio
avatar_url
level

rooms
id
host_id
room_name
room_type
max_users
created_at

room_members
id
room_id
user_id
role
joined_at

messages
id
room_id
sender_id
content
message_type
created_at

gifts
id
gift_name
coin_cost
animation_url

wallets
id
user_id
coin_balance

wallet_transactions
id
user_id
transaction_type
amount
created_at
