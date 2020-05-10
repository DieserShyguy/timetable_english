# Timetable
## Information:
Dieses Repository ist in Deutsch verfügbar: [hier](https://github.com/diesershyguy/stundenplan_deutsch)

## Example:
You can find an example on this page: [here](https://diesershyguy.github.io/timetable_english)
## Usage:
### Step 0: Downloading
You can download it there: [Downloads](https://github.com/diesershyguy/timetable_english/releases)
### Step 1 Edit file:
Open the ```index.html``` in an Editor like the Windows default Editor or Notepad++ or you can open it in an IDE like Visual Studio Code
### Step 2 Setting up:
Find the part of Code which you can find between line 19 and 23:
```
                    ["Monday","1","2","3","4","5","6","7"],
                    ["Tuesday","1","2","3","4","5","6","7"],
                    ["Wednesday","1","2","3","4","5","6","7"],
                    ["Thursday","1","2","3","4","5","6","7"],
                    ["Friday","1","2","3","4","5","6","7"],
```
You replace it with this line of code:
```
                    ["<YOUR DAY>","Lesson 1"],
```
**Make sure you have marked the free space every time you want do copy something!** Replace `<YOUR DAY>` with something like Monday. If you have different timetables in school, which are changing for example every week. You can put a number before Monday or every other day. It could look like so: `1 Monday`
### Step 3: Adding Lessons
You put a comma after the quotation marks and set new quotation marks. Inside them you can type in the Name of the lesson. It should look like this:
```
                    ["Tuesday","physics","maths","P.E",]
```
### Step 4: Adding Days
To add a day, you have to go to the end of the line after the comma. Press `Enter`. If the Cursor is at the beginning of the line and not under the square bracket then press `Tab` 5x. Then paste the line of code:
```
                     ["<YOUR DAY>","Lesson 1"],
```
Replace `<YOUR DAY>` with something like Monday again. The first entry of the list is the Day. **Don't put your first lesson in there!** Because then you can't find it any more and in the selection box when it doesn't say the timetable of Monday, but it says the timetable of maths. That makes no sense.
### Step 5: Save the File
Click on file and Save or use the Hotkey `Ctrl + S` to save.
### Step 6: Open the file
Navigate to the folder, were your ``index.html`` is. Make a double click on the ```index.html```. Then your default browser should start and shows a selection box. Click on it and and you can see all the days you have entered. When you click on one day, your lessons should show up in a table.That's it!