# DNA Helix Pairer & AJAX - Drupal

#### _A basic Drupal web application with two custom modules. The DNA Helix Pairer module, will return the other half of the double helix after entering the initial half. The AJAX Article Node Loader will display a certain Article on the same page  with AJAX (without reloading the page). December 16, 2016_

#### By _**Stephen Burden**_

## Specifications
| DNA Helix Pairer Example Behavior | Example Input | Example Output |
|------------------|---------------|----------------|
| The application will return a single helix pair based on a valid letter | 'A' | 'T' |
| The application is not case sensitive | 'a' | 'T' |
| The application will return multiple helix pairs based on a valid input | 'ATAAGC' | 'TATTCG' |
| The application will only allow a valid helix letter characters | 'B' | "The only characters that are allowed in your helix half are the letters: 'A', 'C', 'G', or 'T'." |

## Prerequisites
You will need MAMP/WAMP installed on your computer.

## Setup/Installation Requirements
* In the Terminal enter `git clone <repository-url>` this repository
* Open MAMP/WAMP, go to ”Preferences" and then "Web Server". Then set your document root folder to point to our project directory, then Start Server.
* In your web browser http://localhost:8888/phpMyAdmin/ and import the `dna.sql.zip` file (inside the sites/db-backup directory) into MySQL
* Create a database account (user: `dna`, password: `dna`) and Host: Local in MySQL
* To view the go to http://localhost:8888 in your web browser_
* Admin user: `dna`, password: `dna`

## Link
* REPO: https://github.com/spburden/dna-ajax-testing-drupal

## Known Bugs
_There are no known bugs with this application._

## Support and contact details
_spburden@hotmail.com_

## Technologies Used
_Drupal 7.53, PHP, MAMP, MySQL, AJAX, Drupal Testing Module_

### License
The MIT License (MIT)

Copyright (c) 2016 **_Stephen Burden_**
