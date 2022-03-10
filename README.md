# TNA Front end content

## Contents:
 - Open Government License for public sector information (open-government-licence)
 - Trwydded Llywodraeth Agored ar gyfer gwybodaeth y sector cyhoeddus (open-government-licence-cymraeg)
 - Non-Commercial Government License for public sector information (non-commercial-government-licence)
 - Trwydded Llywodraeth Anfasnachol ar gyfer gwybodaeth y sector cyhoeddus (non-commercial-government-licence-cymraeg)
 - Open Supreme Court Licence (open-supreme-court-licence)

## Deployment
 - This should be deployed on the front-end server in /doc/
 - If the css is updated the files from /doc/css/ will need to be copied to /css/
 - If the images are updated the files from /doc/images/ will need to be copied to /images/

## Running locally

1. With NodeJS installed, use `npm i -g http-server` to get a http-server library.
2. Run `http-server -p 8080 --cors` from the root folder to start a localhost server.

## All links

- English OGL v3: http://localhost:8080/open-government-licence/version/3/default.htm
- Welsh OGL v3: http://localhost:8080/open-government-licence-cymraeg/version/3/default.htm

- English OGL v1: http://localhost:8080/open-government-licence/version/1/open-government-licence.htm
- A Welsh OGL v1 does not exist.

- English OGL v2: http://localhost:8080/open-government-licence/version/2/default.htm
- A Welsh OGL v2 does not exist.

- English Non-commercial license v1: http://localhost:8080/non-commercial-government-licence/version/1/default.htm
- Welsh Non-commercial license v1: http://localhost:8080/non-commercial-government-licence-cymraeg/version/1/default.htm

- English Non-commercial license v2: http://localhost:8080/non-commercial-government-licence/version/2/default.htm
- Welsh Non-commercial license v2: http://localhost:8080/non-commercial-government-licence-cymraeg/version/2/default.htm

