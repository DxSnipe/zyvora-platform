PROJECT NAME
Zyvora – Voice Party Social Platform

DESCRIPTION
Zyvora is a scalable social voice platform where users join rooms, talk with others, chat, send gifts, and build communities.

TECH STACK

Mobile Application
Flutter

Backend
Node.js with NestJS framework

Database
PostgreSQL

Cache
Redis

Realtime Communication
WebSockets

Voice Infrastructure
WebRTC or LiveKit

Infrastructure
Docker
CI/CD pipeline
Cloud deployment

BACKEND MODULES

auth
users
social
rooms
chat
gifts
wallet
notifications
moderation

REALTIME EVENTS

user_join_room
user_leave_room
send_message
gift_sent
user_typing

ARCHITECTURE RULES

The backend must follow modular architecture.

Each module must contain:

controller
service
routes
model
dto

All APIs must include:

input validation
error handling
clear code structure
