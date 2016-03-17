# ContactRegister
Android App for managing contacts

Contact Details Android App made in Android Studio

Build a simple contact manager application. The application have the following features:

Adding a list of contacts by name, email address and telephone number
Deleting contacts
Retrieving a list of contacts whose data matches all or part of a search string. (You can search by email address, phone number or name.)

In other words, this is a simple CRUD application!

Explanation:

1)It uses 4 activities ContactRegister:This is the opening activity ,contains "add new" and "search" contact buttons and list view showing added contacts AddEdit: This contains edit text boxes for adding and updating contacts. EditDelete: This shows contact information and contains "edit" and "delete" buttons Search: This page allows user to enter search query and show the results in a list view.

2)ContactRegister-(AddNew)->AddEdit-(Add/Update)->ContactRegister 3)ContactRegister-(List view option)->EditDelete-(Edit)->AddEdit-(AddUpdate)->ContactRegister 4)ContactRegister-(List view option)->EditDelete-(Delete)->ContactRegister 5)ContactRegister-(Search)->Search-(Search By)--(Search Value)--(Search)->ListView-(List View Option)->EditDelete
