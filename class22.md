# Our topic is about Django form handling process

![form](https://techincent.com/wp-content/uploads/2021/07/how-to-create-django-form.jpg)

## How this process is going on ?

1- Display the default form the first time it is requested by the user.  

2- Receive data from a submit request and bind it to the form.

3- Clean and validate the data.

4- If any data is invalid, re-display the form, this time with any user populated values and error messages for the problem fields.

5- If all data is valid, perform required actions (e.g. save the data, send an email, return the result of a search, upload a file, etc.)

6- Once all actions are complete, redirect the user to another page.

## How to write the Form ?

- As a class, the Form class specifies the fields in the form, their layout, display widgets, labels, initial values, valid values, and (once validated) the error messages associated with invalid fields.

- The class also provides methods for rendering itself in templates using predefined formats (tables, lists, etc.) or for getting the value of any element (enabling fine-grained manual rendering).

### Form fields

- There are so many types of form fields: BooleanField, CharField, ChoiceField, TypedChoiceField, DateField, DateTimeField, DecimalField, DurationField, EmailField, FileField, FilePathField, FloatField, ImageField, IntegerField, GenericIPAddressField, MultipleChoiceField, TypedMultipleChoiceField, NullBooleanField, RegexField, SlugField, TimeField, URLField, UUIDField, ComboField, MultiValueField, SplitDateTimeField, ModelMultipleChoiceField, ModelChoiceField.

- The arguments that are common to most fields are :

  - required
  - label: The label to use when rendering the field in HTML. If a label is not specified, Django will create one from the field name by capitalizing the first letter and replacing underscores with spaces (e.g. Renewal date).
  - label_suffix.
  - initial: The initial value for the field when the form is displayed.
  - widget: The display widget to use.
  - help_text
  - disabled

### Validation step:

- Django provides numerous places where we can validate the data.
- The easiest way to validate a single field is to override the method clean_< fieldname >() for the field you want to check.

### Adding the URL Configuration

### Creating the View 

- First, we import the form we created and a number of other useful objects/methods used in the body of the view function:

  - get_object_or_404(): Returns a specified object from a model based on its primary key value, and raises an Http404 exception (not found) if the record does not exist.
    HttpResponseRedirect: This creates a redirect to a specified URL (HTTP status code 302).
  - reverse(): This generates a URL from a URL configuration name and a set of arguments. It is the Python equivalent of the url tag that we've been using in our templates.

### Creating the template:

- We extend the base template and then redefine the content block.
- The form code is relatively simple. 
- First, we declare the form tags, specifying where the form is to be submitted (action) and the method for submitting the data .
- All that's left is the {{ form }} template variable, which we will pass to the template in the context dictionary.
