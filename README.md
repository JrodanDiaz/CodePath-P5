# Web Development Project 5 - Event Finder

Submitted by: Jordan Diaz

This web app: Quickly find events based on your inputted State, City, or desired event type

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **The list displays a list of data fetched using an API call**
- [x] **Data uses the useEffect React hook and async/await syntax**
- [x] **The app dashboard includes at least three summary statistics about the data such as State, City, Event Type**

- [ ] **A search bar allows the user to search for an item in the fetched data**
- [ ] **Multiple different filters (2+) allow the user to filter items in the database by specified categories**

The following **optional** features are implemented:

- [ ] Multiple filters can be applied simultaneously
- [ ] Filters use different input types such as a text input, a selection, or a slider
- [ ] The user can enter specific bounds for filter values

## Walkthrough

Here's a walkthrough of implemented features

![Screenshot 2023-10-17 024817](https://github.com/JrodanDiaz/CodePath-P5/assets/129818825/fa50216b-0727-4cc5-b17e-f095f81d95a7)


## Notes

After changing the state variables of State, City, or EventType, the url would update, but the fetch would return a networkError. When I opened the updated url in my browser, I got the expected JSON response, but it would not work with fetch()

## License

    Copyright 2023 Jordan Diaz

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
