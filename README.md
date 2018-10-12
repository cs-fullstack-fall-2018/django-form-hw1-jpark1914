# django-form-hw1

Watch the video here: https://youtu.be/6oOHlcHkX2U

Below, write out how to create a form in a new views method using any of the classes/models we used today.

So you first you import your form into views
Then you create a new view
Make a variable like "form" under the new view and you will set "FormModel.(request.POST)" to it
if form.is_valid() 
form.save()
#these last two lines allow the information to be saved to the database, once you have the front end set up.
That is how you create a new view for your forms model.
