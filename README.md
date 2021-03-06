# Rails form_tag Lab

## Objectives

1. Build a functional Rails form using form_tag

2. Pass a route helper as the argument to form_tag

3. Pass an options hash with method to form_tag

4. Use text_field_tag and other form controls to create inputs.

5. Build a new action that renders a form that will submit to create


## Instructions

There are two specs for this lab that are currently failing that you need to take from red to green, the specs are located here: ```specs/features/student_spec.rb``` and are in the feature ```form page```.

At a high level you need to build a form to create a new student and have the form redirect back to the new view template and print out the form params to the screen. Below are a few items to keep in mind:

* Draw a `new` and `create` route for the `students` resource

* Print out the student value to the view template page


## Keys to remember

* Look at the tests to see which field values you should be using

* Make sure to use the form tag helpers


## Resources

[Reading](https://github.com/learn-co-curriculum/rails-form_tag-readme)
[Form Helper Documentation](http://api.rubyonrails.org/classes/ActionView/Helpers/FormTagHelper.html)