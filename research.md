# Ideas

## Egypt AI travelling companion
### Summary
You as a tourist want to visit Egypt but don't know where to go so instead of going to a generic AI travelling companion you use our app. with refined data sets and an AI that you can chat with so that it knows your prefrences and edit your trip till you have the perfect vacation plan all laid out and with just one click you'll have everything booked and ready for you.

### System overview
[Flutter App] <--> [.NET Backend API] <--> [Database + AI Engine]
                                  |
                           [External APIs: Google Maps, Booking.com, Yelp...]

### Implementattion steps
Phase 1: Core Infrastructure
  - Setup Flutter project
  - Setup .NET backend (auth, DB)
  - Design DB schema (users, trips, preferences)
  
Phase 2: Data & APIs
  - Collect Egypt tourism dataset (hotels, attractions, restaurants)
  - Integrate external APIs (Google Maps, Booking.com, TripAdvisor if possible)
  
Phase 3: AI Layer
  - Build recommender engine (match user prefs to destinations)
  - AI chatbot for Q&A about attractions (LLM integration)
  - Itinerary generator
  
Phase 4: Frontend Features
  - User profile (preferences, budget)
  - Trip planner UI (cards, maps, schedules)
  - Chatbot interface (text input + answers)
  
Phase 5: Testing & Expansion
  - Test with Egypt destinations
  - Optimize recommendations
  - Plan roadmap to add more countries

### Extra info
https://universe.roboflow.com/gp-yhogh/egypt-attractions/dataset/1?utm_source=chatgpt.com
https://www.reddit.com/r/selfhosted/comments/1hq64cz/free_or_cheap_databases_for_geographical/?utm_source=chatgpt.com
https://www.openstreetmap.org/
https://en.wikipedia.org/wiki/Archeological_Map_of_Egypt?utm_source=chatgpt.com
https://github.com/SaifAshrafHelmy/EgyptoPedia?tab=readme-ov-file
https://github.com/theahmedlatif/egypt_museums_api?tab=readme-ov-file
https://www.xmap.ai/data-catalogs/egypt-surveyed-points-of-interest-data?utm_source=chatgpt.com


---

## Smart Campus assistant
### Summary


### System overview
[Flutter App] <--> [.NET Backend API] <--> [Database + AI Tutor]
     |               |                     |
 [Local LAN Chat]    |             [Course Material Storage]
 [3D Map/AR]         |                     

### Implementation steps
Phase 1: Core Portal
  - Setup Flutter project (login, dashboard, course viewer)
  - Setup .NET backend (auth, DB, role-based access)
  - Database schema (users, roles, courses, assignments)

Phase 2: University Material System
  - Upload/download assignments & notes
  - Student-generated guides system
  - Teacher vs Student role permissions

Phase 3: Local Chat System
  - LAN-based messaging (WiFi Direct / local server sockets)
  - Course-specific chatrooms
  - Group project channels

Phase 4: AI Tutor
  - Ingest PDFs/lecture notes into vector DB
  - Build summarizer (AI model for notes)
  - Build Q&A system over course materials

Phase 5: Campus Navigation
  - Create/scan 3D or AR map of campus
  - Pathfinding logic (classroom → building)
  - Integration into Flutter (map navigation)

Phase 6: Integration & Testing
  - Stress test LAN chat
  - Test AI on real lecture notes
  - Beta test with students

### Extra info
Modelling the university should be a relatively easy task on blender but I don't know how to make the dimensions accurate + I'm not fully on-board with the chat idea (professional project-wise) but I do love it as a concept
