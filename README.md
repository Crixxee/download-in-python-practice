# download-in-python-practice
This is a trial on how to allow users download files(images in jpg,png and ico format) from our favicon website.
the directory is adas, while the project is addas and the app is blog.
# The following files were updated for the download task
The settings (INSTALLED APPS and TEMPLATES),afterwhich a template folder has been created in blog.
views file,
urls file. 
Then runserver and view(download).
# The settings.py
here, blog was added to installed apps and the template folder in blog, linked to templates in addas folder. see below; 
# The views.py
here, modules were imported which are mimetypes, os, httpresponse. then the download path and other reponses were updated. also see below;
# The urls.py
here the urlpattern for the download, and the import views were updated.
