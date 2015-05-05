# magellan-May-05
Buddy List
  Overview
  Create a list of buddies that can be sorted, filtered, searched and prioritized. Clicking on a buddy should show their expanded information.

  Requirements
  The List
  Pre-populate the list with mock data.
  Stub out the data as if it were an api response.

  Buddies
  Each buddy in the list view should display their username, first name, last name and status
  The expanded information should display their email address, birthday and bio
  Buddies should be able to be added, prioritized and deleted.
  Deleting should prompt a confirmation dialog.

  Buddy Status
  Buddies can be Available, Busy, Idle or Offline.
  If the buddy is offline, the expanded information should also show the last sign in date.

  Add Buddy
  Clicking this button should open a dialog with a form to add a new buddy.
  Form should contain all required fields.
  On submit, the buddy should be added to the list.

var list = {
                "people": [
                            {
                                "username": "rashmika23",
                                "firstname": "Rashmika",
                                "lastname": "Kallepu",
                                "status": "Available",
                                "moreInfo": {
                                    "emailAddress":"rashmika@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1990"
                                }
                            },
                            {
                                "username": "radhika14",
                                "firstname": "Radhika",
                                "lastname": "Sastry",
                                "status": "Available",
                                "moreInfo": {
                                    "emailAddress":"radhika@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1990"
                                }
                            },
                            {
                                "username": "rithesh04",
                                "firstname": "Rithesh",
                                "lastname": "Kallepu",
                                "status": "Busy",
                                "moreInfo": {
                                    "emailAddress":"rithesh@golivelabs.com",
                                    "address": "780 South Mathilda Avenue, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "4th Dec 2000"
                                }
                            },
                            {
                                "username": "vavo",
                                "firstname": "Varun",
                                "lastname": "Voddi",
                                "status": "Away",
                                "moreInfo": {
                                    "emailAddress":"vavo@golivelabs.com",
                                    "address": "607 Historic Murphy Avenue, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "24th June 1984"
                                }
                            },
                            {
                                "username": "amunugal",
                                "firstname": "Apoorva",
                                "lastname": "Munugala",
                                "status": "Available",
                                "moreInfo": {
                                    "emailAddress":"apoorva@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "11th Feb 1989"
                                }
                            },
                            {
                                "username": "ash",
                                "firstname": "Ashish",
                                "lastname": "Vujjeni",
                                "status": "Busy",
                                "moreInfo": {
                                    "emailAddress":"ashish@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1983"
                                }
                            },
                            {
                                "username": "bittu567",
                                "firstname": "Anvesh",
                                "lastname": "Rao",
                                "status": "Away",
                                "moreInfo": {
                                    "emailAddress":"anvesh@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd Jan 1991"
                                }
                            },
                            {
                                "username": "chris007",
                                "firstname": "Chris",
                                "lastname": "Jyap",
                                "status": "Available",
                                "moreInfo": {
                                    "emailAddress":"chrisjyap@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1990"
                                }
                            },
                            {
                                "username": "aditya016",
                                "firstname": "Aditya",
                                "lastname": "Rao",
                                "status": "Available",
                                "moreInfo": {
                                    "emailAddress":"aditya@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1990"
                                }
                            },
                            {
                                "username": "nina89",
                                "firstname": "Nina",
                                "lastname": "Agarwal",
                                "status": "Busy",
                                "moreInfo": {
                                    "emailAddress":"nina@golivelabs.com",
                                    "address": "560 Gorman street, Sunnyvale,CA-93780",
                                    "bioData": "hobbies: instrumental music, reading books",
                                    "birthday": "23rd April 1990"
                                }
                            },
            ]};

