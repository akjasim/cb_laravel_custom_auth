# Laravel Custom Authentication using Username/Phone number

Customising the default Email based authentication to a username/phone_number based authentication.

## Usage

#### 1) Add username/phone_number column to users migration file.
#### 2) Migrate all files.
#### 3) Edit Registration view to add username/phone_number input field.
#### 4) Edit RegisterController
    a) Add username/phone_number to the validate() method.
    b) Add username/phone_number to the create() method.
#### 5) Add username/phone_number to $fillable property in User model.
#### 6) Override username() method in LoginController to return username/phone_number.
#### 7) Edit the Login view to display username/phone_number input instead of Email.

That's it.
