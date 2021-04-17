<div dir="rtl" lang="he">

# אנשי השלג

כיתבו פונקציה המציירת איש-שלג!
הגדרה מפורטת של הקלט והפלט נמצאת כאן:
https://codegolf.stackexchange.com/q/49671/12019

בשלב ב עליכם לכתוב מימוש מלא. המימוש צריך לעבור את כל הבדיקות (75% מהציון):

<div dir='ltr'>

    make test
    ./test

</div>

הסקריפט משתמש בתוכנה curl - ייתכן שתצטרכו להתקין אותה ע"י `sudo apt install curl`.

בנוסף, הקוד צריך לעבור בהצלחה את מבחן הקריאות (25% מהציון):

<div dir='ltr'>

    make tidy

</div>

הסקריפט משתמש בתוכנה clang-tidy - ייתכן שתצטרכו להתקין אותה ע"י `sudo apt install clang-tidy`.

בנוסף, יש לכתוב **תוכנית ראשית** כלשהי המדגימה את הפתרון שלכם.
תוכן התוכנית לבחירתכם - תהיו יצירתיים. התוכנית לא תיבדק אוטומטית אלא רק בהצגה.

כשהגעתם למצב ששתי הפקודות רצות בלי שגיאות, תוכלו לבדוק את הציון שלכם ע"י הפקודה:

<div dir='ltr'>

    bash grade

</div>

עצה: כדי שהסקריפט grade ירוץ מהר יותר במהלך הפיתוח, מומלץ להגדיר את משתנה-הסביבה DEBUG:
<div dir='ltr'>

    export DEBUG=1

</div>



אין לשנות קבצים קיימים, אלא רק להוסיף קבצים חדשים.
מערכת הבדיקה האוטומטית מעתיקה מחדש את כל הקבצים הקיימים על-גבי הפתרון שאתם מגישים,
ולכן כל שינוי שתעשו בקבצים הקיימים יימחק.
</div>



