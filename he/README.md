<span align="right" dir="rtl">
# כיצד להיות מתכנת:  מהדורת הקהילה
[//]: # (גרסה :1.0.0)
רוברט ל. ריד והקהילה

מתרגם: ים מסיקה

Copyright 2002, 2003, 2016 Robert L. Read

תחת רישיון [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

[זמין גם ב־gitbook לקריאה מקוונת או להורדה לצורך קריאה במצב לא מקוון (PDF, ePub או Mobi)](https://www.gitbook.com/book/braydie/how-to-be-a-programmer/details)

[זמין לרכישה כספר בכריכה קשה (מכסה עלויות יצור ומשלוח בלבד)](http://www.blurb.com/b/6999069-how-to-be-a-programmer) – מהדורה ראשונה, פורסמה ב־04/01/16

## הקדמה

להיות מתכנת טוב זה דבר קשה ואצילי. החלק הקשה ביותר ביצירת חזון קולקטיבי של פרויקט תוכנה הוא התמודדות עם השותפים והלקוחות. כתיבת תוכנות מחשב זה חשוב, וזה מצריך הרבה תבונה ומיומנות. אבל זה באמת משחק ילדים בהשוואה לכל דבר שמתכנת טוב חייב לעשות על־מנת ליצור תוכנה שתצליח גם עבור הלקוחות וגם עבור מספר עצום של עמיתים לעבודה, עליהם הוא אחראי במידה מסוימת. בחיבור זה אני אנסה לתמצת בבהירות ככל הניתן את הדברים שהייתי רוצה שמישהו יסביר לי כשהייתי בן עשרים ואחת.

זהו דבר מאוד סובייקטיבי, ולכן, על חיבור זה נגזר להיות אישי ובמידת־מה דעתני. אני מגביל את עצמי לבעיות שלמתכנת יש סיכוי רב להתמודד איתן בעבודתו. רבות מבעיות אלו ופתרונותיהן כל־כך נפוצים במצבים אנושיים שאני ודאי אצטייר כמטיף. אני מקווה שלמרות זאת החיבור הזה יהיה שימושי.

תכנות מחשבים נלמד בקורסים. כל הספרים המצוינים: The Pragmatic Programmer [Prag99], Code Complete [CodeC93], Rapid Development [RDev96], וכן Extreme Programming Explained [XP99] מלמדים תכנות, ועל הבעיות הגדולות שבלהיות מתכנת. המאמרים של Paul Graham [PGSite] ושל Eric Raymond [Hacker] בוודאות צריכים להיקרא לפני או תוך־כדי קריאת ספר זה. חיבור זה שונה מהעבודות המצוינות האלו בכך שהוא מדגיש את הבעיות החברתיות ומסכם באופן מקיף את כלל המיומנויות הנחוצות כפי שאני רואה אותן.

בחיבור זה, נעשה שימוש במונח "בוס" כדי להתייחס למי שנותן לך פרויקטים לביצוע. אני משתמש במילים "עסק", "חברה" ו"שבט" כמילים נרדפות, פרט לכך שהמילה "עסק" מרמזת על יצירת רווחים כספיים, המילה "חברה" מרמזת על מקום העבודה המודרני והמילה "שבט" בדרך־כלל תייצג אנשים שאתה חולק עמם קשר של אמון.

ברוך הבא לשבט.

## תוכן עניינים

**[זמין גם באנגלית](en/README.md)**

**[זמין גם בסינית](zh/README.md)**

1. [מתחיל](he/1-Beginner)
	- מיומנויות אישיות
		- [למד לנפות תקלים](he/1-Beginner/Personal-Skills/01-Learn To Debug.md)
		- [כיצד לנפות תקלים בעזרת פיצול מרחב הבעיה](he/1-Beginner/Personal-Skills/02-How to Debug by Splitting the Problem Space.md)
		- [כיצד למחוק שגיאה](he/1-Beginner/Personal-Skills/03-How to Remove an Error.md)
		- [כיצד לנפות תקלים בעזרת לוג](he/1-Beginner/Personal-Skills/04-How to Debug Using a Log.md)
		- [כיצד להבין בעיות ביצועים](he/1-Beginner/Personal-Skills/05-How to Understand Performance Problems.md)
		- [כיצד לתקן בעיות ביצועים](he/1-Beginner/Personal-Skills/06-How to Fix Performance Problems.md)
		- [כיצד לייעל לולאות](he/1-Beginner/Personal-Skills/07-How to Optimize Loops.md)
		- [כיצד להתמודד מול עלויות קלט־פלט](he/1-Beginner/Personal-Skills/08-How to Deal with IO Expense.md)
		- [כיצד לנהל זיכרון](he/1-Beginner/Personal-Skills/09-How to Manage Memory.md)
		- [כיצד להתמודד עם תקלים שקורים לסירוגין](he/1-Beginner/Personal-Skills/10-How to Deal with Intermittent Bugs.md)
		- [כיצד ללמוד מיומנויות עיצוב תוכנה](he/1-Beginner/Personal-Skills/11-How to Learn Design Skills.md)
		- [כיצד לבצע ניסויים](he/1-Beginner/Personal-Skills/12-How to Conduct Experiments.md)
	- מיומנויות צוותיות
		- [מדוע הערכות זה חשוב](he/1-Beginner/Team-Skills/01-Why Estimation is Important.md)
		- [כיצד להעריך זמן תכנות](he/1-Beginner/Team-Skills/02-How to Estimate Programming Time.md)
		- [כיצד למצוא מידע](he/1-Beginner/Team-Skills/03-How to Find Out Information.md)
		- [כיצד להשתמש באנשים כמקורות מידע](he/1-Beginner/Team-Skills/04-How to Utilize People as Information Sources.md)
		- [כיצד לתעד בחוכמה](he/1-Beginner/Team-Skills/05-How to Document Wisely.md)
		- [כיצד לעבוד עם קוד גרוע](he/1-Beginner/Team-Skills/06-How to Work with Poor Code.md)
		- [כיצד להשתמש בניהול קוד](he/1-Beginner/Team-Skills/07-How to Use Source Code Control.md)
		- [כיצד לעשות בדיקות יחידה](he/1-Beginner/Team-Skills/08-How to Unit Test.md)
		- [קח הפסקות כשאתה אובד עצות](he/1-Beginner/Team-Skills/09-Take Breaks when Stumped.md)
		- [כיצד לזהות מתי ללכת הביתה](he/1-Beginner/Team-Skills/10-How to Recognize When to Go Home.md)
		- [כיצד להתמודד עם אנשים קשים](he/1-Beginner/Team-Skills/11-How to Deal with Difficult People.md)
2. [בינוני](he/2-Intermediate)
	- מיומנויות אישיות
		- [כיצד לשמור על מוטיבציה](he/2-Intermediate/Personal-Skills/01-How to Stay Motivated.md)
		- [כיצד להשיג אמון נרחב](he/2-Intermediate/Personal-Skills/02-How to be Widely Trusted.md)
		- [כיצד לאזן בין זמן ואחסון](he/2-Intermediate/Personal-Skills/03-How to Tradeoff Time vs Space.md)
		- [כיצד לעשות בדיקות מאמץ](he/2-Intermediate/Personal-Skills/04-How to Stress Test.md)
		- [כיצד לאזן בין קיצור להפשטה](he/2-Intermediate/Personal-Skills/05-How to Balance Brevity and Abstraction.md)
		- [כיצד ללמוד מיומנויות חדשות](he/2-Intermediate/Personal-Skills/06-How to Learn New Skills.md)
		- [למד להקליד](he/2-Intermediate/Personal-Skills/07-Learn to Type.md)
		- [כיצד לבצע בדיקות שילוב](he/2-Intermediate/Personal-Skills/08-How to Do Integration Testing.md)
		- [שפות תקשורת](he/2-Intermediate/Personal-Skills/09-Communication Languages.md)
		- [כלים כבדים](he/2-Intermediate/Personal-Skills/10-Heavy Tools.md)
		- [כיצד לנתח מידע](he/2-Intermediate/Personal-Skills/11-How to analyze data.md)
	- מיומנויות צוותיות
		- [כיצד לנהל זמן פיתוח](he/2-Intermediate/Team-Skills/01-How to Manage Development Time.md)
		- [כיצד לנהל סיכוני תוכנה צד־שלישי](he/2-Intermediate/Team-Skills/02-How to Manage Third-Party Software Risks.md)
		- [כיצד לנהל יועצים](he/2-Intermediate/Team-Skills/03-How to Manage Consultants.md)
		- [כיצד לתקשר במידה הנכונה](he/2-Intermediate/Team-Skills/04-How to Communicate the Right Amount.md)
		- [כיצד לא להסכים בכנות ולהצליח לצאת מזה](he/2-Intermediate/Team-Skills/05-How to Disagree Honestly and Get Away with It.md)
	- שיפוט
		- [כיצד לאזן בין איכות לבין זמן הפיתוח](he/2-Intermediate/Judgment/01-How to Tradeoff Quality Against Development Time.md)
		- [כיצד לנהל קשרי תלות בתוכנה](he/2-Intermediate/Judgment/02-How to Manage Software System Dependence.md)
		- [כיצד להחליט האם התוכנה בוסרית מדי](he/2-Intermediate/Judgment/03-How to Decide if Software is Too Immature.md)
		- [כיצד לקבל החלטות קנייה או פיתוח בעצמך](he/2-Intermediate/Judgment/04-How to Make a Buy vs Build Decision.md)
		- [כיצד להתפתח מקצועית](he/2-Intermediate/Judgment/05-How to Grow Professionally.md)
		- [כיצד להעריך מרואיינים](he/2-Intermediate/Judgment/06-How to Evaluate Interviewees.md)
		- [כיצד לדעת מתי להחיל תעלולים מגונדרים של מדעי המחשב](he/2-Intermediate/Judgment/07-How to Know When to Apply Fancy Computer Science.md)
		- [כיצד לדבר עם לא מהנדסים](he/2-Intermediate/Judgment/08-How to Talk to Non-Engineers.md)
3. [מתקדם](he/3-Advanced)
    - שיפוט טכנולוגי
        - [כיצד להבדיל בין הקשה לבלתי־אפשרי](he/3-Advanced/Technical-Judgment/01-How to Tell the Hard From the Impossible.md)
        - [כיצד להשתמש בשפות משובצות](he/3-Advanced/Technical-Judgment/02-How to Utilize Embedded Languages.md)
        - [בחירת שפות](he/3-Advanced/Technical-Judgment/03-Choosing Languages.md)
    - התפשרות בחוכמה
        - [כיצד להלחם בלחץ של לוחות זמנים](he/3-Advanced/Compromising-Wisely/01-How to Fight Schedule Pressure.md)
        - [כיצד להבין את המשתמש](he/3-Advanced/Compromising-Wisely/02-How to Understand the User.md)
        - [כיצד לקבל קידום](he/3-Advanced/Compromising-Wisely/03-How to Get a Promotion.md)
    - שירות הצוות שלך
        - [כיצד לפתח כישרון](he/3-Advanced/Serving-Your-Team/01-How to Develop Talent.md)
        - [כיצד לבחור על מה לעבוד](he/3-Advanced/Serving-Your-Team/02-How to Choose What to Work On.md)
        - [כיצד להשיג את המיטב מחבריך לצוות](he/3-Advanced/Serving-Your-Team/03-How to Get the Most From Your Teammates.md)
        - [כיצד לחלק בעיות](he/3-Advanced/Serving-Your-Team/04-How to Divide Problems Up.md)
        - [כיצד לטפל במשימות משעממות](he/3-Advanced/Serving-Your-Team/05-How to Handle Boring Tasks.md)
        - [כיצד לגייס תמיכה עבור הפרויקט שלך](he/3-Advanced/Serving-Your-Team/06-How to Gather Support for a Project.md)
        - [כיצד להגדיל מערכת](he/3-Advanced/Serving-Your-Team/07-How to Grow a System.md)
        - [כיצד לתקשר היטב](he/3-Advanced/Serving-Your-Team/08-How to Communicate Well.md)
        - [כיצד להגיד לאנשים דברים שהם לא רוצים לשמוע](he/3-Advanced/Serving-Your-Team/09-How to Tell People Things They Don't Want to Hear.md)
        - [כיצד להתמודד עם מיתוסים של מנהלים](he/3-Advanced/Serving-Your-Team/10-How to Deal with Managerial Myths.md)
        - [כיצד להתמודד עם תוהו־ובוהו ארגוני](he/3-Advanced/Serving-Your-Team/11-How to Deal with Organizational Chaos.md)
4. [מילון](he/GLOSSARY.md)
5. [נספח א' - ביבליוגרפיה/אתרוגרפיה](he/5-Bibliography.md)
6. [נספח ב' – היסטוריה (נכון לינואר 2016)](he/6-History.md)
6. [נספח ג' – תרומות (נכון לינואר 2016)](he/7-Contributions.md)


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">How To Be A Programmer: Community Version</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Robert L. Read with Community</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</span>
