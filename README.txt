גרסת רב מסר מעודכנת

קבצים:
- index.html — המשחק + מסך ההרשמה עם טופס רב מסר
- result.html — דף התודה/תוצאה אחרי הרשמה

כתובות בגיטהאב:
- משחק: https://zchootmusicmedia.github.io/oved-hazak/
- דף תודה ברב מסר: https://zchootmusicmedia.github.io/oved-hazak/result.html

מה תוקן:
1. הוסר מסך "לאן לשלוח את האוצר" הכפול.
2. אחרי סיום המשחק מופיע רק מסך "כספת האנרגיה שלך מוכנה".
3. בתוך המסך הזה נטען טופס רב מסר.
4. קוד רב מסר מוטמע כ-script דינמי עם כתובת https מלאה.
5. לאחר הרשמה ברב מסר יש להפנות את המשתמשת ל-result.html.
6. result.html קורא את התוצאה שנשמרה בדפדפן ב-LocalStorage.

חשוב:
ברב מסר יש להגדיר את דף התודה:
https://zchootmusicmedia.github.io/oved-hazak/result.html

אם הטופס לא מופיע:
- לבדוק שהטופס ברב מסר פורסם ופעיל.
- לבדוק שהקוד שניתן הוא "קוד הטמעה לאתרים / דפי נחיתה סטנדרטיים".
- אם הקוד משתנה, להחליף את ה-src בתוך הפונקציה injectRavMesserForm בקובץ index.html.
