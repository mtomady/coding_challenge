# Coding Challenge

We want to build an application that lets a patient who arrives at a clinic
select which treatment they want to receive. Your task is to build this
application!

You are welcome to use any technologies you like, with the only requirement
that the backend is built using Ruby. All the other technical choices are yours
(ie. database, framework, frontend). It's good to keep your decisions in mind,
and we may ask why you chose one technology over another.

Some of these requirements may be vague. You are welcome to make your own
assumptions or you can contact us for clarification. If you do make your own
decisions, we recommend you document them.

You can submit the application as you wish, but we ask that you include
instructions on how to run the application (and tests, if included), and to
seed the initial data.

You do not need to deploy your application; it is enough to send the code to
us. But your code should be deployment-ready :)

Your submission does not need to be perfect. If we like your submission, we'll
use discuss it during the next step. If we don't like it, we'll give you
feedback as to why, and how it could be improved.

## Treatment Selector

The Treatment Selector will be used by two people:

 * Patients - to select a treatment
 * Admins - to translate the treatments

Patients will use the TreatmentSelector when they go to a clinic. They will
pick a treatment from a pre-defined list, enter their name, and confirm their
choice.

Admins must be able to provide translations (into French or Malagasy) of the
treatment names. Patients will see the names of the treatments in the language
that their browser is set to.

You are welcome to use any data source as a list of treatments. We can suggest
the [Britannica List of medical tests and diagnostic procedures](https://www.britannica.com/topic/list-of-medical-tests-and-diagnostic-procedures-2074273),
but you're welcome to find your own sources. Treatments should be grouped into
categories, and patients can see these categories. You do not need to translate
the treatment names into French or Malagasy - that is up to the Admins :)

As the list of treatments is constantly changing, there should be some
mechanism to periodically repopulate the list of treatments (whether nightly,
or weekly, or monthly).
