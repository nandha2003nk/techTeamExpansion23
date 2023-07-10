# Task: Create a Form and Store Data in Firestore

## Description

As a tech head, you want to expand your team and have prepared a task to select the right candidates. The task involves creating a form with specific fields and submitting the form. On submission, the data should be stored in a Firestore database. Participants are also required to create a collection with their first name and branch, following a specific naming convention.

## Task Requirements

1. Create a form with the following fields:
   - **Name**: A field for participants to enter their full name.
   - **Branch**: A field for participants to enter their branch of study.
   - **Email**: A field for participants to enter their email address.
   - **PhoneNumber**: A field for participants to enter their phone number.

2. All fields mentioned above are required, meaning participants must provide information for each field before submitting the form.

3. Implement form validation to ensure that participants provide valid data. For example, validate that the email address follows the proper format, and ensure the phone number is in a valid format as well.

4. Design and implement a user interface (UI) for the form. Participants are free to choose any framework they prefer for building the UI.

5. Configure Firebase Firestore to store the form data. You will provide the participants with the Firebase configuration file that they will need to integrate into their solution.

6. Participants should create a collection in Firestore with the following naming convention:
   - Collection Name: FirstNameBranch
   - For example, if a participant's name is "Balveer Singh Rao" and their branch is "electrical," the collection name would be "BalveerElectrical".

7. Once participants complete the task, they are required to raise a pull request on your repository. Make sure to provide them with the necessary information on how to do so.

## Deadline

The deadline for completing this task is the end of the day (EOD) on July 13th.

## Additional Notes

- Participants are free to use any framework of their choice for building the form and UI. They can select from popular options such as React, Angular, Vue.js, or any other framework they are comfortable with.

- It is essential to ensure the security and privacy of the collected data. Participants should handle sensitive information, such as email addresses and phone numbers, with care and follow best practices for data storage and protection.

- Encourage participants to write clean and well-documented code. This will make reviewing their submissions easier and allow for better evaluation of their skills.

- Provide clear instructions to the participants on how to access the Firebase configuration file and integrate it into their solution. Additionally, specify any specific requirements or guidelines they need to follow when setting up Firestore.

- Once the pull requests are submitted, make sure to review each submission thoroughly, taking into account the completeness of the task, code quality, form validation, UI design, and adherence to best practices.

- Feel free to provide additional guidance or resources to the participants, such as helpful tutorials or examples that may assist them in completing the task successfully.