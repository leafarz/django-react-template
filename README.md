# django-react-template
Template for running both django and react.

## Notes
- Steps for deploying to Heroku are not included. Refer to Reference for deployment steps.

## Run
1) In root directory, create a virtual environment
    ```
    python -m venv venv
    ```
2) Install python pachages
    ```
    pip install -r requirements.txt
    ```
3) Build server. This will create files in the build folder.
    ```
    python manage.py collectstatic
    ```
4) Install node packages
    ```
    yarn install
    ```
5) Build react. This will create files also in the build folder.
    ```
    yarn build
    ```
6) Run server
    ```
    python manage.py runserver
    ```

## Reference
- [Deploy Your Django + React.js app to Heroku](https://dev.to/shakib609/deploy-your-django-react-js-app-to-heroku-2bck) by [
Shakib Hossain](https://dev.to/shakib609)
- [React & Django TUTORIAL Integration // REACTify Django](https://www.youtube.com/watch?v=AHhQRHE8IR8) by [CodingEntrepreneurs](https://www.youtube.com/channel/UCWEHue8kksIaktO8KTTN_zg)