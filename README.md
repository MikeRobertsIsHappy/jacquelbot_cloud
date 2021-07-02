## Google App Engine Flexible Environment Python Samples

[![Open in Cloud Shell][shell_img]][shell_link]

[shell_img]: http://gstatic.com/cloudssh/images/open-btn.png
[shell_link]: https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/GoogleCloudPlatform/python-docs-samples&page=editor&open_in_editor=appengine/flexible/README.md

These are samples for using Python on Google App Engine Flexible Environment. These samples are typically referenced from the [docs](https://cloud.google.com/appengine/docs).

See our other [Google Cloud Platform github repos](https://github.com/GoogleCloudPlatform) for sample applications and
scaffolding for other frameworks and use cases.

## Run Locally

1. Clone this repo.

   ```
   git clone https://github.com/MikeRobertsIsHappy/jacquelbot_cloud

   ```

2. Open a sample folder, create a virtualenv, install dependencies, and run the sample:

   ```
   cd <to directroy>
   virtualenv env
   env\Scripts\activate.ps1
   pip install -r requirements.txt
   python main.py
   http://127.0.0.1:8080/
   ```

3. Visit the application at [http://localhost:8080](http://localhost:8080).


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