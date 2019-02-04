# Planning and Meetings

## Sprint 1 Planning

Users will work by checking OAuth and then send that username to program and reply with if the exists (404/200)
  * Security Concerns - not something that we really would have to worry about
  * Other options - not really - Look deeper into OAuth and see what they suggest
  
ERD/Database
  * Using none relational database
    * User, jobs, time sheet entries as tables
    * $7/month for database through Firebase
    
Where to format into CSV (Front End/Back End)? Will be a discussion later in the process
Hosting with Firebase, Cost?
Cron job - set hours to 0 and reset pay period


Client Questions
  * When uploading csv file with jobs, Is it going to have the old jobs as well? Will it have the jobs such that the jobs correctly point to the old jobs?
    * Old jobs should be saved for at least +1 year and will be reset on Jan 1st of each year
  * Is there is an entry for a user and that user is removed, how do we deal with that?
    * As with old jobs, they should be kept at least +1 year
  * How long should we store the data? Will they want to go back and look at it?
    * See above
  * Dev account for Firebase
    * Will create @Tanner
  * Enter how long they worked or when they worked (start/stop times)?
    * When they worked
      * Start/Stop button
      * Additional capability to enter times if forgotten
    * Add location caching (expect location services available)
  * Do they own their own domain? Probably have to buy it
  * If there is a call in the middle of the night on the day that the time period switches over, which pay period does it go into?
    * Wednesday at 0:00am is the beginning of the pay period. Should be split at that time to each pay period

## Stand Up Meeting: 1/22/2019
  
| Name | Yesterday     | Today         | 
| ---- | ------------- |:-------------:| 
| Olivia | Started Lynda course on React. | Finish Lynda course on Reacgt. | 
| Brian | Improved functionality when adding times. | Display jobs according to type (construction, service or other). |
| Diego | Read up on Hapi. | Connect API and Firebase and continue learning... |
| Tanner | Setup Firebase and Muller dev account. |  Define database models. |

## Stand Up Meeting: 1/24/2019
  
| Name | Yesterday     | Today         | 
| ---- | ------------- |:-------------:| 
| Olivia | Learned js. | Learn React and work on the proposal. | 
| Brian | Welcome page, button to add a new time entry. Changed table view cell size. | ERD and more UI. |
| Diego | Read up more on Hapi and firebase. | Work on connecting db with Cloud Firebase. |
| Tanner | Develped models, initialized firebase. |  Work on models. |

## Stand Up Meeting: 1/28/2019
  
| Name | Yesterday     | Today         | 
| ---- | ------------- |:-------------:| 
| Olivia | Learned React kind of. Worked on project proposal. | Planning out website. | 
| Brian | Finished ER diagram. Worked on custom talbe view cells. | Finalize app functionality(populating cost code field and validation). |
| Diego | Read up more on firebase. | Create the collections . |
| Tanner | Configured app to work with ES6. |  . |

## Stand Up Meeting: 1/30/2019
  
| Name | Yesterday     | Today         | 
| ---- | ------------- |:-------------:| 
| Olivia | Created layout for the admin website. Finished editing project proposal. | Write some code for the admin website. | 
| Brian | Added edit functionality for time entries. | Add ability to delete a time entry and start testing. Edit project proposal.|
| Diego | API and db connected. | Set up basic route to display users. |
| Tanner | Mostly resting. Testing is working. |  Keep working on tests. |

## Retro 1

What did we accomplish?
  * App - Basic views and CRUD operations for time entries
  * Website - Learned and preliminary modifications for website
  * APIs - Setting up repo, write/read from database
  
What did we do well?
  * Communication
  * Stayed on track
 
What did we do poorly?
  * Testing

## Sprint 1 Planning
Client Meeting: Thursdays 4:00pm (Feb 7th, 21st, Mar 7th, Mar 21st, Apr 4th, Apr 18th, May 2nd)

App - Research and Learning to connect to APIs and testing, few UI improvements

APIs - Implementing signon, routing

Website - Basic pages and templates, Learning

Client Feeback

## Stand Up Meeting: 2/4/2019
  
| Name | Yesterday     | Today         | 
| ---- | ------------- |:-------------:| 
| Olivia | Nothing, fun weekend. | Play around with React. Grading PLC hw. | 
| Brian | Added date headers to separate time entries. | Learning. Figure out how data is stored on the phone. |
| Diego | Set up route to add and return cost-codes. | Validate routes with Joi. |
| Tanner | Implemented testing and example test. Updated models. | Put in sign on. Move over to REACT. |
   
           |   |
      / | . | | . | \
     /  /|  | |  |\  \
      /   | | | |  \ 
          -------
         |/     \|
         |   /\  |
         |  | |  |
         ---   ---
        |___| |___| 
