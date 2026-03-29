# Test cases for GreenCity events page


## Test Case 1: Verify events list is displayed

**Preconditions:**
User opens the GreenCity events page

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open browser | - | Browser opens |
| 2 | Enter URL | https://www.greencity.cx.ua/#/greenCity/events | Page loads |
| 3 | Observe events section | - | List of events is visible (cards with titles, images, dates) |


## Test Case 2: Verify event card interaction

**Preconditions:**
Events page is opened and events are visible

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Click on an event card | Any event | Event details or new page opens |
| 2 | Check event info | - | Event title, description and image are displayed |


## Test Case 3: Verify page behavior with invalid URL (negative)

**Preconditions:**
User has browser

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open browser | - | Browser opens |
| 2 | Enter incorrect URL | https://www.greencity.cx.ua/invalid | Error page or message is shown |
