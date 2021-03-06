Ticket: User Preferences
========================

**Problem:**

**User Story**

"As a user, I want to be able to store preferences such as my favorite cast member and preferred language."

---

**Task**

For this Ticket, you'll be required to implement the **updateUserPreferences** method in _UserDao.java_. This method allows updates to be made to the _"preferences"_ field in the _users_ collection.

---

**MFlix Functionality**

Once this ticket is completed, users will be able to save preferences in their account information.

---

**Testing and Running the Application**

If the application is already running, **stop the application** and run the unit tests for this ticket by executing the following command:

```
mvn test -Dtest=UserPreferencesTest
```

Once the unit tests are passing, run the application with:

```
mvn spring-boot:run
```

Or run the _Application.java_ from your IDE.

Now proceed to the status page to run the full suite of integration tests and get your validation code.

To have the application use the changes that you implemented for this ticket, make sure to **restart the application** after you completed those changes. Also, only refresh the status page to see the new results of the tests, after the application has been restarted.

<details> 
  <summary>After passing the relevant tests, what is the validation code for User Preferences?</summary>
   Answer: 5aabe31503ac76bc4f73e267
</details>