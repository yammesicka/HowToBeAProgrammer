<h1 align="right" dir="rtl" style="float: right !important;">כיצד להיות מתכנת:  מהדורת הקהילה</h1>
[//]: # (גרסה :1.0.0)
<p align="right" dir="rtl" style="float: right !important;">רוברט ל. ריד והקהילה</p>

<p align="right" dir="rtl" style="float: right !important;">מתרגם: ים מסיקה</p>

<p align="right" dir="rtl" style="float: right !important;">Copyright 2002, 2003, 2016 Robert L. Read</p>

<p align="right" dir="rtl" style="float: right !important;">תחת רישיון <a href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.</p>

<p align="right" dir="rtl" style="float: right !important;"><a href="https://www.gitbook.com/book/braydie/how-to-be-a-programmer/details">זמין גם ב־gitbook לקריאה מקוונת או להורדה לצורך קריאה במצב לא מקוון (PDF, ePub או Mobi)</a></p>

<p align="right" dir="rtl" style="float: right !important;"><a href="http://www.blurb.com/b/6999069-how-to-be-a-programmer">זמין לרכישה כספר בכריכה קשה (מכסה עלויות יצור ומשלוח בלבד)</a> – מהדורה ראשונה, פורסמה ב־04/01/16

<h2 align="right" dir="rtl" style="float: right !important;">הקדמה</h2>

<p align="right" dir="rtl" style="float: right !important;">להיות מתכנת טוב זה דבר קשה ואצילי. החלק הקשה ביותר ביצירת חזון קולקטיבי של פרויקט תוכנה הוא התמודדות עם השותפים והלקוחות. כתיבת תוכנות מחשב זה חשוב, וזה מצריך הרבה תבונה ומיומנות. אבל זה באמת משחק ילדים בהשוואה לכל דבר שמתכנת טוב חייב לעשות על־מנת ליצור תוכנה שתצליח גם עבור הלקוחות וגם עבור מספר עצום של עמיתים לעבודה, עליהם הוא אחראי במידה מסוימת. בחיבור זה אני אנסה לתמצת בבהירות ככל הניתן את הדברים שהייתי רוצה שמישהו יסביר לי כשהייתי בן עשרים ואחת.</p>

<p align="right" dir="rtl" style="float: right !important;">זהו דבר מאוד סובייקטיבי, ולכן, על חיבור זה נגזר להיות אישי ובמידת־מה דעתני. אני מגביל את עצמי לבעיות שלמתכנת יש סיכוי רב להתמודד איתן בעבודתו. רבות מבעיות אלו ופתרונותיהן כל־כך נפוצים במצבים אנושיים שאני ודאי אצטייר כמטיף. אני מקווה שלמרות זאת החיבור הזה יהיה שימושי.</p>

<p align="right" dir="rtl" style="float: right !important;">תכנות מחשבים נלמד בקורסים. כל הספרים המצוינים: The Pragmatic Programmer [Prag99], Code Complete [CodeC93], Rapid Development [RDev96], וכן Extreme Programming Explained [XP99] מלמדים תכנות, ועל הבעיות הגדולות שבלהיות מתכנת. המאמרים של Paul Graham [PGSite] ושל Eric Raymond [Hacker] בוודאות צריכים להיקרא לפני או תוך־כדי קריאת ספר זה. חיבור זה שונה מהעבודות המצוינות האלו בכך שהוא מדגיש את הבעיות החברתיות ומסכם באופן מקיף את כלל המיומנויות הנחוצות כפי שאני רואה אותן.</p>

<p align="right" dir="rtl" style="float: right !important;">בחיבור זה, נעשה שימוש במונח "בוס" כדי להתייחס למי שנותן לך פרויקטים לביצוע. אני משתמש במילים "עסק", "חברה" ו"שבט" כמילים נרדפות, פרט לכך שהמילה "עסק" מרמזת על יצירת רווחים כספיים, המילה "חברה" מרמזת על מקום העבודה המודרני והמילה "שבט" בדרך־כלל תייצג אנשים שאתה חולק עמם קשר של אמון.</p>

<p align="right" dir="rtl" style="float: right !important;">ברוך הבא לשבט.</p>

<h2 align="right" dir="rtl" style="float: right !important;">תוכן עניינים</h2>

<p align="right" dir="rtl" style="float: right !important;">**[זמין גם באנגלית](../en/README.md)**

<p align="right" dir="rtl" style="float: right !important;">**[זמין גם בסינית](../zh/README.md)**

<ul align="right" dir="rtl" style="float: right !important;">
<li><a href="1-Beginner">מתחיל</a></li>
    <ul>
    <li>מיומנויות אישיות</li>
        <ul>
            <li><a href="1-Beginner/Personal-Skills/01-Learn To Debug.md">למד לנפות תקלים</a></li>
            <li><a href="1-Beginner/Personal-Skills/02-How to Debug by Splitting the Problem Space.md">כיצד לנפות תקלים בעזרת פיצול מרחב הבעיה</a></li>
            <li><a href="1-Beginner/Personal-Skills/03-How to Remove an Error.md">כיצד למחוק שגיאה</a></li>
            <li><a href="1-Beginner/Personal-Skills/04-How to Debug Using a Log.md">כיצד לנפות תקלים בעזרת לוג</a></li>
            <li><a href="1-Beginner/Personal-Skills/05-How to Understand Performance Problems.md">כיצד להבין בעיות ביצועים</a></li>
            <li><a href="1-Beginner/Personal-Skills/06-How to Fix Performance Problems.md">כיצד לתקן בעיות ביצועים</a></li>
            <li><a href="1-Beginner/Personal-Skills/07-How to Optimize Loops.md">כיצד לייעל לולאות</a></li>
            <li><a href="1-Beginner/Personal-Skills/08-How to Deal with IO Expense.md">כיצד להתמודד מול עלויות קלט־פלט</a></li>
            <li><a href="1-Beginner/Personal-Skills/09-How to Manage Memory.md">כיצד לנהל זיכרון</a></li>
            <li><a href="1-Beginner/Personal-Skills/10-How to Deal with Intermittent Bugs.md">כיצד להתמודד עם תקלים שקורים לסירוגין</a></li>
            <li><a href="1-Beginner/Personal-Skills/11-How to Learn Design Skills.md">כיצד ללמוד מיומנויות עיצוב תוכנה</a></li>
            <li><a href="1-Beginner/Personal-Skills/12-How to Conduct Experiments.md">כיצד לבצע ניסויים</a></li>
        </ul>
    <li>מיומנויות צוותיות</li>
        <ul>
            <li><a href="1-Beginner/Team-Skills/01-Why Estimation is Important.md">מדוע הערכות זה חשוב</a></li>
            <li><a href="1-Beginner/Team-Skills/02-How to Estimate Programming Time.md">כיצד להעריך זמן תכנות</a></li>
            <li><a href="1-Beginner/Team-Skills/03-How to Find Out Information.md">כיצד למצוא מידע</a></li>
            <li><a href="1-Beginner/Team-Skills/04-How to Utilize People as Information Sources.md">כיצד להשתמש באנשים כמקורות מידע</a></li>
            <li><a href="1-Beginner/Team-Skills/05-How to Document Wisely.md">כיצד לתעד בחוכמה</a></li>
            <li><a href="1-Beginner/Team-Skills/06-How to Work with Poor Code.md">כיצד לעבוד עם קוד גרוע</a></li>
            <li><a href="1-Beginner/Team-Skills/07-How to Use Source Code Control.md">כיצד להשתמש בניהול קוד</a></li>
            <li><a href="1-Beginner/Team-Skills/08-How to Unit Test.md">כיצד לעשות בדיקות יחידה</a></li>
            <li><a href="1-Beginner/Team-Skills/09-Take Breaks when Stumped.md">קח הפסקות כשאתה אובד עצות</a></li>
            <li><a href="1-Beginner/Team-Skills/10-How to Recognize When to Go Home.md">כיצד לזהות מתי ללכת הביתה</a></li>
            <li><a href="1-Beginner/Team-Skills/11-How to Deal with Difficult People.md">כיצד להתמודד עם אנשים קשים</a></li>
        </ul>
    </ul>
<li><a href="2-Intermediate">בינוני</a></li>
    <ul>
    <li>מיומנויות אישיות</li>
        <ul>
            <li><a href="2-Intermediate/Personal-Skills/01-How to Stay Motivated.md">כיצד לשמור על מוטיבציה</a></li>
            <li><a href="2-Intermediate/Personal-Skills/02-How to be Widely Trusted.md">כיצד להשיג אמון נרחב</a></li>
            <li><a href="2-Intermediate/Personal-Skills/03-How to Tradeoff Time vs Space.md">כיצד לאזן בין זמן ואחסון</a></li>
            <li><a href="2-Intermediate/Personal-Skills/04-How to Stress Test.md">כיצד לעשות בדיקות מאמץ</a></li>
            <li><a href="2-Intermediate/Personal-Skills/05-How to Balance Brevity and Abstraction.md">כיצד לאזן בין קיצור להפשטה</a></li>
            <li><a href="2-Intermediate/Personal-Skills/06-How to Learn New Skills.md">כיצד ללמוד מיומנויות חדשות</a></li>
            <li><a href="2-Intermediate/Personal-Skills/07-Learn to Type.md">למד להקליד</a></li>
            <li><a href="2-Intermediate/Personal-Skills/08-How to Do Integration Testing.md">כיצד לבצע בדיקות שילוב</a></li>
            <li><a href="2-Intermediate/Personal-Skills/09-Communication Languages.md">שפות תקשורת</a></li>
            <li><a href="2-Intermediate/Personal-Skills/10-Heavy Tools.md">כלים כבדים</a></li>
            <li><a href="2-Intermediate/Personal-Skills/11-How to analyze data.md">כיצד לנתח מידע</a></li>
        </ul>
    <li>מיומנויות צוותיות</li>
        <ul>
            <li><a href="2-Intermediate/Team-Skills/01-How to Manage Development Time.md">כיצד לנהל זמן פיתוח</a></li>
            <li><a href="2-Intermediate/Team-Skills/02-How to Manage Third-Party Software Risks.md">כיצד לנהל סיכוני תוכנה צד־שלישי</a></li>
            <li><a href="2-Intermediate/Team-Skills/03-How to Manage Consultants.md">כיצד לנהל יועצים</a></li>
            <li><a href="2-Intermediate/Team-Skills/04-How to Communicate the Right Amount.md">כיצד לתקשר במידה הנכונה</a></li>
            <li><a href="2-Intermediate/Team-Skills/05-How to Disagree Honestly and Get Away with It.md">כיצד לא להסכים בכנות ולהצליח לצאת מזה</a></li>
        </ul>
    <li>שיפוט</li>
        <ul>
            <li><a href="2-Intermediate/Judgment/01-How to Tradeoff Quality Against Development Time.md">כיצד לאזן בין איכות לבין זמן הפיתוח</a></li>
            <li><a href="2-Intermediate/Judgment/02-How to Manage Software System Dependence.md">כיצד לנהל קשרי תלות בתוכנה</a></li>
            <li><a href="2-Intermediate/Judgment/03-How to Decide if Software is Too Immature.md">כיצד להחליט האם התוכנה בוסרית מדי</a></li>
            <li><a href="2-Intermediate/Judgment/04-How to Make a Buy vs Build Decision.md">כיצד לקבל החלטות קנייה או פיתוח בעצמך</a></li>
            <li><a href="2-Intermediate/Judgment/05-How to Grow Professionally.md">כיצד להתפתח מקצועית</a></li>
            <li><a href="2-Intermediate/Judgment/06-How to Evaluate Interviewees.md">כיצד להעריך מרואיינים</a></li>
            <li><a href="2-Intermediate/Judgment/07-How to Know When to Apply Fancy Computer Science.md">כיצד לדעת מתי להחיל תעלולים מגונדרים של מדעי המחשב</a></li>
            <li><a href="2-Intermediate/Judgment/08-How to Talk to Non-Engineers.md">כיצד לדבר עם לא מהנדסים</a></li>
        </ul>
    </ul>
<li><a href="3-Advanced">מתקדם</a></li>
    <ul>
    <li>שיפוט טכנולוגי</li>
        <ul>
        <li><a href="3-Advanced/Technical-Judgment/01-How to Tell the Hard From the Impossible.md">כיצד להבדיל בין הקשה לבלתי־אפשרי</a></li>
        <li><a href="3-Advanced/Technical-Judgment/02-How to Utilize Embedded Languages.md">כיצד להשתמש בשפות משובצות</a></li>
        <li><a href="3-Advanced/Technical-Judgment/03-Choosing Languages.md">בחירת שפות</a></li>
        </ul>
    <li>התפשרות בחוכמה</li>
        <ul>
        <li><a href="3-Advanced/Compromising-Wisely/01-How to Fight Schedule Pressure.md">כיצד להלחם בלחץ של לוחות זמנים</a></li>
        <li><a href="3-Advanced/Compromising-Wisely/02-How to Understand the User.md">כיצד להבין את המשתמש</a></li>
        <li><a href="3-Advanced/Compromising-Wisely/03-How to Get a Promotion.md">כיצד לקבל קידום</a></li>
        </ul>
    <li>שירות הצוות שלך</li>
        <ul>
        <li><a href="3-Advanced/Serving-Your-Team/01-How to Develop Talent.md">כיצד לפתח כישרון</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/02-How to Choose What to Work On.md">כיצד לבחור על מה לעבוד</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/03-How to Get the Most From Your Teammates.md">כיצד להשיג את המיטב מחבריך לצוות</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/04-How to Divide Problems Up.md">כיצד לחלק בעיות</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/05-How to Handle Boring Tasks.md">כיצד לטפל במשימות משעממות</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/06-How to Gather Support for a Project.md">כיצד לגייס תמיכה עבור הפרויקט שלך</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/07-How to Grow a System.md">כיצד להגדיל מערכת</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/08-How to Communicate Well.md">כיצד לתקשר היטב</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/09-How to Tell People Things They Don't Want to Hear.md">כיצד להגיד לאנשים דברים שהם לא רוצים לשמוע</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/10-How to Deal with Managerial Myths.md">כיצד להתמודד עם מיתוסים של מנהלים</a></li>
        <li><a href="3-Advanced/Serving-Your-Team/11-How to Deal with Organizational Chaos.md">כיצד להתמודד עם תוהו־ובוהו ארגוני</a></li>
        </ul>
    </ul>
<li><a href="GLOSSARY.md">מילון</a></li>
<li><a href="5-Bibliography.md">נספח א' - ביבליוגרפיה/אתרוגרפיה</a></li>
<li><a href="6-History.md">נספח ב' – היסטוריה (נכון לינואר 2016)</a></li>
<li><a href="7-Contributions.md">נספח ג' – תרומות (נכון לינואר 2016)</a></li>
</ul>

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">How To Be A Programmer: Community Version</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Robert L. Read with Community</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</span>
