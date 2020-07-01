# read-21
### 16 june 2020
# [table of contents](https://h-griffin.github.io/reading-notes-401/)

## reading
- [Using Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)
models for books would be large shared inforation or **objects**, like books, book instances, and authors. models may also represent something you would put in a drop down list of choises, like genre or language. the a model can have any number of feilds (like a table) you import models from django.db import and create it as a class and inherit models.Model the fields are then declared in teh class along with nay metadata and methods 


```from django.db import models

class MyModelName(models.Model):
    """A typical class defining a model, derived from the Model class."""

    # Fields
    my_field_name = models.CharField(max_length=20, help_text='Enter field documentation')
    ...

    # Metadata
    class Meta: 
        ordering = ['-my_field_name']

    # Methods
    def get_absolute_url(self):
        """Returns the url to access a particular instance of MyModelName."""
        return reverse('model-detail-view', args=[str(self.id)])
    
    def __str__(self):
        """String for representing the MyModelName object (in Admin site etc.)."""
        return self.my_field_name
```

- [Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
    - Advanced configuration section is optional
    - The tutorial is really good but some of the tools are dated so when reading try to understand the concepts more than the code.

## Additional Resources
- [Read (Optional): Beginner’s Guide to Django - Part 1](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html)


## Bookmark/Skim
- [Beginner’s Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)

