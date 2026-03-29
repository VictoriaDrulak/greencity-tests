# Test Cases for GreenCity Events Page


## Test Case 1: Verify events list is displayed correctly
**Preconditions:**
User has internet access

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open browser | - | Browser opens |
| 2 | Enter URL | https://www.greencity.cx.ua/#/greenCity/events | Events page loads successfully |
| 3 | Observe events section | - | List of event cards is displayed |
| 4 | Check event cards | - | Each card contains title, image and date |


## Test Case 2: Verify event details page opens from card
**Preconditions:**
Events page is opened and events are visible

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Click on any event card | - | Event details page opens |
| 2 | Observe event details | - | Event title is displayed |
| 3 | Check additional info | - | Description and image are visible |
| 4 | Check page stability | - | Page loads without errors |


## Test Case 3: Verify behavior when invalid URL is entered (negative)
**Preconditions:**
User has browser

| Step | Action | Data | Expected Result |
|------|--------|------|----------------|
| 1 | Open browser | - | Browser opens |
| 2 | Enter invalid URL | https://www.greencity.cx.ua/invalid | Page does not load correctly |
| 3 | Observe result | - | Error message or empty page is shown |
