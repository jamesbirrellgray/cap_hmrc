# CAP GEMINI HRMC TEST
Test Started at 07:55 04/07/2017

* Unsure as to if the govuk/HMRC libraries can be used such as the https://github.com/alphagov/govuk_template, https://github.com/alphagov/govuk_frontend_toolkit and https://github.com/alphagov/govuk_elements libraries
* For this kind of work there is also the https://github.com/alphagov/govuk_prototype_kit library
* For the sake of this test I have utilised the "assets" from the govuk template lbrary (HTML output) and the initial index.html
* To ensure that the markup is semantic and accesable I will use the existing patterns available in the govuk_elements library (https://govuk-elements.herokuapp.com/) and https://github.com/hmrc/assets-frontend library (http://hmrc.github.io/assets-frontend/)
* As I'm unsure if I can use the pattern libraries, I have created a css file (rather than ustilising scss) where I will re-create the gov elements located here `assets/stylesheets/cap_gemini_hmrc_test.css`

## Steps in test
* Initialy re-created the css for the service title and heading with media queries (for the test I decided to use the retina image for speed however I could have added retina quiries for the image)

## Starting a test server
* Make sure you have python installed
* Using terminal go to the directory where this readme is and enter the following command `python -m SimpleHTTPServer`
* The exmaple will be available on your localhost on port 8000 (http://localhost:8000)
