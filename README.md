# YearBook
The pandemic has affected each and every part of our lifestyle in a major way. Those who have had it especially difficult are the students who are in the final year of their study. While we cannot do anything about the uncertainties whether their exams will be conducted, we identified one problem that we can attempt to solve. Every final year batch gets a grand farewell from their juniors, celebrating their foray into the real world. There’s the yearbook with quotes of each student which will serve as a source of nostalgia years down the line. There’s a Scribble Day where students reminisce the best parts about the journey they have had in these four years. The Class Of 2020 missed it all.

The Yearbook will contain all the students of the #ClassOf2020. Each student will have his/her profile. Each student can post “scraps” on other’s profiles, which the other can choose to display to everyone on his/her profile.

## Components
This is a complete FOSS project, which means that it includes the backend as well as the frontend for creation of this service. Although, we do not want to restrict the utility of this apptication to a certain form of product. Hence, we have created an independent REST API backend which can be used with any frontend. Colleges or Universities, can use the api and make the frontend of the service as per their desire.

Consequently, any issues, pull requests etc. related to the backend API must have the label `api` and the issues, pull requests etc. related to any form of graphical frontend must have the `gui` label.

### API
The API is hosted on AWS Lambda. The code (and `README`) for the same can be found in the `api`.

### GUI
As of now (May 2021), there is no work done on the frontend. Please feel free to fork this repository, add a new folder for a new frontend, like `android`, or `web`, to start building such a GUI for end-users to be able to fully utilize this program.
