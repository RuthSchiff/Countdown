# ספירה לאחור לחתונה
## תיאור הפרויקט
אפליקציה אינטראקטיבית לספירה לאחור לחתונה, המאפשרת התאמה אישית של חוויית המשתמש. המשתמש יכול להזין את שמות החתן והכלה, לבחור תאריך חתונה, לשנות צבעים, להעלות תמונת רקע מותאמת אישית, ולצפות בספירה לאחור מעוצבת ורספונסיבית.

## תכונות עיקריות
## ספירה לאחור דינמית:

### הצגת הזמן שנותר עד לתאריך החתונה (ימים, שעות, דקות ושניות).
עדכון אוטומטי של הספירה בכל שנייה.
התאמה אישית:

### אפשרות להזין את שמות החתן והכלה.
בחירת צבע טקסט מותאם אישית.
העלאת תמונת רקע מותאמת אישית.
### שמירת נתונים:

שימוש ב-localStorage לשמירת שמות החתן והכלה, תאריך החתונה, וצבע הטקסט.
שימוש ב-IndexedDB לשמירת תמונת הרקע.
### עיצוב רספונסיבי:

התאמה מלאה לכל סוגי המסכים (מחשבים, טאבלטים, וניידים).
שימוש ב-Flexbox ו-Media Queries לעיצוב רספונסיבי.
### אנימציות ואפקטים:

אנימציית לבבות נופלים ביום החתונה.
אפקטים של צללים וטקסט זוהר.
# מבנה הפרויקט
HTML:
מבנה דף אינטרנט הכולל טפסים להזנת נתונים, כפתור עריכה, ותצוגת ספירה לאחור.
CSS:
עיצוב רספונסיבי עם Flexbox, Media Queries, ואפקטים דינמיים.
JavaScript:
לוגיקה לניהול הספירה לאחור, שמירת נתונים ב-localStorage ו-IndexedDB, ואינטראקציות עם המשתמש.
דרישות מערכת
דפדפן מודרני התומך ב-localStorage ו-IndexedDB.
חיבור אינטרנט (לא חובה, אך נדרש להורדת תמונת רקע ברירת מחדל).
### הוראות התקנה
הורד את קבצי הפרויקט.
פתח את הקובץ index.html בדפדפן.
שימוש
הזן את שמות החתן והכלה בשדות המתאימים.
בחר תאריך חתונה.
שנה את צבע הטקסט או העלה תמונת רקע מותאמת אישית.
לחץ על "התחל ספירה" כדי להציג את הספירה לאחור.
ניתן לערוך את ההגדרות על ידי לחיצה על כפתור "עריכה".
### מבנה הקוד
HTML
#panel: טופס להזנת שמות, תאריך, צבעים ותמונת רקע.
#countdown: תצוגת הספירה לאחור.
#titleNames: כותרת המציגה את שמות החתן והכלה.
#titleStarted: כותרת המציינת שהספירה לאחור החלה.
CSS
עיצוב רספונסיבי עם Flexbox ו-Media Queries.
אפקטים דינמיים כמו צללים, אנימציות, ולבבות נופלים.
JavaScript
### פונקציות עיקריות:
#### startCountdown: מתחילה את הספירה לאחור.
#### createHearts: יוצר אפקט לבבות נופלים.
#### saveBgImage ו-loadBgImage: שמירה וטעינה של תמונת רקע מ-IndexedDB.
#### window.onload: localStorage ו-IndexedDB - נטענים הנתונים בעת טעינת הדף מ.

##
##

# Wedding Countdown

## Project Description  
An interactive wedding countdown app that allows users to personalize their experience. The user can enter the names of the bride and groom, choose a wedding date, change text colors, upload a custom background image, and view a styled, responsive countdown timer.

## Key Features

### Dynamic Countdown:  
- Displays the time remaining until the wedding date (days, hours, minutes, and seconds).  
- Automatically updates the countdown every second.

### Personalization:  
- Option to input the names of the bride and groom.  
- Custom text color selection.  
- Upload a personalized background image.

### Data Storage:  
- Uses `localStorage` to save the names, wedding date, and text color.  
- Uses `IndexedDB` to store the background image.

### Responsive Design:  
- Fully responsive for all screen types (desktops, tablets, and mobile devices).  
- Built with Flexbox and Media Queries for responsive layout.

### Animations and Effects:  
- Falling heart animation on the wedding day.  
- Shadow and glowing text effects.

## Project Structure

**HTML:**  
Defines the webpage structure, including data input forms, an edit button, and the countdown display.

**CSS:**  
Responsive design with Flexbox, Media Queries, and dynamic effects.

**JavaScript:**  
Logic for countdown management, data saving with localStorage and IndexedDB, and user interaction handling.

## System Requirements  
- A modern browser that supports `localStorage` and `IndexedDB`.  
- Internet connection (optional, but needed to load the default background image).

## Installation Instructions  
1. Download the project files.  
2. Open the `index.html` file in your browser.

## Usage  
- Enter the names of the bride and groom.  
- Choose a wedding date.  
- Customize the text color or upload a background image.  
- Click “Start Countdown” to begin.  
- You can edit the settings anytime by clicking the “Edit” button.

## Code Structure

**HTML**  
- `#panel`: Form for entering names, date, colors, and background image.  
- `#countdown`: The countdown display section.  
- `#titleNames`: Title displaying the names of the couple.  
- `#titleStarted`: Title indicating the countdown has started.

**CSS**  
- Responsive styling with Flexbox and Media Queries.  
- Dynamic effects like shadows, animations, and falling hearts.

**JavaScript**

### Main Functions:
- `startCountdown`: Starts the countdown timer.  
- `createHearts`: Creates the falling heart effect.  
- `saveBgImage` and `loadBgImage`: Save and load background images using IndexedDB.  
- `window.onload`: Loads saved data from localStorage and IndexedDB on page load.

