# Online PECS binder

..every readme should have an ascii text art..

░█████╗░███╗░░██╗██╗░░░░░██╗███╗░░██╗███████╗  ██████╗░███████╗░█████╗░░██████╗
██╔══██╗████╗░██║██║░░░░░██║████╗░██║██╔════╝  ██╔══██╗██╔════╝██╔══██╗██╔════╝
██║░░██║██╔██╗██║██║░░░░░██║██╔██╗██║█████╗░░  ██████╔╝█████╗░░██║░░╚═╝╚█████╗░
██║░░██║██║╚████║██║░░░░░██║██║╚████║██╔══╝░░  ██╔═══╝░██╔══╝░░██║░░██╗░╚═══██╗
╚█████╔╝██║░╚███║███████╗██║██║░╚███║███████╗  ██║░░░░░███████╗╚█████╔╝██████╔╝
░╚════╝░╚═╝░░╚══╝╚══════╝╚═╝╚═╝░░╚══╝╚══════╝  ╚═╝░░░░░╚══════╝░╚════╝░╚═════╝░

  ██████╗░██╗███╗░░██╗██████╗░███████╗██████╗░
  ██╔══██╗██║████╗░██║██╔══██╗██╔════╝██╔══██╗
  ██████╦╝██║██╔██╗██║██║░░██║█████╗░░██████╔╝
  ██╔══██╗██║██║╚████║██║░░██║██╔══╝░░██╔══██╗
  ██████╦╝██║██║░╚███║██████╔╝███████╗██║░░██║
  ╚═════╝░╚═╝╚═╝░░╚══╝╚═════╝░╚══════╝╚═╝░░╚═╝
  





## About

PECS stands for Picture Exchange Communication System.
The PECS helps anyone with communication challenges, such as persons with Autism, communicate by exchanging pictures.

PECS have different phases and The Online Binder is designed for use in the 4th Phase,
where we are able to use an “I want” picture followed by a picture of the item being requested.
Learn more about PECS from Pyramid Educational Consultants who developed the PECS -
[https://pecs.com/picture-exchange-communication-system-pecs/](https://pecs.com/picture-exchange-communication-system-pecs/)

## Description

The Website Application is designed to allow the use of the Binder even without registering.
The PECS available are the generic items available to everyone.
Registration will allow users of the application to upload their own PECS and add PECS to a favourites tab.

### PECS Strips ( Home / Index )
<img src="images/binder-index-parts.jpg" width="700px">

The Interface is designed to be simple and resemble a PECS Binder with the I Want Strip at the top and the available PECS at the bottom
The availabl PECS are all available in the tabs and sorted by their tags. The Available PECS show only one row and scrollable sidways.
The Website is optimal in a wide-screen mode, such as on a tablet or computer or a device in landscape mode.

Clicking on the available PECS or the PECS on the Strips will provide an audio feedback as well as Clicking on the "Read" icon which will read the whole sentence structure.
Clicking on the Reset icon will clear the Strip of any chosen PECS.

#### Strip Tabs

##### I Want Strip
<img src="images/binder-iwant.jpg" width="700px">
The I Want Strip can be used by the individual to request for an activity or item, based on the PECS chosen.
The PECS can be chosen by clicking scrolling through the PECS tab then clicking on the available PECS,
The chosen PECS then will automatically appear beside the I Want Picture.

##### First .. Then Strip
<img src="images/binder-first-then.jpg" width="700px">

The First .. Then strip is atuclaly used to communicate with the individual and  is used to convey a sequence of events,
i.e. First an item or activity must be done, before Then recieving the item or performing an activity.
The First Box is active by default (which can be recognized because of the black border), Choosing a PECS will fill the First Box.
The active box will automatically move to "Then" after choosing a PECS, the next chosen pecs will fill up the Then Box

### Registered Function

#### Upload
<img src="images/binder-upload.jpg" width="700px">
Upload allows a registred user to upload a PECS.
The PECS will then appear with the rest of the Available PECS and will only be available to the person that uploaded the picture.

<img src="images/binder-upload-success.jpg" width="700px">
Upon a successful upload, the PECS uplaoded will be shown including the description and the tag.
An audio for the description is also generated for the PECS.

#### Edit
<img src="images/binder-edit-tag.jpg" width="700px">
Edit allows the user to change the Description and Tag of the PECS or delete the picture.
Clicking on the Description will provide a cursor to allow the user to change the description.
Clicking on the tag will show all available tags in a drop-down.
The changes, once made are saved to the database autmatically and will not need any additional action to save.
Only the PECS that the user has uploaded will be show in this section.

#### Manage Faves
<img src="images/binder-manage_fave.jpg" width="700px">
PECS can be added to a favourite tab.
All Available PECS, including the standard PECS will be available to be tagged in favourites.
Clicking on an empty star will add the PECS to favourites,
Clicking on a solid star will remove it from favourites.

<img src="images/binder-home-fave.jpg" width="700px">
A favourites tab will appear with all the PECS tagged as favourite.

## Project Resources

### CS50 ide

The project was created in the CS50 ide environment and used the following libraries that were already available:

- [Werkzeug library](https://pypi.org/project/Werkzeug/)
- [CS50 library](https://cs50.readthedocs.io/libraries/cs50/python/)
- [Flask library](https://pypi.org/project/Flask/)
- [flask_session](https://pypi.org/project/Flask-Session/)
- [HTML 5](https://en.wikipedia.org/wiki/HTML5) is used for HTML. [Jinja version 2.11](https://jinja.palletsprojects.com/en/2.11.x/) was used to autogenerate HTML using python.
- [CSS](https://en.wikipedia.org/wiki/CSS) was implemented using my own [stylesheet](https://github.com/Amjuks/My-CS50-Project/blob/master/static/style.css) and a bit of [Bootstrap](https://getbootstrap.com). [Font Awesome](https://fontawesome.com) was used to display the star icons.
- [Javascript](https://www.javascript.com) was used with HTML to replace some stuff done with python(Errors when the input feilds are empty instead of redirecting into another page)

### Google Text to Speech

The Applications uses Googles Text to Speech to generate the Audio files.
The Google Text to Speech Package needs to be installed first in the ide to make the gTTx library available.

Run the command from ide to install gTTs package

    $ pip install gTTS

### Folder Structure

#### Root Folder

Comtains the Python Code and other helper functions as well as the database.

#### Static Folder

Contains items that are available to Flask Application, including css and the following subfolders include:

- [uploads] Will contain the uploaded images.
- [audio] Will comtain the generated audio files.

#### Templates Folder

Contains the html files.

### Database Schema

The application used sqlite3 database and the table below are needed to store and manage data..

#### Users Table

Table to store user information for registered users.

Special Users:
User 1 : Public - used to upload images available to unregistered and registered users.

CREATE TABLE IF NOT EXISTS 'users' (
'id' INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,
'username' TEXT NOT NULL,
'hash' TEXT NOT NULL
);
CREATE UNIQUE INDEX 'username' ON "users" ("username");

#### Image Table

Table to be used to store Image location.

CREATE TABLE img(
'id' INTEGER PRIMARY KEY AUTOINCREMENT NOT NULL,
'name' TEXT NOT NULL,
'desc' TEXT NOT NULL
);


##### Sample Table
sqlite> select * from img;
| id  | name       | desc |
|-----|------------|------|
| 4   | black.jpg  | black|
| 5   | blue.jpg   | blue |
| 6   | brown.jpg  | brown|
| 7   | gray.jpg   | gray |

#### Tag Table

Table to store image tags references image table and user table.

    CREATE TABLE tag(
    'image_id' INTEGER NOT NULL,
    'user_id' INTEGER NOT NULL DEFAULT "0",
    'tag' TEXT NOT NULL DEFAULT "ALL",
    FOREIGN KEY(image_id) REFERENCES img(id),
    FOREIGN KEY(user_id) REFERENCES users(id)
    );

##### Sample Table
| image_id  |  user_id   |  tag         |
|-----------|------------|--------------|
| 4         |  1         |  color       |
| 5         |  1         |  color       |
| 52        |  1         |  places      |
| 53        |  1         |  places      |
| 54        |  1         |  places      |
| 55        |  1         |  places      |
| 34        |  104       |  favourites  |
| 44        |  104       |  favourites  |
| 35        |  104       |  favourites  |


## References
- [gTTS](https://gtts.readthedocs.io/en/latest/)
- [Bootstrap](https://getbootstrap.com)
- [jQuery](https://jquery.com/)
