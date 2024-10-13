# Dymior Forms Plugin For Umbraco CMS

With the Dymior Forms Plugin, web form creation becomes a seamless and
efficient process. This versatile plugin empowers users to design and
deploy a wide variety of web forms with remarkable speed and
intelligence. Whether you\'re a web developer, marketer, or business
owner, Dymior Forms simplifies the task of gathering data and
interacting with your audience.

Dymior Forms is designed to streamline the entire form-building
experience. Its user-friendly interface and intuitive features make it
accessible to users of all skill levels. From simple contact forms to
complex surveys and registration pages, this plugin offers a
comprehensive range of customization options.

One of the standout features of Dymior Forms is its responsiveness. It
ensures that your forms not only look great on desktop screens but also
adapt seamlessly to mobile devices, providing an optimal user experience
across different platforms. This is crucial in today\'s mobile-driven
world, where responsive design is a fundamental aspect of online
success.

The intelligence of Dymior Forms is evident in its ability to automate
and optimize various aspects of form management. You can set up
autoresponders to engage with form submitters and integrate the
collected data directly into your database.

In summary, the Dymior Forms Plugin is a powerful tool that empowers
users to create and manage web forms efficiently and effectively. Its
ease of use, adaptability, and automation capabilities make it an
essential addition to any web development toolkit, helping businesses
and website owners enhance their online interactions and streamline data
collection.

## Features

The Dymior Forms plugin offers the following fields and their
capabilities:

### Form

-   Ability to create simple forms.

-   Responsive design for displaying forms on desktop, tablet, and
    mobile devices using drag and drop functionality.

-   Field validation during input or upon form submission.

-   Integration of Google reCAPTCHA to prevent bot submissions.

-   Capability to embed icon fonts and CSS URLs.

-   Ability to embed CSS files or add CSS directly to form fields in the
    admin panel.

-   Easy modification of form styles through CSS variable adjustments.

-   Rendering that respects screen size or container size.

-   Option to take forms offline when user input is not required, with
    customizable offline messages in the admin panel.

-   Ability to hide or disable fields upon form submission.

-   Customization of success and failure messages after submission.

-   Option to copy and move forms along with their fields to another
    node.

-   Ability to copy and move individual fields along with their
    subfields to another node.

-   Display of submissions in a grid format in the admin panel, with
    date range filters and CSV export capability.

### Wizard

-   Capability to create wizard-style forms.

-   Field validation during input or upon form submission.

-   Integration of Google reCAPTCHA to prevent bot submissions.

-   Ability to embed icon fonts and CSS URLs.

-   Ability to embed CSS files or add CSS directly to form fields in the
    admin panel.

-   Easy modification of form styles through CSS variable adjustments.

-   Rendering that respects screen size or container size.

-   Option to take forms offline when user input is not required, with
    customizable offline messages in the admin panel.

-   Ability to hide or disable fields upon form submission.

-   Customization of success and failure messages after submission.

-   In wizard forms, options to position step tabs at the top, bottom,
    left, or right.

-   Ability to copy and move wizard forms and their fields to another
    node.

-   Display of submissions in a grid format in the admin panel, with
    date range filters and CSV export capability.

### Step

A step node can contain wizard forms and allows for responsive design
for display on desktop, tablet, and mobile devices using drag and drop.

### Folder

This field provides a method for organizing related forms within a
structured hierarchy. While it does not directly affect individual form
functionality, it allows systematic management and categorization based
on specific criteria such as project, department, or topic.

### Textbox Field

-   Editing capabilities for label, help text, placeholder text, input
    prefix, input suffix, and autocomplete suggestions.

-   Validation options for maximum length, required fields, and
    patterns, along with customizable failure messages.

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    textbox field.

-   Option to determine whether to save data to the database.

### Email Field

-   Editing capabilities for label, help text, placeholder text, input
    prefix, input suffix, and autocomplete suggestions.

-   Validation options for maximum length, required fields, email
    format, and customizable failure messages.

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    email field.

-   Option to determine whether to save data to the database.

### HTML Field

-   This field does not collect user input. The administrator can input
    HTML content to display within the form.

### Date & Time Field

-   Editing capabilities for label, help text, input prefix, input
    suffix, and autocomplete suggestions.

-   Configuration for date with time, date only, or time only.

-   Minimum/maximum validation settings.

-   Initial and final time settings, with adjustable step intervals for
    dropdowns.

-   Date format adheres to the site\'s current culture.

-   Option to determine whether to save data to the database.

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    date & time field.

### Textarea Field

-   Editing capabilities for label, help text, placeholder text, and
    autocomplete suggestions.

-   Adjustable height settings in pixels.

-   Validation options for maximum length and required fields, along
    with customizable failure messages.

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    textarea field.

-   Option to determine whether to save data to the database.

### Dropdown Field

-   Editing capabilities for label, help text, placeholder text, and
    autocomplete suggestions.

-   Required validation and customizable failure messages.

-   Options for user selection (all checkboxes/radios or at least one).

-   Alignment settings for checkboxes/radios (left or right).

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    dropdown field.

-   Options for entering dropdown options via a user-friendly editor.

-   Extension of the options list through specific interface
    inheritance, with guidance provided in the info tab.

### Number Field

-   Editing capabilities for label, help text, placeholder text,
    autocomplete suggestions, prefix, and suffix.

-   Required, minimum/maximum value, and number validation options, with
    customizable failure messages.

-   Adjustable decimal places.

-   Option to determine whether to save data to the database.

-   Number format adheres to the site\'s current culture.

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    number field.

### Checkbox List and Radio List Fields

-   Editing capabilities for label and help text.

-   Required validation and customizable failure messages.

-   Configuration for user selection (all checkboxes/radios or at least
    one).

-   Alignment settings for checkboxes/radios (left or right).

-   Extension of validation capabilities by implementing specific
    interface inheritance, with guidance provided in the info tab of the
    checkbox/radio list fields.

-   Option to determine whether to save data to the database.

-   Options for entering checkbox/radio options via a user-friendly
    editor.

-   Extension of the options list through specific interface
    inheritance, with guidance provided in the info tab.

### Human Verification (ReCAPTCHA)

-   Editing capabilities for label, help text, and customizable failure
    messages for reCAPTCHA validation.

-   Configuration for visible or invisible reCAPTCHA types and
    associated keys.

### Group

This field serves as a placeholder that can contain other fields with
its own design. It is useful for grouping fields, such as for work
experience entries. The group can include add and remove buttons as
needed.

-   Configuration for group name and introductory HTML text.

-   Minimum and maximum entries settings with customizable error
    messages.

-   Option to determine whether to save data to the database.

-   Responsive design capabilities for group fields on desktop, tablet,
    and mobile devices using drag and drop.

### Add and Remove Button

Administrators can add an add/remove button to a group field when users
need to make repeated entries.

-   Configuration for button name and help text.

### Next and Back Buttons

Administrators can add next and back buttons to wizard forms, allowing
users to navigate between steps.

### Submit Button

This pertains to the submit button of the form, allowing administrators
to customize text and help text.

### Mail Action

Under the submit button node, administrators can add mail actions,
enabling users to configure email notifications upon successful form
submissions.

-   Configuration options include subject, from email, from name, to
    email list, CC email list, BCC email list, attachment of user
    uploads, and message body.

-   Administrators can use tokens from form fields, which will be
    replaced with actual values upon sending the email. Guidance for
    using tokens is available at the top of the admin page.

-   Administrators can set the process to occur before or after form
    submission to the database. In the event of failure, an error
    message can be displayed, and subsequent actions can be canceled
    with customizable failure messages.

### Custom Action

Developers can create a custom action by inheriting a specific
interface, with instructions provided in the info tab of the field.

-   Administrators can determine whether the process will execute before
    or after saving the form entry to the database. In case of failure,
    an error message can be displayed, and subsequent actions can be
    canceled with customizable failure messages.

## Additional Information

### Installation

The Dymior Forms plugin can be installed in Umbraco CMS using the
following commands:

dotnet add package Dymior.Forms

dotnet add package Dymior.Forms.Core

### During the installation process, three sample forms are included, each with different styles: Contact Form, CV/Resume Form, and Request a Quote Form.

### *Please ensure that the existing Umbraco installation is configured with the SMTP server and that the correct email addresses are entered in the mail action field.*

### Frameworks and Umbraco Versions

The plugin supports .NET 6, .NET 7, and .NET 8 for Umbraco versions 10,
11, 12, and 13.

### Database Support

Dymior Forms is compatible with Microsoft SQL Server and SQLite.

### How to Embed

Forms can be embedded on the site in three ways:

1.  **JavaScript Snippet**: Use the JavaScript snippet for the form,
    which can be found in the Info tab.

2.  **Dymior Forms Macro**: Utilize the \"Dymior Forms Macro,\" which
    includes a Form Picker Editor and can be inserted into an HTML
    editor within the CMS.

3.  **Razor View Invocation**: Call the form directly using \@await
    Component.InvokeAsync(\"DymiorForm\", new { FormId = formId })
    within the necessary Razor view.

Please note that using the JavaScript snippet allows embedding on
different sites (Cross-Origin Resource Sharing, or CORS), provided the
domains are registered under the license and cookie settings permit it.

### License

The Dymior Forms plugin is a startup solution designed to enhance form
management within your Umbraco CMS environment.

The license for the Dymior Forms plugin is priced at **200 euros per
domain**. Each production domain is permitted to have **one test
domain** for testing purposes only.

To purchase a license, please contact us at dymiorforms@outlook.com.

The license includes updates for the plugin. Please note that a new
license is required for each change in the major version.

### Support and Feedback

If you encounter any issues with the Dymior Forms Plugin, please
feel free to report them on our GitHub page. As a startup,
we greatly value your feedback and are committed to improving
the plugin based on user experiences.
