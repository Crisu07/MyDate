# MyDate Object 📅 🧾
Help manipulate and manage Julian and Gregorian dates.

## 📆 Instructions 📆
Create a C++ class called myDate. It should have the following operations:
-	myDate() – default constructor. This will set the date to May 11, 1959
-	myDate(int M, int D, int Y) – overloaded constructor. This will set the date to the values passed in through the parameter list represented by Month, Day and Year.
-	void display() – display the date in the following format (May 11, 1959) Do NOT print a linefeed after the date.
-	void increaseDate(int N) – increment the date by N days.
-	void decreaseDate(int N) – decrement the date by N days.
-	int daysBetween(myDate D) – return the number of days between this date and the date D.  If date D is a future date, the return value will be a positive int.  If date D is in the past, the return value will be a negative int.
-	int getMonth() – return the month in integer form
-	int getDay() – return the day of the month
-	int getYear() – return the year
-	int dayOfYear() - return the number of days since the current year began. Example Jan 1 is 1, Feb 1 is 32.
- string dayName() – returns Monday, Tuesday, etc according to the day of the week. 

### 📆 Things to keep in mind 📆
- You can never have a date that is invalid. The only opportunity for this to happen will be with the overloaded constructor. Therefore if any invalid data is passed to this constructor, ignore all data and set the values to the default date.

## 📆 Running the Program 📆
- Download the zip file and open in an IDE compatible of compiling C++ (I use Visual Studio Community 2022 in this case)
- Run the app and follow the menu instructions on the console
