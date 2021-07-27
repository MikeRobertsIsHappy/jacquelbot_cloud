## Jacquelbot_cloud

leveraging

These are samples for using Python on Google App Engine Flexible Environment. These samples are typically referenced from the [docs](https://cloud.google.com/appengine/docs).


## Run Locally

1. Clone this repo.

   ```
   git clone https://github.com/MikeRobertsIsHappy/jacquelbot_cloud

   ```

2. Open a sample folder, create a virtualenv, install dependencies, and run the sample:

   ```
n
   cd <to directroy>
   virtualenv env  # for first time
   env\Scripts\activate.ps1
   pip install -r requirements.txt   OR    pip install --no-cache-dir -r requirements.txt    # for first time
   python main.py
   http://127.0.0.1:8080/
   ```

3. Visit the application at  http://127.0.0.1:8080/.


## Deploying

Some samples in this repositories may have special deployment instructions. Refer to the readme in the sample directory.

1. Use the [Google Developers Console](https://console.developer.google.com)  to create a project/app id. (App id and project id are identical)

2. Setup the gcloud tool, if you haven't already.

   ```
   gcloud init
   ```

3. Use gcloud to deploy your app.

   ```
   gcloud app deploy
   ```

4. Congratulations!  Your application is now live at `your-app-id.appspot.com`